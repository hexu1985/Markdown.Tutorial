### 数学公式



#### 逻辑运算公式

| 功能     | 语法                  | 效果                  |
| -------- | --------------------- | --------------------- |
| 逻辑与   | `p \and q`            | $p \and q$            |
| 逻辑与   | `p \land q`           | $p \land q$           |
| 逻辑与   | `p \wedge q`          | $p \wedge q$          |
| 逻辑与   | `p \bigwedge q`       | $p \bigwedge q$       |
| 逻辑或   | `p \or q`             | $p \or q$             |
| 逻辑或   | `p \lor q`            | $p \lor q$            |
| 逻辑或   | `p \vee q`            | $p \vee q$            |
| 逻辑或   | `p \bigvee q`         | $p \bigvee q$         |
| 逻辑非   | `\bar{q}`             | $\bar{q}$             |
| 逻辑非   | `\lnot q`             | $\lnot q$             |
| 逻辑异或 | `p \oplus q `         | $p \oplus q$          |
| 逻辑蕴含 | `p \rightarrow q`     | $p \rightarrow q$     |
| 逻辑等价 | `p \leftrightarrow q` | $p \leftrightarrow q$ |
| 逻辑等价 | `p \equiv q`          | $p \equiv q$          |
| 永真式   | `\mathbf{T}`          | $\mathbf{T}$          |
| 矛盾式   | `\mathbf{F}`          | $\mathbf{F}$          |
| 全称量化 | `\forall x P(x)`      | $\forall x P(x)$      |
| 存在量化 | `\exists x P(x)`      | $\exists x P(x)$      |

#### 根式

| 功能                 | 语法                                                         | 效果                                                         |
| -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 根号                 | `\sqrt{2}`                                                   | $\sqrt{2}$                                                   |
| 根号                 | `\sqrt[n]{2}`                                                | $\sqrt[n]{x}$                                                |

#### 模运算公式

| 功能 | 语法                    | 效果                    |
| ---- | ----------------------- | ----------------------- |
| 同余 | `s_k \equiv 0 \pmod{m}` | $s_k \equiv 0 \pmod{m}$ |
| 取模 | `a \bmod b`             | $a \bmod b$             |

#### 微分公式

| 功能             | 语法                                                         | 效果                                                         |
| ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 哈密顿算子       | `\nabla f`                                                   | $\nabla f$                                                   |
| 梯度向量         | `\nabla f = \cfrac{\partial f}{\partial x} \boldsymbol{i} + \cfrac{\partial f}{\partial y} \boldsymbol{j}` | $\nabla f = \cfrac{\partial f}{\partial x} \boldsymbol{i} + \cfrac{\partial f}{\partial y} \boldsymbol{j}$ |
| 偏微分           | `\partial x`                                                 | $\partial x$                                                 |
| 微分             | `dx`                                                         | $dx$                                                         |
| 导数（牛顿）     | `\dot x`                                                     | $\dot x$                                                     |
| 二阶导数（牛顿） | `\ddot y`                                                    | $\ddot y$                                                    |
| 导数（莱布尼茨） | `$\cfrac{dy}{dx}`                                            | $\cfrac{dy}{dx}$                                             |
| 二阶混合偏导数   | `\cfrac{\partial ^2 y}{\partial x_1 \partial x_2}`           | $\cfrac{\partial ^2 y}{\partial x_1 \partial x_2}$           |

#### 上标、下标及积分等

