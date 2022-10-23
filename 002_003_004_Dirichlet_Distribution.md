# ディリクレ分布

## 確率分布関数の定義域に関するパラメータ
$$
k \in \mathbb{N}
$$

特に $k=2$ の場合、ベータ分布と呼ぶ場合があります。

## 確率分布関数の値に関するパラメータ
$$
\alpha_{1}, \alpha_{2}, \dots, \alpha_{k} \in [0, \infty)
$$

## 確率密度関数
確率密度関数 $f \colon [0,1]^{k} \rightarrow [0, \infty)$ は以下のようにあらわされます。

$$
f(x_{1}, x_{2}, \dots, x_{k}) = 
\left\{
\begin{array}{ll}
\frac{\Gamma(\displaystyle{\sum_{i=1}^{k} \alpha_{i}})}{\displaystyle{\prod_{i=1}^{k}\Gamma(\alpha_{i})}} \times \displaystyle{\prod_{i=1}^{k} x_{i}^{\alpha_{i}}} & (\displaystyle{\sum_{i=1}^{k} x_{i} = 1})\\
0 & (\displaystyle{\sum_{i=1}^{k} x_{i} \neq 1})
\end{array}
\right.
$$