# 🔰 交換環

[代數](../) ⟩ [環](./) ⟩ 交換環

{% hint style="success" %}
具有「<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**交換律**</mark>」的「[環](./)╱[ring](./)」，稱為 <mark style="color:yellow;">**commutative ring**</mark> (<mark style="color:purple;">**交換環**</mark>)。

* <mark style="color:yellow;">**M4：乘法**</mark><mark style="color:orange;">**交換律**</mark>： $$ab=ba$$
{% endhint %}

{% hint style="info" %}
「[交換環](commut.md)╱<mark style="color:yellow;">**commutative ring**</mark>」 $$(\mathbf{R,+,\cdot)}$$ 的兩個必要運算：

* <mark style="color:yellow;">**加法**</mark>： $$a+b \in \mathbf{R}$$ (<mark style="color:yellow;">**加法**</mark><mark style="color:orange;">**封閉性**</mark>)
* <mark style="color:yellow;">**乘法**</mark>： $$a\cdot b \in \mathbf{R}$$ (<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**封閉性**</mark>) (註：習慣上會省略乘法符號)

且兩運算符合以下 <mark style="color:yellow;">**8**</mark> 條件：

* <mark style="color:yellow;">**A1：加法**</mark><mark style="color:orange;">**結合律**</mark>： $$(a+b)+c=a+(b+c)$$
* <mark style="color:yellow;">**A2：加法**</mark><mark style="color:orange;">**零元素**</mark>： $$a + {\color{orange}\mathbf{0}} = a$$
* <mark style="color:yellow;">**A3：加法**</mark><mark style="color:orange;">**反元素**</mark>： $$a+ ({\color{orange}-a}) = \mathbf{0}$$
* <mark style="color:yellow;">**A4：加法**</mark><mark style="color:orange;">**交換律**</mark>： $$a+b=b+a$$
* <mark style="color:yellow;">**M1：乘法**</mark><mark style="color:orange;">**結合律**</mark>： $$(ab)c=a(bc)$$
* <mark style="color:yellow;">**M4：乘法**</mark><mark style="color:orange;">**交換律**</mark>： $$ab=ba$$（⭐️ <mark style="color:yellow;">**M4**</mark>為 [交換環](commut.md)特有性質，其他為[環](./)的性質）
* <mark style="color:yellow;">**D1：左**</mark><mark style="color:orange;">**分配律**</mark>： $$a(b+c)=ab+ac$$
* <mark style="color:yellow;">**D2：右**</mark><mark style="color:orange;">**分配律**</mark>： $$(a+b)c=ac+bc$$
{% endhint %}

{% tabs %}
{% tab title="🗺️ 圖表" %}
<img src="../../.gitbook/assets/group.ring.field.svg" alt="代數結構" class="gitbook-drawing">
{% endtab %}

{% tab title="👥 相關" %}
* A [field](../field/) is a <mark style="color:purple;">**commutative ring**</mark> with [unity](id.md) in which <mark style="color:yellow;">**every nonzero element**</mark> is a [unit](unit.md).
{% endtab %}

{% tab title="📗 參考" %}
* Contemporary Abstract Algebra (2017), Ch. 12 Rings, p.228.
{% endtab %}
{% endtabs %}
