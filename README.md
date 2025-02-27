# 线程池项目文档

## 概述

本项目是一个基于C++简单的线程池实现，旨在提供一种方便的方式来管理并发执行的任务。线程池是一种常见的并发编程模式，通过重用线程来降低创建和销毁线程的开销，从而提高程序的性能和效率。

## 项目结构
等我画个图

## 功能特性

- 管理线程生命周期：自动创建和销毁线程，根据任务的数量动态调整线程池大小。（我还没实现）
- 提供任务队列：支持提交任务到线程池执行，并按顺序执行。
- 可配置的参数：允许设置线程池大小、任务队列大小、拒绝策略等参数。（我还没实现完）

## 用法示例
不告诉你

### 创建线程池
不告诉你
### 销毁线程池
不告诉你
### 加入任务
不告诉你

## 执行结果说明
在执行过程中，由于使用了 `std::cout` 进行输出，可能会导致输出结果混乱的情况。这种现象在多线程环境下是比较常见的，并且是由于 `std::cout` 的特性所致。如果想要避免这种情况，可以将 `task()` 放入上方的代码块执行原子操作。或者使用线程安全的输出，如果你确实需要实时输出，可以考虑使用线程安全的输出库，比如 `spdlog` 等，这些库能够更好地处理多线程环境下的输出问题。
