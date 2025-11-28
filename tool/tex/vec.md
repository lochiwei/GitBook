# 🔰 vector

[LaTeX](./) ⟩ vector&#x20;

{% hint style="success" %}
```tex
\|\vec{u}\|    % vector magnitude
```
{% endhint %}

{% tabs %}
{% tab title="💈基本" %}
<table><thead><tr><th width="201">example</th><th>code</th></tr></thead><tbody><tr><td><span class="math">(a_1, a_2, \cdots, a_n)</span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/vec/">向量</a></p><pre class="language-tex"><code class="lang-tex">% vector
(a_1, a_2, \cdots, a_n)
</code></pre></td></tr><tr><td><span class="math">\|\vec{u}\|</span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/vec/norm.md">向量長度</a></p><pre class="language-tex"><code class="lang-tex">% vector magnitude / norm / length
\|\vec{u}\|
</code></pre></td></tr><tr><td><span class="math">\mathbf{u}\times\mathbf{v}</span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/vec/op/cross/">外積</a></p><pre class="language-tex"><code class="lang-tex">% cross product
\mathbf{u}\times\mathbf{v}
</code></pre></td></tr><tr><td><span class="math">\mathbf{u}\cdot\mathbf{v}</span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/vec/op/dot/">內積</a></p><pre class="language-tex"><code class="lang-tex">% dot product
\mathbf{u}\cdot\mathbf{v}
</code></pre></td></tr><tr><td><span class="math">(\mathbf{u}\times\mathbf{v})\times\mathbf{w}</span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/vec/op/triple/vec.md">向量三重積</a></p><pre class="language-tex"><code class="lang-tex">% vector triple product
(\mathbf{u}\times\mathbf{v})\times\mathbf{w}
</code></pre></td></tr><tr><td><span class="math">(\mathbf{u}\times\mathbf{v})\cdot\mathbf{w}</span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/vec/op/triple/scalar.md">純量三重積</a></p><pre class="language-tex"><code class="lang-tex">% scalar triple produc
(\mathbf{u}\times\mathbf{v})\cdot\mathbf{w}
</code></pre></td></tr><tr><td><span class="math">\begin{bmatrix} x &#x26; y &#x26; z \end{bmatrix}</span></td><td><pre class="language-tex"><code class="lang-tex">% row vector
\begin{bmatrix} x &#x26; y &#x26; z \end{bmatrix}
</code></pre></td></tr><tr><td><span class="math">\begin{bmatrix} x \\ y \\ z \end{bmatrix}</span></td><td><pre class="language-tex"><code class="lang-tex">% column vector
\begin{bmatrix} x \\ y \\ z \end{bmatrix}
</code></pre></td></tr><tr><td><span class="math">% dot product as matrix multiplication \begin{bmatrix} u_1 &#x26; u_2 &#x26; u_3 \end{bmatrix}   \begin{bmatrix} v_1 \\ v_2 \\ v_3 \end{bmatrix} </span><span class="math">% dot product as matrix multiplication \begin{bmatrix} u_1 &#x26; u_2 &#x26; u_3 \end{bmatrix}   \begin{bmatrix} v_1 \\ v_2 \\ v_3 \end{bmatrix} </span><span class="math">\begin{bmatrix} u_1 &#x26; u_2 &#x26; u_3 \end{bmatrix}   \begin{bmatrix} v_1 \\ v_2 \\ v_3 \end{bmatrix} </span></td><td><pre class="language-tex"><code class="lang-tex">% dot product as matrix multiplication
\begin{bmatrix} u_1 &#x26; u_2 &#x26; u_3 \end{bmatrix}  
\begin{bmatrix} v_1 \\ v_2 \\ v_3 \end{bmatrix} 
</code></pre></td></tr><tr><td><span class="math">\{ \mathbf{v_1}, \mathbf{v_2}, \cdots, \mathbf{v_n} \}</span></td><td><pre class="language-tex"><code class="lang-tex">% set of vectors
\{ \mathbf{v_1}, \mathbf{v_2}, \cdots, \mathbf{v_n} \}
</code></pre></td></tr></tbody></table>
{% endtab %}

