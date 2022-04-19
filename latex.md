---
title: Latex
categories:
  - latex
tags:
  - demo
date: 2022-04-8 15:33:01

---

> written by [Smileyan](https://smileyan.cn)

## python 代码

```python
import js
def maxSubList(labels):
    index = -1
    maxLength = 0
    countLength = 0
    # 循环一次
    for i, one in enumerate(labels):
        if (one == 1):
            countLength += 1
            # 如果检测到更大的子序列
            if(countLength > maxLength):
                maxLength = countLength
                index = i
        else:
        	# 子序列长度结束计数
            countLength = 0
    return maxLength,index
```

## c++ 代码

```cpp
#include <iostream>
using namespace std;

/**
 * 注释
 */
int main() {
  int x,y;
  cin>>x;
  // 注释
  cin>>y;
  cout<<x+y<<endl;cout<<x+y<<endl;cout<<x+y<<endl;
  return 0;
}
```

c 代码

```c
#include <iostream>
using namespace std;

int main() {
  int x,y;
  cin>>x;
  cin>>y;
  cout<<x+y<<endl;
  return 0;
}
```

java 代码

```java
package cn.smileyan;

/**
 * @author yanshili
 */
public class Hello {
    public static void main(String[] args) {
        int x = 0;
        int y = 18;
        for (int i=0; i<y; i++) {
            x += i;
        }
        System.out.println("Hello World");
    }
}

```

html

```html
<!DOCTYPE html>
<html>
<head>
  <title>Bootstrap5 实例</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.staticfile.org/twitter-bootstrap/5.1.1/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.staticfile.org/twitter-bootstrap/5.1.1/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container-fluid p-5 bg-primary text-white text-center">
  <h1>我的第一个 Bootstrap 页面</h1>
  <p>这是一个响应式页面，重置浏览器大小查看效果!</p> 
</div>
  
<div class="container mt-5">
  <div class="row">
    <div class="col-sm-4">
      <h3>第一列</h3>
      <p>菜鸟教程</p>
      <p>学的不仅是技术，更是梦想！！！</p>
    </div>
    <div class="col-sm-4">
      <h3>第二列</h3>
      <p>菜鸟教程</p>
      <p>学的不仅是技术，更是梦想！！！</p>
    </div>
    <div class="col-sm-4">
      <h3>第三列</h3>        
      <p>菜鸟教程</p>
      <p>学的不仅是技术，更是梦想！！！</p>
    </div>
  </div>
</div>

</body>
</html>
```


css

```css
#rcorners1 {
    border-radius: 25px;
    background: #8AC007;
    padding: 20px; 
    width: 200px;
    height: 150px;    
}

#rcorners2 {
    border-radius: 25px;
    border: 2px solid #8AC007;
    padding: 20px; 
    width: 200px;
    height: 150px;    
}

.rcorners3 {
    border-radius: 25px;
    background: url(/images/paper.gif);
    background-position: left top;
    background-repeat: repeat;
    padding: 20px; 
    width: 200px;
    height: 150px;    
}
```

javascript

```javascript
function displayDate(){
	document.getElementById("demo").innerHTML=Date();
}
```

## scala

```scala
object HelloWorld {
  def main(args: Array[String]): Unit = {
    println("Hello, world!")
  }
}
```

## bash

```bash
$ cd ~
$ npm install hello-world
$ git clone wwesf
$ yum -y install 
$ make & make install
```



# 字母



|    字母    |  表达式  |     字母      |    符号     |
| :--------: | :------: | :-----------: | :---------: |
|  $\theta$  |  \theta  |  $\upsilon$   |  \upsilon   |
|  $\sigma$  |  \sigma  |   $\lambda$   |   \lambda   |
|  $\alpha$  |  \alpha  |   $\Omega$    |   \Omega    |
|  $\beta$   |  \beta   |    $\Phi$     |    \Phi     |
|  $\gamma$  |  \gamma  |   $\varphi$   |   \varphi   |
|   $\phi$   |   \phi   |     $\Pi$     |     \pi     |
|   $\mu$    |   \mu    |   $\omega$    |   \omega    |
|   $\xi$    |   \xi    |    $\psi$     |    \psi     |
|   $\pi$    |   \pi    |    $\chi$     |    \chi     |
|  $\delta$  |  \delta  |    $\tau$     |    \tau     |
| $\epsilon$ | \epsilon |  $\epsilon$   |  \epsilon   |
|  $\zeta$   |  \zeta   | $\varepsilon$ | \varepsilon |
|   $\eta$   |   \eta   |    $\rho$     |    \rho     |
| $\partial$​ | \partial |               |             |


有一些字母的大写就是大写第一个字符即可。比如 $\Tau$ \Tau 是 $\tau$ \tau 的大写。 

哥特体：

比如说字母 S，\mathfrak {S} ：<big><big>$\mathfrak{S}$ </big></big>

|  字体名  |    表达式     |        例子        |
| :------: | :-----------: | :----------------: |
|  手写体  | \mathcal { }  | $\mathcal {A,B,C}$ |
|  哥特体  | \mathfrak { } | $\mathfrak{A,B,C}$ |
|  正粗体  |  \mathbf { }  |  $\mathbf{A,B,C}$  |
| 黑板粗体 |  \mathbb { }  |  $\mathbb{A,B,C}$  |
|   斜体   |  \mathif { }  |  $\mathit{A,B,C}$  |
|  罗马体  |  \mathrm { }  |  $\mathrm{A,B,C}$  |

### 运算符号

|              符号              |            表达式            |       解释（索引）       |
| :----------------------------: | :--------------------------: | :----------------------: |
|            $\times$            |            \times            |           乘法           |
|             $\div$             |             \div             |           除法           |
|             $\pm$              |             \pm              |     正负号（正或负）     |
|           $\forall$            |           \forall            |        任意，所有        |
|           $\exists$            |       \exist , \exists       |           存在           |
|            $\not=$             |            \not=             |      不等于，不等号      |
|           $\approx$            |           \approx            |      约等于，约等号      |
|             $\geq$             |          \geq，\ge           |         大于等于         |
|             $\leq$             |             \leq             |         小于等于         |
|             $\gg$              |             \gg              |          远大于          |
|             $\ll$              |             \ll              |          远小于          |
|            $\nabla$            |            \nabla            | 算子，倒三角，偏导，梯度 |
|             $\in$              |             \in              |           属于           |
|           $\subset$            |        \sub ，\subset        |          包含于          |
|          $\subseteq$           |          \subseteq           |          包含于          |
|          $\subsetneq$          |          \subsetneq          |         真包含于         |
|            $\cdot$             |            \cdot             |         点，点乘         |
|           $\partial$           |           \partial           |          求偏导          |
|            $\infty$            |            \infty            |           无穷           |
|           $\propto$            |           \propto            |       近似于，似然       |
|           $\dot{x}$            |           \dot{x}            |       上点，导数点       |
|           $\vec{AB}$           |           \vec{AB}           |           向量           |
|    $\int_{-N}^{N} e^x\, dx$    |    \int_{-N}^{N} e^x\, dx    |           积分           |
|   $\iint_{D}^{W} \, dx\,dy$    |   \iint_{D}^{W} \, dx\,dy    |         双重积分         |
| $\iiint_{E}^{V} \, dx\,dy\,dz$ | \iiint_{E}^{V} \, dx\,dy\,dz |         三重积分         |
|       $\sum_{k=1}^N k^2$       |       \sum_{k=1}^N k^2       |           求和           |
|      $\prod_{i=1}^N x_i$       |      \prod_{i=1}^N x_i       |           连乘           |
|             $\sim$             |             \sim             |          波浪号          |
|           $\backsim$           |           \backsim           |         反波浪号         |
|              $\S$              |              \S              |         章节符号         |
|             $\ell$             |             \ell             |           范数           |
|              $\|$              |              \\              |                          |
|          $\text{\/}$           |          \text{\\/}          |          反斜杆          |
|               \                |              \               |          反斜杠          |
|      $\lfloor x \rfloor$       |      \lfloor x \rfloor       |         向下取整         |
|       $\lceil x \rceil$        |       \lceil x \rceil        |         向上取整         |

反斜杠可以考虑不加入 \$$ 中间直接使用，需要输入两个 反斜杠即可。

```bash
方法一：

$$ 
f(x)=\left\{
\begin{aligned}
x & = & \cos(t) \\
y & = & \sin(t) \\
z & = & \frac xy
\end{aligned}
\right.
$$

方法二：
$$ 
F^{HLLC}=\left\{
\begin{array}{rcl}
F_L       &      & {0      <      S_L}\\
F^*_L     &      & {S_L \leq 0 < S_M}\\
F^*_R     &      & {S_M \leq 0 < S_R}\\
F_R       &      & {S_R \leq 0}
\end{array} \right. 
$$

方法三:
$$
f(x)=
\begin{cases}
0,& \text{x=0}\\
1,& \text{x!=0}
\end{cases}
$$

```



对应的效果如图：

<p>
$$
f(x)=\left\{
\begin{aligned}
x & = & \cos(t) \\
y & = & \sin(t) \\
z & = & \frac xy
\end{aligned}
\right.
$$
</p>


<p>
$$
F^{HLLC}=\left\{
\begin{array}{rcl}
F_L       &      & {0      <      S_L}\\
F^*_L     &      & {S_L \leq 0 < S_M}\\
F^*_R     &      & {S_M \leq 0 < S_R}\\
F_R       &      & {S_R \leq 0}
\end{array} \right. 
$$
</p>


<p>
$$
f(x)=
\begin{cases}
0,& \text{x=0}\\
1,& \text{x!=0}
\end{cases}
$$
</p>



字母头上有：



|                符号                 |              表达式               | 解释(索引) |
| :---------------------------------: | :-------------------------------: | :--------: |
|              $\vec{c}$              |              \vec{c}              |   向量c    |
|        $\overleftarrow{ab}$         |        \overleftarrow{ab}         |  指向左边  |
|        $\overrightarrow{ab}$        |          \overrightarrow          |  指向右边  |
|              $\hat{A}$              |              \hat{A}              |     帽     |
|            $\widehat{A}$            |             \widehat              | 大帽，宽帽 |
|           $\overline{ab}$           |             \overline             |   上划线   |
|          $\underline{ab}$           |            \underline             |   下划线   |
|       $\overset{\frown}{ab}$        |             \overset              |    上弧    |
|          $\widetilde{ab}$           |          \widetilde{ab}           |  上波浪号  |
|    $\overbrace{1+2+\cdots+100}$     |    \overbrace{1+2+\cdots+100}     |   上括号   |
| $\overbrace{1+2+\cdots+100}^{5050}$ | \overbrace{1+2+\cdots+100}^{5050} |   上括号   |
|     $\underbrace{a+b+\cdots+z}$     |     \underbrace{a+b+\cdots+z}     |   下括号   |
|  $\underbrace{a+b+\cdots+z}_{26}$   |  \underbrace{a+b+\cdots+z}_{26}   |   下括号   |








https://blog.csdn.net/young951023/article/details/79601664

https://www.cnblogs.com/q735613050/p/7474449.html

