---
description: 1️⃣2️⃣3️⃣4️⃣5️⃣6️⃣7️⃣╱🚧 under construction
---

# 🚧 非負實數運算性質

[數學](../../../../) ⟩ [數系](../../../) ⟩ [實數](../../) ⟩ [建造](../) ⟩ 非負實數運算性質

{% hint style="success" %}
當 $${\color{orange}a}, {\color{orange}b}, {\color{orange}c}  \ge {\color{orange}\mathbb{𝟘}}$$ 時：

* 1️⃣ $${\color{orange}a} + {\color{orange}b} \ge {\color{orange}\mathbb{𝟘}}$$ （<mark style="color:yellow;">**加法**</mark>在 $${\color{orange}\mathbb{R}}^+ \cup \{ {\color{orange}\mathbb{𝟘}} \}$$ <mark style="color:orange;">**封閉**</mark>）
* 2️⃣ $${\color{orange}ab} \ge {\color{orange}\mathbb{𝟘}}$$ （<mark style="color:yellow;">**乘法**</mark>在 $${\color{orange}\mathbb{R}}^+ \cup \{ {\color{orange}\mathbb{𝟘}} \}$$ <mark style="color:orange;">**封閉**</mark>）
* 3️⃣ $${\color{orange}𝟘} \cdot {\color{orange}a} = {\color{orange}a} \cdot  {\color{orange}𝟘} = {\color{orange}𝟘}$$  （<mark style="color:yellow;">**加法**</mark><mark style="color:orange;">**單位元素**</mark>）
* 4️⃣ $${\color{orange}\mathbf{𝕝}} \cdot {\color{orange}a} = {\color{orange}a} \cdot  {\color{orange}\mathbf{𝕝}} = {\color{orange}a}$$   （<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**單位元素**</mark>）
* 5️⃣ $${\color{orange}ab} = {\color{orange}ba}$$ （<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**交換律**</mark>）
* 6️⃣ $${\color{orange}a} ( {\color{orange}b} + {\color{orange}c}) = {\color{orange}ab} + {\color{orange}ac}$$  （<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**分配律**</mark>）
* 7️⃣ 若 $${\color{orange}a} > {\color{orange}𝟘}$$ 則 $$0 \in {\color{orange}a}$$
{% endhint %}

{% tabs %}
{% tab title="👥 先備" %}
* [order.md](../order.md "mention")
* [zero.md](../add/zero.md "mention")
* [add.md](../add/add.md "mention")
* [nonnegative.md](nonnegative.md "mention")
{% endtab %}

{% tab title="📗 參考" %}
* Understanding Analysis ⟩ 8.6 A Construction of R From Q
{% endtab %}
{% endtabs %}

## 性質證明 <a href="#proof" id="proof"></a>

{% tabs %}
{% tab title="1️⃣" %}
{% hint style="info" %}
1️⃣ 若 $${\color{orange}a}, {\color{orange}b} \ge {\color{orange}\mathbb{𝟘}}$$，則： $${\color{orange}a} + {\color{orange}b} \ge {\color{orange}\mathbb{𝟘}}$$&#x20;
{% endhint %}

![](<../../../../.gitbook/assets/proof 79x30.png>)

若要證明 $${\color{orange}a} + {\color{orange}b} \ge {\color{orange}\mathbb{𝟘}}$$，則必須證明 $${\color{orange}𝟘} \subseteq {\color{orange}a} + {\color{orange}b}$$ (參考[實數順序](../order.md)的定義)，也就是要證明 $$\forall r \in {\color{orange}𝟘}, \exists p \in {\color{orange}a}, q \in {\color{orange}b} \ni r = p+q$$

1. 因為 $$r \in {\color{orange}𝟘}$$，所以 $$r<0$$。
2. 令 $$p=q=\frac{r}{2}<0$$
3. 因為 $${\color{orange}a}, {\color{orange}b} \ge {\color{orange}\mathbb{𝟘}}$$，所以知道 $$\frac{r}{2} \in {\color{orange}𝟘} \subseteq {\color{orange}a}, {\color{orange}b}$$
4. 因此 $$r=\frac{r}{2}+\frac{r}{2}=p+q \in  {\color{orange}a} + {\color{orange}b}$$，故得證  ▨
{% endtab %}

