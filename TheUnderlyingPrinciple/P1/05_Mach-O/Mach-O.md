## APP的生命周期

### APP从开发到安装到手机的过程

![image-20211205144258534](images/image-20211205144258534.png)

![image-20211205144344932](images/image-20211205144344932.png)

## 逆向APP的思路

![image-20211205144624193](images/image-20211205144624193.png)

## class-dump

![image-20211205144958359](images/image-20211205144958359.png)

- http://stevenygard.com/projects/class-dump/

## Hopper

### 代码的编译过程

![image-20211205145132208](images/image-20211205145132208.png)

![image-20211205145213243](images/image-20211205145213243.png)

### Hopper Disassmbler

![image-20211205145312027](images/image-20211205145312027.png)

## 系统的动态库

### 动态库共享缓存（dyld shared cache）

![image-20211205145506605](images/image-20211205145506605.png)

![image-20211205145527760](images/image-20211205145527760.png)

![image-20211205145541774](images/image-20211205145541774.png)

### 动态库的加载

![image-20211205145613068](images/image-20211205145613068.png)

- https://opensource.apple.com/tarballs/dyld/

### 从动态库共享缓存抽取动态库

![image-20211205155010360](images/image-20211205155010360.png)

## Mach-O

![image-20211205155119774](images/image-20211205155119774.png)

- https://opensource.apple.com/tarballs/xnu/

### 常见的Mach-O文件类型

![image-20211205155246210](images/image-20211205155246210.png)

![image-20211205155335075](images/image-20211205155335075.png)

### 在Xcode中查看target的Mach-O类型

![image-20211205155429198](images/image-20211205155429198.png)

### Mach-O的基本结构

![image-20211205155528827](images/image-20211205155528827.png)

- https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/MachOTopics/0-Introduction/introduction.html

### 窥探Mach-O的结构

![image-20211205155748835](images/image-20211205155748835.png)

- https://github.com/gdbinit/MachOView

### Universal Binary（通用二进制文件）

![image-20211205155849347](images/image-20211205155849347.png)

### dyld和Mach-O

![image-20211205160015016](images/image-20211205160015016.png)