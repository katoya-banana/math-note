# ベイズの定理

## ベイズの定理
確率空間 $(S, \Sigma, \mu)$ および、可測空間 $(S_{X}, \Sigma_{X})$ 上に、確率変数 $X$ および $X$ の確率分布関数 $P \colon \Sigma_{X} \rightarrow [0, 1]$ が定義されているものとします。

このとき、任意の $\sigma_{X, 1}, \sigma_{X, 2} \in \Sigma_{X}$ について以下が成り立ちます。

$$
X^{-1}(\sigma_{X, 1}) = \delta_{1}
$$

$$
X^{-1}(\sigma_{X, 2}) = \delta_{2}
$$

とし、  

$S$ の分割 

$$
\Delta_{1} = \lbrace \delta_{1}, S \backslash \delta_{1} \rbrace
$$

$$
\Delta_{2} = \lbrace \delta_{2}, S \backslash \delta_{2} \rbrace
$$

によって定義される、条件付確率  $P_{1} \colon \Sigma_{X} \times \Delta_{1} \rightarrow [0, 1], P_{2} \colon \Sigma_{X} \times \Delta_{2} \rightarrow [0, 1]$ について、

$$
P_{1}(\sigma_{X, 2}\mid\delta_{1}) P(\sigma_{X, 1}) = P_{2}(\sigma_{X, 1}\mid\delta_{2}) P(\sigma_{X, 2})
$$

