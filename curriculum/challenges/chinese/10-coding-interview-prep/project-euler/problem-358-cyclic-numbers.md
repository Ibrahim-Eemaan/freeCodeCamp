---
id: 5900f4d21000cf542c50ffe5
title: 问题358：循环数
challengeType: 5
videoUrl: ''
---

# --description--

具有n位数字的循环数具有一个非常有趣的属性：

当乘以1、2、3、4，... n时，所有乘积都具有完全相同的数字，并且顺序相同，但是以循环方式旋转！

最小的循环数是6位数字142857： 142857×1 = 142857 142857×2 = 285714 142857×3 = 428571 142857×4 = 571428 142857×5 = 714285 142857×6 = 857142

下一个循环号是16位数字0588235294117647： 0588235294117647×1 = 0588235294117647 0588235294117647×2 = 1176470588235294 0588235294117647×3 = 1764705882352941 ... 0588235294117647×16 = 9411764705882352

请注意，对于循环数，前导零很重要。

只有一个循环数，其最左边的11个数字为00000000137，最右边的5个数字为56789（即其形式为00000000137 ... 56789，中间是未知数字）。 查找所有数字的总和。

# --hints--

`euler358()`应返回3284144505。

```js
assert.strictEqual(euler358(), 3284144505);
```

# --solutions--

