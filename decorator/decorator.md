# 装饰器模式
使用对象组合的方式增加对象的行为。  
Go语言使用非入侵式接口可以很方便地实现装饰器模式。

## 入侵式接口 vs 非入侵式接口
入侵式接口：例如Java、PHP的类要声明自己实现了哪些接口。
非入侵式接口：Go语言的对象不需要声明要实现的接口。