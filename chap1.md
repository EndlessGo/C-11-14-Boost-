# 第1章 全新的C++语言
## 1.2 左值与右值
+ 右值与右值引用T&& 
+ 转移语意std::move()
+ std::emplace()
+ 完美转发std::forward()

## 1.3 自动类型推导
+ auto
+ decltype
+ decltype(auto)

## 1.4 面向过程编程
+ 空指针nullptr，类型nullptr_t
+ 列表初始化 std::initializer_list
+ 范围for循环 for(const auto& x : v)  for(auto& x : v)
+ 新式函数声明，返回值后置 auto func(...) -> type

## 1.5 面向对象编程
+ default显示声明构造/析构/拷贝构造/拷贝赋值/移动构造/移动赋值函数
+ delete显示禁用函数
+ override继承中重载基类虚函数
+ final禁止继承或派生
+ 类成员初始化
+ 委托构造