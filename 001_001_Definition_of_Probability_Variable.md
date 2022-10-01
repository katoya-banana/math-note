# 確率変数の定義

## 確率変数

確率空間 $(S, \Sigma, \mu)$ および、可測空間 $(S_{X}, \Sigma_{X})$ に対し、ある $(\Sigma, \Sigma_{X})$-可測な関数 $X \colon S \rightarrow S_{X}$ が与えられたとき、 $X$ を確率変数とよびます。  
$X$ が $(\Sigma, \Sigma_{X})$-可測であるため、以下が成り立ちます。

$$
\sigma_{X} \in \Sigma_{X} \Rightarrow \{s| s \in S, X(s) \in \sigma_{X} \} \in \Sigma
$$

このとき逆像 $X^{-1} \colon \Sigma_{X} \rightarrow \Sigma$ を、

$$
X^{-1}(\sigma_{X}) = \{s| s \in S, X(s) \in \sigma_{X} \}
$$

と定義します。逆像は逆関数とは異なり、定義域と値域にそれぞれの $\sigma$ 加法族をとる点に注意してください。
