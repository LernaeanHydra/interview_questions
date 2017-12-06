# Java并发编程

## 名词

## 问题

* synchronized关键字的底层是如何实现的？
* 序列化的底层是如何实现的？
* 乐观锁、悲观锁
* Java线程池原理
* 什么是ThreadLocal？（ThreadLocal 不继承 Thread，也不实现 Runable 接口，ThreadLocal 类为每一个线程都维
护了自己独有的变量拷贝。每个线程都拥有自己独立的变量，其作用在于数据独立。
ThreadLocal 采用 hash 表的方式来为每个线程提供一个变量的副本。）
* 描述一下HashMap在resize()过程中可能发生死锁的过程
* ConcurrentHashMap的实现机制？
* 说一下你了解哪些Lock？什么是ReentrantLock？ReadWriteLock？
* 什么是CAS？
* 什么是happen-before原则？
* 什么是可重入？
