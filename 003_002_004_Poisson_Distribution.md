# ポアソン分布

## 確率分布関数の値に関するパラメータ
$$
\lambda \in [0, \infty)
$$

## 確率分布関数
以下を満たす $f \colon \mathbb{N} \rightarrow [0, 1]$ を用いて、

$$
f(x) = \frac{\lambda ^{x} e^{- \lambda}}{x!}
$$

確率分布関数 $P \colon 2^{\mathbb{N}} \rightarrow [0, 1]$ は以下のようにあらわされます。

$$
P(\sigma_{X}) = \displaystyle{\sum_{x \in \sigma_{X}} f(x)}
$$
