# 共役事前分布

## 共役事前分布
確率変数 $X_{\Theta} \colon S \rightarrow \Theta$ に対し、パラメータ $\xi \in \Xi$ で特徴づけられる $X_{\Theta}$ の確率分布関数 $P_{\xi} \colon \Sigma_{\Theta} \rightarrow [0, 1]$ または、パラメータ $\xi \in \Xi$ で特徴づけられる $X_{\Theta}$ 確率密度関数 $f_{\xi} \colon \Theta \rightarrow [0, \infty]$ が定義されているものとします。

このとき、パラメータ $\theta \in \Theta$ によって特徴づけられる尤度関数 $L_{\theta} \colon D \rightarrow [0, \infty]$ に対し、任意の観測値 $d \in D$ において、ベイズ推定により得られる $\Theta$ の確率分布関数 $P^{*}_{\xi}$ または $\Theta$ の確率密度関数 $f^{*}_{\xi}$ について、

$$
P_{\xi^{*}} = P^{*}_{\xi}
$$

または

$$
f_{\xi^{*}} = f^{*}_{\xi}
$$

を与えるような、 $\xi^{*} \in \Xi$ が存在するとき、 $P_{\xi}$ または $f_{\xi}$ のことを $L_{\theta}$ に対する共役事前分布と呼びます。
