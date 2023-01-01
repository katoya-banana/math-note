# 正規逆ウィシャート分布

## 確率分布関数の定義域に関するパラメータ
$$
k \in \mathbb{N}
$$

特に $k=1$ の場合、正規逆ガンマ分布と呼ぶ場合があります。

## 確率分布関数の値に関するパラメータ
$$
\overrightarrow{\mu_0} \in \mathbb{R}^{k}
$$

$$
\lambda \in (0, \infty)
$$

$$
\Psi \in \mathbb{R}^{k \times k}
$$

$$
\nu \in (D-1, \infty)
$$

ただし、 $\Psi$ は正定値行列であるものとします。  

## 確率密度関数
確率密度関数 $f \colon \mathbb{R}^{k} \times \mathbb{R}^{k \times k} \rightarrow [0, \infty)$ は以下のようにあらわされます。

$$
f(\overrightarrow{\mu}, V) = \frac{1}{\sqrt{2\pi}^{k}} \frac{\sqrt{\lambda}^{k}}{ \sqrt{\|V\|}} e^{- \frac{\lambda}{2} (\overrightarrow{x} - \overrightarrow{\mu})^{T} V^{-1} (\overrightarrow{x} - \overrightarrow{\mu})} \frac{\sqrt{\|\Psi\|}^\nu}{\Gamma_{k}(\frac{\nu}{2}) \sqrt{2}^{\nu k} \sqrt{V}^{\frac{\nu + k + 1}{2}}} e^{― \frac{1}{2} Tr(\Psi V^{-1})}
$$

ただし、 $Tr$ は行列のトレースを返す関数、 $\Gamma_{k}$ は多変量ガンマ関数である点に注意してください。