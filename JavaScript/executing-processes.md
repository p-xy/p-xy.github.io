# 执行过程

- 程序 = 算法 + 数据结构
- 算法 = 控制逻辑（执行过程）+ 业务逻辑

我们站在JavaScript引擎的角度，从宏观到微观，看代码是以什么样的规则被执行的。

首先是事件循环机制：

A：什么是事件循环机制？
Q：JavaScript引擎对JavaScript代码的执行是单线程的，为了解决阻塞问题（对什么是阻塞没有一个明确的名词解释，阻塞的意思大概可以理解为：引擎在当前代码执行上耗时过长，而导致后面的代码需要等待），引入了事件循环，把耗时的操作（比如http请求、IO操作、延时等等，一般都是web API）交给浏览器的其他线程去执行，等调用栈为空了之后，事件循环把web API的执行结果（以回调函数的方式）从任务队列，放入调用栈。

A：为什么有事件循环机制？
Q： JavaScript在设计之初，目的是设计成一个简单的脚本语言，所以被设计成单线程的，事件循环机制被设计为解决JavaScript代码阻塞的方案。

## 1. 事件循环

[浏览器和Node中的JavaScript是如何工作的? 可视化解释](https://juejin.im/post/5d693d8b6fb9a06aca383488)

## 2. 宏任务和微任务



## 3. 函数的执行




## 4.语句级的执行