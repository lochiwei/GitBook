---
description: 'Quaternions: ring of real quaternions ╱🚧 under construction'
---

# 🔰 四元數 ℍ

[數學](../../) ⟩ [數系](../) ⟩ 四元數 ℍ

{% hint style="success" %}
四元數 $$(\mathbb{H},+,\cdot)$$ 是在四維[向量空間](../../linear/space/) $$\mathbb{R}^4$$ 上定義[自己的乘法](op/x.md)，並擁有以下性質：

* $$\Bbb{i}^2=\Bbb{j}^2=\Bbb{k}^2= \Bbb{ijk}=-1$$

其中： $$\mathbb{1}=(1,0,0,0)$$, $$\mathbb{i}=(0,1,0,0)$$, $$\mathbb{j}=(0,0, 1,0)$$, $$\mathbb{k}=(0, 0, 0,1)$$
{% endhint %}

{% tabs %}
{% tab title="🔴 主題" %}
* [notation.md](notation.md "mention")
* [conjugate.md](conjugate.md "mention")
* [length.md](length.md "mention")
* [op](op/ "mention")
{% endtab %}

{% tab title="🖥️ 影片" %}
{% embed url="https://youtu.be/d4EgbgTm0Bg" %}
Visualizing Quaternons
{% endembed %}
{% endtab %}

{% tab title="⭐️ 重點" %}
{% hint style="warning" %}
通常<mark style="color:red;">**省略**</mark>四元數的<mark style="color:yellow;">**乘法符號**</mark>，以避免與向量空間的[內積](../../linear/vec/op/dot/)符號混淆。
{% endhint %}

{% hint style="danger" %}
四元數<mark style="color:red;">**沒有**</mark><mark style="color:yellow;">**「**</mark>[**乘法**](op/x.md)<mark style="color:yellow;">**交換律」**</mark>❗️&#x20;
{% endhint %}

{% hint style="info" %}
四元數 $$(\mathbb{H},+,\cdot)$$&#x20;

* 是一個 [skew field](../../algebra/ring/skew-field.md)。
* 可視為[複數](../complex/) $$(\mathbb{C},+,\cdot)$$ 的<mark style="color:yellow;">**擴充**</mark>。
{% endhint %}

{% hint style="success" %}
四元數的優點就是：

* 可<mark style="color:orange;">**同時處理**</mark><mark style="color:yellow;">**純量**</mark>與[**向量**](../../linear/vec/)。( :point\_right: [四元數表示法](notation.md) )
* 它的[乘法](op/x.md)可以<mark style="color:orange;">**同時處理**</mark>[內積](../../linear/vec/op/dot/)與[外積](../../linear/vec/op/cross/3d/)。( :point\_right: [四元數旋轉](op/rotate.md) )
{% endhint %}
{% endtab %}

{% tab title="👥 相關" %}
* [complex](../complex/ "mention")
{% endtab %}

