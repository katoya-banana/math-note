# ベイジアンネットワーク

## 確率分布関数の近似
確率空間 $(S, \Sigma, \mu)$ 、有限個の可測空間 $(S_{1}, \Sigma_{1}), (S_{2}, \Sigma_{2}), \dots, (S_{n}, \Sigma_{n})$ と、有限個の確率変数 $X_{1}, X_{2}, \dots, X_{n}$ が定義されているものとします。また、確率分布関数 $P \colon \Sigma_{1} \times \Sigma_{2} \times \dots \times \Sigma_{n} \rightarrow [0, 1]$ が与えられているものとします。

このとき、 $P(\sigma_{1}, \sigma_{2}, \dots, \sigma_{n})$ を、

$$
\displaystyle{\prod_{k=1}^{n} P_{k}(\sigma_{k} | \bigcap_{j \in C_{k}} X_{j}^{-1}(\sigma_{j}) )}
$$

で近似することを考えます。

ただし、 $C_{k} = \emptyset$ のとき、

$$
\displaystyle{\bigcap_{j \in C_{k}} X_{j}^{-1}(\sigma_{j}) = S}
$$

であるものとします。

また、$C_{k}$ は、以下を満たすような $1, 2, \dots, n$ の順列 $A$ が存在するように取る必要があります。

$$
C_{k} \subseteq \lbrace A_i | i = 1, 2, \dots, k-1 \rbrace 
$$

## グラフ構造
$1, 2, \dots, n$ の番号のついた $n$ 個の頂点を持ち、 $i \in C_{k}$ の場合、 $k$ から $i$ に有向辺を持つグラフを考えます。  

このグラフは、DAG になります。

