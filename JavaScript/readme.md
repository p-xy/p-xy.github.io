# 学习JavaScript

## 知识地图
- JavaScript
  - 运行时
    - 数据结构
      - 类型系统（JS的类型系统就是它的7种基本数据类型）
        - 对象（对象比其他6种类型都要复杂，是需要大量篇幅讲解的重点）
      - 实例（JS内置对象，或者叫基础库，150多个）
        - 应用和机制（我们从应用和机制的角度，挑选几个体系讲解内置对象）
    - 执行过程（算法 = 控制逻辑（执行过程）+ 业务逻辑）
        - 事件循环
        - 微任务的执行
        - 函数的执行
        - 语句级的执行
  - 文法
    - 词法
    - 语法
- 语义（语义的大部分内容我们在运行时的讲解中透出，不再单独讲解）

## 地图说明

把语言按照文法、语义和运行时来拆分，符合编程语言的一般规律：***用一定的词法和语法，表达一定语义，从而操作运行时***。

- 对于执行过程，我们从大结构到小结构的角度讲解，从最顶层的程序与模块、事件循环和微任务，到函数、再到语句级的执行。
