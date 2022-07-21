# MySTL
基于C++11的STL标准库
- 实现空间**配置器**的标准接口、实现一个内存池，为配置器提供相应接口； 
- 实现**序列式容器和关联式容器**的基本接口，并实现**底层的数据结构**以及各个容器的迭代器； 
- 实现常用的**算法、仿函数**（算术类、关系运算类、逻辑运算类）。

# 编辑环境

* 操作系统
  * linux
* 编译器
  * g++ 5.4 

# 快速运行
* gcc/clang on linux
  1. 克隆仓库
```bash
$ git clone git@github.com:HIT2020HK/MySTL.git
$ cd MySTL
```
  2. 构建并运行
```bash
$ mkdir build && cd build
$ cmake ..
$ make
$ cd ../bin && ./stltest
```
  
# 单元测试
## 测试环境
- linux
- ubuntu 18.04
- gcc7
## 测试框架
在 [test.h]() 中，用了两个类实现了一个简单的测试框架，并定义了大量宏来封装测试过程。
