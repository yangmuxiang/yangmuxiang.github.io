---
layout: post
title: "Java面试题"
date: 2017-04-17
---

工作需要，收集一些Java面试题.


# Java语言
2. ThreadLocal的应用场景、实现原理以及与Synchronize的区别
2. N个线程访问M个资源，如何避免死锁？

# 系统
linux找出占用8080端口的程序

# 数据库
1. MyISAM与innodb引擎有什么区别？
5. innodb引擎的索引实现原理和锁机制(mvcc)
2. innodb如何实现事务
3. mysql索引数据结构，索引创建的考量因素，索引如何优化。什么是多列索引，覆盖索引。
4. sql注入原理; mybatis框架里如何防止sql注入？
5. 数据库联表
````
已知TableA 有字段（id 姓名 年龄）Table B 有字段（id 性别 Aid) 。
请写一句sql查询出年龄大于18的男性姓名？是否还有其他写法？
````

# 编程
1. 二分查找、快速排序、选择排序原理
3. 输出两个数组中的重复数字
4. 有一个日志文件，其中保存学生成绩数据，如:
```
    zhangshan,1112200,510
    lisi,1112233,740
```
  设计一个算法，实现输出文件按照考试成绩降序排序，要求时间复杂度是o(n)
3. 找出字符串中第一个非重复的字符，如果没有返回空。
例：输入`stress`，输出`t`，输入`teeter`,输出`r`；输入`aabbcc`，输出`null`


# 设计
1. 利用数据库，实现一个分布式锁，尽可能多地考虑异常情况。