| 功能                 | 语法                                                         | 效果                                                         |
| -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 上标                 | `a^2`                                                        | $a^2$                                                        |
| 下标                 | `a_2`                                                        | $a_2$                                                        |
| 组合                 | `a^{2+2}`                                                    | $a^{2+2}$                                                    |
| 组合                 | `a_{i,j}`                                                    | $a_{i,j}$                                                    |
| 结合上下标           | `x_2^3`                                                      | $x_2^3$                                                      |
| 结合上下标           | `{}_1^2\!X_3^4`                                              | ${}_1^2\!X_3^4$                                              |
| 导数（HTML）         | `x'`                                                         | $x'$                                                         |
| 导数（PNG）          | `x^\prime`                                                   | $x^\prime$                                                   |
| 导数（错误）         | `x\prime`                                                    | $x\prime$                                                    |
| 导数点               | `\dot{x}`                                                    | $\dot{x}$                                                    |
| 导数点               | `\ddot{y}`                                                   | $\ddot{y}$                                                   |
| 向量                 | `\vec{c}`                                                    | $\vec{c}$                                                    |
| 向量                 | `\overleftarrow{a b}`                                        | $\overleftarrow{a b}$                                        |
| 向量                 | `\overrightarrow{c d}`                                       | $\overrightarrow{c d}$                                       |
| 向量                 | `\widehat{e f g}`                                            | $\widehat{e f g}$                                            |
| 上弧                 | `\overset{\frown} {AB}`                                      | $\overset{\frown} {AB}$                                      |
| 上划线               | `\overline{h i j}`                                           | $\overline{h i j}$                                           |
| 下划线               | `\underline{k l m}`                                          | $\underline{k l m}$                                          |
| 公式上下的直线       | `\overline{\overline{a}^2 + \underline{xy}+\overline{\overline{z}}}` | $\overline{\overline{a}^2 + \underline{xy}+\overline{\overline{z}}}$ |
| 上括号               | `\overbrace{1+2+\cdots+100}`                                 | $\overbrace{1+2+\cdots+100}$                                 |
| 上括号               | `\begin{matrix} 5050 \\ \overbrace{1+2+\cdots+100 } \end{matrix}` | $\begin{matrix} 5050 \\ \overbrace{1+2+\cdots+100 } \end{matrix}$ |
| 下括号               | `\underbrace{a+b+\cdots+z}`                                  | $\underbrace{a+b+\cdots+z}$                                  |
| 下括号               | `\begin{matrix} \underbrace{ a+b+\cdots+z} \\ 26 \end{matrix}` | $\begin{matrix} \underbrace{ a+b+\cdots+z} \\ 26 \end{matrix}$ |
| 公式上下的括号       | `\overbrace{a + \underbrace{b+c} +d}`                        | $\overbrace{a + \underbrace{b+c} +d}$                        |
| 公式上下的括号       | `\underbrace{a + \overbrace{b + \cdots + y}^{123} + z}_{\alpha\beta\gamma}` | $\underbrace{a + \overbrace{b + \cdots + y}^{123} + z}_{\alpha\beta\gamma}$ |
| 求和                 | `\sum\limits_{k=1}^N k^2`                                    | $\sum\limits_{k=1}^N k^2$                                    |
| 求和                 | `\sum_{k=1}^N k^2`                                           | $\sum_{k=1}^N k^2$                                           |
| 求和                 | `\begin{matrix} \sum_{k=1}^N k^2\end{matrix}`                | $\begin{matrix} \sum_{k=1}^N k^2\end{matrix}$                |
| 求和（多行下标）     | `\sum\limits_{\substack{a=0\\b>a>10}}^{a=c}\sqrt{a^2+1}`     | $\sum\limits_{\substack{a=0\\b>a>10}}^{a=c}\sqrt{a^2+1}$     |
| 求积                 | `\prod\limits_{i=1}^N x_i`                                   | $\prod\limits_{i=1}^N x_i$                                   |
| 求积                 | `\prod_{i=1}^N x_i`                                          | $\prod_{i=1}^N x_i$                                          |
| 求积                 | `\begin{matrix} \prod_{i=1}^N x_i\end{matrix}`               | $\begin{matrix} \prod_{i=1}^N x_i\end{matrix}$               |
| 上积                 | `\coprod\limits_{i=1}^N x_i`                                 | $\coprod\limits_{i=1}^N x_i$                                 |
| 上积                 | `\coprod_{i=1}^N x_i`                                        | $\coprod_{i=1}^N x_i$                                        |
| 上积                 | `\begin{matrix} \coprod_{i=1}^N x_i\end{matrix}`             | $\begin{matrix} \coprod_{i=1}^N x_i\end{matrix}$             |
| 极限                 | `\lim\limits_{n \to \infty}x_n`                              | $\lim\limits_{n \to \infty}x_n$                              |
| 极限                 | `\lim_{n \to \infty}x_n`                                     | $\lim_{n \to \infty}x_n$                                     |
| 极限                 | `\begin{matrix} \lim_{n \to \infty}x_n\end{matrix}`          | $\begin{matrix} \lim_{n \to \infty}x_n\end{matrix}$          |
| 积分                 | `\int_{-N}^{N} e^x\, dx`                                     | $\int_{-N}^{N} e^x\, dx$                                     |
| 积分                 | `\begin{matrix} \int_{-N}^{N} e^x\, dx\end{matrix}`          | $\begin{matrix} \int_{-N}^{N} e^x\, dx\end{matrix}$          |
| 环积分               | `\oint\limits_P\boldsymbol{F}\cdot \hat{\boldsymbol{t}} ds`  | $\oint\limits_P\boldsymbol{F}\cdot \hat{\boldsymbol{t}} ds$  |
| 双重积分             | `\iint_{D}^{W} \, dx\,dy`                                    | $\iint_{D}^{W} \, dx\,dy$                                    |
| 双重积分             | `\iint\limits_{S}G(x,y,z)dS`                                 | $\iint\limits_{S}G(x,y,z)dS$                                 |
| 三重积分             | `\iiint_{E}^{V}\,dx\,dy\,dz`                                 | $\iiint_{E}^{V}\,dx\,dy\,dz$                                 |
| 四重积分             | `\iiiint_{F}^{U}\,dx\,dy\,dz\,dt`                            | $\iiiint_{F}^{U}\,dx\,dy\,dz\,dt$                            |
| 闭合的曲线、曲面积分 | `\oint_{C} x^3\, dx + 4y^2\, dy`                             | $\oint_{C} x^3\, dx + 4y^2\, dy$                             |
| 交集                 | `\bigcap_1^{n}p`                                             | $\bigcap_1^{n}p$                                             |
| 并集                 | `\bigcup_1^{k}p`                                             | $\bigcup_1^{k}p$                                             |

