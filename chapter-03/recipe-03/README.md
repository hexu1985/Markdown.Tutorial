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

| 运算符            | 指令              | 运算符            | 指令              | 运算符        | 指令          |
| :---------------- | :---------------- | :---------------- | :---------------- | :------------ | :------------ |
| $\not<$           | `\not<`           | $\not>$           | `\not>`           | $\not=$       | `\not=`       |
| $\not\le$         | `\not\le`         | $\not\ge$         | `\not\ge`         | $\not\equiv$  | `\not\equiv`  |
| $\not\prec$       | `\not\prec`       | $\not\succ$       | `\not\succ`       | $\not\sim$    | `\not\sim`    |
| $\not\preceq$     | `\not\preceq`     | $\not\succeq$     | `\not\succeq`     | $\not\simeq$  | `\not\simeq`  |
| $\not\subset$     | `\not\subset`     | $\not\supset$     | `\not\supset`     | $\not\approx$ | `\not\approx` |
| $\not\subseteq$   | `\not\subseteq`   | $\not\supseteq$   | `\not\supseteq`   | $\not\cong$   | `\not\cong`   |
| $\not\sqsubseteq$ | `\not\sqsubseteq` | $\not\sqsupseteq$ | `\not\sqsupseteq` | $\not\asymp$  | `\not\asymp`  |
| $\not\in$         | `\not\in`         | $\notin$          | `\notin`          |               |               |

#### 箭头与指针

| 运算符               | 指令                 | 运算符                | 指令                  | 运算符         | 指令           |
| :------------------- | :------------------- | :-------------------- | :-------------------- | :------------- | :------------- |
| $\leftarrow$         | `\leftarrow \gets`   | $\longleftarrow$      | `\longleftarrow`      | $\uparrow$     | `\uparrow`     |
| $\Leftarrow$         | `\Leftarrow`         | $\Longleftarrow$      | `\Longleftarrow`      | $\Uparrow$     | `\Uparrow`     |
| $\rightarrow$        | `\rightarrow \to`    | $\longrightarrow$     | `\longrightarrow`     | $\downarrow$   | `\downarrow`   |
| $\Rightarrow$        | `\Rightarrow`        | $\Longrightarrow$     | `\Longrightarrow`     | $\Downarrow$   | `\Downarrow`   |
| $\leftrightarrow$    | `\leftrightarrow`    | $\longleftrightarrow$ | `\longleftrightarrow` | $\updownarrow$ | `\updownarrow` |
| $\Leftrightarrow$    | `\Leftrightarrow`    | $\Longleftrightarrow$ | `\Longleftrightarrow` | $\Updownarrow$ | `\Updownarrow` |
| $\mapsto$            | `\mapsto`            | $\longmapsto$         | `\longmapsto`         | $\nearrow$     | `\nearrow`     |
| $\hookleftarrow$     | `\hookleftarrow`     | $\hookrightarrow$     | `\hookrightarrow`     | $\searrow$     | `\searrow`     |
| $\leftharpoonup$     | `\leftharpoonup`     | $\rightharpoonup$     | `\rightharpoonup`     | $\swarrow$     | `\swarrow`     |
| $\leftharpoondown$   | `\leftharpoondown`   | $\rightharpoondown$   | `\rightharpoondown`   | $\nwarrow$     | `\nwarrow`     |
| $\rightleftharpoons$ | `\rightleftharpoons` | $\leftrightharpoons$  | `\leftrightharpoons`  | $\leadsto$     | `\leadsto`     |

#### 逻辑运算符

| 运算符        | 指令                | 运算符            | 指令              | 运算符   | 指令     |
| :------------ | :------------------ | :---------------- | :---------------- | :------- | :------- |
| $\land$       | `\and \land \wedge` | $\bigwedge$       | `\bigwedge`       | $\lnot$  | `\lnot`  |
| $\lor$        | `\or \lor \vee`     | $\bigvee$         | `\bigvee`         | $\oplus$ | `\oplus` |
| $\forall$     | `\forall`           | $\exists$         | `\exists`         | $=$      | `=`      |
| $\rightarrow$ | `\rightarrow \to`   | $\leftrightarrow$ | `\leftrightarrow` | $\equiv$ | `\equiv` |

