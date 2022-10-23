# ベータ二項分布

## 確率分布関数の値に関するパラメータ
$$
n \in \mathbb{N}\\
\alpha, \beta \in [0, \infty)
$$

## 確率分布関数
以下を満たす $f \colon \mathbb{N} \rightarrow [0, 1]$ を用いて、

$$
f(x) = 
\left\{
\begin{array}{ll}
\frac{n!}{x! (n-x)!} \times \frac{\Gamma(x+\alpha) \Gamma(n-x+\beta)}{\Gamma(x+\alpha+\beta)} \times \frac{\Gamma(\alpha + \beta)}{\Gamma(\alpha) \Gamma(\beta)} & (0 \leq x \leq n)\\
0 & (\text{otherwise})
\end{array}
\right.
$$

確率分布関数 $P \colon (2^{\mathbb{N}})^{k} \rightarrow [0, 1]$ は以下のようにあらわされます。

$$
P(\sigma_{X}) = \displaystyle{\sum_{x \in \sigma_{X}} f(x)}
$$
