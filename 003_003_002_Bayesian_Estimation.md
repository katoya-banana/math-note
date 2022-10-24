# ベイズ推定

## ベイズ推定
確率変数 $X_{\Theta} \colon S \rightarrow \Theta$ と、その確率分布関数 $P \colon \Sigma_{\Theta} \rightarrow [0, 1]$ または、確率密度関数 $f \colon \Theta \rightarrow [0, \infty]$ が定義されているものとします。

このとき、パラメータ $\theta \in \Theta$ によって特徴づけられる尤度関数 $L_{\theta} \colon D \rightarrow [0, \infty]$ と、観測値 $d \in D$ が与えられたときに、

$$
P'(X_{\Theta} = \theta) = \frac{L_{\theta}(d) P(X_{\Theta} = \theta)}{\displaystyle{\int_{\Theta} L_{\theta}(d) P(X_{\Theta} = \theta) \ d \mu_{\theta}}}
$$

または

$$
f'(\theta) = \frac{L_{\theta}(d) f(\theta)}{\displaystyle{\int_{\Theta} L_{\theta}(d) f(\theta) \ d \mu_{\theta}}}
$$


として、関数 $P' \colon \Sigma_{\Theta} \rightarrow [0, 1]$ または、関数 $f' \colon \Theta \rightarrow [0, \infty]$ を得る操作を、ベイズ推定と呼びます。

このようにして得られる $P'$ は $X_{\Theta}$ の確率分布関数、$f'$ は $X_{\Theta}$ の確率密度関数となる条件を満たしていることに注意してください。