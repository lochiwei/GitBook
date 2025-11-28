---
description: ╱🚧
---

# 🚧 包含關係：A ⊆ B

[集合](../) ⟩ [關係](../relation.md) ⟩ [二元關係](../binary/) ⟩ [集合間關係](./) ⟩ 包含關係：A ⊆ B

{% hint style="success" %}
若「 $$x \in A \implies x \in B$$ 」，這時我們用 $$\boxed{A \ {\color{orange}\subseteq} \ B}$$ 來代表這個事實，並且說：

* 「$$A$$ 是 $$B$$ 的<mark style="color:purple;">**子集**</mark>╱<mark style="color:yellow;">**subset**</mark>」、「$$B$$ 是 $$A$$ 的<mark style="color:purple;">**母集**</mark>╱<mark style="color:yellow;">**superset**</mark>」
* 「$$A$$ <mark style="color:yellow;">**包含**</mark><mark style="color:orange;">**於**</mark> $$B$$」、「$$B$$ <mark style="color:yellow;">**包含**</mark> $$A$$」
{% endhint %}

{% tabs %}
{% tab title="🔸 性質" %}
{% hint style="info" %}
若 $$A,B,C$$ 為[集合](../)，則：

1. [反身性](../binary/prop/reflexive.md)：$$A \ {\color{orange}\subseteq} \ A$$&#x20;
2. [遞移性](../binary/prop/transitive.md)：$$A \ {\color{orange}\subseteq} \ B \ \land \ B \ {\color{orange}\subseteq} \ C \implies A \ {\color{orange}\subseteq} \ C$$&#x20;
3. [反對稱](../binary/prop/antisymmetric.md)：$$A \ {\color{orange}\subseteq} \ B \ \land \ B \ {\color{orange}\subseteq} \ A \implies A \ {\color{orange}=} \ B$$&#x20;
{% endhint %}
{% endtab %}

{% tab title="👥 相關" %}
* <mark style="color:yellow;">**應用**</mark>：
  * [order.md](../../num/real/def/order.md "mention")
{% endtab %}

{% tab title="📗 參考" %}
* [ ] Discrete Mathematics (Oscar Levin) ⟩ 0.2 Sets (p.6)
{% endtab %}
{% endtabs %}
