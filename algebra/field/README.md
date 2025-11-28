---
description: ╱ 🚧 -> 列出明確的條件
---

# 🚧 Field╱體

[代數](../) ⟩ [系統](../system.md) ⟩ 體 (field)

{% hint style="success" %}
A field is a [commutative ring](../ring/commut.md) with [unity](../ring/id.md) in which <mark style="color:yellow;">**every nonzero element**</mark> is a [unit](../ring/unit.md).
{% endhint %}

{% hint style="info" %}
「[交換環](../ring/commut.md)╱<mark style="color:yellow;">**commutative ring**</mark>」 $$(\mathbf{R,+,\cdot)}$$ 的兩個必要運算：

* <mark style="color:yellow;">**加法**</mark>： $$a+b \in \mathbf{R}$$ (<mark style="color:yellow;">**加法**</mark><mark style="color:orange;">**封閉性**</mark>)
* <mark style="color:yellow;">**乘法**</mark>： $$a\cdot b \in \mathbf{R}$$ (<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**封閉性**</mark>) (註：習慣上會省略乘法符號)

且兩運算符合以下 <mark style="color:yellow;">**8**</mark> 條件：

* <mark style="color:yellow;">**A1：加法**</mark><mark style="color:orange;">**結合律**</mark>： $$(a+b)+c=a+(b+c)$$
* <mark style="color:yellow;">**A2：加法**</mark><mark style="color:orange;">**零元素**</mark>： $$a + {\color{orange}\mathbf{0}} = a$$
* <mark style="color:yellow;">**A3：加法**</mark><mark style="color:orange;">**反元素**</mark>： $$a+ ({\color{orange}-a}) = \mathbf{0}$$
* <mark style="color:yellow;">**A4：加法**</mark><mark style="color:orange;">**交換律**</mark>： $$a+b=b+a$$
* <mark style="color:yellow;">**M1：乘法**</mark><mark style="color:orange;">**結合律**</mark>： $$(ab)c=a(bc)$$
* <mark style="color:yellow;">**M4：乘法**</mark><mark style="color:orange;">**交換律**</mark>： $$ab=ba$$（⭐️ <mark style="color:yellow;">**M4**</mark> 為[交換環](../ring/commut.md)特有性質，其他為[環](../ring/)的性質）
* <mark style="color:yellow;">**D1：左**</mark><mark style="color:orange;">**分配律**</mark>： $$a(b+c)=ab+ac$$
* <mark style="color:yellow;">**D2：右**</mark><mark style="color:orange;">**分配律**</mark>： $$(a+b)c=ac+bc$$
{% endhint %}

{% hint style="warning" %}
「<mark style="color:purple;">**體**</mark>」有別於「[交換環](../ring/commut.md)」的特有性質：

* <mark style="color:yellow;">**M2：乘法**</mark><mark style="color:orange;">**單位元素**</mark>： $${\color{orange}\mathbf{1}} a=a {\color{orange}\mathbf{1}}=a$$
* <mark style="color:yellow;">**M3：乘法**</mark><mark style="color:orange;">**反元素**</mark>： $$a {\color{orange}a^{-1}} = {\color{orange}a^{-1}} a = \mathbf{1} \ (a \neq  \mathbf{0})$$
{% endhint %}

{% tabs %}
{% tab title="🗺️ 圖表" %}
<img src="../../.gitbook/assets/group.ring.field.svg" alt="代數結構" class="gitbook-drawing">
{% endtab %}

{% tab title="👥 相關" %}
* [實數](../../num/real/) ⟩ [建造](../../num/real/def/) ⟩ [add.md](../../num/real/def/add/add.md "mention")
* 「<mark style="color:yellow;">**field**</mark>╱<mark style="color:purple;">體</mark>」的範例： [real](../../num/real/ "mention")、[complex](../../num/complex/ "mention")
{% endtab %}

{% tab title="📗 參考" %}
* Socratica ⟩ [Abstract Algebra Playlist](https://youtube.com/playlist?list=RDCMUCW6TXMZ5Pq6yL6_k5NZ2e0Q\&playnext=1) ⭐️
* Contemporary Abstract Algebra (2017), Ch. 13 Integral Domains, p.239
{% endtab %}

{% tab title="🖥️ 影片" %}
{% embed url="https://youtu.be/KCSZ4QhOw0I" %}
Field Definition
{% endembed %}

{% embed url="https://youtu.be/9hmr_Fjot_8" %}
Field Examples
{% endembed %}
{% endtab %}
{% endtabs %}
