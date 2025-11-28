---
description: 🚧 under construction -> prove 1. 2.(1)
---

# 🚧 反方陣

[線代](../../../) ⟩ [矩陣](../../) ⟩ [運算](../) ⟩ [乘法](./) ⟩ 反方陣 ("<mark style="color:purple;">**inverse**</mark>")

{% hint style="success" %}
如果 $$\mathbf{AB=BA=I}$$，我們就說&#x20;

* $$\mathbf{A,B}$$ 互為彼此的「<mark style="color:purple;">**反方陣**</mark>」(inverse)，
* 並分別用 $$\mathbf{B}^{-1},\ \mathbf{A}^{-1}$$ 代表 $$\mathbf{A,B}$$，
* 並說 $$\mathbf{A,B}$$ 為「<mark style="color:yellow;">可逆方陣</mark>」(invertible)。
{% endhint %}

{% tabs %}
{% tab title="🔸 性質" %}
{% hint style="info" %}
1. (1) <mark style="color:purple;">**反方陣**</mark>是<mark style="color:yellow;">**唯一的**</mark>。\
   (2) $$\mathbf{AB = I} \implies \mathbf{BA = I}$$
{% endhint %}

{% hint style="info" %}
2. (1) 若 $$\mathbf{A,B}$$  為<mark style="color:yellow;">**可逆方陣**</mark>，則：$$(\mathbf{AB})^{-1} = \mathbf{B}^{-1} \mathbf{A}^{-1}$$\
   (2) 若 $$\mathbf{M}$$  為<mark style="color:yellow;">**可逆方陣**</mark>，則：$$\left(\mathbf{M}^{-1}\right)^T =  \left(\mathbf{M}^{T}\right)^{-1}$$
{% endhint %}

* 證明：(2) $$\left(\mathbf{M}^{-1}\right)^T \mathbf{M}^T = \left(\mathbf{M} \mathbf{M}^{-1}\right)^T = \mathbf{I}^T = \mathbf{I}$$ ▨
* 相關： [normal-vec.md](../../../space/transform/normal-vec.md "mention")
{% endtab %}

{% tab title="⭐️ 重點" %}
{% hint style="info" %}
1. $$\left(\mathbf{M}^{-1}\right)^T$$ 稱為 $$\mathbf{M}$$ 的 "<mark style="color:yellow;">**inverse transpose**</mark>"。 :point\_right: [normal-vec.md](../../../space/transform/normal-vec.md "mention")
{% endhint %}
{% endtab %}

{% tab title="👥 相關" %}
* [identity.md](identity.md "mention")
* [transpose.md](../transpose.md "mention")
* [matrix.md](../../../space/basis/ortho/matrix.md "mention")
{% endtab %}

{% tab title="📗 參考" %}
* [ ] Math for 3D Game ⟩ 2.3 Matrix Inverses
{% endtab %}
{% endtabs %}
