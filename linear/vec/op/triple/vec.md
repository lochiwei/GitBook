---
description: 🚧 under construction
---

# 🔰 向量三重積

[線性代數](../../../) ⟩ [向量](../../) ⟩ [運算](../) ⟩ [三重積](./) ⟩ 向量三重積

{% hint style="success" %}
( :star: <mark style="color:red;">**只**</mark>適用於<mark style="color:yellow;">**座標空間**</mark>:exclamation:)

$$(\mathbf{u}\times\mathbf{v})\times\mathbf{w}  = \begin{vmatrix}   \mathbf{u}\cdot\mathbf{w} & \mathbf{v}\cdot\mathbf{w} \\   \mathbf{u} & \mathbf{v} \\ \end{vmatrix}$$

:u6307: 同義詞："<mark style="color:purple;">**vector triple product**</mark>"
{% endhint %}

{% tabs %}
{% tab title="🔸 性質" %}
{% hint style="success" %}
1. $$(\mathbf{u}\times\mathbf{v})\times\mathbf{w} \ne \mathbf{u}\times (\mathbf{v}\times\mathbf{w})$$  (:star:「[空間外積](../cross/3d/)」<mark style="color:red;">**沒有**</mark>「<mark style="color:yellow;">**結合律**</mark>」:exclamation:)
2. $$(\mathbf{u}\times\mathbf{v})\times\mathbf{u} = \mathbf{u}\times(\mathbf{v}\times\mathbf{u})$$
{% endhint %}
{% endtab %}

{% tab title="👥 相關" %}
* 外積 ⟩ [性質](../cross/#xing-zhi)&#x20;
* [tex](../../../../tool/tex/ "mention") ⟩  [vec.md](../../../../tool/tex/vec.md "mention")
{% endtab %}

{% tab title="📘 手冊" %}
* wiki ⟩ [triple product](https://en.wikipedia.org/wiki/Triple_product)
{% endtab %}

{% tab title="🎖 證明" %}
{% hint style="success" %}
$$(\mathbf{u}\times\mathbf{v})\times\mathbf{u} = \mathbf{u}\times(\mathbf{v}\times\mathbf{u})$$
{% endhint %}

🎖 證明：

$$(\mathbf{u}\times\mathbf{v})\times\mathbf{u} = -(\mathbf{v}\times\mathbf{u})\times\mathbf{u} = \mathbf{u}\times(\mathbf{v}\times\mathbf{u})$$ ▨
{% endtab %}
{% endtabs %}
