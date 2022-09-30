# 確率密度関数による確率空間の特徴づけ

## 確率密度関数による確率空間の特徴づけ

可測空間 $(S, \Sigma)$ および、可測空間 $(S_{X}, \Sigma_{X})$ が存在し、可測関数 $X \colon S \rightarrow S_{X}$ が定義されているものとします。  
また、可測空間 $(S_{X}, \Sigma_{X})$ 上には、測度 $\lambda$ が定義されているものとします。   

このとき、ある関数 $f \colon S_{X} \rightarrow [0, \infty]$ が存在し、

$$
\displaystyle{\int_{S_{X}} f\ d\lambda} = 1
$$

を満たす場合、  
以下を満たすような関数 $\mu \colon \Sigma \rightarrow [0, 1]$ および $P \colon \Sigma_{X} \rightarrow [0, 1]$ を定義できます。  

$$
P(\sigma_{X}) = \mu(X^{-1}(\sigma_{X})) = \displaystyle{\int_{\sigma_{X}\in \Sigma_{X}} f\ d\lambda}
$$

定義域の性質上、$f$ により $P$ は一意に定まりますが、$\mu$ は定まらない点に注意してください。

このとき、$\mu$ を可測空間 $(S, \Sigma)$ の測度となるように定義すると、$\mu$ は 可測空間 $(S, \Sigma)$ の確率測度となり、$X$ は確率変数となり、$P$ は $X$ の確率分布関数となります。

