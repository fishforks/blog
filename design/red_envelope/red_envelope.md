# Golang 实现红包


## 红包业务为背景按照软件研发的流程
```
+-------------+       +-------------+       +--------------+      +---------------+
|             |       |             |       |              |      |               |
|  需 求 分 析 +------>+   概 要 设 计 +----->+   详 细 设 计  +----->+    开 发      |
|             |       |             |       |              |      |               |
+-------------+       +-------------+       +--------------+      +------+--------+
                                                                         |
                                                                         |
                                                                         v
                                                                  +------+--------+
                                                                  |               |
                                                                  |     测 试      |
                                                                  |               |
                                                                  +---------------+

```

## 流程简介

- 需求分析方法和用例定义方法

- 四色建模法和核心模型设计

- 系统架构设计

- 数据库物理模型设计

- 数据库物理模型设计

- Golang 编程实践


## 探讨问题

- 资金交易安全问题探讨

- 超卖问题的解决方案

- 表结构设计中的性能优化考虑

- 红包拆解和红包算法

- 系统设计和算法的选择

## 红包秒杀系统架构概览

todo

## 红包系统演进之路

- 满足红包业务需求，快速迭代上线

- 出现超卖现象，事务锁来帮忙

- 流量增加，收红包出现性能瓶颈，改为乐观锁，性能提高3倍

- 流量继续增加，乐观锁也扛不住了，那就上缓存吧

- 缓存还没跑溜呢，服务器挂了，数据丢失了？

- 分布式消息队列来解决异步写

- 数据分片来解决数据库横向扩展？

- Golang 编码 0到1 构建红包秒杀系统

## 学到什么？

1. 红包业务系统的需求分析方法和用例定义方法

2. 学习四色建模法的基本知识，并结合红包业务场景把需求转化为业务模型来深入学习四色建模法

3. 学习在四色建模法过程中如何绘制时间轴事件模型图？

4. 通过业务模型如何来拆分业务系统模块？然后通过业务模型学习如何定义业务边界？

5. 从业务模型和架构目标和愿景来学习架构设计过程、设计方法？

6. 学习如何从业务模型推导物理模型？

7. 如何从数据库物理模型设计上和系统架构设计上来优化性能？

8. 如何解决资金交易安全（超卖）问题和资金交易上的性能优化？并结合超卖方案来学习使用 Golang 编程语言做基准测试。

9. 如何在不同的场景和时机中设计和应用红包算法？

10. 学习 Golang 项目如何构建？

11. 在 Golang 中如何设计和解决基础公共资源的访问问题？

12. 学习使用 Golang 接口来设计基础资源加载和启动的基础设置组件，学习对基础资源组件生命周期的管理的设计？

## 感谢

[3小时极简春节抢红包之Go的实战](https://www.imooc.com/learn/1101)

















