# 線形補完

## 近似対象となる関数

ある $d \in \mathbb{N}$ について、

$$
f \colon [0,1]^d \rightarrow \mathbb{K}
$$

ただし、 $\mathbb{K}$ は加法について閉じており、 $[0,1]$ との積 $\cdot \colon [0,1] \times \mathbb{K} \rightarrow \mathbb{K}$ が定義されているものとします。

## 代表点

代表点の集合は

$$
\mathbb{P} = \lbrace (q_{1}, q_{2}, \dots, q_{d}) | i \in \lbrace 1, 2, \dots, d\rbrace, q_{i} \in \lbrace 0, 1\rbrace \rbrace
$$

となります。代表点の個数は $2^{d}$ 個で、辞書順に早い方から $P_{1}, P_{2}, \dots, P_{2^{d}}$ と呼ぶことにします。

## 線形補完

$f$ の近似関数 $\overline{f}$ として以下を得ます。

$$
\begin{array}{ll}
\overline{f}(P) = 
\begin{cases}
f(P) & (P \in \mathbb{P}) \\
(1-q_{i}) \overline{f} (P_{i, 0}) + q_{i} \overline{f} (P_{i, 1}) & 
(P \notin \mathbb{P})
\end{cases}
\end{array}
$$

ただし、
$$
P = (q_{1}, q_{2}, \dots, q_{n}) \in [0, 1]^{d}
$$

$$
i = \operatorname{min}(\lbrace j | q_{j} \notin \lbrace 0, 1 \rbrace \rbrace)
$$

$$
P_{i,0} = (q_{1}, q_{2}, \dots, q_{i-1}, 0, q_{i+1}, \dots, q_{n}) \in [0, 1]^{d}
$$

$$
P_{i,1} = (q_{1}, q_{2}, \dots, q_{i-1}, 1, q_{i+1}, \dots, q_{n}) \in [0, 1]^{d}
$$

とします。

再帰的な定義になっていますが、値が確定する点に注意してください。