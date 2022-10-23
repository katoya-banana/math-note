# 多項分布

## 確率分布関数の定義域に関するパラメータ
$$
k \in \mathbb{N}
$$

特に $k=2$ の場合、二項分布と呼ぶ場合があります。

## 確率分布関数の値に関するパラメータ
$$
n \in \mathbb{N} \\
p_{1}, p_{2}, \dots, p_{k} \in [0, 1]
$$

ただし、

$$
\displaystyle{\sum_{i=1}^{k} p_{i} = 1}
$$

を満たすものとします。

## 確率分布関数
以下を満たす $f \colon \mathbb{N}^{k} \rightarrow [0, 1]$ を用いて、

$$
f(x_{1}, x_{2}, \dots, x_{k}) = 
\left\{
\begin{array}{ll}
\frac{n!}{\displaystyle{\prod_{i=1}^{k} x_{i}! }} \times \displaystyle{\prod_{i=1}^{k} p_{i}^{x_{i}}} & (\displaystyle{\sum_{i=1}^{k} x_{i} = n})\\
0 & (\displaystyle{\sum_{i=1}^{k} x_{i} \neq n})
\end{array}
\right.
$$

確率分布関数 $P \colon (2^{\mathbb{N}})^{k} \rightarrow [0, 1]$ は以下のようにあらわされます。

$$
P(\sigma_{1}, \sigma_{2}, \dots, \sigma_{k}) = \displaystyle{\sum_{x_{1} \in \sigma_{1}}\sum_{x_{2} \in \sigma_{2}} \dots \sum_{x_{k} \in \sigma_{k}} f(x_{1}, x_{2}, \dots, x_{k})}
$$
