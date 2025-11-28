---
description: ╱
---

# 🔰 Group╱群

[代數](../) ⟩ [系統](../system.md) ⟩ 群

{% hint style="success" %}
$$(\mathbf{G}, \ast)$$ 稱為一個「<mark style="color:purple;">群</mark>」(<mark style="color:yellow;">**group under the**</mark> $$\ast$$ <mark style="color:yellow;">**operation**</mark>)，如果它的[運算](../binary/)具有：

* <mark style="color:orange;">**封閉性**</mark> ([closure](../binary/closure.md))： $$a \ast b \in \mathbf{G}$$

並符合下列 <mark style="color:yellow;">**3**</mark> 點：

* <mark style="color:yellow;">**G1：結合律**</mark> ([associativity](../binary/associativity.md))： $$(ab)c = a(bc)$$
* <mark style="color:yellow;">**G2：單位元素**</mark> ([identity](../binary/identity.md)) $$e$$： $$ea = ae = a$$
* <mark style="color:yellow;">**G3：反元素**</mark> ([inverse](../binary/inverse.md)) $$a^{-1}$$： $$a \ast a^{-1} = a^{-1} \ast a = e$$
{% endhint %}

{% hint style="danger" %}
* <mark style="color:purple;">群</mark><mark style="color:red;">**不一定**</mark>有[交換律](../binary/commutativity.md)： $$ab=ba$$，但如果有就稱為「[交換群](commute.md)」。
{% endhint %}

{% tabs %}
{% tab title="🔴 主題" %}
* [props.md](props.md "mention")
* [commute.md](commute.md "mention")： 有[交換律](../binary/commutativity.md) $$ab=ba$$ 的<mark style="color:purple;">群</mark>。
{% endtab %}

{% tab title="⭐️ 重點" %}
{% hint style="info" %}
一個擁有「[結合律](../binary/associativity.md)」的「[代數系統](../system.md)」稱為「<mark style="color:yellow;">**半群**</mark>╱<mark style="color:yellow;">**semigroup**</mark>」。
{% endhint %}
{% endtab %}

{% tab title="🗺️ 圖表" %}
<img src="../../.gitbook/assets/group.ring.field.svg" alt="代數結構" class="gitbook-drawing">
{% endtab %}

{% tab title="🖥️ 影片" %}
{% embed url="https://youtu.be/g7L_r6zw4-c" %}
Group Definition
{% endembed %}

{% embed url="https://youtu.be/BwHspSCXFNM" %}
Group Multiplication Tables (Cayley Tables)
{% endembed %}

{% embed url="https://youtu.be/jhVMBXl5jTA" %}
Simple Groups
{% endembed %}
{% endtab %}

{% tab title="📗 參考" %}
* [ ] Contemporary Abstract Algebra (2017), Ch. 2 Groups, p.43
{% endtab %}
{% endtabs %}
