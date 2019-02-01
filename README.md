# pasox_zab_protocol

分布式一致性协议相关论文及中文译文，涵盖Paxos、Raft、Zab。

## Paxos

### 论文

Leslie Lamport（Paxos之父）论文《The Part-Time Parliament》、《Paxos Made Simple》。

**The-Part-Time-Parliament**:

[>> 译文](paxos/The-Part-Time-Parliament_zh.pdf)

[>> 原文](paxos/The-Part-Time-Parliament.pdf)

**Paxos-Made-Simple**：

[>> 译文](paxos/Paxos-Made-Simple_zh.pdf)

[>> 原文](paxos/Paxos-Made-Simple.pdf)

### 斯坦福大学

作者：John Ousterhout(斯坦福大学教授) 和Diego Ongaro(斯坦福大学获得博士学位，Raft算法发明人)

[>> 译文](paxos/paxos_zh.pptx)

[>> 原文](paxos/paxos.pptx)

该 PPT 深入分析了 Paxos 的设计原理，并以日志复制同步（Replicated Logs）为背景，详细介绍如何使用 Paxos 协议实现日志复制同步系统。
这也是我所遇到的讲解 Paxos 最为详尽的一份不可多得的资料。
如果大家对 PPT 里的内容不是很理解，可以订阅我的课程，对 PPT 的每一页都做了详细的讲解，并总结了算法实现概述。

[详解 Paxos 分布式一致性协议，从零实现分布式日志同步复制（Replicated Logs）](https://gitbook.cn/gitchat/activity/5bb038b45828f008f1d73fd6)

## Raft

作者：John Ousterhout(斯坦福大学教授) 和Diego Ongaro(斯坦福大学获得博士学位，Raft算法发明人)

[>> 译文](raft/raft_zh.pptx)

[>> 原文](raft/raft.pptx)

[>> raft协议详解](raft/raft.md)

## ZAB

[>> 译文](zab/ZooKeeper原子广播协议理论与实践.md)

[>> 原文](zab/2012-deSouzaMedeiros.pdf)

> 翻译的不好，如果有晦涩难懂或者翻译不好的地方欢迎大家提issues👏
>
> 对于一些专有名词，则采取使用原英文形式，以保持其含义的准确性。

## TODO

**ZAB：**

* TODO<sup>①</sup>、TODO<sup>②</sup> 结合issues进行理解；
* Fast Leader Election 快速选举算法完成其余的流程分析；