#### 分数

| 功能               | 语法                                                         | 效果                                                         |
| ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 分数               | `\frac{2}{4} = 0.5 `                                         | $\frac{2}{4} = 0.5$                                          |
| 小型分数           | `\tfrac{2}{4} = 0.5`                                         | $\tfrac{2}{4} = 0.5$                                         |
| 大型分数（嵌套）   | `\cfrac{2}{c + \cfrac{2}{d + \cfrac{2}{4}}} = a`             | $\cfrac{2}{c + \cfrac{2}{d + \cfrac{2}{4}}} = a$             |
| 大型分数（不嵌套） | `\dfrac{2}{4} = 0.5 \qquad \dfrac{2}{c + \dfrac{2}{d + \dfrac{2}{4}}} = a` | $\dfrac{2}{4} = 0.5 \qquad \dfrac{2}{c + \dfrac{2}{d + \dfrac{2}{4}}} = a$ |

#### 二项式系数

| 功能           | 语法                                                  | 效果                                                  |
| -------------- | ----------------------------------------------------- | ----------------------------------------------------- |
| 二项式系数     | `\binom{n}{r} = \binom{n}{n-r} = C^n_r = C^n_{n-r}`   | $\binom{n}{r} = \binom{n}{n-r} = C^n_r = C^n_{n-r}$   |
| 小型二项式系数 | `\tbinom{n}{r} = \tbinom{n}{n-r} = C^n_r = C^n_{n-r}` | $\tbinom{n}{r} = \tbinom{n}{n-r} = C^n_r = C^n_{n-r}$ |
| 大型二项式系数 | `\dbinom{n}{r} = \dbinom{n}{n-r} = C^n_r = C^n_{n-r}` | $\dbinom{n}{r} = \dbinom{n}{n-r} = C^n_r = C^n_{n-r}$ |

#### 括号

