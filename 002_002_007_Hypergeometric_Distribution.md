# 超幾何分布

## 確率分布関数の値に関するパラメータ
$$
n, K, N \in \mathbb{N}
$$

ただし、
$$
n \leq N, k \leq N
$$
を満たすものとします。

## 確率分布関数
以下を満たす $f \colon \mathbb{N} \rightarrow [0, 1]$ を用いて、

$$
f(x) = 
\left\{
\begin{array}{ll}
\frac{K!}{x!(K-x)!} \times \frac{(N-K)!}{(n-x)! (N-K-n+x)!} \times \frac{(N-n)! n!}{N!} & (\max(0, n-(N-K)) \leq x \leq \min(K, n) )\\
0 & (\text{otherwise})
\end{array}
\right.

$$

確率分布関数 $P \colon 2^{\mathbb{N}} \rightarrow [0, 1]$ は以下のようにあらわされます。

$$
P(\sigma_{X}) = \displaystyle{\sum_{x \in \sigma_{X}}} f(x)
$$
