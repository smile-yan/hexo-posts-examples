# hexo-posts-examples

Examples with categories and tags of hexo's posts.

## scripts for creating posts

```python
import datetime

import time
import random

def to_int(valid_time):
#  = '2021-08-08 15:47:01'
    d1 = datetime.datetime.strptime(valid_time,'%Y-%m-%d %H:%M:%S')
    ts = int(time.mktime(d1.timetuple()))
    return ts

def to_date(intTime):
    time1 = time.localtime(intTime)
    return time.strftime('%Y-%m-%d %H:%M:%S', time1)
    

def content(one_type, one_tag, title):
    # 开始时间与结束时间中随机
    start = to_int('2022-04-01 12:12:00')
    end = to_int('2022-04-18 12:12:00')
    res1 = random.randrange(start, end, 100)
    
    format_date = to_date(res1)
    
    content = '---\n' + \
              'title:' + title + '\n' + \
              'categories: ' + '\n' + \
              '  - ' + one_type + '\n' + \
                'tags: \n' + \
                '  - ' + one_tag + "\n" + \
                'date: ' + format_date + "\n" + \
                '---\n\n' + '# ' + title + '\n'            
    return content

types = ('python', 'java', 'linux', 'scala', 'html', 'javascript')
tags = ('示例', '笔记', '心得', '随笔')
times = 6
for t, one in enumerate(types):
    for i in range(times):
        file_name = '{0}_{1}.md'.format(one, i+1)
        with open(file_name, mode='w+') as f:
            f.write( content(one, tags[t%len(tags)], '{0}_{1}'.format(one, i+1)) )
```
