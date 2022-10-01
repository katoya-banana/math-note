# ベイズの定理

## ベイズの定理
確率空間 $(S, \Sigma, \mu)$ および、可測空間 $(S_{X}, \Sigma_{X})$ 上に、確率変数 $X$ が定義されているものとします。  

このとき、任意の $\sigma_{x, 1}, \sigma_{x, 2} \in \Sigma_{X}$ について以下が成り立ちます。

$$
P(\sigma_{x, 2}|b_{1}) P(\sigma_{x, 1}) = P(\sigma_{x, 1}|b_{2}) P(\sigma_{x, 2})
$$

確率分布関数 $P \colon \Sigma_{X} \rightarrow [0,1]$ と、 $\Sigma_{1}$ 上の条件付き確率分布関数 $P \colon \Sigma_{X} \times B_{1} \rightarrow [0,1]$ と、 $\Sigma_{2}$ 上の条件付き確率分布関数 $P \colon \Sigma_{X} \times B_{2} \rightarrow [0,1]$ が混在している点に注意してください。

ただし、

$$
b_{1} = X^{-1}(\sigma_{x, 1})
$$

$$
B_{1} = \{b_{1}, S \backslash b_{1}\}
$$

$$
b_{2} = X^{-1}(\sigma_{x, 2})
$$

$$
B_{2} = \{b_{2}, S \backslash b_{2}\}
$$

であり、 $\Sigma_{1}$ は $b_{1}$ から生成される $\sigma$ -加法族、 $\Sigma_{2}$ は $b_{2}$ から生成される $\sigma$ -加法族です。


