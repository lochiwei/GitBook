---
description: ╱
---

# 🔸 identity╱乘法單位元素

[代數](../) ⟩ [環](./) ⟩ 乘法單位元素╱identity╱unity

{% hint style="success" %}
「環╱[ring](./)」中如果有「<mark style="color:yellow;">**非零元素**</mark> $${\color{orange}\mathbf{1}}$$ 」符合以下條件 ：

* <mark style="color:yellow;">**M2：乘法**</mark><mark style="color:orange;">**單位元素**</mark>： $${\color{orange}\mathbf{1}} a=a {\color{orange}\mathbf{1}}=a$$

則稱此元素為「<mark style="color:purple;">**乘法單位元素**</mark>╱<mark style="color:yellow;">**unity**</mark>╱<mark style="color:yellow;">**identity**</mark>」
{% endhint %}

{% tabs %}
{% tab title="🔸 性質" %}
{% hint style="info" %}
1. 若 $$(\mathbf{R,+,\cdot)}$$ 不只有一個元素，則： $$1 \neq 0$$
{% endhint %}

* 註：為了省掉一些旁枝末節的麻煩，我們不討論「只有一個元素」的環 (ring)。
* 🎖 證明：若 $$1=0$$，設 $$a ≠ 0$$，則 $$a = a1 = a0 = 0$$，顯然矛盾。
{% endtab %}

{% tab title="⭐️ 環" %}
{% hint style="info" %}
「[環](./)╱[ring](./)」 $$(\mathbf{R,+,\cdot)}$$ 的兩個必要運算：

* <mark style="color:yellow;">**加法**</mark>： $$a+b \in \mathbf{R}$$ (<mark style="color:yellow;">**加法**</mark><mark style="color:orange;">**封閉性**</mark>)
* <mark style="color:yellow;">**乘法**</mark>： $$a\cdot b \in \mathbf{R}$$ (<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**封閉性**</mark>) (註：習慣上會省略乘法符號)

而且這兩個運算符合以下 <mark style="color:yellow;">**7**</mark> 條件：

* <mark style="color:yellow;">**A1：加法**</mark><mark style="color:orange;">**結合律**</mark>： $$(a+b)+c=a+(b+c)$$
* <mark style="color:yellow;">**A2：加法**</mark><mark style="color:orange;">**單位元素**</mark> $$\mathbf{0}$$，使得 $$a + \mathbf{0} = a$$
* <mark style="color:yellow;">**A3：加法**</mark><mark style="color:orange;">**反元素**</mark> $$-a$$，使得 $$a+ (-a) = \mathbf{0}$$
* <mark style="color:yellow;">**A4：加法**</mark><mark style="color:orange;">**交換律**</mark>： $$a+b=b+a$$
* <mark style="color:yellow;">**M1：乘法**</mark><mark style="color:orange;">**結合律**</mark>： $$(ab)c=a(bc)$$
* <mark style="color:yellow;">**D1：左**</mark><mark style="color:orange;">**分配律**</mark>： $$a(b+c)=ab+ac$$
* <mark style="color:yellow;">**D2：右**</mark><mark style="color:orange;">**分配律**</mark>： $$(a+b)c=ac+bc$$
{% endhint %}
{% endtab %}

{% tab title="👥 相關" %}
* A [field](../field/) is a [commutative ring](commut.md) with <mark style="color:purple;">**unity**</mark> in which <mark style="color:yellow;">**every nonzero element**</mark> is a [unit](unit.md).
{% endtab %}

{% tab title="📗 參考" %}
* Contemporary Abstract Algebra (2017)
{% endtab %}
{% endtabs %}
