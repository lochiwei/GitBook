---
description: 🚧 under construction -> 1). T(q) = p x q 線性變換 2). [T] 矩陣
---

# 🚧 四元數外積

[數系](../../) ⟩ [四元數](../) ⟩ [運算](./) ⟩ 外積

* 如果比較[四元數乘法性質 4, 8](x.md#xing-zhi)：\
  \
  $$\mathbf{\overline{p}} \mathbf{q} =  \underbrace{ st + (\mathbf{u} \cdot \mathbf{v}) }_{\text{scalar part}} \ + \ \underbrace{   s \mathbf{v} - t \mathbf{u} - (\mathbf{u} \times \mathbf{v}) }_{\text{vector part}}$$\
  $$\mathbf{\overline{u}} \mathbf{v} =  (\mathbf{u} \cdot \mathbf{v}) - (\mathbf{u} \times \mathbf{v})$$<br>
* 也許我們可以將「<mark style="color:purple;">**四元數的外積**</mark>」定義為：

{% hint style="success" %}
$$\mathbf{p} \times \mathbf{q} = ( {\color{orange}s} + \mathbf{u}) \times ( {\color{orange}t} + \mathbf{v}) = -{\color{orange}s} \mathbf{v} + {\color{orange}t} \mathbf{u} + (\mathbf{u} \times \mathbf{v})$$
{% endhint %}

{% tabs %}
{% tab title="🔸 性質" %}
{% hint style="info" %}
1. $${\color{orange}s} \times {\color{orange}t} = \mathbf{0}$$（兩純量外積為零）
2. $${\color{orange}s} \times \mathbf{v} = - {\color{orange}s}\mathbf{v}$$
{% endhint %}

{% hint style="success" %}
3. $$\mathbf{q} \times \mathbf{q} = \mathbf{0}$$
4. (<mark style="color:red;">**反**</mark><mark style="color:yellow;">**交換律**</mark>)： $$\mathbf{q} \times \mathbf{p} = - (\mathbf{p} \times \mathbf{q})$$
5. (<mark style="color:red;">**類**</mark><mark style="color:yellow;">**結合律**</mark>)：$${\color{orange}k}(\mathbf{p}\times\mathbf{q}) =  ({\color{orange}k}\mathbf{p})\times\mathbf{q} =  \mathbf{p}\times({\color{orange}k}\mathbf{q})$$
6. (**左**<mark style="color:yellow;">**分配律**</mark>)：$$\mathbf{p}\times (\mathbf{q} + \mathbf{r}) = \mathbf{p}\times\mathbf{q} + \mathbf{p}\times\mathbf{r}$$ (**右**<mark style="color:yellow;">**分配律**</mark>也成立)&#x20;
{% endhint %}

* :point\_right: 比較： [外積性質](../../../linear/vec/op/cross/#xing-zhi)
* 🎖 證明： 4. 5. 6. :point\_right: <img src="../../../.gitbook/assets/Quaternions_cross_product.png" alt="" data-size="line">

{% hint style="success" %}
7. $$\mathbf{\overline{p}} \mathbf{q} =   \underbrace{ (\mathbf{p} \cdot \mathbf{q}) }_{\text{scalar part}} \underbrace{  - (\mathbf{p} \times \mathbf{q}) }_{\text{vector part}}$$
8. $$\|\mathbf{p}\|^2 \|\mathbf{q}\|^2 = |\mathbf{p}\cdot\mathbf{q}|^2 + \| \mathbf{p}\times\mathbf{q} \|^2$$  (可由上式證得)
{% endhint %}

* :point\_right: 比較： [norm.md](../../../linear/vec/norm.md "mention")
* <mark style="color:yellow;">**(7)**</mark> 式可視為是四元數[乘法性質 (8)](x.md#xing-zhi) 的擴充。
{% endtab %}

{% tab title="⭐️ 重點" %}
{% hint style="success" %}
* 這定義並不牴觸原來兩個「只有[純向量部分](../notation.md)的[外積](../../../linear/vec/op/cross/3d/) $$\mathbf{u} \times \mathbf{v}$$」，兩個定義是<mark style="color:yellow;">**相容的**</mark>。
* 這可看作是將[外積](../../../linear/vec/op/cross/3d/)定義從 $$\mathbb{R}^3$$ <mark style="color:yellow;">**擴充**</mark>到 $$\mathbb{H}$$。
* 這定義的<mark style="color:yellow;">**運算結果**</mark>是個「[純向量](../notation.md)」四元數。
{% endhint %}
{% endtab %}

{% tab title="⬇️ 應用" %}
* [decomp](../../../linear/vec/decomp/ "mention")
{% endtab %}

{% tab title="👥 相關" %}
* [四元數](../) ⟩ [乘法](x.md)、 [內積](dot.md) 、[旋轉](rotate.md)
* [2d.md](../../../linear/vec/op/cross/2d.md "mention")
* [3d](../../../linear/vec/op/cross/3d/ "mention")
* [mult.md](../../complex/mult.md "mention")
{% endtab %}
{% endtabs %}
