# 🔰 matrix

[LaTeX](./) ⟩ matrix&#x20;

{% hint style="success" %}
```tex
\begin{matrix} a & b \\ c & d \end{matrix}      % matrix
\begin{bmatrix} a & b \\ c & d \end{bmatrix}    % [ ... ]
\begin{vmatrix} a & b \\ c & d \end{vmatrix}    % | ... |
\begin{pmatrix} a & b \\ c & d \end{pmatrix}    % ( ... )
```
{% endhint %}

{% tabs %}
{% tab title="💈基本" %}
<table><thead><tr><th width="254">example</th><th>code</th></tr></thead><tbody><tr><td><span class="math">\begin{matrix} a &#x26; b \\ c &#x26; d \end{matrix}</span></td><td><pre class="language-tex"><code class="lang-tex">\begin{matrix} a &#x26; b \\ c &#x26; d \end{matrix}
</code></pre></td></tr><tr><td><span class="math">\begin{bmatrix} a &#x26; b \\ c &#x26; d \end{bmatrix}</span></td><td><pre class="language-tex"><code class="lang-tex">\begin{bmatrix} a &#x26; b \\ c &#x26; d \end{bmatrix}
</code></pre></td></tr><tr><td><span class="math">\begin{vmatrix} a &#x26; b \\ c &#x26; d \end{vmatrix}</span></td><td><pre class="language-tex"><code class="lang-tex">\begin{vmatrix} a &#x26; b \\ c &#x26; d \end{vmatrix}
</code></pre></td></tr><tr><td><span class="math">\begin{pmatrix} a &#x26; b \\ c &#x26; d \end{pmatrix}</span></td><td><pre class="language-tex"><code class="lang-tex">\begin{pmatrix} a &#x26; b \\ c &#x26; d \end{pmatrix}
</code></pre></td></tr><tr><td><span class="math">\begin{bmatrix}   0 &#x26; 0 &#x26; 0 \\    0 &#x26; 0 &#x26; 0 \\    0 &#x26; 0 &#x26; 0 \end{bmatrix}</span></td><td><pre class="language-tex"><code class="lang-tex">% zero matrix
\begin{bmatrix}
  0 &#x26; 0 &#x26; 0 \\ 
  0 &#x26; 0 &#x26; 0 \\ 
  0 &#x26; 0 &#x26; 0
\end{bmatrix}
</code></pre></td></tr><tr><td><span class="math">\begin{bmatrix}       1 &#x26; 0 &#x26; 0 \\       0 &#x26; 1 &#x26; 0 \\      0 &#x26; 0 &#x26; 1   \end{bmatrix} </span></td><td><pre class="language-tex"><code class="lang-tex">% identity matrix
\begin{bmatrix}    
  1 &#x26; 0 &#x26; 0 \\    
  0 &#x26; 1 &#x26; 0 \\   
  0 &#x26; 0 &#x26; 1  
\end{bmatrix} 
</code></pre></td></tr><tr><td><span class="math">\begin{bmatrix}   a_{1} &#x26;      &#x26;     \\    &#x26;     \ddots &#x26;     \\    &#x26;     &#x26;      a_{n} \end{bmatrix}</span></td><td><pre class="language-tex"><code class="lang-tex">% diagonal matrix
\begin{bmatrix}
  a_{1} &#x26;      &#x26;     \\ 
  &#x26;     \ddots &#x26;     \\ 
  &#x26;     &#x26;      a_{n}
\end{bmatrix}
</code></pre></td></tr><tr><td><span class="math">\begin{Vmatrix}   a_{11} &#x26; a_{12} &#x26; a_{13} \\    a_{21} &#x26; a_{22} &#x26; a_{23} \\   a_{31} &#x26; a_{32} &#x26; a_{33}  \end{Vmatrix}</span></td><td><pre class="language-tex"><code class="lang-tex">% V matrix
\begin{Vmatrix}
  a_{11} &#x26; a_{12} &#x26; a_{13} \\ 
  a_{21} &#x26; a_{22} &#x26; a_{23} \\
  a_{31} &#x26; a_{32} &#x26; a_{33} 
\end{Vmatrix}
</code></pre></td></tr><tr><td><span class="math">\begin{Bmatrix}   a_{11} &#x26; a_{12} &#x26; a_{13} \\    a_{21} &#x26; a_{22} &#x26; a_{23} \\   a_{31} &#x26; a_{32} &#x26; a_{33}  \end{Bmatrix}</span></td><td><pre class="language-tex"><code class="lang-tex">% B matrix
\begin{Bmatrix}
  a_{11} &#x26; a_{12} &#x26; a_{13} \\ 
  a_{21} &#x26; a_{22} &#x26; a_{23} \\
  a_{31} &#x26; a_{32} &#x26; a_{33} 