{% tab title="2️⃣" %}
{% hint style="info" %}
2️⃣ 當 $${\color{orange}a}, {\color{orange}b} \ge {\color{orange}\mathbb{𝟘}}$$ 時：$${\color{orange}ab} \ge {\color{orange}\mathbb{𝟘}}$$ （<mark style="color:yellow;">**乘法**</mark>在 $${\color{orange}\mathbb{R}}^+ \cup \{ {\color{orange}\mathbb{𝟘}} \}$$ <mark style="color:orange;">**封閉**</mark>）
{% endhint %}

![](<../../../../.gitbook/assets/proof 79x30.png>)  &#x20;

1. 根據上面 $${\color{orange}ab}$$ 的定義： $${\color{orange}\mathbb{𝟘}} \subseteq {\color{orange}ab}$$&#x20;
2. 根據實數[順序](../order.md)的定義： $${\color{orange}\mathbb{𝟘}} \le {\color{orange}ab}$$  ▨
{% endtab %}

{% tab title="3️⃣" %}
{% hint style="info" %}
3️⃣ $${\color{orange}𝟘} \cdot {\color{orange}a} = {\color{orange}a} \cdot  {\color{orange}𝟘} = {\color{orange}𝟘}$$  （<mark style="color:yellow;">**加法**</mark><mark style="color:orange;">**單位元素**</mark>）
{% endhint %}

&#x20;![](<../../../../.gitbook/assets/proof 79x30.png>)

1. 根據[非負實數乘法](nonnegative.md)定義：當 $${\color{orange}a}, {\color{orange}b} \ge {\color{orange}\mathbb{𝟘}}$$ 時， $${\color{orange}ab} = \{ \ pq \in {\color{orange}\mathbb{Q}} \ | \  0 \le p \in {\color{orange}a}, \ 0 \le q \in {\color{orange}b} \} \cup {\color{orange}\mathbb{𝟘}}$$
2. 但如果 $${\color{orange}a} = {\color{orange}𝟘}$$ 或 $${\color{orange}b} = {\color{orange}𝟘}$$ 時， $$\{ \ pq \in {\color{orange}\mathbb{Q}} \ | \  0 \le p \in {\color{orange}a}, \ 0 \le q \in {\color{orange}b} \}$$ 會變成空集合
3. 因此 $${\color{orange}ab} = \empty \cup {\color{orange}𝟘} = {\color{orange}𝟘}$$，故得證  ▨
{% endtab %}

{% tab title="4️⃣" %}
{% hint style="info" %}
4️⃣ $${\color{orange}\mathbf{𝕝}} \cdot {\color{orange}a} = {\color{orange}a} \cdot  {\color{orange}\mathbf{𝕝}} = {\color{orange}a}$$   （<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**單位元素**</mark>）
{% endhint %}

&#x20;![](<../../../../.gitbook/assets/proof 79x30.png>)

根據性質 5️⃣ $${\color{orange}ab} = {\color{orange}ba}$$ 可知：  $${\color{orange}\mathbf{𝕝}} \cdot {\color{orange}a} = {\color{orange}a} \cdot  {\color{orange}\mathbf{𝕝}}$$，因此我們只要證明 $${\color{orange}a} \cdot  {\color{orange}\mathbf{𝕝}} = {\color{orange}a}$$ 即可，也就是證明 $${\color{orange}a} \cdot  {\color{orange}\mathbf{𝕝}} \subseteq {\color{orange}a}$$ 且 $${\color{orange}a} \cdot  {\color{orange}\mathbf{𝕝}} \supseteq {\color{orange}a}$$。

***

首先，我們先證明 $${\color{orange}a} \cdot  {\color{orange}\mathbf{𝕝}} \subseteq {\color{orange}a}$$：

