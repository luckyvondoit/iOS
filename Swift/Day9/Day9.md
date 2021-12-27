## 方法

### 方法（method）

![image-20211117111510307](images/image-20211117111510307.png)

### mutating

![image-20211117111636534](images/image-20211117111636534.png)

### @discardableResult

<img src="images/image-20211117112025012.png" alt="image-20211117112025012" style="zoom:50%;float:left" />

## 下标

### 下标( subscript )

<img src="images/image-20211117112203360.png" alt="image-20211117112203360" style="zoom:50%;float:left" />

### 下标的细节

![image-20211117112556066](images/image-20211117112556066.png)

![image-20211117112755004](images/image-20211117112755004.png)

#### 结构体、类作为返回值对比

![image-20211117113145908](images/image-20211117113145908.png)

- class类型subscript方法中可以不写set，如果写了，相当于重新生成了一个point对象赋值，而不是修改之前的point属性。struct赋值是修改原来的，可以观察内存变化。

#### 接收多个参数的下标

![image-20211117113337407](images/image-20211117113337407.png)

## 继承

### 继承 ( Inheritance )

<img src="images/image-20211117165855006.png" alt="image-20211117165855006" style="zoom: 67%; float: left;" />

#### 内存结构

![image-20211117114246026](images/image-20211117114246026.png)

### 重写

#### 重写实例方法、下标

![image-20211117114452324](images/image-20211117114452324.png)

#### 重写类型方法、下标

![image-20211117114740879](images/image-20211117114740879.png)

#### 重写属性

<img src="images/image-20211117115005222.png" alt="image-20211117115005222" style="zoom:50%;float:left" />

#### 重写实例属性

<img src="images/image-20211117115214011.png" alt="image-20211117115214011" style="zoom:50%;float:left" />

<img src="images/image-20211117115500681.png" alt="image-20211117115500681"  />

#### 重写类型属性

![image-20211117115947176](images/image-20211117115947176.png)

### 属性观测器

<img src="images/image-20211117120502467.png" alt="image-20211117120502467" style="zoom:50%;float:left" />

<img src="images/image-20211117120613962.png" alt="image-20211117120613962" style="zoom:50%;float:left" />

![image-20211117120849000](images/image-20211117120849000.png)

- 设置之前需要先拿到之前的值赋值给oldvalue，newvalue

### final

- 被final修饰的方法、下标、 属性，禁止被重写
- 被final修饰的类,禁止被继承