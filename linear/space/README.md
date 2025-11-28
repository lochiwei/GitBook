---
description: 🚧 under construction -> + algebra / field
---

# 🔰 向量空間

[線代](../) ⟩ [向量](../vec/) ⟩ 向量空間 (:u6307: 同義詞："<mark style="color:purple;">**vector space**</mark>")

我們稱 $$(\mathbb{V, F,+,\cdot)}$$ 為一個「<mark style="color:purple;">**向量空間**</mark>」(vector space over the [field](../../algebra/field/) $$\mathbb{F}$$)，如果：&#x20;

* $$\mathbb{V}$$ 是一個<mark style="color:yellow;">**集合**</mark>，其上元素稱為[**向量**](../vec/) (<mark style="color:purple;">**vector**</mark>)。
* $$\mathbb{F}$$ 是一個<mark style="color:yellow;">**體**</mark> ([field](../../algebra/field/)) (通常為實數 $$\mathbb{R}$$)，其上元素稱為<mark style="color:yellow;">**係數**</mark> (<mark style="color:purple;">**scalar**</mark>)。

並且有兩個必要的運算：

{% hint style="success" %}
* [<mark style="color:yellow;">**向量加法**</mark>](../vec/op/+.md) (<mark style="color:purple;">**vector addition**</mark>)： $$\mathbf{u} + \mathbf{v} \in \mathbb{V}$$ (<mark style="color:yellow;">**加法**</mark><mark style="color:orange;">**封閉性**</mark>)
* [<mark style="color:yellow;">**係數積**</mark>](../vec/op/scalar-mult.md) (<mark style="color:purple;">**scalar multiplication**</mark>)： $$k \mathbf{u}\in \mathbb{V}$$ (<mark style="color:yellow;">**係數積**</mark><mark style="color:orange;">**封閉性**</mark>)

(註：習慣上會<mark style="color:red;">**省略**</mark><mark style="color:yellow;">**係數積**</mark>的符號，以避免與[內積](../vec/op/dot/)混淆)
{% endhint %}

而且這兩個運算符合以下 <mark style="color:yellow;">**8**</mark> 條件：

{% hint style="success" %}
[<mark style="color:yellow;">**向量加法**</mark>](../vec/op/+.md) (<mark style="color:purple;">**vector addition**</mark>)：

1. <mark style="color:orange;">**結合律**</mark>： $$(\mathbf{u} + \mathbf{v}) + \mathbf{w} = \mathbf{u} + (\mathbf{v} + \mathbf{w})$$
2. <mark style="color:yellow;">**零向量**</mark>： $$\mathbf{0} + \mathbf{v} = \mathbf{v} + \mathbf{0} = \mathbf{v}$$
3. <mark style="color:yellow;">**反向量**</mark>： $$\mathbf{v} + (-\mathbf{v}) = (-\mathbf{v}) + \mathbf{v} = \mathbf{0}$$
4. <mark style="color:orange;">**交換律**</mark>： $$\mathbf{u} + \mathbf{v} = \mathbf{v} + \mathbf{u}$$

[<mark style="color:yellow;">**係數積**</mark>](../vec/op/scalar-mult.md) (<mark style="color:purple;">**scalar multiplication**</mark>)：

5. <mark style="color:orange;">**單位係數**</mark>： $$1\mathbf{v} = \mathbf{v}$$
6. <mark style="color:red;">**類**</mark><mark style="color:orange;">**結合律**</mark>： $$(ab)\mathbf{v} = a(b\mathbf{v})$$

<mark style="color:yellow;">**分配律**</mark>：

7. $$k(\mathbf{u} + \mathbf{v}) = k\mathbf{u} + k\mathbf{v}$$
8. $$(a+b)\mathbf{v} = a\mathbf{v} + b\mathbf{v}$$
{% endhint %}

{% tabs %}
{% tab title="🔴 主題" %}
* [線性組合](../combination.md)
* [線性獨立](../indep.md)
* [基底](basis/)
{% endtab %}

{% tab title="⭐️ 重點" %}
{% hint style="info" %}
<mark style="color:purple;">**向量空間**</mark>的 <mark style="color:yellow;">**8**</mark> 條件：

* 1.2.3.4. 是「[<mark style="color:yellow;">**向量加法**</mark>](../vec/op/+.md)」的特性，有這些特性的集合又稱為「<mark style="color:yellow;">**加法交換群**</mark>」。
* 5.6. 是<mark style="color:yellow;">**係數積**</mark><mark style="color:orange;">**單位係數**</mark>與<mark style="color:red;">**類**</mark><mark style="color:orange;">**結合律**</mark>。
* 7.8. 是<mark style="color:orange;">**分配律**</mark>。
{% endhint %}
{% endtab %}

{% tab title="👥 相關" %}
* [向量加法](../vec/op/+.md)
* [向量係數積](../vec/op/scalar-mult.md)
* [Ring](../../algebra/ring/)
{% endtab %}

{% tab title="🗺️ 圖表" %}
<img src="../../.gitbook/assets/group.ring.field.svg" alt="代數結構" class="gitbook-drawing">
{% endtab %}

{% tab title="📗 參考" %}
* wiki ⟩ [Vector Space](https://en.wikipedia.org/wiki/Vector_space)
* Linear Algebar - A Modern Introduction (4th edition), David Poole
{% endtab %}

{% tab title="💈範例" %}
* [矩陣](../matrix/)
* [四元數](../../num/quaternion/) ⟩ [內積](../../num/quaternion/op/dot.md)、[外積](../../num/quaternion/op/cross.md)、[乘法](../../num/quaternion/op/x.md)&#x20;
{% endtab %}

{% tab title="📔 手稿" %}
{% file src="../../.gitbook/assets/note_20230205_1138.svg" %}
0v = 0? 1v = v ?
{% endfile %}
{% endtab %}
{% endtabs %}
