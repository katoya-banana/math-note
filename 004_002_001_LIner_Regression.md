# 線形回帰

## 説明変数と目的変数

説明変数は $\mathbb{R}^{d}$ ただし $d \in \mathbb{N}$ 、目的変数は $\mathbb{R}$ とします。  
また、説明変数と目的変数の組は $n \in \mathbb{N}$ 個与えられているものとします。

## 線形回帰
説明変数と目的変数の間の線形近似関数 $\overline{f} \colon \mathbb{R}^{d} \rightarrow \mathbb{R}$ として以下を得ます。

$$
\overline{f}(x_{1}, x_{2}, \dots, x_{d}) = \beta_{0} + \beta_{1} x_{1} + \dots + \beta_{d} x_{d}
$$

ただし、 $\beta_{0}, \beta_{1}, \dots, \beta_{n} \in \mathbb{R}$ であり、

$$
\overrightarrow{\beta} = 
\begin{bmatrix}
\beta_{0} \\
\beta_{1} \\
\vdots \\
\beta_{d}
\end{bmatrix}
, \quad
X = 
\begin{bmatrix}
1 & x_{1, 0} & \dots & x_{1, d}\\
1 & x_{2, 0} & \dots & x_{2, d}\\
\vdots & \vdots & \ddots & \vdots \\ 
1 & x_{n, 0}  & \dots & x_{n, d}\\
\end{bmatrix}
, \quad
Y = 
\begin{bmatrix}
y_{1} \\
y_{2} \\
\vdots \\
y_{n}
\end{bmatrix}
$$

としたとき、

$$
\overrightarrow{\beta} = (X^{T} X)^{-1} X^{T} Y
$$

です。

この $\overrightarrow{\beta}$ は以下と等しいです。

$$
\underset{\overrightarrow{\beta}}{\operatorname{argmin}} (Y − X \overrightarrow{\beta})^{T}(Y − X \overrightarrow{\beta})
$$