| 功能                         | 语法                                                 | 效果                                                 |
| ---------------------------- | ---------------------------------------------------- | ---------------------------------------------------- |
| 圆括号，小括号               | `\left( \frac{a}{b} \right)`                         | $\left( \frac{a}{b} \right)$                         |
| 方括号，中括号               | `\left[ \frac{a}{b} \right]`                         | $\left[ \frac{a}{b} \right]$                         |
| 花括号，大括号               | `\left\{ \frac{a}{b} \right\}`                       | $\left\{ \frac{a}{b} \right\}$                       |
| 角括号                       | `\left \langle \frac{a}{b} \right \rangle`           | $\left \langle \frac{a}{b} \right \rangle$           |
| 单竖线，绝对值               | `\left| \frac{a}{b} \right|`                         | $\left| \frac{a}{b} \right|$                         |
| 双竖线，范                   | `\left \| \frac{a}{b} \right \|`                     | $\left \| \frac{a}{b} \right \|$                     |
| 取整函数（Floor function）   | `\left \lfloor \frac{a}{b} \right \rfloor`           | $\left \lfloor \frac{a}{b} \right \rfloor$           |
| 取顶函数（Ceiling function） | `\left \lceil \frac{a}{b} \right \rceil`             | $\left \lceil \frac{a}{b} \right \rceil$             |
| 上下箭头                     | `\left \uparrow \frac{a}{b} \right \downarrow`       | $\left \uparrow \frac{a}{b} \right \downarrow$       |
| 上下箭头                     | `\left \Uparrow \frac{a}{b} \right \Downarrow`       | $\left \Uparrow \frac{a}{b} \right \Downarrow$       |
| 上下箭头                     | `\left \updownarrow \frac{a}{b} \right \Updownarrow` | $\left \updownarrow \frac{a}{b} \right \Updownarrow$ |
| 混合括号                     | `\left [ 0, 1 \right)`                               | $\left [ 0, 1 \right)$                               |
| 混合括号                     | `\left \langle \psi \right |`                        | $\left \langle \psi \right |$                        |
| 单左括号                     | `\left \{ \frac{a}{b} \right .`                      | $\left \{ \frac{a}{b} \right .$                      |
| 单右括号                     | `\left . \frac{a}{b} \right \}`                      | $\left . \frac{a}{b} \right \}$                      |

备注：

可以使用`\big`, `\Big`, `\bigg`, `\Bigg`控制括号的大小，比如代码

```
\Bigg (  \bigg [ \Big \{ \big \langle \left | \| \frac{a}{b} \| \right | \big \rangle  \Big \} \bigg ] \Bigg )
```

显示：
$$
\Bigg (  \bigg [ \Big \{ \big \langle \left | \| \frac{a}{b} \| \right | \big \rangle  \Big \} \bigg ] \Bigg )
$$

#### 空格

| 功能        | 语法                  | 效果                  | 宽度            |
| ----------- | --------------------- | --------------------- | --------------- |
| 2个quad空格 | `\alpha \qquad \beta` | $\alpha \qquad \beta$ | $2m$            |
| quad空格    | `\alpha \quad \beta`  | $\alpha \quad \beta$  | $m$             |
| 大空格      | `\alpha \ \beta`      | $\alpha \ \beta$      | $\cfrac{m}{3}$  |
| 中等空格    | `\alpha \; \beta`     | $\alpha \; \beta$     | $\cfrac{2m}{7}$ |
| 小空格      | `\alpha \, \beta`     | $\alpha \, \beta$     | $\cfrac{m}{6}$  |
| 没有空格    | `\alpha \beta`        | $\alpha \beta$        | $0$             |
| 紧贴        | `\alpha \! \beta`     | $\alpha \! \beta$     | $-\cfrac{m}{6}$ |

#### 矩阵

