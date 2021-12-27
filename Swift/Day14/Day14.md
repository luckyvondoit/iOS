## 高级运算符

### 溢出运算符( Overflow Operator )

![image-20211117224949169](images/image-20211117224949169.png)

### 运算符重载( Operator Overload )

![image-20211117225547398](images/image-20211117225547398.png)

![image-20211117225521560](images/image-20211117225521560.png)

### Equatable

<img src="images/image-20211117230256857.png" alt="image-20211117230256857" style="zoom:50%;float:left" />

### Comparable

![image-20211117230546503](images/image-20211117230546503.png)

### 自定义运算符( Custom Operator )

![image-20211117231156292](images/image-20211117231156292.png)

- https://developer.apple.com/documentation/swift/swift_standard_library/operator_declarations
- https://docs.swift.org/swift-book/ReferenceManual/Declarations.html#ID380

<img src="images/image-20211117232107534.png" alt="image-20211117232107534" style="zoom:50%;float:left" />

- 如果p为nil = 右边的getAage()不会调用，自定义运算符assignment为ture和赋值运算符一样。

## 扩展( Extension )

- Swift中的扩展，有点类似于0C中的分类( Category )
- 扩展可以为枚举、结构体、类、协议添加新功能
  - 可以添加方法、计算属性、下标、( 便捷)初始化器、嵌套类型、协议等等
- 扩展不能办到的事情
  - 不能覆盖原有的功能
  - 不能添加存储属性，不能向已有的属性添加属性观察器
  - 不能添加父类
  - 不能添加指定初始化器,不能添加反初始化器
  - ...

### 常见使用

#### 计算属性、下标、方法、嵌套类型

<img src="images/image-20211118101257357.png" alt="image-20211118101257357" style="zoom:50%;float:left" />

#### 协议、初始化器

![image-20211118103054794](images/image-20211118103054794.png)

#### 协议

<img src="images/image-20211118103129844.png" alt="image-20211118103129844" style="zoom:50%;float:left" />

![image-20211118103850340](images/image-20211118103850340.png)

- cls2声明的是TestProtocol类型，TestProtocol声明了test1方法，所以调用类中的，没有申明test2方法，认为class中可能没有实现这个方法，调用协议扩展中的方法。

#### 泛型

<img src="images/image-20211118104410958.png" alt="image-20211118104410958" style="zoom:50%;float:left" />