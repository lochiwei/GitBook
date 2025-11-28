# 🔰 繞軸旋轉矩陣

[線代](../../) ⟩ [矩陣](../) ⟩ [旋轉矩陣](./) ⟩ 繞軸旋轉

<figure><img src="../../../.gitbook/assets/LA_rotate_about_axis.png" alt=""><figcaption><p>對特定軸的旋轉</p></figcaption></figure>

{% hint style="success" %}
* 若以[單位向量](../../vec/unit.md) $$\mathbf{u} = [u_1 \ u_2 \ u_3]^T$$ 為<mark style="color:yellow;">**軸**</mark>，將 $$\mathbf{P}$$ 點<mark style="color:yellow;">**旋轉**</mark> $$\theta$$ 角，得到 $$\mathbf{P'}$$ 點，則：\
  $$(1) \ \  \mathbf{P'} =  ({\color{orange} \cos\theta}) \ \mathbf{P} \ + \    ({\color{orange}1-\cos\theta}) \ (\mathbf{P\cdot u})  \mathbf{u} + \    ({\color{orange}\sin\theta}) \ (\mathbf{u\times P})$$\
  $$(2) \ \  \mathbf{P'} = [ \ ({\color{orange}\cos\theta}) \ \mathbf{I} \ + \   ({\color{orange}1-\cos\theta}) \ \mathbf{u}  \mathbf{u}^T + \   ({\color{orange}\sin\theta}) \ \mathbf{M} \  ] \ \mathbf{P}$$
* 其中：\
  $$\mathbf{I}  =  \begin{bmatrix}        1 & 0  & 0 \\        0 & 1  & 0 \\        0 & 0  & 1    \end{bmatrix}$$ (單位矩陣)\
  $$\mathbf{uu^T}  =  \begin{bmatrix}        u_{1}^2 & u_{1} u_2  & u_{1} u_3 \\        u_{2} u_1 & u_{2}^2  & u_{2} u_3 \\        u_{3} u_1 & u_{3} u_2   & u_{3}^2  \end{bmatrix}$$ (:star: 注意：① <mark style="color:yellow;">**行向量**</mark>都<mark style="color:orange;">**平行**</mark> $$\mathbf{u}$$  ② $$\mathbf{M^T} = \mathbf{M}$$ )\
  $$\mathbf{M}  =  \begin{bmatrix}        0 & -u_3  & u_2 \\        u_3 & 0  & -u_1 \\        -u_2 & u_1  & 0    \end{bmatrix}$$ (:star: 注意：① <mark style="color:yellow;">**行向量**</mark>都[垂直](../../vec/perp/) $$\mathbf{u}$$  ② $$\mathbf{M^T} = -\mathbf{M}$$ )
{% endhint %}

{% tabs %}
{% tab title="⬆️ 需要" %}
* [perp](../../vec/decomp/perp/ "mention")
* [內積](../../vec/op/dot/cos-rule.md) ⟩ [內積的矩陣表示法](../../vec/op/dot/in-matrix.md)
* [外積](../../vec/op/cross/3d/) ⟩ [外積的矩陣表示法](../../vec/op/cross/3d/matrix.md)
{% endtab %}

{% tab title="⬇️ 應用" %}
* [perp](../../vec/perp/ "mention")
* [rotate.md](../../../num/quaternion/op/rotate.md "mention")
{% endtab %}

{% tab title="🎖 證明" %}
<figure><img src="../../../.gitbook/assets/LA_rotation_about_axis_proof.png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="👥 相關" %}
* [旋轉](./)是一種[線性變換](../../space/transform/)。
* 「[四元數旋轉](../../../num/quaternion/op/rotate.md)」就是一種繞軸旋轉。
{% endtab %}

{% tab title="📗 參考" %}
* Mathematics for 3D Game ⟩ 3.3 Rotation Transforms ⟩ Rotations about an Axis&#x20;
{% endtab %}
{% endtabs %}
