# 確率密度関数

## 確率密度関数

確率空間 $(S, \Sigma, \mu)$ および、可測空間 $(S_{X}, \Sigma_{X})$ 上に、確率変数 $X$ が定義されているものとします。  
また、可測空間 $(S_{X}, \Sigma_{X})$ 上にも、測度 $\lambda$ が定義されているものとします。   

確率分布関数 $P \colon \Sigma_{X} \rightarrow [0, 1]$ が存在するとき、以下を満たすような $f \colon S_{X} \rightarrow [0, \infty]$ を確率密度関数と呼びます。

$$
\forall \sigma_{X} \in \Sigma_{X}, P(\sigma_{X}) = \displaystyle{\int_{\sigma_{X}} f\ d\lambda}
$$


## 確率密度関数の一意性について

ある関数 $f, g$ が上記の条件を満たすとき、$f$ と $g$ はほとんどいたるところで一致します。  
任意の $s_{X} \in S_{X}$ で $f(s_{X}) = g(s_{X})$ が成り立つとは限らない点に注意してください。