1. 若 $$\alpha \in {\color{orange}a} \cdot {\color{orange}𝕝}$$，則 $$\alpha < 0$$ 或 $$\alpha = pq$$，其中 $$0 \le p \in {\color{orange}a}, 0 \le q < 1$$
2. 若 $$\alpha < 0$$ ，則 $$\alpha \in {\color{orange}𝟘} \subseteq {\color{orange}a}$$（因為 $${\color{orange}a} \ge {\color{orange}𝟘}$$），因此 $$\alpha \in  {\color{orange}a}$$
3. 若 $$\alpha = pq$$ ，其中 $$0 \le p \in {\color{orange}a}, 0 \le q < 1$$，則對 $$0 \le q < 1$$ 同時乘以 $$p$$ 可得： $$0 \le pq \le p$$
4. 因為 $$pq \le p$$ 且 $$p \in {\color{orange}a}$$，因此 $$pq = \alpha \in {\color{orange}a}$$ （[戴德金分割](../reals/dedekind-cut.md) ⑵ <mark style="color:yellow;">**DC2**</mark> 左半線性質）
5. 由 2. 與 4. 知：若 $$\alpha \in {\color{orange}a} \cdot {\color{orange}𝕝}$$，則 $$\alpha \in  {\color{orange}a}$$ ，因此 $${\color{orange}a} \cdot  {\color{orange}\mathbf{𝕝}} \subseteq {\color{orange}a}$$

***

另一方面，我們必須證明 $${\color{orange}a}  \subseteq  {\color{orange}a} \cdot  {\color{orange}𝕝}$$：

1. 若 $$p \in  {\color{orange}a}$$，則 $$p < 0$$ 或 $$0 \le p \in {\color{orange}a}$$
2. 若 $$p < 0$$，則 $$p \in {\color{orange}𝟘} \subseteq {\color{orange}a} \cdot {\color{orange}𝕝}$$ （ 由性質 ⑵ 可知：$${\color{orange}a} \cdot {\color{orange}𝕝} \ge {\color{orange}𝟘}$$ ），因此 $$p \in  {\color{orange}a} \cdot {\color{orange}𝕝}$$
3. 若 $$0 \le p \in {\color{orange}a}$$，則存在 $$q \in {\color{orange}a}$$ 使得 $$p<q$$ （[戴德金分割](../reals/dedekind-cut.md) ⑶ <mark style="color:yellow;">**DC3**</mark> 開放性）
4. 因此： $$p=q \cdot \frac{p}{q}$$，其中因為 $$0 \le p < q$$，所以 $$0 \le \frac{p}{q} <1$$
5. 因為 $$0 \le q \in {\color{orange}a}$$ 且 $$0 \le \frac{p}{q} \in {\color{orange}𝕝}$$，因此 $$p=q \cdot \frac{p}{q} \in {\color{orange}a} \cdot {\color{orange}𝕝}$$
6. 由 2. 與 5. 知：若 $$p \in  {\color{orange}a}$$，則 $$p \in {\color{orange}a} \cdot {\color{orange}𝕝}$$ ，因此 $${\color{orange}a}  \subseteq  {\color{orange}a} \cdot  {\color{orange}𝕝}$$  ▨
{% endtab %}

{% tab title="5️⃣" %}
{% hint style="info" %}
&#x20;5️⃣ $${\color{orange}ab} = {\color{orange}ba}$$ （<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**交換律**</mark>）
{% endhint %}

![](<../../../../.gitbook/assets/proof 79x30.png>)&#x20;

根據定義，當 $${\color{orange}a}, {\color{orange}b} \ge {\color{orange}\mathbb{𝟘}}$$ 時：：

* $${\color{orange}ab} = \{ \ pq \in {\color{orange}\mathbb{Q}} \ | \  0 \le p \in {\color{orange}a}, \ 0 \le q \in {\color{orange}b} \} \cup {\color{orange}\mathbb{𝟘}}$$&#x20;
* $${\color{orange}ba} = \{ \ qp \in {\color{orange}\mathbb{Q}} \ | \ 0 \le q \in {\color{orange}b} , \ 0 \le p \in {\color{orange}a} \ \} \cup {\color{orange}\mathbb{𝟘}}$$&#x20;

但[有理數](../../../rational/)本身就具有<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**交換律**</mark>（ $$pq=qp$$ ），因此 $${\color{orange}ab} = {\color{orange}ba}$$  ▨
{% endtab %}

{% tab title="6️⃣ 🚧" %}
{% hint style="info" %}
6️⃣ $${\color{orange}a} ( {\color{orange}b} + {\color{orange}c}) = {\color{orange}ab} + {\color{orange}ac}$$  （<mark style="color:yellow;">**乘法**</mark><mark style="color:orange;">**分配律**</mark>）
{% endhint %}

