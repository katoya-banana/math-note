# 確率変数の条件付き独立

## 確率変数の条件付き独立（ $S$ の分割による定義）
確率空間 $(S, \Sigma, \mu)$ が定義されているものとします。  

また、添え字集合 $\Lambda$ を用いて、可測空間の集合 $\lbrace (S_{\lambda}, \Sigma_{\lambda}) \rbrace_{\lambda \in \Lambda}$ と、確率変数の集合 $\lbrace X_{\lambda} \rbrace_{\lambda \in \Lambda}$ が与えられており、さらに  $S$ の分割 $\Delta_{c}$ による条件付き確率分布関数の集合 $\lbrace P_{\lambda} \rbrace_{\lambda \in \Lambda}$ が与えられたとします。ただし、 $X_{\lambda}$ は $(\Sigma, \Sigma_{\lambda})$-可測な関数であり、 $P_{\lambda} \colon \Sigma_{\lambda} \times \Delta_{c} \rightarrow [0,1]$ です。

任意の相違なる有限個の $\Lambda$ の元 $\lambda_{1}, \lambda_{2}, \dots, \lambda_{n}$ について、

$$
\delta_{c} \in \Delta_{c},\ \sigma_{\lambda_{i}} \in \Sigma_{\lambda_{i}} \ (i = 1, 2, \dots, n) \Rightarrow
P(\sigma_{\lambda_{1}}, \sigma_{\lambda_{2}}, \dots, \sigma_{\lambda_{n}}|\delta_{c}) = \displaystyle{\prod_{i=1}^{n} P_{\lambda_{i}}(\sigma_{\lambda_{i}}|\delta_{c})}
$$

が成り立つとき、確率変数の集合 $\lbrace X_{\lambda} \rbrace_{\lambda \in \Lambda}$ が $\Sigma_{c}$ の下で条件付き独立であるといいます。

ただし、関数 $P$ は確率変数 $\overrightarrow{X} = (X_{\lambda_{1}}, X_{\lambda_{2}}, \dots, X_{\lambda_{n}})$ に対する $\Delta_{c}$ による条件付き確率分布関数 $P \colon \Sigma_{\lambda_{1}} \times \Sigma_{\lambda_{2}} \times \dots \times \Sigma_{\lambda_{n}} \times \Delta_{c} \rightarrow [0, 1]$ です。

## 確率変数の条件付き独立（確率変数による定義）
添え字集合 $\Xi$ を用いて与えられる確率変数の集合 $\lbrace C_{\xi} \rbrace_{\xi \in \Xi}$ から誘導される $\sigma$ -加法族 $\Sigma_{c}$ について、確率変数の集合 $\lbrace X_{\lambda} \rbrace_{\lambda \in \Lambda}$ が $\Sigma_{c}$ の下で条件付き独立である場合、代わりに、確率変数の集合 $\lbrace X_{\lambda} \rbrace_{\lambda \in \Lambda}$ が確率変数の集合 $\lbrace C_{\xi} \rbrace_{\xi \in \Xi}$ の下で条件付き独立であるといいます。

任意の $\Sigma_{c}$ について、それを生成するような $S$ の分割 $\Delta$ が存在する点に注意してください。