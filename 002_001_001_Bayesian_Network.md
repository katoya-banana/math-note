# ベイジアンネットワーク

## 確率分布関数の近似
確率空間 $(S, \Sigma, \mu)$ 、有限個の可測空間 $(S_{1}, \Sigma_{1}), (S_{2}, \Sigma_{2}), \dots, (S_{n}, \Sigma_{n})$ と、有限個の確率変数 $X_{1}, X_{2}, \dots, X_{n}$ が定義されているものとします。また、確率分布関数 $P \colon \Sigma_{1} \times \Sigma_{2} \times \dots \times \Sigma_{n} \rightarrow [0, 1]$ が与えられているものとします。

このとき、 $P(\sigma_{1}, \sigma_{2}, \dots, \sigma_{n})$ を、 $n$ 個の条件付確率分布関数 $P_{k} \colon \Sigma_{k} \times \Delta_{k} \rightarrow [0,1] \ (k=1, 2, \dots, n)$ と、確率変数の集合 $C_k \subseteq \lbrace X_{1}, X_{2} \dots, X_{n} \rbrace \ (k=1, 2, \dots, n)$ を用いて、以下の式で近似することを考えます。

$$
\displaystyle{\prod_{k=1}^{n} P_{k}(\sigma_{k} \mid \bigcap_{X_{j} \in C_{k}} X_{j}^{-1}(\sigma_{j}) )}
$$

ただし、 $C_{k} = \emptyset$ のとき、 $ \displaystyle{\bigcap_{X_{j} \in C_{k}} X_{j}^{-1}(\sigma_{j}) = S} $ とします。

また、$C_{1}, C_{2}, \dots, C_{n}$ は、以下を満たすような $1, 2, \dots, n$ の順列 $A$ が存在するように取る必要があります。

$$
C_{k} \subseteq \lbrace X_{A_{i}} \mid\ i \in \mathbb{N}, 0 \lt i \lt k \rbrace 
$$

## グラフ構造
有向グラフ $G = (V, E)$ を考えます。ただし 

$$
V = \lbrace 1, 2, \dots, n \rbrace
$$

$$
E = \lbrace (i, j) \mid\ X_{j} \in C_{i} \rbrace
$$

$E$ の要素 $(i, j)$ は、 $i$ から $j$ に有向辺が張られていることを表します。 $C_{1}, C_{2}, \dots, C_{n}$ に成り立つ条件より、このグラフは、非巡回有向グラフになります。


## ベイジアンネットワーク
ある、非巡回有向グラフ $G = (V, E)$ と、その頂点数に等しい個数の、条件付確率分布関数 $P_{k} \colon \Sigma_{k} \times \Delta_{k} \rightarrow [0,1]$ の組を、ベイジアンネットワークと呼びます。

また、確率分布関数 $P \colon \Sigma_{1} \times \Sigma_{2} \times \dots \times \Sigma_{n} \rightarrow [0,1]$ が、上記の近似式によって誤差なく近似される場合、確率分布関数 $P$ がベイジアンネットワーク $(G, P_{1}, P_{2}, \dots, P_{n})$ に従うと言います。
