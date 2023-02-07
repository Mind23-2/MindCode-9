# GhostNet描述

## 概述

GhostNet由华为诺亚方舟实验室在2020年提出，此网络提供了一个全新的Ghost模块，旨在通过廉价操作生成更多的特征图。基于一组原始的特征图，作者应用一系列线性变换，以很小的代价生成许多能从原始特征发掘所需信息的“幻影”特征图（Ghost feature maps）。该Ghost模块即插即用，通过堆叠Ghost模块得出Ghost bottleneck，进而搭建轻量级神经网络——GhostNet。该架构可以在同样精度下，速度和计算量均少于SOTA算法。

如下为MindSpore使用ImageNet2012数据集对GhostNet进行训练的示例。

## 论文

1. [论文](https://gitee.com/link?target=https%3A%2F%2Farxiv.org%2Fpdf%2F1911.11907.pdf): Kai Han, Yunhe Wang, Qi Tian."GhostNet: More Features From Cheap Operations"

# 模型架构

GhostNet的总体网络架构如下：[链接](https://gitee.com/link?target=https%3A%2F%2Farxiv.org%2Fpdf%2F1911.11907.pdf)
[RepoLink](https://gitee.com/mindspore/models/tree/r1.6/research/cv/ghostnet)