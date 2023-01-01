# 有向分離

## 有向分離
ある非巡回有向グラフ $G(V, E)$ において、頂点集合 $C \subseteq V$ が頂点集合の組 $A, B \subseteq V$ の有向分離であるとは、 $A, B, C$ が互いに素であることに加え、任意の頂点 $a \in A, b \in B$ において、以下がすべて成り立つことを指します。

* $a$ から $b$ または $b$ から $a$ の任意のパスにおいて、パス上の頂点集合（端点は除く） $R$ について 、 $R \cap C \neq \emptyset$ である。

* $a$ と $b$ に最小共通祖先 $l$ が存在する場合、 $l \in C$ である。

* 頂点 $d$ が $a$ の子孫かつ $b$ の子孫である場合、 $d \notin C$ である。

## 有向分離により与えられる条件付き独立な確率変数の組
有限個の確率変数 $X_{1}, X_{2}, \dots, X_{n}$ が存在し、確率分布関数 $P \colon \Sigma_{1} \times \Sigma_{2} \times \dots \times \Sigma_{n} \rightarrow [0,1]$ が、非巡回有向グラフ $G(V, E)$ と条件付確率 $P_{k} \colon \Sigma_{k} \times \Delta_{k} \rightarrow [0,1] \ (k=1, 2, \dots, n)$ により表現されるベイジアンネットワークに従うものとします。

このとき、 $C$ が $A, B$ の有向分離であるとき、任意の $a \in A, b \in B$ について、 $\lbrace X_{a}, X_{b} \rbrace$ は、 $\lbrace X_{c} \mid c \in C \rbrace$ 上で条件付き独立となります。
