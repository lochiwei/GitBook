# 🔸 正交矩陣

[線性代數](../../../) ⟩ [向量空間](../../) ⟩ [基底](../) ⟩ [正交基底](./) ⟩ 正交矩陣 ("<mark style="color:purple;">**orthogonal matrix**</mark>")

{% hint style="success" %}
如果一組[**基底**](../)向量 ① <mark style="color:yellow;">**兩兩**</mark>[**相互垂直**](../../../vec/perp/) ② <mark style="color:yellow;">**均為**</mark>[**單位向量**](../../../vec/unit.md)，若：&#x20;

* $$\mathbf{M}$$ 代表由這些基底<mark style="color:yellow;">**(列)向量**</mark>所形成的矩陣，
* 其[轉置矩陣](../../../matrix/op/transpose.md) $$\mathbf{M}^T$$ 就是由這些基底<mark style="color:yellow;">**(行)向量**</mark>所形成的矩陣，

這時：&#x20;

* $$\mathbf{M}^T \mathbf{M} = \mathbf{I}$$ ，也就是 $$\mathbf{M}^T = \mathbf{M}^{-1}$$

我們稱 $$\mathbf{M}$$ 為「<mark style="color:purple;">**正交矩陣**</mark>」。
{% endhint %}

{% tabs %}
{% tab title="⭐️ 重點" %}
{% hint style="warning" %}
1. 「[正交基底](./)」的向量<mark style="color:yellow;">**不須**</mark>為[單位向量](../../../vec/unit.md)，但<mark style="color:purple;">**正交矩陣**</mark>的（列或行）向量<mark style="color:red;">**必須**</mark>是:exclamation:
{% endhint %}
{% endtab %}

{% tab title="👥 相關" %}
* [inverse.md](../../../matrix/op/mult/inverse.md "mention")
* [normal-vec.md](../../transform/normal-vec.md "mention")
{% endtab %}

{% tab title="📗 參考" %}
* [ ] wiki ⟩  [正交矩陣](https://zh.wikipedia.org/zh-hant/%E6%AD%A3%E4%BA%A4%E7%9F%A9%E9%98%B5)
{% endtab %}
{% endtabs %}
