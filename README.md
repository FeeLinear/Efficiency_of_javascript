# Efficiency_of_javascript
JS代码效率笔记

## 1. in 操作符
* 检测对象是否存在某个属性(可以是对象本身的属性也可以是继承的属性)

* "__proto__" in {}  //true

* 应用于数组时如： "0" in ["a","b"] // true  "length" in ["a","b"] //true
