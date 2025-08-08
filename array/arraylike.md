# ArrayLike



**什么是Array-Like**

ArrayLike就是类数组对象，不是类型数组，ArrayLike Object，类数组对象在JS中没有固定的类型，慢慢整理收集吧。

类数组对象有以下两个特点：

* 没有固定类型，却像对象一样有自己的属性
* 内部实现了`Symbol.iterator`这个属性，支持通过`for...of`迭代
* 不会继承`Array.prototype`，所以不能使用数组的高阶函数
