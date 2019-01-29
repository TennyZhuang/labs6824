# Talent traning

## Talent traning 是什么？

Talent traning 是 PingCAP 面向社区开设的分布式系统课程。课程分为两部分：讲课和实验。

目前内容覆盖了 Rust 编程语言，Percolator 分布式事务算法和 Raft 分布式一致性算法。后续我们计划
添加 Multi-Raft 和资源调度相关内容。

## Rust

Rust 是一门高效，安全的编程语言，也是该课程所有实验的基础（用 Rust 编写）。这节将会介绍 Rust
的基本语法和一些高阶用法。大体将会分为几个小节，每节会有配套的实验。

## Percolator

Percolator 是一个分布式事务算法。该课程除了讲解 Percolator 之外还会介绍 TiDB/TiKV 对它的
一些优化。

## Raft

Raft 是一个分布式一致性算法，TiDB/TiKV 用它来保证节点数据的一致。这节将会介绍 Raft 的
基本概念： Leader 选举，Raft Log 复制等。我们还会用 Raft 构建一个 KV 服务集群，对外提供满足
线性一致性的服务。

## TODO

- [ ] Rust
- [ ] Percolator
- [ ] Raft
  - [x] labrpc
  - [ ] basic raft
  - [ ] kv raft

## 如何使用？

由于该课程的所有实验都是基于 Rust，我们推荐首先学 Rust 章节。Percolator 和 Raft 相对独立，
先学哪个都没问题。

提示：学语言最快的方法就是用，掌握 Rust 基本语法后就大胆尝试后续实验吧！

## 致谢

该课程中 Raft 章节的实验来自于 [MIT 6.824]，感谢 6.824 工作人员的付出。

[MIT 6.824]: https://pdos.csail.mit.edu/6.824/index.html
