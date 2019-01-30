# Talent training

## Talent training 是什么？

Talent training 是 PingCAP 面向社区开设的分布式系统课程，目的是培养分布式系统人才。我们希望
大家通过该课程能学习到分布式系统的几个关键算法，对分布式系统能有初步的认识。

目前课程内容覆盖了 Rust 编程语言，Percolator 分布式事务算法和 Raft 分布式一致性算法。
后续我们计划添加 Multi-Raft 和资源调度相关内容。

课程分为两部分：讲课和实验。

## Rust

Rust 是一门高效，安全的编程语言，也是该课程所有实验的基础（用 Rust 编写）。这节将会介绍 Rust
的基本语法和一些高阶用法，大体将会分为几个小节，每节会有配套的实验。

通过这节，你阅读大型 Rust 项目将不会有语言障碍。

## Percolator

Percolator 是一个分布式事务算法。该课程除了讲解 Percolator 之外还会介绍 TiDB/TiKV 对它的
一些优化。

通过这节，你将了解 2PC， snapshot isolation 和悲观锁。

## Raft

Raft 是一个分布式一致性算法，TiDB/TiKV 用它来保证节点数据的一致。这节将会介绍 Raft 的
基本概念，Leader 选举，Raft Log 复制，Snapshot等。

通过这节，你将了解线性一致性和 Raft。

## 时间和目标

课程的安排：

1. Rust，大约需要一个星期的学习时间
2. Raft，大约需两个星期的学习时间
3. Percolator,大约需一个星期的学习时间

完成这门课程后，我们希望你能用 Rust 实现一个分布式的，满足线性一致性的，支持事务的 KV 服务。

当然我们也希望大家能快速上手 TiDB/TiKV，早日成为 TiDB/TiKV committer。:)

## TODO

- [ ] Rust
- [ ] Percolator
- [ ] Raft
  - [x] labrpc
  - [ ] basic raft
  - [ ] kv raft

## 如何使用？

由于该课程的所有实验都基于 Rust，我们推荐首先学 Rust 章节。Percolator 和 Raft 相对独立，
之后先学哪个都没问题。

完成课程后，请大家不要把答案放到 Github 或者其他公开的地方。

提示：学语言最快的方法就是写，掌握 Rust 基本语法后就大胆尝试后续实验吧！

## 致谢

该课程中 Raft 章节的实验来自于 [MIT 6.824]，感谢 6.824 工作人员的辛勤付出。

[MIT 6.824]: https://pdos.csail.mit.edu/6.824/index.html
