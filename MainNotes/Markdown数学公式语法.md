> DATA: 2025-06-16 20:25
> TAGS: [[Markdown]]
> Course: #None 
> Author: [ApolloMonasa](https://github.com/ApolloMonasa)
> Pre: 简单了解Markdown的数学语法

# Markdown数学公式语法
---
## 1.行内式与独立式

$x+y=1$

$$x+y=1$$
## 2.上下标

$$
x^2+y_1=x^{x_1+y}
x+y = 1
$$

## 3.多行公式
### 1.对齐/居中模式align/gather

$$
\begin{align}
f(x)&=3x^2 + 2x + 1\\
&=3(x^2+\frac{2}{3}x)+1\\
&=3(x^2+\frac{2}{3}x+\frac{1}{9}-\frac{1}{9})+1\\
&=3(x+\frac{1}{3})^2+\frac{2}{3}
\end{align}
$$
---
$$
\begin{gather}
a+b=c\\
d-r=f
\end{gather}
$$
### 2.分段函数case
$$
F(n)=\begin{cases}
\frac{n}{2}, &\text{if n is even}\\
3n+1, &\text{if n is odd}
\end{cases}
$$
> 1. &可以指定对齐位置
> 2. \begin{}和\end{}包裹环境下"\\"表示换行
> 3. align(ed)代表对齐，case代表分段函数

### 3.矩阵/行列式
#### (1)无括号矩阵matrix(&分隔)
$$
\begin{matrix}
1&0&0\\
0&1&0\\
0&0&1\\
\end{matrix}
$$
#### (2)圆括号矩阵pmatrix
$$
\begin{pmatrix}
a\\
b\\
c\\
d
\end{pmatrix}
$$
#### (3)方括号矩阵bmatrix
$$
\begin{bmatrix}
a&c\\
b&d\\
\end{bmatrix}
$$
#### (4)单双竖线行列式v\V
$$
\begin{vmatrix}
a\\
b\\
c\\
d
\end{vmatrix}
$$
---
$$
\begin{Vmatrix}
a\\
b\\
c\\
d
\end{Vmatrix}
$$
#### (5)表格tabular
##### markdown语法

| 列   | 列   |
| --- | --- |
|     |     |
> 左对齐:--
> 居中:--:
> 右对齐--:

$$
\begin{tablular}{|1|2|3|}
\hline
s&s&
\end{tabular}
$$
## 4.括号

$$
f(x,y)=x^2+y_2,x \epsilon [1, 10], y \epsilon \{1, 2, 3\}
$$
$$
\begin{aligned}
\lparen\sqrt{{1 \over 2} + 1}\rparen\\
\lbrack a,b\rbrack\\
\end{aligned}
$$
## 5.省略号
$$
{1 \over 2}, {1 \over 3}, \ldots, {1 \over n}
$$
$$
{1 \over 2}, {1 \over 3}, \cdots, {1 \over n}
$$

## 6.向量
$$
\vec a
$$
$$
\vec {ab}
$$
## 7.极限
$$
\lim_{n\rightarrow+\infty} \frac{1}{n}
$$
> \in 和 \epsilom 都是 $\epsilon$

## 8.求导
$$
y \prime = nx^{n-1}
$$
## 9.对数
$$
\log3\ln2\lg1
$$

## 10.数学符号
$$
\begin{aligned}
\not= \\
\approx \\
\leq \\
\geq \\
\cdot \\
\pm \\
\div \\
\infty \\
\sum \\
\prod \\
\coprod \\
\uparrow \\
\downarrow \\
\leftarrow \\
\rightarrow \\
\overline{a + b + c } \\
\bar{a+b+c}\\
\end{aligned}
$$
## 11.定积分
$$
\begin{aligned}
\int \\
\iint\\
\iiint \\
\iiiint \\
\oint \\
\end{aligned}
$$
## 12.三角函数
$$
\begin{align}
\bot \\
\angle \\
30^\circ \\
\sin \\
\cos \\
\tan \\
\cot \\
\sec \\
\csc
\end{align}
$$
## 13.集合
$$
\begin{cases}
\emptyset \\
\in \\
\notin \\
\supset \\
\supseteq \\
\bigcap \\
\bigcup \\
\bigvee \\
\bigwedge \\
\end{cases}
$$
## 14.希腊字母

| 1          | 2             | 3           | 4        |
| ---------- | ------------- | ----------- | -------- |
| $\alpha$   | $\beta$       | $\gamma$    | $\delta$ |
| $\epsilon$ | $\varepsilon$ | $\zeta$     | $\eta$   |
| $\theta$   | $\Theta$      | $\vartheta$ | $\pi$    |
| $\phi$     | $\psi$        | $\Psi$      | $\omega$ |
| $\Omega$   | $\rho$        | $\sigma$    | $\xi$    |
| $\mu$      | $\partial$    |             |          |
| $\Sigma$   | $\Delta$      |             |          |

## 15.离散记号
$$
\begin{align}
\neg \\
\land\wedge\\
\lor\vee\\
\to\rightarrow\\
\subset\\
\leftrightarrow\\
\forall\\
\exists\\
\in\\
\varnothing\emptyset\\
\iff\\
\because\\
\therefore\\
\end{align}
$$
## 16.粗体
$$
\begin{align}
\textbf{Hello textbf!}\\
\bf{Hello bf!}\\
\boldsymbol{Hello boldsymbol!}\\
\end{align}
$$
## 17.算符
$$
\begin{align}
\mp\\
\pm\\
+\\
-\\
\star\\
*\\
\\\
\end{align}
$$
# Reference
[B站教学1](https://www.bilibili.com/video/BV1Fg411i7wH?vd_source=bf539df4a6ae0f9adeb837e24e051caf)
[推荐辅助工具](https://simpletex.cn/download)

[Docs](https://katex.org/docs/supported)



---
Recommend Links