| 功能     | 语法                                                         | 效果                                                         |
| -------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 矩阵     | `\begin{matrix} x & y \\ z & v \end{matrix}`                 | $\begin{matrix} x & y \\ z & v \end{matrix}$                 |
| 行列式   | `\begin{vmatrix} x & y \\ z & v \end{vmatrix}`               | $\begin{vmatrix} x & y \\ z & v \end{vmatrix}$               |
| 范数     | `\begin{Vmatrix} x & y \\ z & v \end{Vmatrix}`               | $\begin{Vmatrix} x & y \\ z & v \end{Vmatrix}$               |
| 矩阵     | `\begin{bmatrix} 0 & \cdots & 0 \\ \vdots & \ddots & \vdots \\ 0 & \cdots & 0 \end{bmatrix}` | $\begin{bmatrix} 0 & \cdots & 0 \\ \vdots & \ddots & \vdots \\ 0 & \cdots & 0 \end{bmatrix}$ |
| 矩阵     | `\begin{Bmatrix} x & y \\ z & v \end{Bmatrix}`               | $\begin{Bmatrix} x & y \\ z & v \end{Bmatrix}$               |
| 矩阵     | `\begin{pmatrix} x & y \\ z & v\end{pmatrix}`                | $\begin{pmatrix} x & y \\ z & v\end{pmatrix}$                |
| 小型矩阵 | `\bigl( \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \bigr)` | $\bigl( \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \bigr)$ |



```
\begin{matrix}
x & y \\
z & v
\end{matrix}
```

$$
\begin{matrix}x & y \\z & v\end{matrix}
$$

```
\begin{vmatrix}
x & y \\
z & v
\end{vmatrix}
```

$$
\begin{vmatrix}
x & y \\
z & v
\end{vmatrix}
$$

```
\begin{Vmatrix}
x & y \\
z & v
\end{Vmatrix}
```

$$
\begin{Vmatrix}
x & y \\
z & v
\end{Vmatrix}
$$

```
\begin{bmatrix}
0      & \cdots & 0      \\
\vdots & \ddots & \vdots \\
0      & \cdots & 0 
\end{bmatrix}
```

$$
\begin{bmatrix}
0      & \cdots & 0      \\
\vdots & \ddots & \vdots \\
0      & \cdots & 0 
\end{bmatrix}
$$

```
\begin{Bmatrix}
x & y \\
z & v
\end{Bmatrix}
```

$$
\begin{Bmatrix}
x & y \\
z & v
\end{Bmatrix}
$$

```
\begin{pmatrix}
x & y \\
z & v
\end{pmatrix}
```

$$
\begin{pmatrix}
x & y \\
z & v
\end{pmatrix}
$$

```
\bigl( \begin{smallmatrix}
a & b \\
c & d
\end{smallmatrix} \bigr)
```

$$
\bigl( \begin{smallmatrix}
a & b \\
c & d
\end{smallmatrix} \bigr)
$$

#### 多行公式

| 功能               | 语法                                                         | 效果                                                         |
| ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 条件定义           | `f(n) = \begin{cases} n/2, & \mbox{if }n \mbox{ is even} \\ 3n+1, & \mbox{if }n \mbox{ is odd} \end{cases}` | $f(n) = \begin{cases} n/2, & \mbox{if }n \mbox{ is even} \\ 3n+1, & \mbox{if }n \mbox{ is odd} \end{cases}$ |
| 多行等式           | `\begin{align} f(x) & = (m+n)^2 \\ & = m^2 + 2mn + n^2 \\ \end{align}` | $\begin{align} f(x) & = (m+n)^2 \\ & = m^2 + 2mn + n^2 \\ \end{align}$ |
| 多行等式           | `\begin{alignat}{2} f(x) & = (m-n)^2 \\ f(x) & = (-m+n)^2 \\ & = m^2 - 2mn + n^2 \\ \end{alignat}` | $\begin{alignat}{2} f(x) & = (m-n)^2 \\ f(x) & = (-m+n)^2 \\ & = m^2 - 2mn + n^2 \\ \end{alignat}$ |
| 多行等式（左对齐） | `\begin{array}{l} z & = & a \\ f(x,y,z) & = & x + y + z \end{array}` | $\begin{array}{l} z & = & a \\ f(x,y,z) & = & x + y + z \end{array}$ |
| 多行等式（右对齐） | `\begin{array}{r} z & = & a \\ f(x,y,z) & = & x + y + z \end{array}` | $\begin{array}{r} z & = & a \\ f(x,y,z) & = & x + y + z \end{array}$ |
| 多行等式(居中对齐) | `\begin{array}{rcl} z & = & a \\ f(x,y,z) & = & x + y + z \end{array}` | $\begin{array}{rcl} z & = & a \\ f(x,y,z) & = & x + y + z \end{array}$ |
| 多行等式(两边对齐) | `\begin{array}{lcr} z & = & a \\ f(x,y,z) & = & x + y + z \end{array}` | $\begin{array}{lcr} z & = & a \\ f(x,y,z) & = & x + y + z \end{array}$ |
| 方程组             | `\begin{cases} 3x + 5y + z = 0\\ 7x - 2y + 4z = 0 \\ -6x + 3y + 2z = 0 \end{cases}` | $\begin{cases} 3x + 5y + z = 0\\ 7x - 2y + 4z = 0 \\ -6x + 3y + 2z = 0 \end{cases}$ |
| 数组               | `\begin{array}{|c|c|c|} a & b & S \\ \hline 0 & 0 & 1 \\ 0 & 1 & 1 \\ 1 & 0 & 1 \\ 1 & 1 & 0 \\ \end{array}` | $\begin{array}{|c|c|c|} a & b & S \\ \hline 0 & 0 & 1 \\ 0 & 1 & 1 \\ 1 & 0 & 1 \\ 1 & 1 & 0 \\ \end{array}$ |



