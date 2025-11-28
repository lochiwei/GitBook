# #️ 矩陣符號

[線代](../) ⟩ [矩陣](./) ⟩ 符號

{% hint style="success" %}
* $${\color{orange}\mathbf{a}_{ij}}$$ 或 $${\color{orange}\mathbf{A}_{ij}}$$ 代表：$$\mathbf{A}$$ 矩陣第 $$i$$ 列、第 $$j$$ 行的<mark style="color:yellow;">**元素**</mark>。
* $${\color{orange}\mathbf{A}_{i*}}$$ 代表：$$\mathbf{A}$$ 矩陣的第 $$i$$ <mark style="color:yellow;">**列**</mark> (稱為[列向量](row-col.md))。
* $${\color{orange}\mathbf{A}_{*j}}$$ 代表：$$\mathbf{A}$$ 矩陣的第 $$j$$ <mark style="color:yellow;">**行**</mark> (稱為[行向量](row-col.md))。
{% endhint %}

{% tabs %}
{% tab title="👥 相關" %}
* [內積](../vec/op/dot/)
* [矩陣乘法](op/mult/)
{% endtab %}

{% tab title="📗 參考" %}
* [ ] Mathematics for 3D Game Programming & Computer Graphics (2nd Edition, 2004) &#x20;
{% endtab %}
{% endtabs %}

在矩陣的世界中：

* [矩陣](./)通常用<mark style="color:yellow;">**大寫粗體**</mark>表示，如： $$\mathbf{A}, \mathbf{B}, \mathbf{M}$$
* 一般的[向量](../vec/)會用<mark style="color:yellow;">**小寫粗體**</mark>表示，並寫成「[列向量](row-col.md)」，如：\
  \
  $$\mathbf{u}=\begin{bmatrix}       1 \\ 2 \\ 3 \end{bmatrix}$$, $$\mathbf{v}=\begin{bmatrix}       4 \\ 5 \\ 6 \end{bmatrix}$$<br>
* 它們的[內積](../vec/op/dot/)則會寫成這樣：\
  \
  $$\mathbf{u}^T\mathbf{v}=\begin{bmatrix}       1 & 2 & 3 \end{bmatrix} \begin{bmatrix}       4 \\ 5 \\ 6 \end{bmatrix}  = \begin{bmatrix}       32 \end{bmatrix}$$

{% hint style="danger" %}
⭐️ 注意：

<mark style="color:yellow;">**通常不區分**</mark>一個<mark style="color:yellow;">**純數**</mark>與 $$1\times 1$$ <mark style="color:yellow;">**矩陣**</mark>之間的區別，但在複雜的矩陣運算中，可能會混雜向量的[係數積](../space/)、[矩陣係數積](op/scalar-mult.md)、向量[內積](../vec/op/dot/)、[矩陣乘法](op/mult/)等，如果任意混用，<mark style="color:yellow;">**有可能會產生**</mark><mark style="color:red;">**計算錯誤**</mark>:exclamation:
{% endhint %}
