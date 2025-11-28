# 🔰 線性獨立

[線性代數](./) ⟩ [向量空間](space/) ⟩ 線性獨立 ("<mark style="color:purple;">**linearly independent**</mark>")

{% hint style="success" %}
如果一組向量 $$\{ \mathbf{v_1}, \mathbf{v_2}, \cdots, \mathbf{v_n} \}$$ 符合以下條件：

$$a_1\mathbf{v_1} + a_2 \mathbf{v_2} \cdots + a_n \mathbf{v_n} = \mathbf{0} \implies  a_1 = a_2 = \cdots = a_n  = 0$$

我們就說這組向量「<mark style="color:purple;">**線性獨立**</mark>」。反之，則說這組向量「<mark style="color:yellow;">**線性相依**</mark>」(linearly dependent)。
{% endhint %}

{% tabs %}
{% tab title="🔸 性質" %}
{% hint style="info" %}
1. 若 $$\{ \mathbf{v_1}, \mathbf{v_2}, \cdots, \mathbf{v_n} \}$$ <mark style="color:purple;">**線性獨立**</mark>，則：$$\{ \mathbf{v_1}, \mathbf{v_2}, \cdots, \mathbf{v_n} \}$$ 皆為<mark style="color:yellow;">**非零向量**</mark>。
{% endhint %}

* 證明：假設 $$\mathbf{v_1}$$ 是零向量，則 $$1\mathbf{v_1} = \mathbf{0}$$，如此會導致 $$\{ \mathbf{v_1}, \mathbf{v_2}, \cdots, \mathbf{v_n} \}$$ 沒有線性獨立，即矛盾。其餘以此類推。<br>

{% hint style="success" %}
2. [平行](vec/parallel/#xing-zhi)即<mark style="color:yellow;">**線性相依**</mark>。
3. 如果一組<mark style="color:red;">**非零向量**</mark><mark style="color:yellow;">**兩兩**</mark>[**相互垂直**](vec/perp/)，則它們必[**線性獨立**](indep.md)。
{% endhint %}

* 證明： (3) 設 $$\{ \mathbf{v}_1, \mathbf{v}_2, \cdots \mathbf{v}ₙ  \}$$ 為一組非零向量、兩兩垂直。假設 $$a_1\mathbf{v}_1 + a_2 \mathbf{v}_2 + \cdots + a_n  \mathbf{v}_n=0$$，若對 $$\mathbf{v}_1$$ 做內積，可得 $$a_1 \|\mathbf{v}_1\|^2=0$$，但因爲 $$\|\mathbf{v}_1\| \neq0$$，所以 $$a_1=0$$，同理，其他係數也都是 0，故得證。
{% endtab %}

{% tab title="⬇️ 應用" %}
* [decomp](vec/decomp/ "mention")
{% endtab %}

{% tab title="👥 相關" %}
* [線性組合](combination.md)
* [perp](vec/perp/ "mention")
* [平行](vec/parallel/#xing-zhi)即<mark style="color:yellow;">**線性相依**</mark>。
{% endtab %}

{% tab title="🗺️ 圖表" %}
<img src="../.gitbook/assets/linearly.indep.svg" alt="" class="gitbook-drawing">
{% endtab %}

{% tab title="📗 參考" %}
* [ ] Linear Algebra - A Modern Introduction v.4, 6.2 Linear Independence
{% endtab %}
{% endtabs %}
