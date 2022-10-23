# MAP 推定

## MAP 推定
確率変数 $X_{\Theta} \colon S \rightarrow \Theta$ と、その確率分布関数 $P \colon \Sigma_{\Theta} \rightarrow [0, 1]$ または、確率密度関数 $f \colon \Theta \rightarrow [0, \infty]$ が定義されているものとします。

このとき、パラメータ $\theta \in \Theta$ によって特徴づけられる尤度関数 $L_{\theta} \colon D \rightarrow [0, \infty]$ と、観測値 $d \in D$ が与えられたときに、

$$
\Theta ' = \displaystyle{\argmax_{\theta \in \Theta} L_{\theta}(d) P(X_{\Theta} = \theta)}
$$

または

$$
\Theta ' = \displaystyle{\argmax_{\theta \in \Theta} L_{\theta}(d)} f(\theta)
$$


として、 $\Theta$ の部分集合 $\Theta'$ を得る操作を、MAP 推定と呼びます。