{% tab title="💈大型" %}
<table><thead><tr><th width="310">example</th><th>code</th></tr></thead><tbody><tr><td><span class="math">\|\mathbf{v}\| = \sqrt{v_1^2 + v_2^2 + \cdots + v_n^2}</span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/vec/norm.md">向量長度</a></p><pre class="language-tex"><code class="lang-tex">% vector length
\|\mathbf{v}\| = \sqrt{v_1^2 + v_2^2 + \cdots + v_n^2}
</code></pre></td></tr><tr><td><span class="math">\|\mathbf{v}\|^2 = v_1^2 + v_2^2 + \cdots + v_n^2</span></td><td><pre class="language-tex"><code class="lang-tex">% vector length
\|\mathbf{v}\|^2 = v_1^2 + v_2^2 + \cdots + v_n^2
</code></pre></td></tr><tr><td><span class="math">a_1\mathbf{v_1} + a_2 \mathbf{v_2} \cdots + a_n \mathbf{v_n}</span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/combination.md">線性組合</a></p><pre class="language-tex"><code class="lang-tex">% linear combination
a_1\mathbf{v_1} + a_2 \mathbf{v_2} \cdots + a_n \mathbf{v_n}
</code></pre></td></tr><tr><td><span class="math">\text{proj}_{\mathbf{v}} (   \textcolor{red}{\mathbf{u}} ) =  \left(   \dfrac     {\textcolor{red}{\mathbf{u}}\cdot\mathbf{v}}     {\mathbf{v}\cdot\mathbf{v}} \right) \mathbf{v} </span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/vec/decomp/perp/">向量的垂直分解</a></p><pre class="language-tex"><code class="lang-tex">% projection of u onto v
\text{proj}_{\mathbf{v}} (
  \textcolor{red}{\mathbf{u}}
) = 
\left(
  \dfrac
    {\textcolor{red}{\mathbf{u}}\cdot\mathbf{v}}
    {\mathbf{v}\cdot\mathbf{v}}
\right)
\mathbf{v} 
</code></pre></td></tr><tr><td><span class="math">\text{perp}_{\mathbf{v}}(   \textcolor{red}{\mathbf{u}} ) =  \textcolor{red}{\mathbf{u}} -  \left(   \dfrac{     \textcolor{red}{\mathbf{u}}\cdot\mathbf{v}   }{     \mathbf{v}\cdot\mathbf{v}   } \right) \mathbf{v}</span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/vec/decomp/perp/">向量的垂直分解</a></p><pre class="language-tex"><code class="lang-tex">% perpendicular vector
\text{perp}_{\mathbf{v}}(
  \textcolor{red}{\mathbf{u}}
) = 
\textcolor{red}{\mathbf{u}} - 
\left(
  \dfrac{
    \textcolor{red}{\mathbf{u}}\cdot\mathbf{v}
  }{
    \mathbf{v}\cdot\mathbf{v}
  }
\right)
\mathbf{v}
</code></pre></td></tr><tr><td><span class="math">\left(   \begin{vmatrix}         u_2 &#x26; u_3 \\     v_2 &#x26; v_3    \end{vmatrix} ,   \begin{vmatrix}         u_3 &#x26; u_1 \\     v_3 &#x26; v_1    \end{vmatrix} ,   \begin{vmatrix}         u_1 &#x26; u_2 \\     v_1 &#x26; v_2    \end{vmatrix}  \right)</span></td><td><p><span data-gb-custom-inline data-tag="emoji" data-code="1f449">👉</span> <a href="../../linear/vec/op/cross/3d/">空間外積</a></p><pre class="language-tex"><code class="lang-tex">% cross product
\left(
  \begin{vmatrix}    
    u_2 &#x26; u_3 \\
    v_2 &#x26; v_3 
  \end{vmatrix}
  ,
  \begin{vmatrix}    
    u_3 &#x26; u_1 \\
    v_3 &#x26; v_1 
  \end{vmatrix}
  ,
  \begin{vmatrix}    
    u_1 &#x26; u_2 \\
    v_1 &#x26; v_2 
  \end{vmatrix} 
\right)
</code></pre></td></tr></tbody></table>
{% endtab %}

{% tab title="⬇️ 應用" %}
* [dot](../../linear/vec/op/dot/ "mention") ⟩ [餘弦定理](../../linear/vec/op/dot/cos-rule.md)&#x20;
* [射影向量的矩陣表示法](../../linear/vec/proj/matrix.md)
{% endtab %}

{% tab title="📘 手冊" %}
* KaTeX > [Accents](https://katex.org/docs/supported.html#accents)
{% endtab %}
{% endtabs %}
