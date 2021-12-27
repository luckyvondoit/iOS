## 函数式编程

### Array

#### Array的常见操作

![image-20211119102648144](images/image-20211119102648144.png)

#### lazy的优化

<img src="images/image-20211119104403807.png" alt="image-20211119104403807" style="zoom:50%;float:left" />

- 使用的时候才进行映射

#### Optional的map和flatMap

![image-20211119104625070](images/image-20211119104625070.png)

![image-20211119105146055](images/image-20211119105146055.png)

<img src="images/image-20211119105724770.png" alt="image-20211119105724770" style="zoom:50%;float:left" />

### FP

#### 函数式编程 ( Funtional Programming )

<img src="images/image-20211119110143707.png" alt="image-20211119110143707" style="zoom:50%;float:left" />

-  参考资料
  - http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html
  - http://www.mokacoding.com/blog/functor-applicative-monads-in-pictures

#### 传统写法

<img src="images/image-20211119110438549.png" alt="image-20211119110438549" style="zoom:50%;float:left" />

#### 函数式写法

<img src="images/image-20211119110635759.png" alt="image-20211119110635759" style="zoom:50%;float:left" />

#### 高阶函数( Higher-Order Function )

<img src="images/image-20211119113050311.png" alt="image-20211119113050311" style="zoom:50%;float:left" />

#### 柯里化( Currying )

<img src="images/image-20211119113208331.png" alt="image-20211119113208331" style="zoom:50%;float:left" />

![image-20211119113330323](images/image-20211119113330323.png)

![image-20211119113359032](images/image-20211119113359032.png)

#### 函子( Functor )

![image-20211119115200639](images/image-20211119115200639.png)

![image-20211119115522973](images/image-20211119115522973.png)

#### 适用函子（Applicative Functor ）

![image-20211119115818842](images/image-20211119115818842.png)

<img src="images/image-20211119115838210.png" alt="image-20211119115838210" style="zoom:50%;float:left" />

#### 单子( Monad )

<img src="images/image-20211119120547014.png" alt="image-20211119120547014" style="zoom:50%;float:left" />

- Array的flatmap进行柯里化处理，本质是接受两个参数的函数。