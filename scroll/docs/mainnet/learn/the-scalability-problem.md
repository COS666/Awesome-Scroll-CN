---
section: learn
date: Last Modified
title: "扩容问题"
lang: "zh"
permalink: "learn/intro-to-rollups"
excerpt: "以太坊强大的去中心化和安全性是以牺牲可扩展性为代价的：为了确保所有参与节点都能跟上网络的进度，网络的吞吐量是有限的。这样的限制最终会导致用户端的成本和延迟增加。"
whatsnext: { "Rollups 介绍": "/learn/intro-to-rollups" }
---

## 以太坊的扩容问题

[以太坊](https://ethereum.org/en/developers/docs/intro-to-ethereum/#what-is-ethereum) 是一个通用的区块链平台，支持 [智能合约](https://ethereum.org/en/developers/docs/intro-to-ethereum/#what-are-smart-contracts) 的部署和执行。

以太坊的核心价值是它坚持于安全和去中心化。以太坊的设计使得世界各地的计算机（甚至是便宜的计算机，如 [树莓派](https://ethereum-on-arm-documentation.readthedocs.io/)）都可以参与网络，运行区块链的本地节点并处理新交易。

然而，以太坊强大的去中心化和安全性是以牺牲可扩展性为代价的：为了确保所有参与节点都能跟上网络的进度，网络的吞吐量是有限的。这样的限制最终会导致用户端的成本和延迟增加。

## 扩容解决方案

以太坊的扩容解决方案旨在在不牺牲去中心化或安全性的情况下提高网络的吞吐量。

扩容解决方案主要有两种类型：一层（Layer 1）扩容解决方案和二层（Layer 2）扩容解决方案。

**Layer 1** (后文简称 **L1**) 扩容解决方案尝试通过直接修改以太坊区块链来扩展网络。这里的术语“Layer 1”是指核心的以太坊区块链。通常，很难设计出能够提高吞吐量并同时保持高级别安全性和去中心化的一层扩展解决方案。因此，最近的扩容工作已从一层解决方案转向二层解决方案。

**Layer 2** (后文简称 **L2**) 扩容解决方案是位于以太坊一层之上的网络 - 它们本质上是独立的区块链，以某种方式“锚定”到底层以太坊区块链。这些二层网络通常可以比底层网络以更高的速率处理交易，因为它们不受相同的限制。“锚定”机制的细节在各个二层中有所不同，使二层网络能够继承以太坊一层网络的强大安全性和去中心化性。
