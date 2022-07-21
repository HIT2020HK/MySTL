# MySTL
基于C++11的STL标准库
- 实现空间**配置器**的标准接口、实现一个内存池，为配置器提供相应接口； 
- 实现**序列式容器和关联式容器**的基本接口，并实现**底层的数据结构**以及各个容器的迭代器； 
- 实现常用的**算法、仿函数**（算术类、关系运算类、逻辑运算类）。

# 

* 操作系统
  * linux
  * windows
  * osx
* 编译器
  * g++ 5.4 或以上
  * clang++ 3.5 或以上
  * msvc 14.0 或以上

## 需要
  * 使用 cmake 2.8 来构建项目（**可选**）

## 运行

如果你想要运行测试，请先阅读 [这个](https://github.com/Alinshans/MyTinySTL/blob/master/Test/README.md) 。

  * gcc/clang on linux/osx
  1. 克隆仓库
```bash
$ git clone git@github.com:Alinshans/MyTinySTL.git
$ cd MyTinySTL
```
  2. 构建并运行
```bash
$ mkdir build && cd build
$ cmake ..
$ make
$ cd ../bin && ./stltest
```

  * msvc on windows
  1. 克隆仓库或 [Download ZIP](https://github.com/Alinshans/MyTinySTL/archive/master.zip)
  2. 使用 `vs2015`（或 `vs2017`）打开 `MSVC/MyTinySTL_VS2015.sln`，配置成 `Release` 模式，（Ctrl + F5）开始执行。
  
## 文档
  见 [Wiki](https://github.com/Alinshans/MyTinySTL/wiki)。

## 测试
  见 [Test](https://github.com/Alinshans/MyTinySTL/tree/master/Test)。