##### 条件定义

```
f(n) =
\begin{cases}
n/2, & \mbox{if }n \mbox{ is even} \\
3n+1, & \mbox{if }n \mbox{ is odd}
\end{cases}
```

$$
f(n) =
\begin{cases}
n/2, & \mbox{if }n \mbox{ is even} \\
3n+1, & \mbox{if }n \mbox{ is odd}
\end{cases}
$$

##### 多行等式

```
\begin{align}
f(x) & = (m+n)^2 \\
     & = m^2 + 2mn + n^2 \\
\end{align}
```

$$
\begin{align}
f(x) & = (m+n)^2 \\
     & = m^2 + 2mn + n^2 \\
\end{align}
$$

```
\begin{alignat}{2}
f(x) & = (m-n)^2 \\
f(x) & = (-m+n)^2 \\
     & = m^2 - 2mn + n^2 \\
\end{alignat}
```

$$
\begin{alignat}{2}
f(x) & = (m-n)^2 \\
f(x) & = (-m+n)^2 \\
     & = m^2 - 2mn + n^2 \\
\end{alignat}
$$

##### 多行等式（左对齐）

```
\begin{array}{l}
z        & = & a \\
f(x,y,z) & = & x + y + z
\end{array}
```

$$
\begin{array}{lcl}
z        & = & a \\
f(x,y,z) & = & x + y + z
\end{array}
$$

##### 多行等式（右对齐）

```
\begin{array}{r}
z        & = & a \\
f(x,y,z) & = & x + y + z
\end{array}
```

$$
\begin{array}{r}
z        & = & a \\
f(x,y,z) & = & x + y + z
\end{array}
$$

##### 多行等式(居中对齐)

```
\begin{array}{rcl}
z        & = & a \\
f(x,y,z) & = & x + y + z
\end{array}
```

$$
\begin{array}{rcl}
z        & = & a \\
f(x,y,z) & = & x + y + z
\end{array}
$$

##### 多行等式(两边对齐)

```
\begin{array}{lcr}
z        & = & a \\
f(x,y,z) & = & x + y + z
\end{array}
```

$$
\begin{array}{lcr}
z        & = & a \\
f(x,y,z) & = & x + y + z
\end{array}
$$

##### 方程组

```
\begin{cases}
3x + 5y + z = 0\\
7x - 2y + 4z = 0 \\
-6x + 3y + 2z = 0
\end{cases}
```

$$
\begin{cases}
3x + 5y + z = 0\\
7x - 2y + 4z = 0 \\
-6x + 3y + 2z = 0
\end{cases}
$$

##### 数组

```
\begin{array}{|c|c|c|} 
a & b & S \\
\hline
0 & 0 & 1 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
1 & 1 & 0 \\
\end{array}
```

$$
\begin{array}{|c|c|c|} 
a & b & S \\
\hline
0 & 0 & 1 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
1 & 1 & 0 \\
\end{array}
$$

