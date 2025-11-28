# 🔰 矩陣

[線代](../) ⟩ 矩陣  (:u6307: 同義詞："<mark style="color:purple;">**matrix**</mark>")

{% hint style="success" %}
下面這個結構稱為 $$m\times n$$ 的「<mark style="color:purple;">**矩陣**</mark>」

$$\begin{bmatrix}    a_{11} & a_{12} & \cdots & a_{1n} \\    a_{21} & a_{22} & \cdots & a_{2n} \\    \vdots & \vdots & \ddots & \vdots  \\    a_{m1} & a_{m2} & \cdots & a_{mn}  \end{bmatrix}$$

具有 $$m$$ 個<mark style="color:yellow;">**橫列**</mark> ([列向量](row-col.md))、 $$n$$ 個<mark style="color:yellow;">**直行**</mark> ([行向量](row-col.md))，內部的每個數字稱為其<mark style="color:yellow;">**元素**</mark>。

:point\_right: 相關符號參閱：[矩陣符號](notation.md)
{% endhint %}

{% tabs %}
{% tab title="🔴 主題" %}
* [矩陣符號](notation.md)
* [矩陣公式表](formula.md)
* [行向量、列向量](row-col.md)
* [矩陣運算](op/)
  * [轉置矩陣](op/transpose.md)
  * [矩陣加法](op/+.md)
  * [矩陣係數積](op/scalar-mult.md)
  * [矩陣乘法](op/mult/)
    * [行 ⨉ 列](op/mult/outer-product/)
    * [矩陣乘法表格化](op/mult/outer-product/sum-of-outer-products.md) :star:
{% endtab %}

{% tab title="⭐️ 重點" %}
{% hint style="info" %}
所有 $$m\times n$$ 的<mark style="color:purple;">**矩陣**</mark>會形成一個[向量空間](../space/) (相當於 $$\mathbb{R}^{mn}$$ )，所以<mark style="color:purple;">**矩陣**</mark>擁有[向量空間](../space/)的所有[性質](../space/#xiang-liang-kong-jian-bi-bei-de-xing-zhi)。
{% endhint %}
{% endtab %}

{% tab title="👥 相關" %}
* Desmos ⟩ [matrix](../../tool/desmos/expr/matrix/ "mention")
* GGB ⟩ [matrix](../../tool/ggb/matrix/ "mention") &#x20;
{% endtab %}

{% tab title="📗 參考" %}
* [ ] Mathematics for 3D Game Programming & Computer Graphics (2nd Edition, 2004)
* [ ] wiki ⟩ [矩陣](https://zh.wikipedia.org/wiki/%E7%9F%A9%E9%98%B5)&#x20;
{% endtab %}
{% endtabs %}

## 🔸 公式

<table><thead><tr><th width="70" data-type="number">#</th><th width="438">🔸 公式</th><th width="220">👉 來源</th></tr></thead><tbody><tr><td>1</td><td><span class="math">(\mathbf{A+B})_{ij} = \mathbf{A}_{ij} + \mathbf{B}_{ij}</span></td><td>矩陣加法 (<a href="op/+.md#def">定義</a>)</td></tr><tr><td>2</td><td><span class="math">({\color{orange}k}\mathbf{A})_{ij} = {\color{orange}k}(\mathbf{A}_{ij})</span></td><td>矩陣係數積 (<a href="op/scalar-mult.md#ding-yi">定義</a>)</td></tr><tr><td>3</td><td><span class="math">(\mathbf{AB})_{{\color{blue}{i}}{\color{red}{j}}} =   \mathbf{A}_{{\color{blue}{i}}*} \mathbf{B}_{*\color{red}{j}}</span></td><td>矩陣乘法 (<a href="op/mult/#def">定義</a>)</td></tr><tr><td>4</td><td><span class="math">( \mathbf{A}_{*\color{red}{k}} \mathbf{B}_{{\color{red}{k}}*} ) _{{\color{blue}{ij}}} =   \mathbf{A}_{{\color{blue}{i}} \color{red}{k}}   \mathbf{B}_{{\color{red}{k}} {\color{blue}{j}}} </span></td><td>矩陣乘法表格化 (<a href="op/mult/outer-product/sum-of-outer-products.md#yin-li">引理</a>)</td></tr><tr><td>5</td><td><span class="math">\mathbf{AB} = \mathbf{A}_{*\color{red}{1}} \mathbf{B}_{{\color{red}{1}}*} + \mathbf{A}_{*\color{red}{2}} \mathbf{B}_{{\color{red}{2}}*} + \cdots + \mathbf{A}_{*\color{red}{p}} \mathbf{B}_{{\color{red}{p}}*}</span></td><td>矩陣乘法表格化 (<a href="op/mult/outer-product/sum-of-outer-products.md#ding-li">定理</a>)</td></tr><tr><td>6</td><td><span class="math">(\mathbf{A}_{{\color{red}{i}} *} )^{\color{orange}{T}} =(\mathbf{A}^{\color{orange}{T}} )_{*\color{red}{i}}</span></td><td>轉置矩陣 (<a href="op/transpose.md#yin-li">引理</a>)</td></tr><tr><td>7</td><td><span class="math">(\mathbf{A}_{* {\color{red}{j}} } )^{\color{orange}{T}} =(\mathbf{A}^{\color{orange}{T}} )_{{\color{red}{j}} *}</span></td><td>轉置矩陣 (<a href="op/transpose.md#yin-li">引理</a>)</td></tr><tr><td>8</td><td><span class="math">\mathbf{(AB)}^T = \mathbf{B}^T \mathbf{A}^T</span></td><td>轉置矩陣 (<a href="op/transpose.md#prop">定理</a>)</td></tr></tbody></table>
