# 確率変数の独立

## 確率変数の独立
確率空間 $(S, \Sigma, \mu)$ が定義されているものとします。  

また、添え字集合 $\Lambda$ を用いて、可測空間の集合 $\lbrace (S_{\lambda}, \Sigma_{\lambda}) \rbrace_{\lambda \in \Lambda}$ と、確率変数の集合 $\lbrace X_{\lambda} \rbrace_{\lambda \in \Lambda} $ と、確率分布関数の集合 $\lbrace P_{\lambda} \rbrace_{\lambda \in \Lambda}$ が与えられたとします。ただし、$X_{\lambda}$ は $(\Sigma, \Sigma_{\lambda})$-可測な関数であり、 $P_{\lambda} \colon \Sigma_{\lambda} \rightarrow [0,1]$ です。

任意の相違なる有限個の $\Lambda$ の元 $\lambda_{1}, \lambda_{2}, \dots, \lambda_{n}$ について、

$$
\sigma_{\lambda_{i}} \in \Sigma_{\lambda_{i}} \ (i = 1, 2, \dots, n) \Rightarrow
P(\sigma_{\lambda_{1}}, \sigma_{\lambda_{2}}, \dots, \sigma_{\lambda_{n}}) = \displaystyle{\prod_{i=1}^{n} P_{\lambda_{i}}(\sigma_{\lambda_{i}})}
$$

が成り立つとき、確率変数の集合 $\lbrace X_{\lambda} \rbrace _{\lambda \in \Lambda}$ が独立であるといいます。

ただし、関数 $P$ は確率変数 $\overrightarrow{X} = (X_{\lambda_{1}}, X_{\lambda_{2}}, \dots, X_{\lambda_{n}})$ に対する確率分布関数 $P \colon \Sigma_{\lambda_{1}} \times \Sigma_{\lambda_{2}} \times \dots \times \Sigma_{\lambda_{n}} \rightarrow [0, 1]$ です。