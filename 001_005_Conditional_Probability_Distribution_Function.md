# 条件付き確率分布関数

## 条件付き確率分布関数
確率空間 $(S, \Sigma, \mu)$ および、可測空間 $(S_{X}, \Sigma_{X})$ 上に、確率変数 $X$ が定義されているものとします。また、 $\Sigma$ の部分 $\sigma$ -加法族 $\Sigma_{c}$ に対し、 $(S, \Sigma_{c})$ の確率測度 $\mu_{c}$ を、任意の $\sigma_{c} \in \Sigma_{c}$ について、 $\mu_{c}(\sigma_{c}) = \mu(\sigma_{c})$ を満たすようにとります。

このとき、任意の $\sigma_{c} \in \Sigma_{c}$ と $\sigma_{X} \in \Sigma_{X}$ について、

$$
\mu(\sigma_{c} \ \cap \ X^{-1}(\sigma_{X})) = \displaystyle{\int_{\sigma_{c}} f_{\sigma_{x}} \ d\mu_{c} }
$$

を満たすような $(\Sigma_{c}, \mathfrak{B}_{[0,1]})$-可測な関数 $f_{\sigma_{x}} \colon S \rightarrow [0,1]$ が存在します。

$B_{c} = \{\sigma_{c}|\sigma_{c} \in \Sigma_{c}, \forall \sigma_{c}' \subset \sigma_{c}, \sigma_{c}' = \emptyset \}$ とおくと、

$$
\forall b_{c} \in B_{c}, \forall s_{1}, s_{2} \in b_{c}, f_{\sigma_{x}}(s_{1}) = f_{\sigma_{x}}(s_{2})
$$ 

となることに注意してください。

このとき、以下を満たすような関数 $P \colon \Sigma_{X} \times B_{c} \rightarrow [0,1]$ を、$X$ の $\Sigma_{c}$ 上の条件付き確率分布関数と呼びます。

$$
\exist s \in b_{c},\ P(\sigma_{x}|b_{c}) = f_{\sigma_{x}}(s)
$$

等式の右辺の値が $s$ の取り方によらないことに注意してください。
