# ✖️ 外積

[線性代數](../../../) ⟩ [向量](../../) ⟩ [運算](../) ⟩ 外積 (:u6307: 同義詞："<mark style="color:purple;">**cross product**</mark>")

{% hint style="success" %}
* 「[平面外積](2d.md)」：\
  \
  $$\mathbf{u}\times\mathbf{v} = \begin{vmatrix}         u_1 & u_2 \\     v_1 & v_2    \end{vmatrix}$$<br>
* 「[空間外積](3d/)」：\
  $$\mathbf{u}\times\mathbf{v}  = \left(   \begin{vmatrix}         u_2 & u_3 \\     v_2 & v_3    \end{vmatrix} ,   \begin{vmatrix}         u_3 & u_1 \\     v_3 & v_1    \end{vmatrix} ,   \begin{vmatrix}         u_1 & u_2 \\     v_1 & v_2    \end{vmatrix}  \right)  = \begin{vmatrix}       \mathbf{i} & \mathbf{j} & \mathbf{k} \\   u_1 & u_2 & u_3 \\   v_1 & v_2 & v_3  \end{vmatrix}$$
* 「[四元數外積](../../../../num/quaternion/op/cross.md)」：\
  \
  $$\mathbf{p} \times \mathbf{q} = ( {\color{orange}s} + \mathbf{u}) \times ( {\color{orange}t} + \mathbf{v}) = -{\color{orange}s} \mathbf{v} + {\color{orange}t} \mathbf{u} + (\mathbf{u} \times \mathbf{v})$$
{% endhint %}

{% tabs %}
{% tab title="🔸 性質" %}
{% hint style="success" %}
1. (<mark style="color:red;">**反**</mark><mark style="color:yellow;">**交換律**</mark>)：$$\mathbf{u}\times\mathbf{v} = -\mathbf{v}\times\mathbf{u}$$&#x20;
2. (**左**<mark style="color:yellow;">**分配律**</mark>)：$$\mathbf{u}\times (\mathbf{v} + \mathbf{w}) = \mathbf{u}\times\mathbf{v} + \mathbf{u}\times\mathbf{w}$$ (**右**<mark style="color:yellow;">**分配律**</mark>也成立)&#x20;
3. (<mark style="color:red;">**類**</mark><mark style="color:yellow;">**結合律**</mark>)：$$k(\mathbf{u}\times\mathbf{v}) = (k\mathbf{u})\times\mathbf{v} = \mathbf{u}\times(k\mathbf{v})$$
4. $$\mathbf{v}\times\mathbf{v}=0$$&#x20;
5. $$|\mathbf{u}\times\mathbf{v}| \le \|\mathbf{u}\| \|\mathbf{v}\|$$
6. $$\|\mathbf{u}\times\mathbf{v}\|=  \|\mathbf{u}\| \|\mathbf{v}\| \sin\theta$$
7. $$\mathbf{u}\times\mathbf{v} = \mathbf{0} \iff \mathbf{u} \parallel \mathbf{v}$$  (:point\_right: [平行向量性質](../../parallel/#xing-zhi))
{% endhint %}
{% endtab %}

{% tab title="🔴 主題" %}
* [平面外積](2d.md)
* [空間外積](3d/)
{% endtab %}

{% tab title="⬇️ 應用" %}
* [空間外積的矩陣表示法](3d/matrix.md)
* [平行向量性質](../../parallel/#xing-zhi)
* [decomp](../../decomp/ "mention")
* [spherical.md](../../decomp/spherical.md "mention")
{% endtab %}

{% tab title="🖥️ 影片" %}
{% embed url="https://youtu.be/51-V4nD1Z80?t=153" %}
{% endtab %}

{% tab title="🧨 雷區" %}
{% hint style="danger" %}
* <mark style="color:purple;">**外積**</mark><mark style="color:red;">**沒有**</mark>「<mark style="color:yellow;">**交換律**</mark>」:exclamation:
* [空間外積](3d/)<mark style="color:red;">**沒有**</mark>「<mark style="color:yellow;">**結合律**</mark>」:exclamation:( :point\_right: [向量三重積](../triple/vec.md#xing-zhi) )
* $$(\mathbf{u}\times\mathbf{v})\times\mathbf{w}$$ 對[平面外積](2d.md)<mark style="color:red;">**沒有**</mark><mark style="color:yellow;">**意義**</mark>:exclamation:
{% endhint %}
{% endtab %}

{% tab title="👥 相關" %}
* 比較：[內積](../dot/) (inner product)、[行向量 ⨉ 列向量](../../../matrix/op/mult/outer-product/) (outer product)
* [矩陣乘法](../../../matrix/op/mult/)
* Desmos ⟩ [matrix](../../../../tool/desmos/expr/matrix/ "mention")
* GGB ⟩ [matrix](../../../../tool/ggb/matrix/ "mention") &#x20;
* LaTeX ⟩ [deco.md](../../../../tool/tex/deco.md "mention")
{% endtab %}

{% tab title="📗 參考" %}
* [ ] Mathematics for 3D Game Programming & Computer Graphics (2nd Edition, 2004) &#x20;
{% endtab %}
{% endtabs %}
