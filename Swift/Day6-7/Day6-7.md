## 闭包

### 闭包表达式( Closure Expression )

<img src="images/image-20211116170657992.png" alt="image-20211116170657992" style="zoom: 67%; float: left;" />

### 闭包表达式的简写

<img src="images/image-20211116170859185.png" alt="image-20211116170859185" style="zoom: 67%; float: left;" />

### 尾随闭包

![image-20211116171422798](images/image-20211116171422798.png)

### 示例 - 数组的排序

![image-20211116171648978](images/image-20211116171648978.png)

### 忽略参数

<img src="images/image-20211116171736807.png" alt="image-20211116171736807" style="zoom: 67%; float: left;" />

## 闭包（Closure）

<img src="images/image-20211116172333244.png" alt="image-20211116172333244" style="zoom:50%;float:left" />

### 练习

![image-20211116192018419](images/image-20211116192018419.png)

![image-20211116203753267](images/image-20211116203753267.png)

### 注意

<img src="images/image-20211116203811204.png" alt="image-20211116203811204" style="zoom: 67%; float: left;" />

## 自动闭包

<img src="images/image-20211116204205115.png" alt="image-20211116204205115" style="zoom:50%;float:left" />

- getNumber这个方法不需要调用，但是还是调用了（会调用print方法），浪费性能。

<img src="images/image-20211116204501611.png" alt="image-20211116204501611" style="zoom:50%;float:left" />

- v2修改成方法不会调用。

<img src="images/image-20211116204716571.png" alt="image-20211116204716571" style="zoom:50%;float:left" />

-  改成自闭包效果和getFirstPositive(10,{20})一样，语法糖。

![image-20211116205513140](images/image-20211116205513140.png)

