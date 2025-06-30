> DATA: 2025-06-14 21:10
> TAGS: [[C++]]
> Course: #Cpp 
> Author: [ApolloMonasa](https://github.com/ApolloMonasa)
> Pre: 尽管我们在C语言的学习中认识到了一种类型转换叫做[[C强制类型转换]]，但是C++还要介绍四种类型转换，以满足更复杂的场景。


# C++类型转换

>学习方法：牢记“一主要三辅助”，其中主要指的是静态转换，其余的是辅助。牢记静态转换的使用场景，做到你能够区分不能用静态准换的场景，以及知道这种情况应该使用何种转换。

## Why more casting?

>为什么需要更多的类型转换？

首先，强制类型转换不安全，它不检查我们转换的类型，那么如果出现以下情况，就可能有危险。
```cpp
int a = 100;
int *p = (int *)a;
```
这从语法角度来说并没有错误，但是也正因为不会报错，才会成为一个隐患，如果这只是我们的笔误，我们将会忽略它。


## 静态转换 static_cast

### 基本语法

```cpp
int a = 10;
double b = stastic_cast<double>(a);
```

### 使用场景

简单概括：**同类**，以及**同类**的**const 和 非const**之间互相转换



## 动态转换 dynamic_cast

## 常量转换 const_cast

## 指针转换 reinterpret_cast




# Reference


---
Recommend Links
