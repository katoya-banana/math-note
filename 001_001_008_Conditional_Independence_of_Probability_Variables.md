# 確率変数の条件付き独立

## 確率変数の条件付き独立（ $S$ の分割による定義）
確率空間 $(S, \Sigma, \mu)$ が定義されているものとします。  

また、添え字集合 $\Lambda$ を用いて、可測空間の集合 $\lbrace (S_{\lambda}, \Sigma_{\lambda}) \rbrace_{\lambda \in \Lambda}$ と、確率変数の集合 $\lbrace X_{\lambda} \rbrace_{\lambda \in \Lambda}$ が与えられており、さらに  $S$ の分割 $\Delta_{c}$ による条件付き確率分布関数の集合 $\lbrace P_{\lambda} \rbrace_{\lambda \in \Lambda}$ が与えられたとします。ただし、 $X_{\lambda}$ は $(\Sigma, \Sigma_{\lambda})$-可測な関数であり、 $P_{\lambda} \colon \Sigma_{\lambda} \times \Delta_{c} \rightarrow [0,1]$ です。

また、

$$
S_{X} = \displaystyle{\prod_{\lambda \in \Lambda} S_{\lambda}}
$$

$$
\Sigma_{X} = \lbrace \displaystyle{\prod_{\lambda \in \Lambda}} \sigma_{\lambda} \subseteq S_{X}  \mid \sigma_{\lambda} \in \Sigma_{\lambda} \rbrace
$$

としたとき、 $(S_{X}, \Sigma_{X})$ は可測空間であり、これに対する確率変数 $X$ と、それに対する $\Delta_{c}$ による条件付き確率分布関数 $P$ を定義します。

このとき、$\Lambda$ の任意の有限部分集合 $\Lambda'$ について、

$$
\forall \delta_{c} \in \Delta_{c}, \forall \sigma_{X} \in \lbrace \displaystyle{\prod_{\lambda \in \Lambda}} \sigma_{\lambda} \mid \sigma_{\lambda} \in \Sigma_{\lambda}, \lambda \notin \Lambda' \Leftrightarrow \sigma_{\lambda} = S_{\lambda} \rbrace, \ P(\sigma_{X}\mid\delta_{c}) = \displaystyle{\prod_{\lambda \in \Lambda'} P_{\lambda}(\sigma_{\lambda}\mid\delta_{c})}
$$

が成り立つとき、確率変数の集合 $\lbrace X_{\lambda} \rbrace_{\lambda \in \Lambda}$ が $\Sigma_{c}$ の下で条件付き独立であるといいます。


## 確率変数の条件付き独立（確率変数による定義）
添え字集合 $\Xi$ を用いて与えられる確率変数の集合 $\lbrace C_{\xi} \rbrace_{\xi \in \Xi}$ から誘導される $\sigma$ -加法族 $\Sigma_{c}$ について、確率変数の集合 $\lbrace X_{\lambda} \rbrace_{\lambda \in \Lambda}$ が $\Sigma_{c}$ の下で条件付き独立である場合、代わりに、確率変数の集合 $\lbrace X_{\lambda} \rbrace_{\lambda \in \Lambda}$ が確率変数の集合 $\lbrace C_{\xi} \rbrace_{\xi \in \Xi}$ の下で条件付き独立であるといいます。

任意の $\Sigma_{c}$ について、それを生成するような $S$ の分割 $\Delta$ が存在する点に注意してください。