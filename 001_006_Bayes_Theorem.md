# ベイズの定理

## ベイズの定理
条件付き確率に関して、 $P(\sigma_{X_{1}}) \neq 0$ かつ $P(\sigma_{X_{2}}) \neq 0$ であるとき  

$$
P(\sigma_{X_{1}} | \sigma_{X_{2}}) = \frac{P(\sigma_{X_{1}} \cap \sigma_{X_{2}})}{P(\sigma_{X_{2}})}
$$

$$
P(\sigma_{X_{2}} | \sigma_{X_{1}}) = \frac{P(\sigma_{X_{2}} \cap \sigma_{X_{1}})}{P(\sigma_{X_{1}})}
$$

が成り立ちます。

$\sigma_{X_{1}} \cap \sigma_{X_{2}} = \sigma_{X_{2}} \cap \sigma_{X_{1}}$ のため、式から $P(\sigma_{X_{1}} \cap \sigma_{X_{2}})$ を削除することで

$$
P(\sigma_{X_{1}} | \sigma_{X_{2}}) = \frac{P(\sigma_{X_{2}} | \sigma_{X_{1}}) P(\sigma_{X_{1}})}{P(\sigma_{X_{2}})} 
$$

を得ます。この等式が成り立つことをベイズの定理とよびます。
