# マルコフブランケット

## マルコフブランケット
ある非巡回有向グラフ $G(V, E)$ において、頂点集合 $M \subset V$ が、頂点 $a \in V$ に対するマルコフブランケットであるとは、以下が全て成り立つことを言います。

* 頂点 $m=a$ であるならば、 $m \notin M$

* 頂点 $m$ が $a$ の親であるならば、 $m \in M$

* 頂点 $m$ が $a$ の子であるならば、 $m \in M$

* 頂点 $m$ と $a$ が、共通の子を持つならば、 $m \in M$

* 頂点 $m$ が上記のいずれにも当てはまらなければ、 $m \notin M$



## マルコフブランケットにより与えられる条件付き独立な確率変数の組
有限個の確率変数 $X_{1}, X_{2}, \dots, X_{n}$ が存在し、確率分布関数 $P \colon \Sigma_{1} \times \Sigma_{2} \times \dots \times \Sigma_{n} \rightarrow [0,1]$ が、非巡回有向グラフ $G(V, E)$ と条件付確率 $P_{k} \colon \Sigma_{k} \times \Delta_{k} \rightarrow [0,1] \ (k=1, 2, \dots, n)$ により表現されるベイジアンネットワークに従うものとします。

頂点集合 $M \subset V$ が、頂点 $a \in V$ に対するマルコフブランケットであるとき、任意の $b \in V \backslash (M \cup \lbrace a \rbrace)$ について、 $\lbrace X_{a}, X_{b} \rbrace$ は、 $\lbrace X_{m} | m \in M \rbrace$ 上で条件付き独立となります。

なお、マルコフブランケット $M$ は $\lbrace a \rbrace,  V \backslash (M \cup \lbrace a \rbrace)$ の有向分離となります。

## マルコフブランケットの最小性
頂点集合 $C$ が $\lbrace a \rbrace, B$ の有向分離であるとき、$C$ の要素数 $\sharp(C)$ と、マルコフブランケット $M$ の要素数  $\sharp(M)$ について、以下が成り立ちます。

$$
\sharp(C) \geq \sharp(M)
$$