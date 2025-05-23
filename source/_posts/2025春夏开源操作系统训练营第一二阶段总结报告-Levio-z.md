---
title: 2025春夏开源操作系统训练营第一二阶段总结报告-Levio-z
date: 2025-05-16 15:20:18
tags:
---
# 第一阶段

- 官方通过要求：
  - rustlings+10道算法题

- 为什么来这个训练营

  - 找rust练手项目看到了，正好对系统级编程感兴趣，于是果断报名参加。

- 主要参考资料：

  - https://rust-book.cs.brown.edu/

  - https://course.rs/about-book.html

- 学习方法

  - 在有些编程基础的情况下，看完一本Rust入门书籍，基本问题不大，我自己额外刷了有100道leetcode，刷题感觉是熟悉语言语法的最好方式，rust写链表题很痛苦。不过写几道链表题感觉能快速理解所有权的概念。

- 感想

  - 在有些算法和编程基础的情况下，看完一本入门书籍，基本问题不大

  - 第一次接触开源性质的学习训练营，学习资料、学习路线和学习经验都很丰富，opencamp社区内容感觉质量都很高，下次还来

# 第二阶段

- 官方通过要求
  - rCore-Camp-Guide-2025S 文档（通过要求）的课后练习

- 参考资料
  - CSAPP
    - https://hansimov.gitbook.io/csapp
      - 查漏补缺
      - 第7章 链接
  - 操作系统导论
    - 关于前19章的内容，之前看过快速翻看
  - RISV手册
    - 主要理解特权级切换
  - rCore-Tutorial-Book-v3 3.6.0-alpha.1 文档（核心）
  - rCore-Camp-Guide-2025S 文档（通过要求）
- 学习方法
  - 前后差不多花了一个月，主要是看rCore-Tutorial-Book-v3 3.6.0-alpha.1 文档看得很详细，其实完成Core-Camp-Guide-2025S 文档题目感觉不难，理解相关代码就行，但是要是能够完全理解和熟悉rcore的所有过程和细节比较难，我的话现在就看了rCore-Tutorial-Book几乎所有的内容，除了最后一章。
  - 后面打算复习一轮，然后写文章去输出。
- 感想
  - 从移除应用执行环境支持，手动链接文件，最简单的调度系统批处理，使用始终中断和异常处理完成时间片轮转来运行多道程序，如何最基本的物理页帧的分配到实现多级页表，还有文件系统、进程和线程。回想这一个多月，才发现一路走下来，学了好多东西。如果你想拥有操作系统来理解程序的视角以及最底层的一些计算机概念和实现，这个训练营还是很不错的。

# 三阶段
- 官方通过要求
  - 6道练习题，一道挑战题
- 参考资料
  - 学习视频
  - 文档：https://oslearning365.github.io/arceos-tutorial-book/
- 学习方法
  - 前后差不多花了2个星期，理解二阶段，三阶段就没有什么问题。
- 感想
  - 二阶段让我真正学明白了操作系统
    - 之前一直算停留在八股文阶段，知道一些概念，但是根本不知道为什么这么设计，这么设计背后的根本原因是什么，在rcore这里，从原理到实际，从实际到原理，这才让我真正弄明白很多和学到了很多东西。新框架和技术层出不穷，但是基础知识基本很多年都没变，其实感觉上层的很多东西都是下层知识的组合，所以下层知识学的扎实，可能上层学的会极快，无非就是换了个形式，投资基础知识的长期收益是很高的。
  - 三阶段，让我对各种系统有了一个宏观的理解，并且接触了前沿的组件化内核设计
    - 阶段的理念非常先进，组件化的方式来构造操作系统，这种设计很有意思，感觉不止可以在操作系统，凭借着rcore天生对组件的友好，crate和feature开启代码的功能。
  - 总之，确实学到了很多，希望能完成四阶段，最后感谢开源训练营，感谢陈渝老师
