---
description: 🚧 under construction -> prove (1) (2)
---

# 🚧 四元數長度

[數系](../) ⟩ [四元數](./) ⟩ 長度 (norm)

{% hint style="success" %}
若 $$\mathbf{q} = w+x\mathbb{i} +y\mathbb{j} +z\mathbb{k}$$，則定義它的<mark style="color:purple;">**長度**</mark>為：

$$\|\mathbf{q}\| = \sqrt{w^2+x^2+y^2+z^2}$$
{% endhint %}

{% tabs %}
{% tab title="🔸 性質" %}
{% hint style="success" %}
1. $$\|\mathbf{q}\|^2 = \mathbf{\overline{q}} \mathbf{q} = \mathbf{q} \mathbf{\overline{q}}$$
2. $$\|\mathbf{pq}\| = \|\mathbf{p}\| \|\mathbf{q}\|$$
3. $$\|\mathbf{p}\|^2 \|\mathbf{q}\|^2 = |\mathbf{p}\cdot\mathbf{q}|^2 + \| \mathbf{p}\times\mathbf{q} \|^2$$ &#x20;
{% endhint %}

* 🎖 證明： (3) :point\_right: 四元數[外積性質](op/cross.md#xing-zhi)&#x20;
{% endtab %}

{% tab title="⬇️ 應用" %}
* 四元數[倒數](inverse.md)
* [向量長度性質 3](../../linear/vec/norm.md#xing-zhi)
{% endtab %}

{% tab title="👥 相關" %}
* 四元數長度的定義就是[向量長度](../../linear/vec/norm.md)的定義。
* [length.md](../complex/length.md "mention")
{% endtab %}
{% endtabs %}
