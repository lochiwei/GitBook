---
description: 🚧 under construction
---

# 🔰 R³ 中的旋轉

[線性代數](../../) ⟩ [向量空間](../) ⟩ [線性變換](./) ⟩ R³ 中的旋轉

{% hint style="success" %}
A <mark style="color:purple;">**rotation**</mark> in $$\mathbb{R}^3$$ is a function $$\rho:\mathbb{R}^3 \to \mathbb{R}^3$$ that <mark style="color:yellow;">**preserves**</mark> <mark style="color:orange;">**lengths**</mark>, <mark style="color:orange;">**angles**</mark>, and <mark style="color:orange;">**handedness**</mark>：

* 保長：$$\|\rho(\mathbf{v})\| =  \|\mathbf{v}\|$$
* 保角：$$\rho(\mathbf{u}) \cdot \rho(\mathbf{v}) = \mathbf{u} \cdot \mathbf{v}$$ (保[內積](../../vec/op/dot/))
* 保方向性：$$\rho(\mathbf{u}) \times \rho(\mathbf{v}) = \rho(\mathbf{u} \times \mathbf{v})$$ (保[外積](../../vec/op/cross/3d/))

(註：「保[內積](../../vec/op/dot/)」即可「保長」，所以第一個條件是多餘的)
{% endhint %}

{% tabs %}
{% tab title="👥 相關" %}
* [四元數](../../../num/quaternion/) ⟩ [內積](../../../num/quaternion/op/dot.md)、[外積](../../../num/quaternion/op/cross.md) 、[旋轉變換](../../../num/quaternion/op/rotate.md)
* [旋轉矩陣](../../matrix/rotation/)
{% endtab %}

{% tab title="📗 參考" %}
* [ ] Math for 3D Game ⟩ 3.6.2 Rotations with Quaternions ⭐️&#x20;
{% endtab %}
{% endtabs %}
