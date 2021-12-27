## 编译流程

![image-20211115191213954](images/image-20211115191213954.png)

## swiftc

- swiftc存放在Xcode内部
  - Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin
- 一些操作
  - 生成语法树: swiftc -dump-ast main.swift
  - 生成最简洁的SIL代码: swiftc -emit-sil main.swift
  - 生成LLVM IR代码: swiftc -emit-ir main.swift -o main.ll
  - 生成汇编代码: swiftc -emit-assembly main.swift -o main.s
- 对汇编代码进行分析，可以真正掌握编程语言的本质

## Hello World

![image-20211115192112497](images/image-20211115192112497.png)

## Playground 

### View

![image-20211115192343389](images/image-20211115192343389.png)

### ViewController

![image-20211120153553234](images/image-20211120153553234.png)

### 多Page

![image-20211115192523119](images/image-20211115192523119.png)

### 注释

![image-20211115201222664](images/image-20211115201222664.png)

![image-20211115201530312](images/image-20211115201530312.png)

## 基本语法

### 常量

![image-20211115202012784](images/image-20211115202012784.png)

### 标识符

- 标识符(比如常量名、变量名、函数名)几乎可以使用任何字符
- 标识符不能以数字开头,不能包含空白字符、制表符、箭头等特殊字符

<img src="images/image-20211115202115707.png" alt="image-20211115202115707" style="zoom:50%;float:left" />

### 常见的数据类型

![image-20211115202413277](images/image-20211115202413277.png)

### 字面量

![image-20211115202541375](images/image-20211115202541375.png)

### 类型转换

<img src="images/image-20211115202746403.png" alt="image-20211115202746403" style="zoom:50%;float:left" />

### 元组（tuple）

<img src="images/image-20211115202932534.png" alt="image-20211115202932534" style="zoom:50%;float:left" />