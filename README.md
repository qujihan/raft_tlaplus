# Raft TLA+ 形式化验证

Raft 论文 以及 Ongaro PhD 论文

[In Search of an Understandable Consensus Algorithm (Extended Version)](https://raft.github.io/raft.pdf)

[CONSENSUS: BRIDGING THEORY AND PRACTICE](https://web.stanford.edu/~ouster/cgi-bin/papers/OngaroPhD.pdf)

- 经典的 Raft 实现: raft_standard
- 经典的 Raft + 添加删除单个节点: raft_reconfig_add_remove
- 经典的 Raft + 联合共识算法: raft_reconfig_joint_consensus

# 参考
- [Vanlightly](https://github.com/Vanlightly/raft-tlaplus): 形式化验证代码
- [TiKV](https://github.com/tikv/raft-rs): Raft-rs
- [Neko(知乎)](https://www.zhihu.com/people/neko.0x0/posts): 集群变更
- [ARTHURCHIAO](https://arthurchiao.art/blog/raft-paper-zh/)
- [戌米的论文笔记(Bilibili)](https://www.bilibili.com/video/BV1pr4y1b7H5/?spm_id_from=333.880.my_history.page.click&vd_source=f1ab996222e44d51588d415020f0337c): 完整梳理了 Raft 的流程
- [叉鸽](https://blog.mrcroxx.com/categories/%E6%B7%B1%E5%85%A5%E6%B5%85%E5%87%BAetcd/raft/)