---
description: ╱
---

# 🔰 Ring╱環

[代數](../) ⟩ [系統](../system.md) ⟩ 環

{% hint style="success" %}
我們稱 $$({\color{orange}\mathbf{R}}, {\color{orange}+},{\color{orange}\cdot})$$ 為一個「<mark style="color:yellow;">**ring**</mark>╱<mark style="color:purple;">**環**</mark>」，如果 $${\color{orange}\mathbf{R}}$$ 具有 <mark style="color:yellow;">**2**</mark> 個必要運算：

* <mark style="color:yellow;">**加法**</mark>： $$a {\color{orange}+} b \in {\color{orange}\mathbf{R}}$$ (<mark style="color:yellow;">**加法**</mark><mark style="color:orange;">**封閉性**</mark>)
* <mark style="color:yellow;">**乘法**</mark>： $$a {\color{orange}\cdot} b \in {\color{orange}\mathbf{R}}$$ (<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**封閉性**</mark>) (註：習慣上會省略乘法符號)

而且這兩個運算符合以下 <mark style="color:yellow;">**7**</mark> 條件：

* <mark style="color:yellow;">**A1：加法**</mark><mark style="color:orange;">**結合律**</mark>： $$(a+b)+c=a+(b+c)$$
* <mark style="color:yellow;">**A2：加法**</mark><mark style="color:orange;">**零元素**</mark>： $$a + {\color{orange}\mathbf{0}} = a$$
* <mark style="color:yellow;">**A3：加法**</mark><mark style="color:orange;">**反元素**</mark>： $$a+ ({\color{orange}-a}) = \mathbf{0}$$
* <mark style="color:yellow;">**A4：加法**</mark><mark style="color:orange;">**交換律**</mark>： $$a+b=b+a$$
* <mark style="color:yellow;">**M1：乘法**</mark><mark style="color:orange;">**結合律**</mark>： $$(ab)c=a(bc)$$
* <mark style="color:yellow;">**D1：左**</mark><mark style="color:orange;">**分配律**</mark>： $$a(b+c)=ab+ac$$
* <mark style="color:yellow;">**D2：右**</mark><mark style="color:orange;">**分配律**</mark>： $$(a+b)c=ac+bc$$
{% endhint %}

{% hint style="info" %}
* 「<mark style="color:purple;">**環**</mark>」的<mark style="color:yellow;">**加法**</mark>一定是「<mark style="color:yellow;">**可**</mark>[**交換**](../group/commute.md)」，外加「<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**結合律**</mark>」與「<mark style="color:yellow;">**左右**</mark><mark style="color:orange;">**分配律**</mark>」的結構。
{% endhint %}

{% hint style="danger" %}
為了省掉一些旁枝末節的麻煩，我們不討論「<mark style="color:yellow;">**只有一個元素**</mark>」的環 ([ring](./))。

:point\_right: [identity](id.md#xing-zhi) 的[性質 1](id.md#xing-zhi) ： $$1 \neq 0$$
{% endhint %}

{% tabs %}
{% tab title="🗺️ 圖表" %}
<img src="../../.gitbook/assets/group.ring.field.svg" alt="代數結構" class="gitbook-drawing">
{% endtab %}

{% tab title="🧨 雷區" %}
{% hint style="warning" %}
「<mark style="color:yellow;">**ring**</mark>╱<mark style="color:purple;">**環**</mark>」的「<mark style="color:yellow;">**乘法**</mark>」：

* <mark style="color:red;">**不一定有**</mark>「<mark style="color:orange;">**交換律**</mark>」:exclamation:( :point\_right: 比較： [commut.md](commut.md "mention") )
* <mark style="color:red;">**不一定有**</mark>「[乘法單位元素](id.md)」:exclamation:
* 有「[乘法單位元素](id.md)」的<mark style="color:purple;">**環**</mark>，它的元素也不見得會有「[乘法反元素](unit.md)」:exclamation:&#x20;
{% endhint %}
{% endtab %}

{% tab title="🔴 主題" %}
* 「[commutative ring](commut.md)╱[commut.md](commut.md "mention")」：具有「<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**交換律**</mark>」的「<mark style="color:purple;">**環**</mark>」
* 「[id.md](id.md "mention")」 -> multiplicative identity
* 「[unit.md](unit.md "mention")」 -> multiplicative inverse
* 「[commut-with-id.md](commut-with-id.md "mention")」&#x20;
* 「[int-domain.md](int-domain.md "mention")」
* 「[skew-field.md](skew-field.md "mention")」
* 「[field](../field/ "mention")」：具有「[乘法單位元素](id.md)」與「[乘法反元素](unit.md)」的「[交換環](commut.md)」
{% endtab %}

{% tab title="👥 相關" %}
* [向量空間](../../linear/space/) (vector space)
* 「<mark style="color:purple;">**環**</mark>」：「<mark style="color:yellow;">**加法**</mark>[**交換群**](../group/commute.md)」外加「<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**結合律**</mark>」與「<mark style="color:orange;">**分配律**</mark>」的結構。
{% endtab %}

{% tab title="📗 參考" %}
* Contemporary Abstract Algebra (2017), Ch. 12 Rings, p.227.
* Socratica ⟩ [Abstract Algebra Playlist](https://youtube.com/playlist?list=RDCMUCW6TXMZ5Pq6yL6_k5NZ2e0Q\&playnext=1) ⭐️
{% endtab %}

{% tab title="🖥️ 影片" %}
{% embed url="https://youtu.be/6RC70C9FNXI" %}
the definition of a Ring
{% endembed %}

{% embed url="https://youtu.be/j_f7O-4Rb9U" %}
Ring Definition
{% endembed %}

{% embed url="https://youtu.be/_RTHvweHlhE" %}
Ring Examples
{% endembed %}
{% endtab %}
{% endtabs %}
