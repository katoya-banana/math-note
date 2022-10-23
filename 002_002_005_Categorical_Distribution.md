# カテゴリカル分布

## 確率分布関数の定義域に関するパラメータ
$$
k \in \mathbb{N}
$$

特に $k=2$ の場合、ベルヌーイ分布と呼ぶ場合があります。

## 確率分布関数の値に関するパラメータ
$$
p_{1}, p_{2}, \dots, p_{k} \in [0, 1]
$$

ただし、

$$
\displaystyle{\sum_{i=1}^{k} p_{i} = 1}
$$

を満たすものとします。

## 確率分布関数
以下を満たす $f \colon \mathbb{N} \rightarrow [0, 1]$ を用いて、

$$
f(x) = 
\left\{
\begin{array}{ll}
p_{x} & (x \in \lbrace 1, 2, \dots, k \rbrace)\\
0 & (x \notin \lbrace 1, 2, \dots, k \rbrace)
\end{array}
\right.
$$

確率分布関数 $P \colon 2^{\mathbb{N}} \rightarrow [0, 1]$ は以下のようにあらわされます。

$$
P(\sigma_{X}) = \displaystyle{\sum_{x \in \sigma_{X}} f(x)}
$$
