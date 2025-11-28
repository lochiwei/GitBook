# 🔰 行向量、列向量

[線代](../) ⟩ [矩陣](./) ⟩ 行向量、列向量

{% hint style="success" %}
* 矩陣的<mark style="color:yellow;">**每一列**</mark>稱為一個「<mark style="color:purple;">**列向量**</mark>」：\
  $$\begin{pmatrix}         &        & \vdots  &        \\  \fcolorbox{black}{lightskyblue}{$a_{i1}$} & \fcolorbox{black}{lightskyblue}{$a_{i2}$} & \cdots  & \fcolorbox{black}{lightskyblue}{$a_{ip}$} \\         &        & \vdots  &  \end{pmatrix}$$  我們用 $${\color{orange}\mathbf{A}_{i*}}$$ 代表 $$\begin{bmatrix}    a_{i1} & a_{i2} & \cdots & a_{ip} \end{bmatrix}$$
* 矩陣的<mark style="color:yellow;">**每一行**</mark>稱為一個「<mark style="color:purple;">**行向量**</mark>」：\
  $$\begin{pmatrix}          & \fcolorbox{black}{yellowgreen}{$b_{1j}$} &        \\          & \fcolorbox{black}{yellowgreen}{$b_{2j}$} &        \\  \cdots  & \vdots & \cdots \\          & \fcolorbox{black}{yellowgreen}{$b_{nj}$} &  \end{pmatrix}$$  我們用 $${\color{orange}\mathbf{B}_{*j}}$$ 代表 $$\begin{bmatrix}    b_{1j} \\ b_{2j} \\ \vdots \\ b_{pj} \end{bmatrix}$$
{% endhint %}

{% tabs %}
{% tab title="🔴 主題" %}
* [矩陣乘法](op/mult/) ⟩  [行 ⨉ 列](op/mult/outer-product/)
{% endtab %}

{% tab title="👥 相關" %}
* [內積](../vec/op/dot/)
* [矩陣乘法](op/mult/)
{% endtab %}

{% tab title="📗 參考" %}
* [ ] Mathematics for 3D Game Programming & Computer Graphics (2nd Edition, 2004) &#x20;
{% endtab %}
{% endtabs %}

## 🔸 性質

<table><thead><tr><th width="70" data-type="number">#</th><th width="438">🔸 性質</th><th width="220">👉 來源</th></tr></thead><tbody><tr><td>1</td><td><span class="math">(\mathbf{AB})_{{\color{blue}{i}}{\color{red}{j}}} =   \mathbf{A}_{{\color{blue}{i}}*} \mathbf{B}_{*\color{red}{j}}</span></td><td>矩陣乘法 (<a href="op/mult/#def">定義</a>)</td></tr><tr><td>2</td><td><span class="math">( \mathbf{A}_{*\color{red}{k}} \mathbf{B}_{{\color{red}{k}}*} ) _{ij} =   \mathbf{A}_{i \color{red}{k}} \mathbf{B}_{{\color{red}{k}} j} </span></td><td>矩陣乘法表格化 (<a href="op/mult/outer-product/sum-of-outer-products.md#yin-li">引理</a>)</td></tr><tr><td>3</td><td><span class="math">\mathbf{AB} = \mathbf{A}_{*\color{red}{1}} \mathbf{B}_{{\color{red}{1}}*} + \mathbf{A}_{*\color{red}{2}} \mathbf{B}_{{\color{red}{2}}*} + \cdots + \mathbf{A}_{*\color{red}{p}} \mathbf{B}_{{\color{red}{p}}*}</span></td><td>矩陣乘法表格化 (<a href="op/mult/outer-product/sum-of-outer-products.md#ding-li">定理</a>)</td></tr></tbody></table>

