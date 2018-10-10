# pasox_zab_protocol

分布式一致性协议相关论文及中文译文

## Paxos

### Leslie Lamport

[>> 译文](./The-Part-Time-Parliament_zh.pdf)

[>> 原文](./The-Part-Time-Parliament.pdf)

### John Ousterhout and Diego Ongaro

[>> 译文](./paxos_zh.pptx)

[>> 原文](./paxos.pdf)

> 该 ppt 深入分析 Paxos 的内部机制，并以日志复制同步（Replicated Logs）为背景，详细介绍使用 Paxos 协议实现日志复制同步。
>
> 这也是我所遇到的讲解 Paxos 最为详尽的一份不可多得的资料。
> 
> 如果大家对 ppt 里的内容不是很理解，可以订阅我的课程：https://gitbook.cn/gitchat/activity/5bb038b45828f008f1d73fd6
> 我在里面对 ppt 的每一页都做了详细的讲解，并提供了伪代码和Java实现。

## ZAB

[>> 译文](./ZooKeeper原子广播协议理论与实践.md)

[>> 原文](./2012-deSouzaMedeiros.pdf)

>翻译的不好，如果有晦涩难懂或者翻译不好的地方欢迎大家提Issues👏
>
>对于一些专有名词，则采取使用原英文形式，以保持其含义的准确性。

## TODO

**ZAB：**

* TODO<sup>①</sup>、TODO<sup>②</sup> 结合issues进行理解；
* Fast Leader Election 快速选举算法完成其余的流程分析；
