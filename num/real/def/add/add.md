# 🔰 定義實數加法 a + b

[數學](../../../../) ⟩ [數系](../../../) ⟩ [實數](../../) ⟩ [建造](../) ⟩ [加法](./) ⟩ 定義

{% hint style="success" %}
![](<../../../../.gitbook/assets/definition 81x31.png>) 若 $$a, b \in \mathbb{R}$$，我們定義： $${\color{orange}a+b} = \{ r+s |  r \in a, s \in b \}$$&#x20;
{% endhint %}

{% tabs %}
{% tab title="👥 先備" %}
* [dedekind-cut.md](../reals/dedekind-cut.md "mention")
{% endtab %}

{% tab title="👥 相關" %}
* [zero.md](zero.md "mention")&#x20;
* [negative.md](negative.md "mention")
{% endtab %}

{% tab title="⬇️ 推論" %}
* [nonneg\_props.md](../mult/nonneg_props.md "mention")
{% endtab %}

{% tab title="📗 參考" %}
* Understanding Analysis ⟩ 8.6 A Construction of R From Q
{% endtab %}
{% endtabs %}

## 加法封閉性 <a href="#properties" id="properties"></a>

{% hint style="info" %}
$${\color{orange}a+b}$$ 具有「<mark style="color:yellow;">**加法**</mark><mark style="color:orange;">**封閉性**</mark>」： $$a+b \in {\color{orange}\mathbb{R}}$$&#x20;
{% endhint %}

要證明 $$a+b \in {\color{orange}\mathbb{R}}$$ ，必須證明 $$a+b$$ 具有以下三點「[戴德金分割](../reals/dedekind-cut.md)」性質：

* ⑴ <mark style="color:yellow;">**DC1**</mark> (非特化)：$${\color{orange}a+b} \neq {\color{orange}\phi}, \ {\color{orange}\mathbb{Q}}$$&#x20;
* ⑵ <mark style="color:yellow;">**DC2**</mark> (左半線)：若 $$p < q$$ 且 $$q \in {\color{orange}a+b}$$ 則 $$p \in {\color{orange}a+b}$$
* ⑶ <mark style="color:yellow;">**DC3**</mark> (開放性)：$${\color{orange}a+b}$$ <mark style="color:red;">**沒有**</mark><mark style="color:orange;">最大值</mark>&#x20;

![](<../../../../.gitbook/assets/proof 79x30.png>) &#x20;

{% tabs %}
{% tab title="⑴" %}
{% hint style="info" %}
⑴ <mark style="color:yellow;">**DC1**</mark> (非特化)：$${\color{orange}a+b} \neq {\color{orange}\phi}, \ {\color{orange}\mathbb{Q}}$$&#x20;
{% endhint %}

因為 $$a , b \in {\color{orange}\mathbb{R}}$$， $$a, b$$ 都是「[戴德金分割](../reals/dedekind-cut.md)」：

1. 根據「[戴德金分割](../reals/dedekind-cut.md)定義 <mark style="color:yellow;">**DC1**</mark>」： \
   $$\exists p \in {\color{orange}a}, q \in {\color{orange}b}, \exists x \notin {\color{orange}a}, y \notin {\color{orange}b}$$<br>
2. 因爲 $$p+q \in {\color{orange}a+b}$$，所以 $${\color{orange}a+b} \neq {\color{orange}\phi}$$ <br>
3. 另外，根據「戴德金分割[補集性質](../reals/dedekind-cut.md#properties)」， $$x,y$$ 分別為 $${\color{orange}a,b}$$ 的上界，因此：\
   　⇨ $$\forall r \in {\color{orange}a}, \forall s \in {\color{orange}b} \ (r < x, s < y)$$ \
   　⇨ $$\forall r \in {\color{orange}a}, \forall s \in {\color{orange}b} \ (r +s< x+y)$$\
   換句話說 $${\color{orange}a+b}$$ 中的<mark style="color:yellow;">**所有元素**</mark>都小於 $$x+y$$，因此 $$x+y \notin {\color{orange}a+b}$$，\
   所以 $${\color{orange}a+b} \neq {\color{orange}\mathbb{Q}}$$   ▨
{% endtab %}

{% tab title="⑵" %}
{% hint style="info" %}
⑵ <mark style="color:yellow;">**DC2**</mark> (左半線)：若 $$p < q$$ 且 $$q \in {\color{orange}a+b}$$ 則 $$p \in {\color{orange}a+b}$$
{% endhint %}

1. 因為 $$q \in {\color{orange}a+b}$$，所以假設 $$q=r+s$$，其中 $$r \in {\color{orange}a}, s \in {\color{orange}b}$$<br>
2. 因為 $$p < r+s$$，所以：$$p-s<r$$，根據「[戴德金分割](../reals/dedekind-cut.md) <mark style="color:yellow;">**DC2**</mark> (左半線)性質」： $$p-s < r \ \land \ r \in {\color{orange}a} \implies p-s \in {\color{orange}a}$$<br>
3. 因此 $$p = (p-s) + s \in {\color{orange}a+b}$$  ▨
{% endtab %}

{% tab title="⑶" %}
{% hint style="info" %}
⑶ <mark style="color:yellow;">**DC3**</mark> (開放性)：$${\color{orange}a+b}$$ <mark style="color:red;">**沒有**</mark><mark style="color:orange;">最大值</mark>&#x20;
{% endhint %}

1. 假設 $$p +q \in {\color{orange}a+b}$$，其中 $$p \in {\color{orange}a}, q \in {\color{orange}b}$$。<br>
2. 根據「[戴德金分割](../reals/dedekind-cut.md) <mark style="color:yellow;">**DC3**</mark> (開放性)性質」，$${\color{orange}a,b}$$ 都沒有<mark style="color:orange;">最大值</mark>，因此： \
   　⇨ $$\exists r \in {\color{orange}a}, s \in {\color{orange}b} \ \ni \ p < r, \ q<s$$\
   　⇨ $$p+q < r+s$$\
   因為 $$r+s \in {\color{orange}a+b}$$，所以對<mark style="color:yellow;">每一個</mark> $${\color{orange}a+b}$$ 內的元素  $$p+q$$ 來說，都另有一個比它大的元素 $$r+s$$ 也在 $${\color{orange}a+b}$$ 裏面，因此 $${\color{orange}a+b}$$ 沒有<mark style="color:orange;">最大值</mark>  ▨
{% endtab %}
{% endtabs %}
