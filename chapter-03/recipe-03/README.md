### 数学符号

#### 希腊字母

小写字母

| 字母          | 指令          | 字母        | 指令        | 字母        | 指令        | 字母       | 指令       |
| :------------ | :------------ | :---------- | :---------- | :---------- | :---------- | :--------- | :--------- |
| $\alpha$      | `\alpha`      | $\theta$    | `\theta`    | $o$         | `o`         | $\tau$     | `\tau`     |
| $\beta$       | `\beta`       | $\vartheta$ | `\vartheta` | $\pi$       | `\pi`       | $\upsilon$ | `\upsilon` |
| $\gamma$      | `\gamma`      | $\iota$     | `\iota`     | $\varpi$    | `\varpi`    | $\phi$     | `\phi`     |
| $\delta$      | `\delta`      | $\kappa$    | `\kappa`    | $\rho$      | `\rho`      | $\varphi$  | `\varphi`  |
| $\epsilon$    | `\epsilon`    | $\lambda$   | `\lambda`   | $\varrho$   | `\varrho`   | $\chi$     | `\chi`     |
| $\varepsilon$ | `\varepsilon` | $\mu$       | `\mu`       | $\sigma$    | `\sigma`    | $\psi$     | `\psi`     |
| $\zeta$       | `\zeta`       | $\nu$       | `\nu`       | $\varsigma$ | `\varsigma` | $\omega$   | `\omega`   |
| $\eta$        | `\eta`        | $\xi$       | `\xi`       |             |             |            |            |

大写字母

| 字母     | 指令     | 字母      | 指令      | 字母       | 指令       | 字母     | 指令     |
| :------- | :------- | :-------- | :-------- | :--------- | :--------- | :------- | :------- |
| $\Gamma$ | `\Gamma` | $\Lambda$ | `\Lambda` | $\Sigma$   | `\Sigma`   | $\Psi$   | `\Psi`   |
| $\Delta$ | `\Delta` | $\Xi$     | `\Xi`     | $\Upsilon$ | `\Upsilon` | $\Omega$ | `\Omega` |
| $\Theta$ | `\Theta` | $\Pi$     | `\Pi`     | $\Phi$     | `\Phi`     |          |          |


#### 花体字母

在数学公式中也可以用26个花体字母：

$$\mathcal{A,B,C,D,E,F,G,H,I,J,K,L,M,N,O,P,Q,R,S,T,U,V,W,X,Y,Z}$$

调用方法是用数学字体样式命令`\mathcal`, 例如：

$\mathcal{A,B,C, \ldots ,Z}$ : `\mathcal{A,B,C, \ldots ,Z}`

#### 二元运算符


| 运算符     | 指令       | 运算符    | 指令      | 运算符     | 指令       | 运算符             | 指令               |
| :--------- | :--------- | :-------- | :-------- | :--------- | :--------- | :----------------- | :----------------- |
| $\pm$      | `\pm`      | $\cap$    | `\cap`    | $\circ$    | `\circr`   | $\bigcirc$         | `\bigcirc`         |
| $\mp$      | `\mp`      | $\cup$    | `\cup`    | $\bullet$  | `\bullet`  | $\Box$             | `\Box`             |
| $\times$   | `\times`   | $\uplus$  | `\uplus`  | $\diamond$ | `\diamond` | $\Diamond$         | `\Diamond`         |
| $\div$     | `\div`     | $\sqcap$  | `\sqcap`  | $\lhd$     | `\lhd`     | $\bigtriangleup$   | `\bigtriangleup`   |
| $\cdot$    | `\cdot`    | $\sqcup$  | `\sqcup`  | $\rhd$     | `\rhd`     | $\bigtriangledown$ | `\bigtriangledown` |
| $\ast$     | `\ast`     | $\vee$    | `\vee`    | $\unlhd$   | `\unlhd`   | $\triangleleft$    | `\triangleleft`    |
| $\star$    | `\star`    | $\wedge$  | `\wedge`  | $\unrhd$   | `\unrhd`   | $\triangleright$   | `\triangleright`   |
| $\dagger$  | `\dagger`  | $\oplus$  | `\oplus`  | $\oslash$  | `\oslash`  | $\setminus$        | `\setminus`        |
| $\ddagger$ | `\ddagger` | $\ominus$ | `\ominus` | $\odot$    | `\odot`    | $\wr$              | `\wr`              |
| $\amalg$   | `\amalg`   | $\otimes$ | `\otimes` |            |            |                    |                    |

#### 关系运算符

| 运算符        | 指令          | 运算符        | 指令          | 运算符      | 指令        | 运算符      | 指令        |
| :------------ | :------------ | :------------ | :------------ | :---------- | :---------- | :---------- | :---------- |
| $\le$         | `\le` `\leq`  | $\ge$         | `\ge` `\geq`  | $\neq$      | `\neq`      | $\sim$      | `\sim`      | 
| $\ll$         | `\ll`         | $\gg$         | `\gg`         | $\doteq$    | `\doteq`    | $\simeq$    | `\simeq`    |
| $\subset$     | `\subset`     | $\supset$     | `\supset`     | $\approx$   | `\approx`   | $\asymp$    | `\asymp`    |
| $\subseteq$   | `\subseteq`   | $\supseteq$   | `\supseteq`   | $\cong$     | `\cong`     | $\smile$    | `\smile`    |
| $\sqsubset$   | `\sqsubset`   | $\sqsupset$   | `\sqsupset`   | $\equiv$    | `\equiv`    | $\frown$    | `\frown`    |
| $\sqsubseteq$ | `\sqsubseteq` | $\sqsupseteq$ | `\sqsupseteq` | $\propto$   | `\propto`   | $\bowtie$   | `\bowtie`   |
| $\in$         | `\in`         | $\ni$         | `\ni`         | $\prec$     | `\prec`     | $\succ$     | `\succ`     |
| $\vdash$      | `\vdash`      | $\dashv$      | `\dashv`      | $\preceq$   | `\preceq`   | $\succeq$   | `\succeq`   |
| $\models$     | `\models`     | $\perp$       | `\perp`       | $\parallel$ | `\parallel` | $\mid$      | `\mid`      |

#### 关系运算符的否定
