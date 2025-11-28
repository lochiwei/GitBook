# 🔰 射影向量的矩陣表示法

[線性代數](../../) ⟩ [向量](../) ⟩ [射影向量](./) ⟩ 矩陣表示法&#x20;

{% hint style="success" %}
$$\text{proj}_{\vec{v}}(\vec{u}) = T (\vec{u})$$ 是一種<mark style="color:yellow;">**線性變換**</mark>，其中：

$$T = \dfrac{1}{\|v\|²} \begin{bmatrix} v_x^2 & v_x v_y & v_x v_z \\  v_y v_x & v_y^2 & v_y v_z \\  v_z v_x & v_z v_y & v_z^2  \end{bmatrix}$$
{% endhint %}

{% tabs %}
{% tab title="⭐️ 重點" %}
{% hint style="info" %}
透過[射影向量](./)，可以將[**向量分解**](../decomp/perp/)成兩個<mark style="color:yellow;">**互相垂直**</mark>的向量。
{% endhint %}
{% endtab %}

{% tab title="🎖 證明" %}
若將 $$\vec{u},\vec{v}$$ 表示為<mark style="color:yellow;">**行向量**</mark>，因為[內積](../op/dot/)可表示為[矩陣乘法](../../matrix/op/mult/)，所以[射影向量](./)也可表示為[矩陣乘法](../../matrix/op/mult/)：

$$(\vec{u}\cdot\vec{v})\vec{v}= \overbrace{ \underbrace{\vec{v}}_{(n\times 1\text{) }}\underbrace{\vec{v}^T\vec{u}}_{(1\times 1\text{, dot product)}} }^{\text{matrix multiplication}} = \vec{v}\vec{v}^T\vec{u} = \begin{bmatrix} v_x^2 & v_x v_y & v_x v_z \\  v_y v_x & v_y^2 & v_y v_z \\  v_z v_x & v_z v_y & v_z^2  \end{bmatrix} \begin{bmatrix}u_x \\ u_y \\ u_z\end{bmatrix}$$
{% endtab %}

{% tab title="⬇️ 應用" %}
* [垂直分解的矩陣表示法](../decomp/perp/decomp-in-matrix.md)
{% endtab %}

{% tab title="👥 相關" %}
* [矩陣乘法](../../matrix/op/mult/)
* <mark style="color:purple;">**射影向量**</mark>是一種[線性變換](../../space/transform/)。
{% endtab %}

{% tab title="📗 參考" %}
* Mathematics for 3D Game Programming & Computer Graphics (2nd Edition, 2004)
{% endtab %}
{% endtabs %}
