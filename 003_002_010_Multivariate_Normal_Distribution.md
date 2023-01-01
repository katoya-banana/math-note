# 多変量正規分布

## 確率分布関数の定義域に関するパラメータ
$$
k \in \mathbb{N}
$$

特に $k=1$ の場合、正規分布と呼ぶ場合があります。

## 確率分布関数の値に関するパラメータ
$$
\overrightarrow{\mu} \in \mathbb{R}^{k}
$$

$$
V \in \mathbb{R}^{k \times k}
$$

ただし、 $V$ は正定値行列であるものとします。  
多変量正規分布を定義する際には、 $V$ の条件として半正定値行列であることのみを課す場合もあるのですが、後述の確率密度関数を定義するため、今回は正定値行列であることを仮定しています。

## 確率密度関数
確率密度関数 $f \colon \mathbb{R}^{k} \rightarrow [0, \infty)$ は以下のようにあらわされます。

$$
f(\overrightarrow{x}) = \frac{1}{\sqrt{2\pi}^{k}} \frac{1}{ \sqrt{\|V\|}} e^{- \frac{1}{2} (\overrightarrow{x} - \overrightarrow{\mu})^{T} V^{-1} (\overrightarrow{x} - \overrightarrow{\mu})}
$$