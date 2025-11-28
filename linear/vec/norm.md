# 🔸 向量長度

[線性代數](../) ⟩ [向量](./) ⟩ [運算](op/) ⟩ 向量長度

{% hint style="warning" %}
這裡定義的<mark style="color:purple;">**向量長度**</mark><mark style="color:yellow;">**只適用於**</mark> $$\mathbb{R}ⁿ$$ ，更廣義的向量長度，要依相對的[向量空間](../space/)而定❗️&#x20;
{% endhint %}

{% hint style="success" %}
$$\|\mathbf{v}\| = \sqrt{v_1^2 + v_2^2 + \cdots + v_n^2}$$
{% endhint %}

{% tabs %}
{% tab title="🔸 性質" %}
{% hint style="success" %}
1. $$\|\mathbf{v}\| = 0 \iff \mathbf{v} = \mathbf{0}$$
2. $$\|\mathbf{v}\|^2 = \mathbf{v}\cdot\mathbf{v}$$ (<mark style="color:purple;">**長度**</mark>**&#x20;**<mark style="color:yellow;">**->**</mark> [**內積**](op/dot/))
3. $$\|\mathbf{u}\|^2 \|\mathbf{v}\|^2 = |\mathbf{u}\cdot\mathbf{v}|^2 + \| \mathbf{u}\times\mathbf{v} \|^2$$  (適用於： $$\mathbb{R}^2$$, $$\mathbb{R}^3$$, $$\mathbb{C}$$, $$\mathbb{H}$$)
4. $$|\mathbf{u}\cdot\mathbf{v}| \le \|\mathbf{u}\| \|\mathbf{v}\|$$
5. $$\|\mathbf{u+v}\| \le \|\mathbf{u}\| + \|\mathbf{v}\|$$ (<mark style="color:yellow;">**三角不等式**</mark>)
{% endhint %}

* 🎖 證明： (3) :point\_right: [四元數長度性質](../../num/quaternion/length.md#xing-zhi)
{% endtab %}

{% tab title="⬇️ 應用" %}
* 「<mark style="color:yellow;">**平行向量**</mark>」[性質 3](parallel/#xing-zhi)： $$\mathbf{u} \perp \mathbf{v} \ , \ \mathbf{u} \parallel \mathbf{v} \iff \mathbf{u} = \mathbf{0} \text{ or } \mathbf{v} = \mathbf{0}$$
* 「<mark style="color:yellow;">**向量除法**</mark>」[性質 2](op/div/#xing-zhi)： $$\left(\dfrac{\mathbf{\color{orange}u}}{\mathbf{v}}\right)^{-1} = \dfrac{\mathbf{v}}{\mathbf{\color{orange}u}} \iff \mathbf{u} \parallel \mathbf{v}$$  ( $$\mathbf{u}, \mathbf{v} \neq \mathbf{0}$$ )
{% endtab %}

{% tab title="👥 相關" %}
* :point\_right: 比較：[內積性質](op/dot/#xing-zhi)
* [複數長度](../../num/complex/length.md)的定義就是向量長度的定義。
* [cross.md](../../num/quaternion/op/cross.md "mention")
{% endtab %}
{% endtabs %}
