---
term: 纤维

---
快速互联网比特币中继引擎*"的缩写。它是马特-科拉罗（Matt Corallo）于 2016 年设计的一项协议，旨在加快比特币区块在全球范围内的传播速度。其目标是尽可能减少传播延迟，使其接近物理极限。FIBRE 旨在确保更公平地分配挖矿机会，方法是确保参与者挖出的区块比例准确反映其在算力方面的贡献，无论其在网络中的位置如何。

事实上，区块传输的延迟会有利于大型、连接良好的挖矿群组，而不利于小型挖矿群组。随着时间的推移，这种现象可能会加剧挖矿的集中化，降低系统的整体安全性。为解决这一问题，FIBRE 引入了纠错码和传输额外数据以抵消数据包丢失，并使用类似于 BIP152 中描述的紧凑区块，所有这些都通过 UDP 运行，以绕过某些 TCP 限制。尽管如此，FIBRE 还是在 2020 年被放弃了，主要原因是它依赖于单一的维护者，而且 BIP152 的采用也使这样一个系统变得不那么重要。