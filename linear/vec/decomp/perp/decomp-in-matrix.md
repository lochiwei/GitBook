# 🔰 向量垂直分解矩陣

[線性代數](../../../) ⟩ [向量](../../) ⟩ [射影向量](../../proj/) ⟩ 向量垂直分解矩陣&#x20;

{% hint style="success" %}
* 向量 $$\mathbf{u}$$ 可<mark style="color:yellow;">**分解**</mark>成「沿著 $$\mathbf{v}$$ 向量」與「<mark style="color:yellow;">**垂直**</mark> $$\mathbf{v}$$ 向量」的兩個分量：$$\mathbf{u} = \text{proj}_{\mathbf{v}}(\mathbf{u}) + \text{perp}_{\mathbf{v}}(\mathbf{u})$$
* 其中：\
  $$\text{proj}_{\mathbf{v}}(\mathbf{u}) = \left(\dfrac{\mathbf{u}\cdot\mathbf{v}}{\mathbf{v}\cdot\mathbf{v}}\right)\mathbf{v} =  \mathbf{Au}$$ \
  $$\text{perp}_{\mathbf{v}}(\mathbf{u}) = \mathbf{u} - \left(\dfrac{\mathbf{u}\cdot\mathbf{v}}{\mathbf{v}\cdot\mathbf{v}}\right)\mathbf{v} = \mathbf{Bu}$$\
  $$\mathbf{A}  = \dfrac{1}{\|\mathbf{v}\|²}  \begin{bmatrix}    v_1^2 & v_1 v_2 & v_1 v_3 \\      v_2 v_1 & v_2^2 & v_2 v_3 \\     v_3 v_1 & v_3 v_2 & v_3^2   \end{bmatrix}   =  \begin{bmatrix}    \dfrac{v_1\mathbf{v}}{\|\mathbf{v}\|²}  &     \dfrac{v_2 \mathbf{v}}{\|\mathbf{v}\|²} &    \dfrac{v_3 \mathbf{v}}{\|\mathbf{v}\|²}  \end{bmatrix}$$ ([證明](../../proj/matrix.md))\
  $$\mathbf{B}  = \dfrac{1}{\|\mathbf{v}\|²}   \begin{bmatrix}       v_2^2 + v_3^2 & -v_1 v_2       & -v_1 v_3 \\       -v_2 v_1      & v_1^2 + v_3^2 & -v_2 v_3 \\      -v_3 v_1      & -v_3 v_2       & v_1^2 + v_2^2   \end{bmatrix}$$
{% endhint %}

{% tabs %}
{% tab title="⭐️ 重點" %}
{% hint style="success" %}
如果我們知道 $$\text{proj}_{\mathbf{v}}(\mathbf{u})$$ 是一個[線性變換](../../../space/transform/)，就可以推導出：

* $$\text{proj}_{\mathbf{v}}(\mathbf{u})  =  \begin{bmatrix}    \dfrac{v_1\mathbf{v}}{\|\mathbf{v}\|²}  &     \dfrac{v_2 \mathbf{v}}{\|\mathbf{v}\|²} &    \dfrac{v_3 \mathbf{v}}{\|\mathbf{v}\|²}  \end{bmatrix}  \mathbf{u}$$

因為此線性變換的<mark style="color:yellow;">**三個行向量**</mark>就是<mark style="color:yellow;">**三個基底向量**</mark> $$\mathbf{i}, \mathbf{j}, \mathbf{k}$$ 在向量 $$\mathbf{v}$$ 上的[投影](../../proj/)，例如：

* $$\text{proj}_{\mathbf{v}}(\mathbf{i})  =  \left(\dfrac{\mathbf{i}\cdot\mathbf{v}}{\mathbf{v}\cdot\mathbf{v}}\right)\mathbf{v}  =   \dfrac{v_1\mathbf{v}}{\|\mathbf{v}\|²}$$
{% endhint %}
{% endtab %}

{% tab title="🎖 證明" %}
{% hint style="success" %}
$$\mathbf{A}  = \dfrac{1}{\|\mathbf{v}\|²}  \begin{bmatrix}    v_1^2 & v_1 v_2 & v_1 v_3 \\      v_2 v_1 & v_2^2 & v_2 v_3 \\     v_3 v_1 & v_3 v_2 & v_3^2   \end{bmatrix}   =  \begin{bmatrix}    \dfrac{v_1\mathbf{v}}{\|\mathbf{v}\|²}  &     \dfrac{v_2 \mathbf{v}}{\|\mathbf{v}\|²} &    \dfrac{v_3 \mathbf{v}}{\|\mathbf{v}\|²}  \end{bmatrix}$$
{% endhint %}

🎖 證明： :point\_right: [射影向量的矩陣表示法](../../proj/matrix.md)



{% hint style="success" %}
$$\mathbf{B}  = \dfrac{1}{\|\mathbf{v}\|²}   \begin{bmatrix}       v_2^2 + v_3^2 & -v_1 v_2       & -v_1 v_3 \\       -v_2 v_1      & v_1^2 + v_3^2 & -v_2 v_3 \\      -v_3 v_1      & -v_3 v_2       & v_1^2 + v_2^2   \end{bmatrix}$$
{% endhint %}

🎖 證明：

$$\text{perp}_{\mathbf{v}}(\mathbf{u})  = \mathbf{u} - \mathbf{Au} = \mathbf{Bu}$$

$$\mathbf{B} = \mathbf{I-A} = \begin{bmatrix}       1 & 0       & 0 \\       0      & 1 & 0 \\      0      & 0       & 1   \end{bmatrix}    - \dfrac{1}{\|\mathbf{v}\|²}  \begin{bmatrix}    v_1^2 & v_1 v_2 & v_1 v_3 \\      v_2 v_1 & v_2^2 & v_2 v_3 \\     v_3 v_1 & v_3 v_2 & v_3^2   \end{bmatrix}$$，其中 $$\|\mathbf{v}\|^2 = v_1^2 + v_2^2 + v_3^2$$

通分後，即可得結果。
{% endtab %}

{% tab title="⬇️ 應用" %}
* [對特定軸的旋轉矩陣](../../../matrix/rotation/about-axis.md)
{% endtab %}

{% tab title="👥 相關" %}
* [矩陣乘法](../../../matrix/op/mult/)
{% endtab %}

{% tab title="📗 參考" %}
* Mathematics for 3D Game Programming & Computer Graphics (2nd Edition, 2004)
{% endtab %}
{% endtabs %}