\end{Bmatrix}
</code></pre></td></tr><tr><td><span class="math">\begin{bmatrix}    a_{11} &#x26; a_{12} &#x26; \cdots &#x26; a_{1n} \\    a_{21} &#x26; a_{22} &#x26; \cdots &#x26; a_{2n} \\    \vdots &#x26; \vdots &#x26; \ddots &#x26; \vdots  \\    a_{m1} &#x26; a_{m2} &#x26; \cdots &#x26; a_{mn}  \end{bmatrix}</span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/matrix/">矩陣</a></p><pre class="language-tex"><code class="lang-tex">% big matrix
\begin{bmatrix}
   a_{11} &#x26; a_{12} &#x26; \cdots &#x26; a_{1n} \\
   a_{21} &#x26; a_{22} &#x26; \cdots &#x26; a_{2n} \\
   \vdots &#x26; \vdots &#x26; \ddots &#x26; \vdots  \\
   a_{m1} &#x26; a_{m2} &#x26; \cdots &#x26; a_{mn} 
\end{bmatrix}
</code></pre></td></tr></tbody></table>
{% endtab %}

{% tab title="💈線代" %}
<table><thead><tr><th width="201">example</th><th>code</th></tr></thead><tbody><tr><td><span class="math">\begin{bmatrix} x &#x26; y &#x26; z \end{bmatrix}</span><br><span class="math">\begin{bmatrix} a_1 &#x26; \cdots &#x26; a_n \end{bmatrix}</span></td><td><pre class="language-tex"><code class="lang-tex">% row matrix
\begin{bmatrix} x &#x26; y &#x26; z \end{bmatrix}
\begin{bmatrix} a_1 &#x26; \cdots &#x26; a_n \end{bmatrix}
</code></pre></td></tr><tr><td><span class="math">\begin{bmatrix} x \\ y \\ z \end{bmatrix}</span>, <span class="math">\begin{bmatrix} a_1 \\ \vdots \\ a_n \end{bmatrix}</span></td><td><pre class="language-tex"><code class="lang-tex">% column matrix
\begin{bmatrix} x \\ y \\ z \end{bmatrix}
\begin{bmatrix} a_1 \\ \vdots \\ a_n \end{bmatrix}
</code></pre></td></tr><tr><td><span class="math">\begin{bmatrix}       u_1 &#x26; u_2 &#x26; u_3 \end{bmatrix}    \begin{bmatrix}       v_1 \\ v_2 \\ v_3 \end{bmatrix} </span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/vec/op/dot/">內積</a></p><pre class="language-tex"><code class="lang-tex">% dot product as matrix multiplication
\begin{bmatrix} u_1 &#x26; u_2 &#x26; u_3 \end{bmatrix}  
\begin{bmatrix} v_1 \\ v_2 \\ v_3 \end{bmatrix} 
</code></pre></td></tr><tr><td><span class="math">\begin{vmatrix}       \mathbf{i} &#x26; \mathbf{j} &#x26; \mathbf{k} \\   u_1 &#x26; u_2 &#x26; u_3 \\   v_1 &#x26; v_2 &#x26; v_3  \end{vmatrix} </span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/vec/op/cross/3d/">空間外積</a></p><pre class="language-tex"><code class="lang-tex">% cross product
\begin{vmatrix}    
  \mathbf{i} &#x26; \mathbf{j} &#x26; \mathbf{k} \\
  u_1 &#x26; u_2 &#x26; u_3 \\
  v_1 &#x26; v_2 &#x26; v_3 
\end{vmatrix} 
</code></pre></td></tr><tr><td><span class="math">\begin{bmatrix}       a_1 &#x26; b_1 &#x26; c_1 \\   a_2 &#x26; b_2 &#x26; c_2 \\   a_3 &#x26; b_3 &#x26; c_3  \end{bmatrix}  \begin{bmatrix} x \\ y \\ z \end{bmatrix} </span></td><td><pre class="language-tex"><code class="lang-tex">% linear transformation
\begin{bmatrix}    
  a_1 &#x26; b_1 &#x26; c_1 \\
  a_2 &#x26; b_2 &#x26; c_2 \\
  a_3 &#x26; b_3 &#x26; c_3 
\end{bmatrix}
\begin{bmatrix} x \\ y \\ z \end{bmatrix} 
</code></pre></td></tr></tbody></table>
{% endtab %}

{% tab title="💈大型" %}
:point\_right: [矩陣乘法表格化](../../linear/matrix/op/mult/outer-product/sum-of-outer-products.md)

{% hint style="info" %}
$$\mathbf{A}_{*\color{red}{k}} \mathbf{B}_{{\color{red}{k}}*}$$

