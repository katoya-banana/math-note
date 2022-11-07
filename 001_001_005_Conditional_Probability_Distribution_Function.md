# 条件付き確率分布関数

## 条件付き確率分布関数
確率空間 $(S, \Sigma, \mu)$ および、可測空間 $(S_{X}, \Sigma_{X})$ 上に、確率変数 $X$ が定義されているものとします。また、 $S$ のある分割 $\Delta_{c}$ によっ生成導される $\sigma$ -加法族 $\Sigma_c$ について、可測空間 $(S, \Sigma_{c})$ の確率測度 $\mu_{c}$ を、任意の $\sigma_{c} \in \Sigma_{c}$ について、 $\mu_{c}(\sigma_{c}) = \mu(\sigma_{c})$ を満たすようにとります。

このとき、任意の $\sigma_{c} \in \Sigma_{c}$ と $\sigma_{X} \in \Sigma_{X}$ について、

$$
\mu(\sigma_{c} \ \cap \ X^{-1}(\sigma_{X})) = \displaystyle{\int_{\sigma_{c}} f_{\sigma_{X}} \ d\mu_{c} }
$$

を満たすような $(\Sigma_{c}, \mathfrak{B_{[0,1]}})$ -可測な関数 $f_{\sigma_{X}} \colon S \rightarrow [0,1]$ が存在します。

このとき、以下を満たすような関数 $P \colon \Sigma_{X} \times \Delta_{c} \rightarrow [0,1]$ を、 $X$ の $\Sigma_{c}$ 上の条件付き確率分布関数と呼びます。

$$
\exists s \in \delta_{c} \in \Delta_{c},\ P(\sigma_{X}|\delta_{c}) = f_{\sigma_{X}}(s)
$$

等式の右辺の値が $s$ の取り方によらないことに注意してください。
