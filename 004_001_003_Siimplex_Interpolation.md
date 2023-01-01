# Simplex Interpolation

## 近似対象となる関数

ある $d \in \mathbb{N}$ について、

$$
f \colon [0,1]^d \rightarrow \mathbb{K}
$$

ただし、 $\mathbb{K}$ は加法について閉じており、 $[0,1]$ との積 $\cdot \colon [0,1] \times \mathbb{K} \rightarrow \mathbb{K}$ が定義されているものとします。

## 代表点

代表点の集合は

$$
\mathbb{P} = \lbrace (q_{1}, q_{2}, \dots, q_{d}) \mid i \in \lbrace 1, 2, \dots, d\rbrace, q_{i} \in \lbrace 0, 1\rbrace \rbrace
$$

となります。代表点の個数は $2^{d}$ 個です。

## Simplex Interpolation

ある座標 $P \in [0,1]^{d}$ が与えられたとき、それを内部（境界上も含む）に持ち、かつ頂点がすべて $\mathbb{P}$ の要素であり、さらに $(0, 0, 0, \dots, 0)$ と $(1, 1, 1, \dots, 1)$ を頂点に持つ $d$ 次元単体をとることができます。

このとき、 $d$ 次元単体上の頂点を $P_{0}, P_{1}, \dots, P_{d}$ とすると、任意の $i$ において $w_{i} \in [0, 1]$ かつ $\displaystyle{\sum_{i=0}^{d} w_i = 1}$ を満たす適当な実数列 $w_{0}, w_{1}, \dots, w_{d}$ を用いて

$$
\overrightarrow{OP} = \displaystyle{\sum_{i=0}^{d} w_{i} \overrightarrow{OP_{i}}}
$$

とあらわすことができます。ただし、 $O = (0, 0, \dots, 0)$ とします。

このとき $f$ の近似関数 $\overline{f}$ として以下を得ます。

$$
\overline{f}(P) = \displaystyle{\sum_{i=0}^{d} w_{i} f(P_{i})}
$$