{% tab title="📗 參考" %}
* [ ] wiki ⟩ [Quaternions](https://www.wikiwand.com/en/Quaternion) ⭐️&#x20;
* [ ] MathWorld ⟩ [Quaternion](https://mathworld.wolfram.com/Quaternion.html) &#x20;
* [ ] Math for 3D Games ⟩ 3.6 Quaternions
* [ ] Abstract and Linear Algebra (Burton) ⟩ 3.3 Integral Domain and Field, p. 210&#x20;
* [ ] [Quaternions for Computer Graphics](https://link.springer.com/content/pdf/bfm:978-0-85729-760-0/1) ([John Vince (John A.)](https://cyut.on.worldcat.org/search?queryString=au%3D%22Vince%2C%20John%22%20AND%20au%3D%22John%20A%22\&clusterResults=false\&groupVariantRecords=false))
* [ ] 3D Game Engine Programming ⟩ [Understanding Quaternions](https://www.3dgep.com/understanding-quaternions/)
* [ ] [Quaternions (Advanced Methods in Computer Graphics) Part 1](http://what-when-how.com/advanced-methods-in-computer-graphics/quaternions-advanced-methods-in-computer-graphics-part-1/)
{% endtab %}

{% tab title="💾 程式" %}
* replit ⟩ [Quaternions](https://replit.com/@pegasusroe/Quaternions#Number+ext.js)&#x20;

```javascript
// 2023.03.04 - 06:50 (+) Quaternion, n.asQuaternion
// 2023.03.01 - 13:30 (/) isEqualTo -> equal, Number.EPSILON -> 1e-10
//                    (-) areEqualNumbers()
//                    (+) .round()
// 2023.01.20 - 16:45 (+) deg
// 2023.01.20 - 11:47 (+) .clamp(), .isEqualTo (*first recorded)
// -----------------------------------------------------

const { Random } = require('./Random.js');
const { sqrt, abs } = Math;
const {log} = console;

// deg
const deg = Math.PI / 180;

// ⭐ Number+ext
// -----------------------------------------------------
//   (constants)
// - deg                // degree = PI/180
// -----------------------------------------------------
//   (quaternion)
// 🔸 n.asQuaternion
//
// -----------------------------------------------------
//   (integer)
// 🔸 n.isEven
// 🔸 n.isOdd
// 🔸 n.binary
// 🔸 n.octal
// 🔸 n.hex
// 🔹 n.toBinary({prefix:, pad: {length:, char:}})
// 🔹 n.toOctal({prefix:, pad: {length:, char:})
// 🔹 n.toHex({prefix:, pad: {length:, char:})
// -----------------------------------------------------
// 🔹 .clamp()
// 🔹 .equal()
// 🔹 .round()
//
Object.defineProperties(Number.prototype, {

    // ---------------
    // quaternion
    // ---------------

    // 🔸 n.asQuaternion
    asQuaternion: {
        get() { return new Quaternion(this) },
    },

    // ---------------
    // integer
    // ---------------

    // 🔸 n.isEven
    isEven: {
        get() { return this % 2 === 0 },
    },

    // 🔸 n.isOdd
    isOdd: {
        get() { return Math.abs(this % 2) === 1 },
    },

    // 🔸 n.binary
    binary: {
        get() { return this.toString(2) },
    },

    // 🔸 n.octal
    octal: {
        get() { return this.toString(8) },
    },

    // 🔸 n.hex
    hex: {
        get() { return this.toString(16).toUpperCase() },
    },

    // 🔹 n.toBinary({prefix:, pad: {length:, char:}})
    toBinary: {
        value: formatFunc('0b', 2),
    },

    // 🔹 n.toOctal({prefix:, pad: {length:, char:}})
    toOctal: {
        value: formatFunc('0o', 8),
    },

    // 🔹 n.toHex({prefix:, pad: {length:, char:}})
    toHex: {
        value: formatFunc('0x', 16),
    },

    // ---------------
    // range
    // ---------------

    // 🔹 .clamp(min, max)
    clamp: {
        value: function(min, max){
            if (min > max) [min, max] = [max, min];
            return Math.min(max, Math.max(min, this));
        },
    },

    // 🔹 .equal()
    equal: {
        value: function(y, {threshold=1e-10}={}){
            return abs(this - y) < threshold; 
        },
    },

    // 🔹 .round()
    round: {
        value: function(places){
            return +this.toFixed(places); 
        },
    },

});

// ⭐ helpers
// -----------------------------------------------------

// general format function
function formatFunc(pre, base) {
    return function format({
        prefix = pre,
        pad = { length: 0, char: '0' },
    } = {}) {
        // ⭐ `pad` might be overridden, better destructure again
        const { length = 0, char = '0' } = pad;
        return prefix + 
            this.toString(base).padStart(length, char).toUpperCase();
    }
}

// 2023.03.04 - 07:19 (+) .scalarPart, .vectorPart
// 2023.03.04 - 06:50 (•) -------- merged into "Number+ext" --------
// 2023.03.03 - 17:08 (+) .dot, .cross
// 2023.03.01 - 13:42 (+) .randomInt, .randomFloat, .toString
// 2023.02.24 - 15:33 (+) static members, .conjugate, .norm, .inverse, ...
// 2023.02.24 - 13:35 (•) first draft (by chatGPT)
// -------------------------------------------------

// ⭐ Quaternion
// --------------------------------------------------
// - Quaternion.zero, .one, .i, .j, .k
// - Quaternion.randomInt()
// - Quaternion.randomFloat()
// --------------------------------------------------
// - .scalarPart, vectorPart
// - .conjugate
// - .normSquare
// - .norm
// - .inverse
// --------------------------------------------------
// - .add()            p + q
// - .subtract()       p - q
// - .multiply()       pq
// - .divide()         p/q = p q^(-1)
// - .scale()          kp
// - .dot()            p • q
// - .cross()          p x q
// --------------------------------------------------
// - .distance()       |p-q|
// - .equal()          p == q
//
class Quaternion {

    // i, j, k
    static get zero() { return new Quaternion(0, 0, 0, 0) }
    static get one() { return new Quaternion(1, 0, 0, 0) }
    static get i() { return new Quaternion(0, 1, 0, 0) }
    static get j() { return new Quaternion(0, 0, 1, 0) }
    static get k() { return new Quaternion(0, 0, 0, 1) }

    // init
    constructor(a=0, b=0, c=0, d=0) {
        this.a = a;
        this.b = b;
        this.c = c;
        this.d = d;
    }

    // ----------------------
    //     static methods
    // ----------------------

    // Quaternion.randomInt()
    static randomInt(min, max) {
        return new Quaternion(
            Random.int(min, max),
            Random.int(min, max),
            Random.int(min, max),
            Random.int(min, max),
        )
    }

    // Quaternion.randomFloat()
    static randomFloat(min, max) {
        return new Quaternion(
            Random.float(min, max),
            Random.float(min, max),
            Random.float(min, max),
            Random.float(min, max),
        )
    }


    // ----------------------
    //     getters
    // ----------------------

    // scalarPart
    get scalarPart() {
        return this.a;
    }

    // vectorPart
    get vectorPart() {
        const { b, c, d } = this;
        return new Quaternion(0, b, c, d);
    }

    // conjugate
    get conjugate() {
        const { a, b, c, d } = this;
        return new Quaternion(a, -b, -c, -d);
    }

    // inverse (reciprocal)
    get inverse() {
        const n = this.normSquare;
        return this.conjugate.scale(1 / n);
    }

    // |p|^2 = p • p
    get normSquare() {
        return this.dot(this);
    }

    // norm
    get norm() {
        const { a, b, c, d } = this;
        return sqrt(this.normSquare);
    }

    // ---------------------------
    //   ⭐ + - * / operations 
    // ---------------------------

    add(q) {
        const { a, b, c, d } = this;
        return new Quaternion(
            a + q.a, b + q.b, c + q.c, d + q.d
        );
    }

    subtract(q) {
        const { a, b, c, d } = this;
        return new Quaternion(
            a - q.a, b - q.b, c - q.c, d - q.d
        );
    }

    multiply(q) {
        const { a, b, c, d } = this;
        return new Quaternion(
            a * q.a - b * q.b - c * q.c - d * q.d,
            a * q.b + b * q.a + c * q.d - d * q.c,
            a * q.c - b * q.d + c * q.a + d * q.b,
            a * q.d + b * q.c - c * q.b + d * q.a,
        );
    }

    // p/q = p q^(-1)
    // ❗ note: p q^(-1) !== q^(-1) p
    divide(q) {
        return this.multiply(q.inverse);
    }

    // kq
    scale(k) {
        const { a, b, c, d } = this;
        return new Quaternion(k * a, k * b, k * c, k * d);
    }

    // p • q
    dot(q) {
        const { a, b, c, d } = q;
        return this.a * a + this.b * b + this.c * c + this.d * d;
    }

    // p x q = (p • q) - bar(p) q
    cross(q) {
        return this.dot(q).asQuaternion.subtract(
            this.conjugate.multiply(q)
        );
    }

    // ---------------------------
    //   ⭐ helpers 
    // ---------------------------

    // distance
    distance(q) {
        return this.subtract(q).norm;
    }

    // equal
    equal(q, {threshold=1e-10}={}) {
        return this.distance(q).equal(0, {threshold});
    }

    // toString
    toString(places=3) {
        const { a, b, c, d } = this;
        return `(${a.round(places)},${b.round(places)},${c.round(places)},${d.round(places)})`;
    }
}


// ⭐ CommonJS export
module.exports = {
    Quaternion,
    deg,
};

// export {deg};    // ES module export
```
{% endtab %}
{% endtabs %}
