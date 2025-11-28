---
description: ╱🚧 under construction ->
---

# 🚧 非負實數乘法

[數學](../../../../) ⟩ [數系](../../../) ⟩ [實數](../../) ⟩ [建造](../) ⟩ [乘法](./) ⟩ 非負實數乘法

{% hint style="success" %}
![](<../../../../.gitbook/assets/definition 81x31.png>) 若 $${\color{orange}a}, {\color{orange}b} \in {\color{orange}\mathbb{R}}$$，當 $${\color{orange}a}, {\color{orange}b} \ge {\color{orange}\mathbb{𝟘}}$$ 時，定義：&#x20;

$${\color{orange}ab} = \{ \ pq \in {\color{orange}\mathbb{Q}} \ | \  0 \le p \in {\color{orange}a}, \ 0 \le q \in {\color{orange}b} \} \cup {\color{orange}\mathbb{𝟘}}$$&#x20;
{% endhint %}

:star: 註： $${\color{orange}\mathbf{𝟘}} = (-\infty, 0 ) = \{ \ p \in {\color{orange}\mathbb{Q}} \ | \ p < 0 \ \}$$

{% tabs %}
{% tab title="👥 先備知識" %}
* [reals](../reals/ "mention")
* [zero.md](../add/zero.md "mention")&#x20;
* [negative.md](../add/negative.md "mention")&#x20;
{% endtab %}

{% tab title="⬇️ 推論" %}
* [nonneg\_props.md](nonneg_props.md "mention")
{% endtab %}

{% tab title="📗 參考" %}
* Understanding Analysis ⟩ 8.6 A Construction of R From Q
{% endtab %}
{% endtabs %}

首先，必須證明 $${\color{orange}ab} \in \color{orange}\mathbb{R}$$，否則乘法沒有「<mark style="color:orange;">封閉性</mark>」就無法構成一個數系([field](../../../../algebra/field/))。

## 乘法封閉性 <a href="#properties" id="properties"></a>

{% hint style="info" %}
當 $${\color{orange}a}, {\color{orange}b} \ge {\color{orange}\mathbb{𝟘}}$$ 時： $${\color{orange}ab} \in \color{orange}\mathbb{R}$$ （<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**封閉性**</mark>）
{% endhint %}

![](<../../../../.gitbook/assets/proof 79x30.png>)  要證明 $${\color{orange}ab}$$ 是一個「[戴德金分割](../reals/dedekind-cut.md)」，必須符合下列三條件：

* <mark style="color:yellow;">**DC1**</mark> (非特化)：$${\color{orange}ab} \neq {\color{orange}\phi}, \ {\color{orange}\mathbb{Q}}$$（ $$\exists p \in {\color{orange}ab}, \exists x \notin {\color{orange}ab}$$ ）&#x20;
* <mark style="color:yellow;">**DC2**</mark> (左半線)：$$p < q \ \land \ q \in {\color{orange}ab}\implies p \in {\color{orange}ab}$$&#x20;
* <mark style="color:yellow;">**DC3**</mark> (開放性)：$$p \in {\color{orange}ab}\implies \exists q \in {\color{orange}ab}, \ \ni p < q$$ ($${\color{orange}ab}$$ <mark style="color:red;">**沒有**</mark><mark style="color:orange;">最大值</mark>)

{% tabs %}
{% tab title="DC1" %}
{% hint style="info" %}
⑴ <mark style="color:yellow;">**DC1**</mark> (非特化)：$${\color{orange}ab} \neq {\color{orange}\phi}, \ {\color{orange}\mathbb{Q}}$$（ $$\exists p \in {\color{orange}ab}, \exists x \notin {\color{orange}ab}$$ ）&#x20;
{% endhint %}

![](<../../../../.gitbook/assets/proof 79x30.png>) &#x20;

