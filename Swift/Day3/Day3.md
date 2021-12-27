## 枚举

### 枚举的基本用法

<img src="images/image-20211116100954391.png" alt="image-20211116100954391" style="zoom:50%;float:left" />

### 关联值( Associated Values )

![image-20211116101904737](images/image-20211116101904737.png)

- case let .points(i) 与case .point(let i)等价

#### 关联值举例

![image-20211116102030427](images/image-20211116102030427.png)

### 原始值（Raw Value）

![image-20211116102255809](images/image-20211116102255809.png)

#### 隐式原始值 ( Implicitly Assigned Raw Values )

![image-20211116102616617](images/image-20211116102616617.png)

### 枚举递归 （Recursive Enumeration )

![image-20211116103014336](images/image-20211116103014336.png)

### MemoryLayout

<img src="images/image-20211116104418705.png" alt="image-20211116104418705" style="zoom:50%;float:left" />

#### 思考下枚举变量的内存布局

![image-20211116122330257](images/image-20211116122330257.png)

<img src="images/image-20211116124027543.png" alt="image-20211116124027543" style="zoom:50%;float:left" />

<img src="images/image-20211116124505233.png" alt="image-20211116124505233" style="zoom:50%;float:left" />

<img src="images/image-20211116124621382.png" alt="image-20211116124621382" style="zoom:50%;float:left" />

- 多个case才会再用一个字节存储成员值

![image-20211116122155326](images/image-20211116122155326.png)

- Mems打印一个变量的地址，通过View Memory查看内存信息。
- ARM芯片是小端模式，遵循高高低低模式（高地址存储高位，低地址存储地位）

#### 进一步观察下列枚举的内存布局

![image-20211116155311736](images/image-20211116155311736.png)

## 可选项

![image-20211116105935977](images/image-20211116105935977.png)

### 强制解包( Forced Unwrapping )

![image-20211116110336832](images/image-20211116110336832.png)

### 判断可选值是否包含值

<img src="images/image-20211116110528412.png" alt="image-20211116110528412" style="zoom:50%;float:left" /> 









### 可选项绑定( Optional Binding )

<img src="images/image-20211116112112598.png" alt="image-20211116112112598" style="zoom:50%;float:left" />

### 等价写法

<img src="images/image-20211116112312982.png" alt="image-20211116112312982" style="zoom:50%;float:left" />

### while循环中使用可选项绑定

<img src="images/image-20211116112454073.png" alt="image-20211116112454073" style="zoom:50%;float:left" />

### 空合并运算符 ?? ( Nil-Coalescing Operator )

![image-20211116112705555](images/image-20211116112705555.png)

<img src="images/image-20211116112819663.png" alt="image-20211116112819663" style="zoom: 67%; float: left;" />

#### 多个??一起使用

<img src="images/image-20211116113044206.png" alt="image-20211116113044206" style="zoom:50%;float:left" />

#### ??跟if let配合使用

<img src="images/image-20211116113203844.png" alt="image-20211116113203844" style="zoom: 67%; float: left;" />

### guard

![image-20211116113353169](images/image-20211116113353169.png)

#### guard语句

![image-20211116113714659](images/image-20211116113714659.png)

### 隐式解包( Implicitly Unwrapped Optional )

![image-20211116114225306](images/image-20211116114225306.png)

### 字符串插值

<img src="images/image-20211116114602481.png" alt="image-20211116114602481" style="zoom:50%;float:left" />

###  多重可选项

![image-20211116121118250](images/image-20211116121118250.png)

![image-20211116120542472](images/image-20211116120542472.png)

