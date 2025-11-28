# 🔰 空間外積

[線性代數](../../../../) ⟩ [向量](../../../) ⟩ [運算](../../) ⟩ [外積](../) ⟩ 空間外積&#x20;

{% hint style="success" %}
( :star: <mark style="color:red;">**只**</mark>適用於<mark style="color:yellow;">**座標空間**</mark>:exclamation:)

$$\mathbf{u}\times\mathbf{v}  = \left(   \begin{vmatrix}         u_2 & u_3 \\     v_2 & v_3    \end{vmatrix} ,   \begin{vmatrix}         u_3 & u_1 \\     v_3 & v_1    \end{vmatrix} ,   \begin{vmatrix}         u_1 & u_2 \\     v_1 & v_2    \end{vmatrix}  \right)  = \begin{vmatrix}       \mathbf{i} & \mathbf{j} & \mathbf{k} \\   u_1 & u_2 & u_3 \\   v_1 & v_2 & v_3  \end{vmatrix}$$

(還有另一種[外積](../)，適用於座標平面， :point\_right: 參見：[**平面外積**](../2d.md))

:u6307: 同義詞："<mark style="color:purple;">**cross product**</mark>", "<mark style="color:purple;">**vector product**</mark>"

:point\_right: 外積 ⟩ [#xing-zhi](../#xing-zhi "mention")
{% endhint %}

{% tabs %}
{% tab title="🔴 主題" %}
* [外積的矩陣表示法](matrix.md)
* [向量三重積](../../triple/vec.md)： $$(\mathbf{u}\times\mathbf{v})\times\mathbf{w}$$
* [純量三重積](../../triple/scalar.md)： $$(\mathbf{u}\times\mathbf{v})\cdot\mathbf{w}$$
{% endtab %}

{% tab title="⬇️ 應用" %}
* [about-axis.md](../../../../matrix/rotation/about-axis.md "mention")
* [decomp](../../../decomp/ "mention")
{% endtab %}

{% tab title="👥 相關" %}
* [矩陣乘法](../../../../matrix/op/mult/)
* [R³ 中的旋轉](../../../../space/transform/rotate3d.md)
{% endtab %}

{% tab title="📗 參考" %}
* [ ] Mathematics for 3D Game Programming & Computer Graphics (2nd Edition, 2004) &#x20;
{% endtab %}
{% endtabs %}