1. 因為： $${\color{orange}\mathbb{𝟘}} \subseteq {\color{orange}ab}$$，所以： $${\color{orange}ab} \neq {\color{orange}\phi}$$&#x20;
2. 因為： $${\color{orange}a}, {\color{orange}b} \in {\color{orange}\mathbb{R}}$$，根據「[戴德金分割](../reals/#dedekind-cut)」定義 <mark style="color:yellow;">**DC1**</mark> ：\
   　⇨　 $$\exists \alpha, \beta \in {\color{orange}\mathbb{Q}}, \ \ni \alpha \notin {\color{orange}a}, \ \beta \notin {\color{orange}b}$$ ，\
   但因為： $${\color{orange}a} \ge {\color{orange}\mathbb{𝟘}}, \,  {\color{orange}b} \ge {\color{orange}\mathbb{𝟘}}$$，也就是 $${\color{orange}a} \supseteq {\color{orange}\mathbb{𝟘}}, \,  {\color{orange}b} \supseteq {\color{orange}\mathbb{𝟘}}$$，\
   所以 $$\alpha \ge 0, \beta \ge 0$$ 必須成立，否則會導致 $$\alpha \in {\color{orange}a}$$ 或 $$\beta \in {\color{orange}b}$$ 而矛盾。
3. 從上一點可知 $$\alpha \beta \ge 0$$，所以： $$\alpha \beta  \notin {\color{orange}\mathbb{𝟘}}$$
4. 另外，根據「[戴德金分割](../reals/#dedekind-cut)」性質： $$\alpha, \beta$$ 必分別為 $${\color{orange}a, b}$$ 的<mark style="color:yellow;">**上界**</mark>，因此若存在 $$0 \le p \in {\color{orange}a}, \ 0 \le q \in {\color{orange}b}$$，則： \
   　⇨　 $$0 \le p < \alpha, \ 0 \le q < \beta$$\
   　⇨　 $$pq < \alpha \beta$$\
   因此 $$\alpha \beta \notin \{ \ pq \in {\color{orange}\mathbb{Q}} \ | \  0 \le p \in {\color{orange}a}, \ 0 \le q \in {\color{orange}b} \}$$
5. 綜合以上 (3)(4) 兩點： $$\alpha \beta  \notin {\color{orange}ab}$$&#x20;
6. 綜合以上 (1)(5) 兩點： $${\color{orange}ab} \neq {\color{orange}\phi}, \ {\color{orange}\mathbb{Q}}$$  <mark style="color:blue;">▨</mark>
{% endtab %}

{% tab title="DC2" %}
{% hint style="info" %}
⑵ <mark style="color:yellow;">**DC2**</mark> (左半線)：$$p < q \ \land \ q \in {\color{orange}ab}\implies p \in {\color{orange}ab}$$&#x20;
{% endhint %}

![](<../../../../.gitbook/assets/proof 79x30.png>) （以下 $$p, q \in {\color{orange}\mathbb{Q}}$$）

若 $$p < q$$ 且 $$q \in {\color{orange}ab}$$，則：

1. 狀況一：  $$p<0$$，則： $$p \in {\color{orange}\mathbb{𝟘}} \subseteq {\color{orange}ab}$$
2. 狀況二：  $$p \ge 0$$，則： \
   　$$0 \le p < q \in \{ \ rs \in {\color{orange}\mathbb{Q}} \ | \  0 \le r \in {\color{orange}a}, \ 0 \le s \in {\color{orange}b} \}$$ \
   假設： $$q=rs$$ 其中 $$0 < r \in {\color{orange}a}, \ 0 < s \in {\color{orange}b}$$\
   (註： $$r, s \neq 0$$ 否則 $$q=0$$ )\
   　⇨ $$p = q\cdot \frac{p}{q} = rs \cdot \frac{p}{q} = r \left( s \cdot \frac{p}{q} \right)$$\
   令： $$s' = s \cdot \frac{p}{q}$$ ，因為： $$0 \le \frac{p}{q} < 1$$  \
   　⇨  $$0 \le s \cdot\frac{p}{q} < s$$  \
   　⇨ $$0\le s' < s$$\
   根據「[戴德金分割](../reals/dedekind-cut.md)」<mark style="color:yellow;">**DC2**</mark> (左半線)性質： \
   　$$s'<s \implies s'\in {\color{orange}b}$$\
   因此：\
   　 $$p=rs' \in \{ \ rs \in {\color{orange}\mathbb{Q}} \ | \  0 \le r \in {\color{orange}a}, \ 0 \le s \in {\color{orange}b} \} \subseteq {\color{orange}ab}$$&#x20;
3. 根據以上兩點： $$p \in {\color{orange}ab}$$ <mark style="color:blue;">▨</mark>
{% endtab %}

{% tab title="DC3" %}
{% hint style="info" %}
⑶ <mark style="color:yellow;">**DC3**</mark> (開放性)：$$p \in {\color{orange}ab}\implies \exists q \in {\color{orange}ab}, \ \ni p < q$$ \
($${\color{orange}ab}$$ <mark style="color:red;">**沒有**</mark><mark style="color:orange;">最大值</mark>)
{% endhint %}

![](<../../../../.gitbook/assets/proof 79x30.png>)  （以下 $$p, q \in {\color{orange}\mathbb{Q}}$$）

若 $$p \in {\color{orange}ab}$$，則：

1. 狀況一：  $$p \in {\color{orange}\mathbb{𝟘}}$$，也就是 $$p<0$$，\
   令  $$q = \frac{p}{2}$$，則 $$p<q<0$$ ，因此 $$q \in {\color{orange}\mathbb{𝟘}} \subseteq {\color{orange}ab}$$<br>
2. 狀況二：  $$p \in \{ \ rs \in {\color{orange}\mathbb{Q}} \ | \  0 \le r \in {\color{orange}a}, \ 0 \le s \in {\color{orange}b} \}$$ \
   假設： $$p=rs$$ 其中 $$0 \le r \in {\color{orange}a}, \ 0 \le s \in {\color{orange}b}$$\
   根據「[戴德金分割](../reals/dedekind-cut.md)」<mark style="color:yellow;">**DC3**</mark> (開放性)性質：\
   　$$\exists r',s'  \in {\color{orange}\mathbb{Q}}, \ni r<r' \in {\color{orange}a}, \  s<s' \in {\color{orange}b}$$\
   令： $$q=r's'$$ ，則： $$q \in \{ \ rs \in {\color{orange}\mathbb{Q}} \ | \  0 \le r \in {\color{orange}a}, \ 0 \le s \in {\color{orange}b} \} \subseteq {\color{orange}ab}$$  \
   且 $$p = rs < r's'=q$$<br>
3. 根據以上兩點： $$\exists q \in {\color{orange}ab}, \ \ni p < q$$ <mark style="color:blue;">▨</mark>
{% endtab %}
{% endtabs %}
