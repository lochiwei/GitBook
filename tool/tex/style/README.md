# 🔰 style

[LaTeX](../) ⟩ style&#x20;

{% hint style="success" %}
```tex
\mathbb{...}              % math font
\color{blue}{...}         % text color
```
{% endhint %}

{% tabs %}
{% tab title="💈顏色" %}
:point\_right: [color-names.md](color-names.md "mention")

<table><thead><tr><th width="185">example</th><th>code</th></tr></thead><tbody><tr><td><span class="math">F=\color{blue}{m}\color{#f00}{a}</span></td><td><pre class="language-tex"><code class="lang-tex">% text color
\color{blue}{...}
\color{#f00}{...}
</code></pre></td></tr><tr><td><span class="math">\fbox {your text here}</span></td><td><pre class="language-tex"><code class="lang-tex">% simple border
\fbox {your text here}
</code></pre></td></tr><tr><td><span class="math">\colorbox{orange}{$F=ma$ ... (1)}</span></td><td><pre class="language-tex"><code class="lang-tex">% background color
% - rendered as text
% - use `$...$` to switch back to math mode
\colorbox{orange}{$F=ma$ ... (1)}
</code></pre></td></tr><tr><td><span class="math">\fcolorbox{orange}{red}{$F=ma$ ... (1)}</span></td><td><pre class="language-tex"><code class="lang-tex">% border and background color
% - rendered as text
% - use `$...$` to switch back to math mode
\fcolorbox{orange}{red}{$F=ma$ ... (1)}
%         {border}{background}{...}
</code></pre></td></tr></tbody></table>
{% endtab %}

{% tab title="💈字體" %}
<table><thead><tr><th width="185">example</th><th>code</th></tr></thead><tbody><tr><td><span class="math">\mathbb{AB}</span></td><td><pre class="language-tex"><code class="lang-tex">\mathbb{AB}
</code></pre></td></tr></tbody></table>
{% endtab %}

{% tab title="⬇️ 應用" %}
* [向量空間](../../../linear/space/)
{% endtab %}

{% tab title="📘 手冊" %}
* KaTeX ⟩ [Style, Color, Size, and Font](https://katex.org/docs/supported.html#style-color-size-and-font)&#x20;
{% endtab %}

{% tab title="📗 參考" %}
* [ ] [Advanced Notion Formatting Using KaTeX Expressions](https://notionthings.com/2021/01/23/advanced-notion-formatting-using-katex-expressions/)
{% endtab %}
{% endtabs %}