$$\begin{pmatrix}  & a_{1 {\color{red}{k}}}& \\  & \vdots  & \\  \cdots  & a_{i{\color{red}{k}}} & \cdots \\  & \vdots  & \\  & a_{m{\color{red}{k}}} &  \end{pmatrix}  \begin{pmatrix}  &  & \vdots  &  & \\  b_{{\color{red}{k}}1} & \cdots  & b_{{\color{red}{k}}j} & \cdots  & b_{{\color{red}{k}}n}\\  &  & \vdots  &  &  \end{pmatrix}$$

```tex
\begin{pmatrix}
 & a_{1 {\color{red}{k}}}& \\
 & \vdots  & \\
 \cdots  & a_{i{\color{red}{k}}} & \cdots \\
 & \vdots  & \\
 & a_{m{\color{red}{k}}} & 
\end{pmatrix}

\begin{pmatrix}
 &  & \vdots  &  & \\
 b_{{\color{red}{k}}1} & \cdots  & b_{{\color{red}{k}}j} & \cdots  & b_{{\color{red}{k}}n}\\
 &  & \vdots  &  & 
\end{pmatrix}
```
{% endhint %}

{% hint style="info" %}
$$\mathbf{AB} = \mathbf{A}_{*\color{red}{1}} \mathbf{B}_{{\color{red}{1}}*} + \mathbf{A}_{*\color{red}{2}} \mathbf{B}_{{\color{red}{2}}*} + \cdots + \mathbf{A}_{*\color{red}{p}} \mathbf{B}_{{\color{red}{p}}*}$$

```tex
\mathbf{AB} =
  \mathbf{A}_{*\color{red}{1}} \mathbf{B}_{{\color{red}{1}}*}
+ \mathbf{A}_{*\color{red}{2}} \mathbf{B}_{{\color{red}{2}}*}
+ \cdots 
+ \mathbf{A}_{*\color{red}{p}} \mathbf{B}_{{\color{red}{p}}*}
```
{% endhint %}

:point\_right: [矩陣乘法](../../linear/matrix/op/mult/)

{% hint style="info" %}
$$\underbrace{\begin{pmatrix}         &        & \vdots  &        \\  a_{i1} & a_{i2} & \cdots  & a_{ip} \\         &        & \vdots  &  \end{pmatrix}}_{m\times p\ \text{matrix}}  \underbrace{\begin{pmatrix}          & b_{1j} &        \\          & b_{2j} &        \\  \cdots  & \vdots & \cdots \\          & b_{pj} &  \end{pmatrix}}_{p\times n\ \text{matrix}}  =  \underbrace{\begin{pmatrix}         & \vdots &        \\  \cdots & c_{ij} & \cdots \\         & \vdots &  \end{pmatrix}}_{m\times n\ \text{matrix}}$$

```tex
\underbrace{\begin{pmatrix}
        &        & \vdots  &        \\
 a_{i1} & a_{i2} & \cdots  & a_{ip} \\
        &        & \vdots  & 
\end{pmatrix}}_{m\times p\ \text{matrix}}
\underbrace{\begin{pmatrix}
         & b_{1j} &        \\
         & b_{2j} &        \\
 \cdots  & \vdots & \cdots \\
         & b_{pj} & 
\end{pmatrix}}_{p\times n\ \text{matrix}}
=
\underbrace{\begin{pmatrix}
        & \vdots &        \\
 \cdots & c_{ij} & \cdots \\
        & \vdots & 
\end{pmatrix}}_{m\times n\ \text{matrix}}
```
{% endhint %}

{% hint style="info" %}
$$\mathbf{A}_{{\color{red}{i}}*} \mathbf{B}_{*\color{red}{j}}$$    :point\_right: [行向量](../../linear/matrix/row-col.md)

$$\begin{pmatrix}  &  & \vdots  & \\  a_{i1} & a_{i2} & \cdots  & a_{ip}\\  &  & \vdots  &  \end{pmatrix}\begin{pmatrix}  & b_{1j} & \\  & b_{2j} & \\ \cdots  & \vdots  & \cdots \\  & b_{pj} &  \end{pmatrix}$$

```tex
\begin{pmatrix}
   &  & \vdots  & \\
   a_{i1} & a_{i2} & \cdots  & a_{ip}\\
   &  & \vdots  & 
\end{pmatrix}
\begin{pmatrix}
   & b_{1j} & \\
   & b_{2j} & \\
\cdots  & \vdots  & \cdots \\
   & b_{pj} & 
\end{pmatrix}
```
{% endhint %}
{% endtab %}

{% tab title="📘 手冊" %}
* KaTeX > [Environments](https://katex.org/docs/supported.html#environments)
{% endtab %}

{% tab title="🗣 討論" %}
* [Matrix change row or column background](https://tex.stackexchange.com/questions/69713/matrix-change-row-or-column-background)
{% endtab %}

{% tab title="❓" %}

{% endtab %}
{% endtabs %}
