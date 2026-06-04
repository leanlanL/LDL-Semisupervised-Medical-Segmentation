# Learning with Local Difficulty Awareness for Semi-Supervised Medical Image Segmentation

本仓库为以下论文提供可复现性信息：

**Learning with Local Difficulty Awareness for Semi-Supervised Medical Image Segmentation**

完整源代码将在论文接收后发布。

## 工作概述

本文研究有限标注条件下的半监督医学图像分割。所提出的方法关注监督不可靠的困难局部区域，并通过监督重构和结构表征增强来改善这些区域的学习。

## 公开数据集

实验使用四个公开基准数据集：

ACDC：https://www.creatis.insa-lyon.fr/Challenge/acdc/
PROMISE12：https://promise12.grand-challenge.org/
LA：https://github.com/yulequan/UA-MT/tree/master/data/2018LA_Seg_Training%20Set
NIH-Pancreas：https://github.com/taozh2017/Text-SemiSeg/tree/main

对于 NIH-Pancreas，本文使用 Text-SemiSeg 提供的处理后 Pancreas-CT 数据。

本仓库不重新分发原始数据集。请从上述公开来源获取数据，并遵守相应的数据访问条款。

## 代码可用性

源代码、配置文件和评估脚本将在论文接收后发布。

本文实现基于 SSL4MIS 和 BCP。复用组件将保留其原始版权和许可证说明。

## 致谢

本项目基于公开的半监督医学图像分割代码库 SSL4MIS 和 BCP。感谢这些代码库作者的开源贡献。

SSL4MIS：https://github.com/HiLab-git/SSL4MIS

BCP：https://github.com/DeepMed-Lab-ECNU/BCP

处理后的 Pancreas-CT 数据遵循 Text-SemiSeg 的公开发布：

Text-SemiSeg：https://github.com/taozh2017/Text-SemiSeg/tree/main

## 联系方式

Yujiao Lan
邮箱：[your_email@163.com](mailto:your_email@163.com)

Yongjun Zhang
邮箱：[yjzhang1@gzu.edu.cn](mailto:yjzhang1@gzu.edu.cn)
