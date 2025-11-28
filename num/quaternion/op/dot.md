---
description: 🚧 under construction -> 1). T(q) = p • q 線性變換 2). [T] 矩陣
---

# 🚧 四元數內積

[數系](../../) ⟩ [四元數](../) ⟩ [運算](./) ⟩ 內積

{% hint style="success" %}
<mark style="color:purple;">**四元數內積**</mark>就是「[向量內積](../../../linear/vec/op/dot/)」。
{% endhint %}

{% hint style="warning" %}
「<mark style="color:purple;">**四元數內積**</mark>」的結果雖然是個<mark style="color:yellow;">**純數**</mark>，但<mark style="color:yellow;">**依然可視為**</mark>一個「[四元數](../)」:exclamation:

因此在 $$\mathbb{R}^2, \mathbb{R}^3$$ 中沒有意義的 $$(\mathbf{p} \cdot \mathbf{q}) \cdot \mathbf{r}$$，在「[四元數](../)」中是有意義的。
{% endhint %}

{% tabs %}
{% tab title="🔸 性質" %}
若： $$\mathbf{p} = s + \mathbf{u}, \ \mathbf{q} = t + \mathbf{v}$$，則：

{% hint style="success" %}
1. $$\mathbf{p} \cdot \mathbf{q}  =  ( {\color{orange}s} + \mathbf{u}) \cdot ( {\color{orange}t} + \mathbf{v})  =  {\color{orange}st} + (\mathbf{u} \cdot \mathbf{v})$$
2. $${\color{orange}s} \cdot \mathbf{v} = {\color{orange}0}$$  (純量與向量的內積為 0)
{% endhint %}
{% endtab %}

{% tab title="👥 相關" %}
* [四元數乘法](x.md)
* [四元數外積](cross.md)
* [四元數旋轉](rotate.md)
{% endtab %}
{% endtabs %}
