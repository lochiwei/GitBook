---
description: Archimedean Property
---

# 🔰 阿基米德性質

[數學](../../) ⟩ [數系](../) ⟩ [有理數](./) ⟩ 阿基米德性質

{% hint style="success" %}
&#x20;$$\forall x, y \in {\color{orange}\mathbb{Q}}^+, \exists n \in {\color{orange}\mathbb{N}} \ \ni nx > y$$
{% endhint %}

<details>

<summary><img src="../../.gitbook/assets/proof 79x30.png" alt=""></summary>

我們必須找到一個夠大的 $$n$$，使得 $$n\cdot \frac{x}{y} > 1$$。

因為 $$x, y \in {\color{orange}\mathbb{Q}}^+$$，所以 $$\frac{x}{y}$$ 依然是個正有理數。

假設 $$\frac{x}{y}=\frac{q}{p}$$，其中 $$p,q \in {\color{orange}\mathbb{N}}$$：

若我們設 $$n=p$$，則：

$$n \cdot \frac{x}{y}= \cancel{p} \cdot\frac{q}{\cancel{p}} = q$$

這時因為 $$q \in {\color{orange}\mathbb{N}}$$，所以可能 $$q=1$$，因此 $$n=p$$ 可能還是不夠大。不過我們只要再調大一點，將 $$n$$ 設為 $$p+1$$ 就可以了，因為 $$n=p+1$$ 時：

&#x20;$$n \cdot \frac{x}{y} = (p+1)\cdot \frac{q}{p} > \cancel{p} \cdot \frac{q}{\cancel{p}} = q \ge 1$$

這時我們可以保證 $$n$$ 足夠大，可以讓 $$n\cdot \frac{x}{y} > 1$$，因此 $$nx>y$$  ▨

</details>

{% tabs %}
{% tab title="👥 相關" %}
* 實數的加法性質：[A3](../real/def/add/prop.md#a3)╱<mark style="color:yellow;">**加法**</mark><mark style="color:orange;">**反元素**</mark>： $${\color{orange}a}+ ({\color{orange}-a}) = {\color{orange}\mathbf{𝟘}}$$
{% endtab %}

{% tab title="📗 參考" %}
* wiki ⟩ [阿基米德性質](https://zh.wikipedia.org/zh-tw/%E9%98%BF%E5%9F%BA%E7%B1%B3%E5%BE%B7%E5%85%AC%E7%90%86)
{% endtab %}
{% endtabs %}

## 推論 <a href="#lemma" id="lemma"></a>

{% hint style="info" %}
⑴ $$\forall r \in {\color{orange}\mathbb{Q}}, \exists n \in {\color{orange}\mathbb{N}} \ \ni n > r$$ （ $${\color{orange}\mathbb{Q}}$$ 沒有<mark style="color:orange;">最大值</mark> ）

⑵ $$\forall \epsilon \in {\color{orange}\mathbb{Q}}^+, \exists n \in {\color{orange}\mathbb{N}} \ \ni 0 < \frac{1}{n} < \epsilon$$ （ $${\color{orange}\mathbb{Q}}^+$$ 沒有<mark style="color:orange;">最小值</mark> ）
{% endhint %}

<div align="left"><figure><img src="../../.gitbook/assets/proof 79x30.png" alt=""><figcaption></figcaption></figure></div>

{% tabs %}
{% tab title="⑴" %}
{% hint style="info" %}
⑴ $$\forall r \in {\color{orange}\mathbb{Q}}, \exists n \in {\color{orange}\mathbb{N}} \ \ni n > r$$ （ $${\color{orange}\mathbb{Q}}$$ 沒有<mark style="color:orange;">最大值</mark> ）
{% endhint %}

1. 若 $$r\le 0$$，取 $$n=1$$ 即可。
2. 若 $$r>0$$，則在上方的「<mark style="color:purple;">阿基米德性質</mark>」中取 $$x=1, y=r$$ 即可。  ▨
{% endtab %}

{% tab title="⑵" %}
{% hint style="info" %}
⑵ $$\forall \epsilon \in {\color{orange}\mathbb{Q}}^+, \exists n \in {\color{orange}\mathbb{N}} \ \ni 0 < \frac{1}{n} < \epsilon$$ （ $${\color{orange}\mathbb{Q}}^+$$ 沒有<mark style="color:orange;">最小值</mark> ）
{% endhint %}

在上方的「<mark style="color:purple;">阿基米德性質</mark>」中取 $$x=\epsilon, y=1$$ 可得：\
$$\exists n \in {\color{orange}\mathbb{N}} \ \ni n \epsilon > 1$$

兩邊同除 $$n$$ 可得：\
$$\epsilon > \frac{1}{n}$$
{% endtab %}
{% endtabs %}

