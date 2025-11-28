# 🔰 (-∞,r) 是戴德金分割

[數學](../../../../) ⟩ [數系](../../../) ⟩ [實數](../../) ⟩ [建造](../) ⟩ [定義實數](./) ⟩ (-∞,r) 是戴德金分割

{% hint style="success" %}
* $${\color{orange}a}  = (-\infty, r) = \{ \ q \in \mathbb{Q} \ | \ q < r \}$$ 是「[戴德金分割](dedekind-cut.md)」，其中 $$r \in \mathbb{Q}$$
{% endhint %}

## 證明 <a href="#proof" id="proof"></a>

{% tabs %}
{% tab title="🔸  DC1" %}
{% hint style="info" %}
<mark style="color:yellow;">**DC1**</mark>：$${\color{orange}a} \neq \phi, \ {\color{orange}a} \neq \mathbb{Q}$$（ $${\color{orange}a}$$ <mark style="color:red;">**不是**</mark><mark style="color:yellow;">**空集合**</mark>，也<mark style="color:red;">**不是**</mark>整個<mark style="color:yellow;">**有理數集**</mark> ）
{% endhint %}

<img src="../../../../.gitbook/assets/file.excalidraw (4).svg" alt="「戴德金分割」定義：(DC1)" class="gitbook-drawing">
{% endtab %}

{% tab title="🔸 DC2" %}
{% hint style="info" %}
<mark style="color:yellow;">**DC2**</mark>：$$p < q \in {\color{orange}a} \implies p \in {\color{orange}a}$$ （ $${\color{orange}a}$$ <mark style="color:yellow;">**是左半數線**</mark> ）
{% endhint %}

<img src="../../../../.gitbook/assets/file.excalidraw (1).svg" alt="「戴德金分割」定義：(DC2)" class="gitbook-drawing">
{% endtab %}

{% tab title="🔸 DC3" %}
{% hint style="info" %}
<mark style="color:yellow;">**DC3**</mark>：$$q \in {\color{orange}a} \implies \exists q' \in {\color{orange}a}, \ \ni q < q'$$ （ $${\color{orange}a}$$ 中<mark style="color:red;">**沒有**</mark><mark style="color:yellow;">**最大值**</mark> ）
{% endhint %}

<img src="../../../../.gitbook/assets/file.excalidraw (5).svg" alt="" class="gitbook-drawing">
{% endtab %}

{% tab title="📗 參考" %}
* [ ] Understanding Analysis ⟩ 8.6 A Construction of R From Q
* [ ] wiki ⟩ [Dedekind cut](https://en.wikipedia.org/wiki/Dedekind_cut)
{% endtab %}
{% endtabs %}
