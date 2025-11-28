# ✖️ 矩陣係數積

[線代](../../) ⟩ [矩陣](../) ⟩ [運算](./) ⟩ 矩陣係數積

{% tabs %}
{% tab title="⭐️ 重點" %}
{% hint style="info" %}
[矩陣](../)事實上是一種「[向量](../../vec/)」，所以<mark style="color:purple;">**矩陣係數積**</mark>其實就是[向量係數積](../../vec/op/scalar-mult.md)。&#x20;
{% endhint %}
{% endtab %}

{% tab title="👥 相關" %}
* 向量加法
{% endtab %}

{% tab title="📗 參考" %}
* [ ] Mathematics for 3D Game Programming & Computer Graphics (2nd Edition, 2004) &#x20;
{% endtab %}
{% endtabs %}

## 🔰 定義

{% hint style="success" %}
若 $$\mathbf{A} = \begin{bmatrix}     a_{11} & a_{12} & \cdots & a_{1n} \\     a_{21} & a_{22} & \cdots & a_{2n} \\     \vdots & \vdots & \ddots & \vdots  \\     a_{m1} & a_{m2} & \cdots & a_{mn}   \end{bmatrix}$$， 則：$${\color{orange}k} \mathbf{A} = \mathbf{A} {\color{orange}k}  = \begin{bmatrix}       {\color{orange}k}a_{11} & {\color{orange}k}a_{12} & \cdots & {\color{orange}k}a_{1n} \\    {\color{orange}k}a_{21} & {\color{orange}k}a_{22} & \cdots & {\color{orange}k}a_{2n} \\     \vdots & \vdots & \ddots & \vdots  \\     {\color{orange}k}a_{m1} & {\color{orange}k}a_{m2} & \cdots & {\color{orange}k}a_{mn}   \end{bmatrix}$$

或者可以簡寫成：

$$({\color{orange}k}\mathbf{A})_{ij} = {\color{orange}k}(\mathbf{A}_{ij})$$
{% endhint %}

## 🔸 性質

{% hint style="success" %}
* [矩陣](../)是一種「[向量空間](../../space/)」，所以[矩陣](../)擁有[向量空間](../../space/)的[所有性質](../../space/#xiang-liang-kong-jian-bi-bei-de-xing-zhi)。
* $$\mathbf{A} \to \mathbf{A}_{{\color{orange}ij}}$$ 是一種「<mark style="color:yellow;">**線性變換**</mark>」，所以 $$({\color{blue}\bullet})_{{\color{orange}ij}}$$ 會有<mark style="color:yellow;">**線性變換**</mark>的所有性質。
{% endhint %}

<table><thead><tr><th width="70" data-type="number">#</th><th width="438">🔸 性質</th><th width="220">👉 來源</th></tr></thead><tbody><tr><td>1</td><td><p><mark style="color:yellow;"><strong>線性變換</strong></mark>性質：</p><ul><li><span class="math">(\mathbf{A+B})_{{\color{orange}ij}} = \mathbf{A}_{{\color{orange}ij}} + \mathbf{B}_{{\color{orange}ij}}</span></li><li><span class="math">({\color{orange}k}\mathbf{A})_{ij} = {\color{orange}k}(\mathbf{A}_{ij})</span></li></ul></td><td>矩陣加法 (<a href="+.md#def">定義</a>)<br>矩陣係數積 (<a href="scalar-mult.md#ding-yi">定義</a>)</td></tr></tbody></table>
