# 🔸 垂直向量

[線性代數](../../) ⟩ [向量](../) ⟩ 垂直向量

{% hint style="success" %}
若兩向量[**內積**](../op/dot/)為 0，我們就說此兩向量<mark style="color:purple;">**垂直**</mark>：

$$\mathbf{u} \cdot \mathbf{v} = 0 \iff \mathbf{u} \perp \mathbf{v}$$

:star: 注意：此兩向量<mark style="color:green;">**可以**</mark>是<mark style="color:yellow;">**零向量**</mark>:exclamation:
{% endhint %}

{% hint style="success" %}
在 $$\mathbb{R}^2$$ 上，若 $$\mathbf{v}=(a,b)$$，我們用 $$\mathbf{v}^{\perp} = (-b,a)$$ 代表 $$\mathbf{v}$$ 旋轉 90° 後的向量。&#x20;
{% endhint %}

{% tabs %}
{% tab title="🔸 性質" %}
{% hint style="warning" %}
1. <mark style="color:yellow;">**零向量**</mark><mark style="color:purple;">**垂直於**</mark>任何向量:exclamation:
{% endhint %}

{% hint style="info" %}
2. $$\mathbf{u} \perp \mathbf{v} \ \text{ and } \ \mathbf{u} \parallel \mathbf{v} \iff \mathbf{u} = \mathbf{v} = \mathbf{0}$$
{% endhint %}

* 證明： (由[向量長度性質 1, 3](../norm.md#xing-zhi) 可得)<br>

{% hint style="info" %}
3. 如果一組<mark style="color:red;">**非零向量**</mark><mark style="color:yellow;">**兩兩**</mark>[**相互垂直**](./)，則它們必[**線性獨立**](../../indep.md)。
{% endhint %}

* 證明：👉 [線性獨立性質 ３](../../indep.md#xing-zhi)
{% endtab %}

{% tab title="⭐️ 重點" %}
{% hint style="warning" %}
1. 在 $$\mathbb{R}^3$$ 中，沒辦法單獨對一個向量 $$\mathbf{v}$$ 旋轉某個角度，除非我們指定它：
   * 要轉的方向：這時可以用「[向量的垂直分解](../decomp/perp/)」來計算。
   * 旋轉軸：這時可以用「[繞軸旋轉矩陣](../../matrix/rotation/about-axis.md)」來計算。
{% endhint %}
{% endtab %}

{% tab title="⬇️ 應用" %}
* [perp](../decomp/perp/ "mention")
* [正交基底](../../space/basis/ortho/)
{% endtab %}

{% tab title="👥 相關" %}
* [parallel](../parallel/ "mention")
* [正交基底](../../space/basis/ortho/)
{% endtab %}
{% endtabs %}
