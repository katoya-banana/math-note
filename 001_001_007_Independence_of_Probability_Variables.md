# 確率変数の独立

## 確率変数の独立
確率空間 $(S, \Sigma, \mu)$ が定義されているものとします。  

また、添え字集合 $\Lambda$ を用いて、可測空間の集合 $\lbrace (S_{\lambda}, \Sigma_{\lambda}) \rbrace_{\lambda \in \Lambda}$ と、確率変数の集合 $\lbrace X_{\lambda}  \rbrace_{\lambda \in \Lambda}$ と、確率分布関数の集合 $\lbrace P_{\lambda} \rbrace_{\lambda \in \Lambda}$ が与えられたとします。ただし、 $X_{\lambda}$ は $(\Sigma, \Sigma_{\lambda})$-可測な関数であり、 $P_{\lambda} \colon \Sigma_{\lambda} \rightarrow [0,1]$ です。

また、

$$
S_{X} = \displaystyle{\prod_{\lambda \in \Lambda} S_{\lambda}}
$$

$$
\Sigma_{X} = \lbrace \displaystyle{\prod_{\lambda \in \Lambda}} \sigma_{\lambda} \subseteq S_{X} \mid \sigma_{\lambda} \in \Sigma_{\lambda} \rbrace
$$

としたとき、 $(S_{X}, \Sigma_{X})$ は可測空間であり、これに対する確率変数 $X$ とそれに対する確率分布関数 $P$ を定義します。

このとき、$\Lambda$ の任意の有限部分集合 $\Lambda'$ について、

$$
\forall \sigma_{X} \in \lbrace \displaystyle{\prod_{\lambda \in \Lambda}} \sigma_{\lambda} \mid \sigma_{\lambda} \in \Sigma_{\lambda}, \lambda \notin \Lambda' \Leftrightarrow \sigma_{\lambda} = S_{\lambda} \rbrace, \ P(\sigma_{X}) = \displaystyle{\prod_{\lambda \in \Lambda'} P_{\lambda}(\sigma_{\lambda})}
$$

が成り立つとき、確率変数の集合 $\lbrace X_{\lambda} \rbrace _{\lambda \in \Lambda}$ が独立であるといいます。
