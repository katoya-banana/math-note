# Kernel Smoothing

## 近似対象となる関数

ある $d \in \mathbb{N}$ について、

$$
f \colon \mathbb{R}^d \rightarrow \mathbb{K}
$$

ただし、 $\mathbb{K}$ は加法について閉じており、 $\mathbb{R}$ との積 $\cdot \colon \mathbb{R} \times \mathbb{K} \rightarrow \mathbb{K}$ が定義されているものとします。

## 代表点

有限個の代表点 $P_{1}, P_{2}, \dots, P_{n} \in \mathbb{R}^d $ をとります。

任意の $i, j \in \lbrace 1, 2, \dots, n \rbrace$ について、 $i \neq j \Leftrightarrow P_{1} \neq P_{j}$ です。

## Kernel Smoothing

ある Kernel Function $K \colon \mathbb{R}^d \rightarrow \mathbb{R}$ を定義したうえで、 $f$ の近似関数 $\overline{f}$ として以下を得ます。

$$
\overline{f}(P) = \frac{\displaystyle{\sum_{i=1}^{n}K(P_{i}, P)}f(P_{i})}{\displaystyle{\sum_{i=1}^{n}K(P_{i}, P)}}
$$

Kernel Function の形状によっては、 $\exist i, \overline{f}(P_{i}) \neq f(P_{i})$ が成り立つ場合がある点に注意してください。

