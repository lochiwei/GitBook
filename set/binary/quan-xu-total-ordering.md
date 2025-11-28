---
description: ╱🚧 under construction
---

# 🔰 全序╱total ordering

[集合](../) ⟩ [關係](../relation.md) ⟩ [二元](./) ⟩ total ordering╱linear ordering

{% hint style="success" %}
An <mark style="color:yellow;">**total**</mark>/<mark style="color:yellow;">**linear**</mark> <mark style="color:purple;">**ordering**</mark> on a set F is a <mark style="color:yellow;">**relation**</mark> (represented by <mark style="color:yellow;">**≤**</mark>) with the following 3 properties：

* (<mark style="color:yellow;">**TO1**</mark>) <mark style="color:orange;">**全序性**</mark>╱[totality](prop/totality.md)：x <mark style="color:yellow;">**≤**</mark> y or y <mark style="color:yellow;">**≤**</mark> x, ∀ x, y ∈ F
* (<mark style="color:yellow;">**TO2**</mark>) <mark style="color:orange;">**反對稱**</mark>╱[antisymmetry](prop/antisymmetric.md)：x <mark style="color:yellow;">**≤**</mark> y, y <mark style="color:yellow;">**≤**</mark> x => x = y
* (<mark style="color:yellow;">**TO3**</mark>) <mark style="color:orange;">**遞移性**</mark>╱[transitivity](prop/transitive.md)：x <mark style="color:yellow;">**≤**</mark> y, y <mark style="color:yellow;">**≤**</mark> z => x <mark style="color:yellow;">**≤**</mark> z
{% endhint %}

{% tabs %}
{% tab title="⭐️ 重點" %}
{% hint style="info" %}
* 「<mark style="color:orange;">**全序性**</mark>」代表：&#x20;
  * (1) <mark style="color:yellow;">**任兩個**</mark><mark style="color:orange;">**不同的**</mark><mark style="color:yellow;">**元素**</mark>間<mark style="color:green;">**必定**</mark>有關係（對稱主對角線的兩個位置<mark style="color:red;">**不能**</mark><mark style="color:yellow;">**都是０**</mark>）
  * (2) <mark style="color:yellow;">**每個元素**</mark>都跟<mark style="color:yellow;">**自己**</mark>有關係（<mark style="color:orange;">**反身性**</mark>)(主對角線的所有位置<mark style="color:yellow;">**都是１**</mark>）
* 「<mark style="color:orange;">**反對稱**</mark>」代表：
  * <mark style="color:yellow;">**不同元素**</mark>間<mark style="color:red;">**不能**</mark><mark style="color:yellow;">**同時有**</mark><mark style="color:red;">**相反的關係**</mark>，關係只能是<mark style="color:yellow;">**單向**</mark>的，或<mark style="color:yellow;">**兩者沒有關係**</mark>。\
    (對稱主對角線的兩個位置<mark style="color:red;">**不能**</mark><mark style="color:yellow;">**都是１**</mark>)\
    (主對角線的位置<mark style="color:green;">**沒任何限制**</mark>）
{% endhint %}

{% hint style="warning" %}
「<mark style="color:orange;">**全序性**</mark>」([totality](prop/totality.md)) 必具有「<mark style="color:orange;">**反身性**</mark>」([reflexivity](prop/reflexive.md))：

&#x20;$$a \ {\color{orange}\simcolon} \ a, \ \forall a \in A$$

換句話說，一個 total order 也一定是個 partial order。
{% endhint %}

{% hint style="info" %}
x < y means x ≤ y, x ≠ y
{% endhint %}
{% endtab %}

{% tab title="📗 參考" %}
* Understanding Analysis ⟩ 8.6 A Construction of R From Q, Def. 8.6.5 (p.299)
{% endtab %}

{% tab title="👥 相關" %}
* 「[ordered.md](../../algebra/field/ordered.md "mention")」
* 建造實數系 ⟩ [order.md](../../num/real/def/order.md "mention")
{% endtab %}
{% endtabs %}
