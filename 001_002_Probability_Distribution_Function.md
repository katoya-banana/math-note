# 確率分布関数

## 確率分布関数

確率空間 $(S, \Sigma, \mu)$ および、可測空間 $(S_{X}, \Sigma_{X})$ 上に、確率変数 $X$ が定義されているものとします。   
このとき、以下で定義される関数 $P \colon \Sigma_{X} \rightarrow [0, 1]$ を、 $X$ の確率分布関数とよびます。  

$$
P(\sigma_{X}) = \mu(X^{-1}(\sigma_{X})) = \mu(\{s| s \in S, X(s) \in \sigma_{X} \})
$$

## 省略記法
ある論理式 $\phi(x)$ が存在し、

$$
P(\phi(X)) = \mu(\{s| s \in S, \phi(X(s)) \})
$$

と書くことにします。

例えば、 $\phi(x) \Leftrightarrow x \geq 0$ のとき、 $P(X \geq 0)$ などと書いたります。
