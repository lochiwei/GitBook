# ✖️ 內積

[線性代數](../../../) ⟩ [向量](../../) ⟩ [運算](../) ⟩ 內積  (:u6307: 同義詞："<mark style="color:purple;">**dot product**</mark>", "<mark style="color:purple;">**inner product**</mark>", "<mark style="color:purple;">**scalar produc**</mark>t")

{% hint style="warning" %}
⭐️ 這裡定義的<mark style="color:purple;">**內積**</mark><mark style="color:yellow;">**只適用於**</mark> $$\mathbb{R}ⁿ$$ ，更廣義的內積，要依相對的[向量空間](../../../space/)而定❗️&#x20;
{% endhint %}

{% hint style="success" %}
若 $$\mathbf{u} = ( u_1 , u_2 , \cdots , u_n )$$、 $$\mathbf{v} = ( v_1 , v_2 , \cdots , v_n )$$ ，定義向量<mark style="color:purple;">**內積**</mark>為：

$$\mathbf{u}\cdot \mathbf{v}=u_1v_1 + u_2v_2 + \cdots + u_nv_n$$
{% endhint %}

{% tabs %}
{% tab title="🔸 性質" %}
{% hint style="success" %}
1. (<mark style="color:yellow;">**交換律**</mark>)：$$\mathbf{u}\cdot\mathbf{v} = \mathbf{v}\cdot\mathbf{u}$$&#x20;
2. (<mark style="color:yellow;">**分配律**</mark>)：$$\mathbf{u}\cdot (\mathbf{v} + \mathbf{w}) = \mathbf{u}\cdot\mathbf{v} + \mathbf{u}\cdot\mathbf{w}$$&#x20;
3. (<mark style="color:red;">**類**</mark><mark style="color:yellow;">**結合律**</mark>)：$$k(\mathbf{u}\cdot\mathbf{v}) = (k\mathbf{u})\cdot\mathbf{v} = \mathbf{u}\cdot(k\mathbf{v})$$
{% endhint %}
{% endtab %}

{% tab title="🔴 主題" %}
* [內積的矩陣表示法](in-matrix.md)
* [內積的餘弦定理](cos-rule.md)
{% endtab %}

{% tab title="⭐️ 重點" %}
{% hint style="info" %}
若用[轉置矩陣](../../../matrix/op/transpose.md)與[矩陣乘法](../../../matrix/op/mult/)，則<mark style="color:purple;">**內積**</mark>也可以寫成：

$$\mathbf{u}\cdot \mathbf{v} = \mathbf{u}^T \mathbf{v}$$    （註：用[矩陣乘法](../../../matrix/op/mult/)計算<mark style="color:purple;">**內積**</mark>時，[向量](../../)通常用「<mark style="color:yellow;">**行向量**</mark>」表示）
{% endhint %}
{% endtab %}

{% tab title="⬇️ 應用" %}
* [向量的垂直分解](../../decomp/perp/) (證明垂直分解是<mark style="color:yellow;">**兩個線性變換**</mark>)
{% endtab %}

{% tab title="🖥️ 影片" %}
{% embed url="https://youtu.be/51-V4nD1Z80?t=153" %}
{% endtab %}

{% tab title="👥 相關" %}
* [向量長度](../../norm.md)可以轉為<mark style="color:purple;">**內積**</mark>。
* [矩陣乘法](../../../matrix/op/mult/)的定義與<mark style="color:purple;">**內積**</mark>有關。
* 比較： [行 ⨉ 列](../../../matrix/op/mult/outer-product/) ("outer product")、[外積](../cross/)
* [mult.md](../../../../num/complex/mult.md "mention")
* [四元數內積](../../../../num/quaternion/op/dot.md)就是[向量](../../)<mark style="color:purple;">**內積**</mark>。
* [R³ 中的旋轉](../../../space/transform/rotate3d.md)
{% endtab %}

{% tab title="📗 參考" %}
* [ ] Mathematics for 3D Game Programming & Computer Graphics (2nd Edition, 2004) &#x20;
{% endtab %}
{% endtabs %}
