# 尤度関数

## 尤度関数
添え字 $\theta \in \Theta$ によって特徴づけられる関数 $L_{\theta} \colon D \rightarrow [0, \infty]$ を尤度関数と呼びます。

尤度関数は、追加で以下の条件を満たす必要がある場合があります。

* $\Theta$ に関する測度空間 $(\Theta, \Sigma_{\Theta}, \mu_{\Theta})$ が定義されていること。

* 任意の $d \in D$ について、以下が成り立つこと。

$$
\displaystyle{\int_{\Theta} L_{\theta}(d) \ d \mu_{\Theta}} \lt \infty
$$