![](<../../../../.gitbook/assets/proof 79x30.png>) 當 $${\color{orange}a}, {\color{orange}b}, {\color{orange}c}  \ge {\color{orange}\mathbb{𝟘}}$$ 時

根據性質 1️⃣ 知： $${\color{orange}b} + {\color{orange}c} \ge {\color{orange}\mathbb{𝟘}}$$，因此 $${\color{orange}a} ( {\color{orange}b} + {\color{orange}c})$$ 有[定義](nonnegative.md)\
根據性質 2️⃣ 知： $${\color{orange}a} ( {\color{orange}b} + {\color{orange}c}) \ge {\color{orange}𝟘}$$&#x20;

***

根據性質 2️⃣ 知： $${\color{orange}ab} \ge {\color{orange}\mathbb{𝟘}}$$, $${\color{orange}ac} \ge {\color{orange}\mathbb{𝟘}}$$\
根據性質 1️⃣ 知： $${\color{orange}ab} + {\color{orange}ac} \ge  {\color{orange}𝟘}$$

***

從上面的討論知道：等號的兩邊都是 $$\ge  {\color{orange}𝟘}$$ 的[戴德金分割](../reals/dedekind-cut.md)，但若要證明 $${\color{orange}a} ( {\color{orange}b} + {\color{orange}c}) = {\color{orange}ab} + {\color{orange}ac}$$，則必須證明兩點：⑴  $${\color{orange}a} ( {\color{orange}b} + {\color{orange}c}) \subseteq {\color{orange}ab} + {\color{orange}ac}$$  ⑵  $${\color{orange}a} ( {\color{orange}b} + {\color{orange}c}) \supseteq {\color{orange}ab} + {\color{orange}ac}$$

{% hint style="info" %}
證明：⑴ $${\color{orange}a} ( {\color{orange}b} + {\color{orange}c}) \subseteq {\color{orange}ab} + {\color{orange}ac}$$
{% endhint %}

1. 令 $$\alpha \in {\color{orange}a} ( {\color{orange}b} + {\color{orange}c})$$，則根據[非負實數乘法](nonnegative.md)定義： $$\alpha < 0$$ 或 $$\alpha = p(q+r)$$ 其中 $$0 \le p, \ 0 \le q+r \ (p \in {\color{orange}a}, \ q \in {\color{orange}b}, \ r \in {\color{orange}c} )$$&#x20;
2. 若 $$\alpha < 0$$，則 $$\alpha \in {\color{orange}𝟘} \le {\color{orange}ab} + {\color{orange}ac}$$，因此 $$\alpha \in  {\color{orange}ab} + {\color{orange}ac}$$   ⬚
3. 若 $$\alpha = p(q+r)$$ 其中 $$0 \le p, \ 0 \le q+r \ (p \in {\color{orange}a}, \ q \in {\color{orange}b}, \ r \in {\color{orange}c} )$$ \
   則 $$\alpha = pq+pr$$

{% hint style="info" %}
證明：⑵  $${\color{orange}a} ( {\color{orange}b} + {\color{orange}c}) \supseteq {\color{orange}ab} + {\color{orange}ac}$$
{% endhint %}
{% endtab %}

{% tab title="7️⃣" %}
{% hint style="info" %}
7️⃣ 若 $${\color{orange}a} > {\color{orange}𝟘}$$ 則 $$0 \in {\color{orange}a}$$
{% endhint %}

<div align="left"><figure><img src="../../../../.gitbook/assets/proof 79x30.png" alt=""><figcaption></figcaption></figure></div>

1. 因為 $${\color{orange}a} > {\color{orange}𝟘}$$，所以存在 $$p \in {\color{orange}a}$$ 使得 $$p \notin {\color{orange}𝟘}$$，換句話說 $$p \ge 0$$
2. 根據[戴德金分割](../reals/dedekind-cut.md#undefined-3)性質 2️⃣： $$0 \le p \in {\color{orange}a}$$ 可推得 $$0 \in {\color{orange}a}$$  ▨
{% endtab %}
{% endtabs %}



