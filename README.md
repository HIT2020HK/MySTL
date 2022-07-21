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
  * 克隆仓库
```bash
$ git clone git@github.com:HIT2020HK/MySTL.git
$ cd MySTL
```
  * 构建并运行
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
- gcc5
## 测试框架
在 [test.h](https://github.com/HIT2020HK/MySTL/blob/main/Test/test.h) 中，用了两个类实现了一个简单的测试框架，并定义了大量宏来封装测试过程
## 测试内容
 在 [test.h](https://github.com/HIT2020HK/MySTL/blob/main/Test/test.h) 中定义了两个宏，`PERFORMANCE_TEST_ON` 和 `LARGER_TEST_DATA_ON`。`PERFORMANCE_TEST_ON` 代表开启性能测试，默认定义为 `1`。`LARGER_TEST_DATA_ON` 代表增大测试数据，默认定义为 `0`
## 测试案例
* [algorithm](https://github.com/HIT2020HK/MySTL/blob/main/Test/algorithm_test.h) *(100%/100%)*
  * [algorithm_performance](https://github.com/HIT2020HK/MySTL/blob/main/Test/algorith_performance_test.h) *(100%/100%)*
  * [deque](https://github.com/HIT2020HK/MySTL/blob/main/Test/deque_test.h) *(100%/100%)*
  * [list](https://github.com/HIT2020HK/MySTL/blob/main/Test/list_test.h) *(100%/100%)*
  * [map](https://github.com/HIT2020HK/MySTL/blob/main/Test/map_test.h) *(100%/100%)*
    * map
    * multimap
  * [queue](https://github.com/HIT2020HK/MySTL/blob/main/Test/queue_test.h) *(100%/100%)*
    * queue
    * priority_queue
  * [set](https://github.com/HIT2020HK/MySTL/blob/main/Test/set_test.h) *(100%/100%)*
    * set
    * multiset
  * [stack](https://github.com/HIT2020HK/MySTL/blob/main/Test/stack_test.h) *(100%/100%)*
  * [string_test](https://github.com/HIT2020HK/MySTL/blob/main/Test/string_test.h) *(100%/100%)*
  * [unordered_map](https://github.com/HIT2020HK/MySTL/blob/main/Test/unordered_map_test.h) *(100%/100%)*
    * unordered_map
    * unordered_multimap
  * [unordered_set](https://github.com/HIT2020HK/MySTL/blob/main/Test/unordered_set_test.h) *(100%/100%)*
    * unordered_set
    * unordered_multiset
  * [vector](https://github.com/HIT2020HK/MySTL/blob/main/Test/vector_test.h) *(100%/100%)*
