# 🔰 二元關係

[集合](../) ⟩ [關係](../relation.md) ⟩ 二元關係

{% hint style="success" %}
<mark style="color:yellow;">**兩個**</mark>集合 Ａ、Ｂ (Ａ、Ｂ<mark style="color:green;">**可以**</mark><mark style="color:yellow;">**是同一個集合**</mark>) 的<mark style="color:yellow;">**元素之間**</mark>的[關係](../relation.md) ，稱為「<mark style="color:purple;">**二元關係**</mark>」(<mark style="color:yellow;">**binary relation**</mark>)，事實上就是一種Ａ到Ｂ的「<mark style="color:yellow;">**對應關係**</mark>」，通常以：

* $$\mathbf{A} \times \mathbf{B}= \{ \ (a,b) \ | \ a \in \mathbf{A}, b \in \mathbf{B} \}$$&#x20;

的<mark style="color:yellow;">**子集**</mark> (<mark style="color:yellow;">**subset**</mark>) 來表示。如果我們用 $${\color{orange}\mapsto}$$ 來表示此<mark style="color:purple;">**二元關係**</mark>，則：

* $$(a,b) \in {\color{orange}\mapsto}$$ 代表 a 對 b 有此關係。
* 此時我們用 $$a \ {\color{orange}\mapsto} \ b$$ 表示。

(:star: 注意： $$a \ {\color{orange}\mapsto} \ b$$ 不代表有  $$b \ {\color{orange}\mapsto} \ a$$:exclamation:)
{% endhint %}

* <mark style="color:purple;">**二元關係**</mark>常用<mark style="color:yellow;">**表格**</mark>來表示 (:point\_right: [prop](prop/ "mention"))

<figure><img src="../../.gitbook/assets/relation_properties.png" alt=""><figcaption></figcaption></figure>

{% tabs %}
{% tab title="🔴 主題" %}
* <mark style="color:purple;">**二元關係**</mark>
  * <mark style="color:yellow;">**equivalence relations**</mark>: \
    satisfy [reflexivity](prop/reflexive.md), [symmetry](prop/symmetric.md), and [transitivity](prop/transitive.md). \
    :diamond\_shape\_with\_a\_dot\_inside: example： $$a \equiv b \text{ (mod 5)}$$&#x20;
  * <mark style="color:yellow;">**partial orders**</mark>: \
    satisfy [reflexivity](prop/reflexive.md), [antisymmetry](prop/antisymmetric.md), and [transitivity](prop/transitive.md). \
    :diamond\_shape\_with\_a\_dot\_inside: example： $$A \subseteq B$$ (is a subset of)
  * [quan-xu-total-ordering.md](quan-xu-total-ordering.md "mention")：\
    satisfy [totality](prop/totality.md), [antisymmetry](prop/antisymmetric.md), and [transitivity](prop/transitive.md). \
    :diamond\_shape\_with\_a\_dot\_inside: example： $$x \le y$$
  * <mark style="color:yellow;">**functions**</mark>: \
    satisfy a special property called <mark style="color:orange;">**functional dependence**</mark>. In a function $${\color{orange}f}:A \to B$$, **each element** of $$A$$ is associated with **exactly one element** of $$B$$, that is,&#x20;
    * $$\forall x \in A, \exists {\color{orange}!} \ y \in B \ni (x,y) \in {\color{orange}f}$$.
* [prop](prop/ "mention")
{% endtab %}

