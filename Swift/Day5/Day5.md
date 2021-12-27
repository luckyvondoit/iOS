## 结构体

![image-20211116155553266](images/image-20211116155553266.png)

### 结构体的初始化器

![image-20211116155725023](images/image-20211116155725023.png)

### 思考：下面代码能编译通过么？

<img src="images/image-20211116155842001.png" alt="image-20211116155842001" style="zoom:50%;float:left" />

### 自定义初始化器

![image-20211116155957569](images/image-20211116155957569.png)

### 窥探初始化器的本质

<img src="images/image-20211116160050577.png" alt="image-20211116160050577" style="zoom: 67%; float: left;" />

### 结构体内存结构

<img src="images/image-20211116160312468.png" alt="image-20211116160312468" style="zoom:50%;float:left" />

## 类

![image-20211116160705882](images/image-20211116160705882.png)

### 类的初始化器

![image-20211116160840380](images/image-20211116160840380.png)

### 结构体与类的本质区别

![image-20211116161448891](images/image-20211116161448891.png)

### 对象的堆空间申请过程

<img src="images/image-20211116161807199.png" alt="image-20211116161807199" style="zoom:50%;float:left" />

### 值类型

<img src="images/image-20211116162616185.png" alt="image-20211116162616185" style="zoom:50%;float:left" />

#### 值类型的赋值操作

<img src="images/image-20211116163534266.png" alt="image-20211116163534266" style="zoom:50%;float:left" />

- 在Swift标准库中，为了提升性能, String、Array、 Dictionary、 Set采取了Copy On Write技术
  - 比如仅当有"写” 操作时，才会真正执行拷贝操作
  - 对于标准库值类型的赋值操作，Swift能确保最佳性能，所有没必要为了保证最佳性能来避免赋值
- 建议:不需要修改的,尽量定义成let

![image-20211116163916495](images/image-20211116163916495.png)

- 值类型赋值，内存地址不变，只修内存数据。

### 引用类型

![image-20211116164309996](images/image-20211116164309996.png)

#### 对象的堆空间申请过程

<img src="images/image-20211120180107975.png" alt="image-20211120180107975" style="zoom:50%;float:left" />

#### 引用类型的赋值操作

![image-20211120180207515](images/image-20211120180207515.png)

### 值类型、引用类型的let

<img src="images/image-20211116165117977.png" alt="image-20211116165117977" style="zoom:50%;float:left" />

## 嵌套类型

<img src="images/image-20211116165800618.png" alt="image-20211116165800618" style="zoom:50%;float:left" />

## 枚举、结构体、类都可以定义方法

![image-20211120180656918](images/image-20211120180656918.png)

## 作业

<img src="images/image-20211120180808319.png" alt="image-20211120180808319" style="zoom:50%;float:left" />