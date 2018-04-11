# Efficiency_of_javascript
JS代码效率笔记

## 1、 in 操作符
* 检测对象是否存在某个属性(可以是对象本身的属性也可以是继承的属性) 

* "__proto__" in {}  //true

* 应用于数组时如： "0" in ["a","b"] // true  "length" in ["a","b"] //true



## 2、 for循环时将lengeh赋值给变量将提升效率，否则每次循环都需要获取数组length


## 3、 数组遍历可以使用forEach 或 map方法

## 4、 call及apply基本应用于改变this指向
``` shell
fun.call(obj, "aa", "hh") / fun.apply(obj, ["aa", "hh"])
fun(a, b){
	//this指向obj
}
```
