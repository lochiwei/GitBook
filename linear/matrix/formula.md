# 🔯 矩陣公式表

[線代](../) ⟩ [矩陣](./) ⟩ 矩陣公式表

{% hint style="success" %}
所有矩陣相關公式會放在這裡，方便查閱。
{% endhint %}

## 矩陣加法

<table><thead><tr><th width="70" data-type="number">#</th><th width="438">🔸 公式</th><th width="220">👉 來源</th></tr></thead><tbody><tr><td>1</td><td><span class="math">(\mathbf{A+B})_{ij} = \mathbf{A}_{ij} + \mathbf{B}_{ij}</span></td><td><a href="op/+.md#def">定義</a></td></tr></tbody></table>

## 矩陣係數積

<table><thead><tr><th width="438">🔸 公式</th><th width="220">👉 來源</th></tr></thead><tbody><tr><td><span class="math">({\color{orange}k}\mathbf{A})_{ij} = {\color{orange}k}(\mathbf{A}_{ij})</span></td><td><a href="op/scalar-mult.md#ding-yi">定義</a></td></tr></tbody></table>

## 轉置矩陣

<table><thead><tr><th width="438">🔸 公式</th><th width="220">👉 來源</th></tr></thead><tbody><tr><td><span class="math">(\mathbf{A}_{{\color{red}{i}} *} )^{\color{orange}{T}} =(\mathbf{A}^{\color{orange}{T}} )_{*\color{red}{i}}</span></td><td><a href="op/transpose.md#yin-li">引理</a></td></tr><tr><td><span class="math">(\mathbf{A}_{* {\color{red}{j}} } )^{\color{orange}{T}} =(\mathbf{A}^{\color{orange}{T}} )_{{\color{red}{j}} *}</span></td><td><a href="op/transpose.md#yin-li">引理</a></td></tr><tr><td><span class="math">\mathbf{(AB)}^T = \mathbf{B}^T \mathbf{A}^T</span></td><td><a href="op/transpose.md#prop">定理</a></td></tr></tbody></table>

## 矩陣乘法

<table><thead><tr><th width="438">🔸 公式</th><th width="220">👉 來源</th></tr></thead><tbody><tr><td><span class="math">(\mathbf{AB})_{{\color{blue}{i}}{\color{red}{j}}}   = a_{i1}b_{1j} + a_{i2}b_{2j} + \cdots + a_{ip}b_{pj} </span></td><td><a href="op/mult/#def">定義</a></td></tr><tr><td><span class="math">(\mathbf{AB})_{{\color{blue}{i}}{\color{red}{j}}} =   \mathbf{A}_{{\color{blue}{i}}*} \mathbf{B}_{*\color{red}{j}}</span></td><td><a href="op/mult/#def">定義</a></td></tr><tr><td><span class="math">( \mathbf{A}_{*\color{red}{k}} \mathbf{B}_{{\color{red}{k}}*} ) _{{\color{blue}{ij}}} =   \mathbf{A}_{{\color{blue}{i}} \color{red}{k}}   \mathbf{B}_{{\color{red}{k}} {\color{blue}{j}}} </span></td><td>表格疊加法 (<a href="op/mult/outer-product/sum-of-outer-products.md#yin-li">引理</a>)</td></tr><tr><td><span class="math">\mathbf{AB} = \mathbf{A}_{*\color{red}{1}} \mathbf{B}_{{\color{red}{1}}*} + \mathbf{A}_{*\color{red}{2}} \mathbf{B}_{{\color{red}{2}}*} + \cdots + \mathbf{A}_{*\color{red}{p}} \mathbf{B}_{{\color{red}{p}}*}</span></td><td>表格疊加法 (<a href="op/mult/outer-product/sum-of-outer-products.md#ding-li">定理</a>)</td></tr><tr><td><mark style="color:red;"><strong>類結合律</strong></mark>：<span class="math">{\color{orange}k} (\mathbf{AB}) =  ({\color{orange}k}\mathbf{A)B} =  \mathbf{A} ({\color{orange}k}\mathbf{B})</span></td><td><a href="op/mult/#prop">性質</a></td></tr><tr><td><mark style="color:yellow;"><strong>結合律</strong></mark>： <span class="math">\mathbf{(AB)C} = \mathbf{A(BC)}</span></td><td><a href="op/mult/#prop">性質</a></td></tr></tbody></table>