{% tab title="🔯 符號" %}
參考：KaTeX ⟩ [Relations](https://katex.org/docs/supported.html#relations)

| = `=`                                                                     | ≑≑ `\doteqdot`                                                         | ⪅⪅ `\lessapprox`    | ⌣⌣ `\smile`                                                 |
| ------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ------------------- | ----------------------------------------------------------- |
| << `<`                                                                    | ≖≖ `\eqcirc`                                                           | ⋚⋚ `\lesseqgtr`     | ⊏⊏ `\sqsubset`                                              |
| >> `>`                                                                    | <p>−: <code>\eqcolon</code> or<br><code>\minuscolon</code></p>         | ⪋⪋ `\lesseqqgtr`    | ⊑⊑ `\sqsubseteq`                                            |
| :: `:`                                                                    | <p>−:: <code>\Eqcolon</code> or<br><code>\minuscoloncolon</code></p>   | ≶≶ `\lessgtr`       | ⊐⊐ `\sqsupset`                                              |
| ≈≈ `\approx`                                                              | <p>=: <code>\eqqcolon</code> or<br><code>\equalscolon</code></p>       | ≲≲ `\lesssim`       | ⊒⊒ `\sqsupseteq`                                            |
| ≈: `\approxcolon`                                                         | <p>=:: <code>\Eqqcolon</code> or<br><code>\equalscoloncolon</code></p> | ≪≪ `\ll`            | ⋐⋐ `\Subset`                                                |
| ≈::`\approxcoloncolon`                                                    | ≂≂ `\eqsim`                                                            | ⋘⋘ `\lll`           | ⊂⊂ `\subset` or `\sub`                                      |
| ≊≊ `\approxeq`                                                            | ⪖⪖ `\eqslantgtr`                                                       | ⋘⋘ `\llless`        | ⊆⊆ `\subseteq` or `\sube`                                   |
| ≍≍ `\asymp`                                                               | ⪕⪕ `\eqslantless`                                                      | << `\lt`            | ⫅⫅ `\subseteqq`                                             |
| ∍∍ `\backepsilon`                                                         | ≡≡ `\equiv`                                                            | ∣∣ `\mid`           | ≻≻ `\succ`                                                  |
| ∽∽ `\backsim`                                                             | ≒≒ `\fallingdotseq`                                                    | ⊨⊨ `\models`        | ⪸⪸ `\succapprox`                                            |
| ⋍⋍ `\backsimeq`                                                           | ⌢⌢ `\frown`                                                            | ⊸⊸ `\multimap`      | ≽≽ `\succcurlyeq`                                           |
| ≬≬ `\between`                                                             | ≥≥ `\ge`                                                               | ⊶⊶ `\origof`        | ⪰⪰ `\succeq`                                                |
| ⋈⋈ `\bowtie`                                                              | ≥≥ `\geq`                                                              | ∋∋ `\owns`          | ≿≿ `\succsim`                                               |
| ≏≏ `\bumpeq`                                                              | ≧≧ `\geqq`                                                             | ∥∥ `\parallel`      | ⋑⋑ `\Supset`                                                |
| ≎≎ `\Bumpeq`                                                              | ⩾⩾ `\geqslant`                                                         | ⊥⊥ `\perp`          | ⊃⊃ `\supset`                                                |
| ≗≗ `\circeq`                                                              | ≫≫ `\gg`                                                               | ⋔⋔ `\pitchfork`     | ⊇⊇ `\supseteq` or `\supe`                                   |
| :≈ `\colonapprox`                                                         | ⋙⋙ `\ggg`                                                              | ≺≺ `\prec`          | ⫆⫆ `\supseteqq`                                             |
| <p>::≈ <code>\Colonapprox</code> or<br><code>\coloncolonapprox</code></p> | ⋙⋙ `\gggtr`                                                            | ⪷⪷ `\precapprox`    | ≈≈ `\thickapprox`                                           |
| <p>:− <code>\coloneq</code> or<br><code>\colonminus</code></p>            | >> `\gt`                                                               | ≼≼ `\preccurlyeq`   | ∼∼ `\thicksim`                                              |
| <p>::− <code>\Coloneq</code> or<br><code>\coloncolonminus</code></p>      | ⪆⪆ `\gtrapprox`                                                        | ⪯⪯ `\preceq`        | ⊴⊴ `\trianglelefteq`                                        |
| <p>:= <code>\coloneqq</code> or<br><code>\colonequals</code></p>          | ⋛⋛ `\gtreqless`                                                        | ≾≾ `\precsim`       | ≜≜ `\triangleq`                                             |
| <p>::= <code>\Coloneqq</code> or<br><code>\coloncolonequals</code></p>    | ⪌⪌ `\gtreqqless`                                                       | ∝∝ `\propto`        | ⊵⊵ `\trianglerighteq`                                       |
| :∼ `\colonsim`                                                            | ≷≷ `\gtrless`                                                          | ≓≓ `\risingdotseq`  | ∝∝ `\varpropto`                                             |
| <p>::∼ <code>\Colonsim</code> or<br><code>\coloncolonsim</code></p>       | ≳≳ `\gtrsim`                                                           | ∣∣ `\shortmid`      | △△ `\vartriangle`                                           |
| ≅≅ `\cong`                                                                | ⊷⊷ `\imageof`                                                          | ∥∥ `\shortparallel` | ⊲⊲ `\vartriangleleft`                                       |
| ⋞⋞ `\curlyeqprec`                                                         | ∈∈ `\in` or `\isin`                                                    | ∼∼ `\sim`           | ⊳⊳ `\vartriangleright`                                      |
| ⋟⋟ `\curlyeqsucc`                                                         | ⋈⋈ `\Join`                                                             | ∼: `\simcolon`      | <p>: <code>\vcentcolon</code> or<br><code>\ratio</code></p> |
| ⊣⊣ `\dashv`                                                               | ≤≤ `\le`                                                               | ∼::`\simcoloncolon` | ⊢⊢ `\vdash`                                                 |
| <p>:: <code>\dblcolon</code> or<br><code>\coloncolon</code></p>           | ≤≤ `\leq`                                                              | ≃≃ `\simeq`         | ⊨⊨ `\vDash`                                                 |
| ≐≐ `\doteq`                                                               | ≦≦ `\leqq`                                                             | ⌢⌢ `\smallfrown`    | ⊩⊩ `\Vdash`                                                 |
| ≑≑ `\Doteq`                                                               | ⩽⩽ `\leqslant`                                                         | ⌣⌣ `\smallsmile`    | ⊪⊪ `\Vvdash`                                                |

Direct Input: =<>:∈∋∝∼∽≂≃≅≈≊≍≎≏≐≑≒≓≖≗≜≡≤≥≦≧≫≬≳≷≺≻≼≽≾≿⊂⊃⊆⊇⊏⊐⊑⊒⊢⊣⊩⊪⊸⋈⋍⋐⋑⋔⋙⋛⋞⋟⌢⌣⩾⪆⪌⪕⪖⪯⪰⪷⪸⫅⫆≲⩽⪅≶⋚⪋⊥⊨⊶⊷=<>:∈∋∝∼∽≂≃≅≈≊≍≎≏≐≑≒≓≖≗≜≡≤≥≦≧≫≬≳≷≺≻≼≽≾≿⊂⊃⊆⊇⊏⊐⊑⊒⊢⊣⊩⊪⊸⋈⋍⋐⋑⋔⋙⋛⋞⋟⌢⌣⩾⪆⪌⪕⪖⪯⪰⪷⪸⫅⫆≲⩽⪅≶⋚⪋⊥⊨⊶⊷ `≔ ≕ ⩴`

#### Negated Relations <a href="#negated-relations" id="negated-relations"></a>

\≠= `\not =`

| ⪊⪊ `\gnapprox`  | ≱ `\ngeqslant`      | ⊈⊈ `\nsubseteq`        | ⪵⪵ `\precneqq`      |
| --------------- | -------------------- | ---------------------- | ------------------- |
| ⪈⪈ `\gneq`      | ≯≯ `\ngtr`           | ⊈ `\nsubseteqq`       | ⋨⋨ `\precnsim`      |
| ≩≩ `\gneqq`     | ≰≰ `\nleq`           | ⊁⊁ `\nsucc`            | ⊊⊊ `\subsetneq`     |
| ⋧⋧ `\gnsim`     | ≰ `\nleqq`          | ⋡⋡ `\nsucceq`          | ⫋⫋ `\subsetneqq`    |
| ≩ `\gvertneqq` | ≰ `\nleqslant`      | ⊉⊉ `\nsupseteq`        | ⪺⪺ `\succnapprox`   |
| ⪉⪉ `\lnapprox`  | ≮≮ `\nless`          | ⊉ `\nsupseteqq`       | ⪶⪶ `\succneqq`      |
| ⪇⪇ `\lneq`      | ∤∤ `\nmid`           | ⋪⋪ `\ntriangleleft`    | ⋩⋩ `\succnsim`      |
| ≨≨ `\lneqq`     | ∉∈/ `\notin`         | ⋬⋬ `\ntrianglelefteq`  | ⊋⊋ `\supsetneq`     |
| ⋦⋦ `\lnsim`     | ∌∋ `\notni`         | ⋫⋫ `\ntriangleright`   | ⫌⫌ `\supsetneqq`    |
| ≨ `\lvertneqq` | ∦∦ `\nparallel`      | ⋭⋭ `\ntrianglerighteq` | ⊊ `\varsubsetneq`  |
| ≆≆ `\ncong`     | ⊀⊀ `\nprec`          | ⊬⊬ `\nvdash`           | ⫋ `\varsubsetneqq` |
| ≠= `\ne`       | ⋠⋠ `\npreceq`        | ⊭⊭ `\nvDash`           | ⊋ `\varsupsetneq`  |
| ≠= `\neq`      | ∤ `\nshortmid`      | ⊯⊯ `\nVDash`           | ⫌ `\varsupsetneqq` |
| ≱≱ `\ngeq`      | ∦ `\nshortparallel` | ⊮⊮ `\nVdash`           |                     |
| ≱ `\ngeqq`     | ≁≁ `\nsim`           | ⪹⪹ `\precnapprox`      |                     |

Direct Input: ∉∌∤∦≁≆≠≨≩≮≯≰≱⊀⊁⊈⊉⊊⊋⊬⊭⊮⊯⋠⋡⋦⋧⋨⋩⋬⋭⪇⪈⪉⪊⪵⪶⪹⪺⫋⫌∈/∋∤∦≁≆=≨≩≮≯≰≱⊀⊁⊈⊉⊊⊋⊬⊭⊮⊯⋠⋡⋦⋧⋨⋩⋬⋭⪇⪈⪉⪊⪵⪶⪹⪺⫋⫌
{% endtab %}

{% tab title="📗 參考" %}
* wiki ⟩&#x20;
  * [Cartesian product](https://en.wikipedia.org/wiki/Cartesian_product) (數學「[關係](../relation.md)」是「笛卡兒積」的子集)
  * [adjacency list](https://en.wikipedia.org/wiki/Adjacency_list) (也算是一種數學「[關係](../relation.md)」)
{% endtab %}
{% endtabs %}
