# Learning with Local Difficulty Awareness for Semi-Supervised Medical Image Segmentation

This repository provides reproducibility information for the manuscript:

**Learning with Local Difficulty Awareness for Semi-Supervised Medical Image Segmentation**

The full source code will be released after manuscript acceptance.

## Overview

This work studies semi-supervised medical image segmentation under limited annotations. The proposed method focuses on difficult local regions with unreliable supervision and improves learning through supervision reconstruction and structural representation enhancement.

## Public datasets

The experiments use four public benchmark datasets:

* ACDC: https://www.creatis.insa-lyon.fr/Challenge/acdc/
* PROMISE12: https://promise12.grand-challenge.org/
* LA: https://github.com/yulequan/UA-MT/tree/master/data/2018LA_Seg_Training%20Set
* NIH-Pancreas: https://github.com/taozh2017/Text-SemiSeg/tree/main

For NIH-Pancreas, we use the pre-processed Pancreas-CT data provided by Text-SemiSeg. The original Pancreas-CT data are publicly available from TCIA.

The raw datasets are not redistributed in this repository. Please obtain the datasets from the listed public sources and follow their respective access terms.

## Code availability

The source code, configuration files, and evaluation scripts will be released after manuscript acceptance.

The implementation builds upon SSL4MIS and BCP. Reused components will retain their original copyright and license notices.

## Acknowledgements

This project builds upon the public semi-supervised medical image segmentation codebases SSL4MIS and BCP. We thank the authors for their open-source contributions.

SSL4MIS: https://github.com/HiLab-git/SSL4MIS

BCP: https://github.com/DeepMed-Lab-ECNU/BCP

The pre-processed Pancreas-CT data follows the public release in Text-SemiSeg:

Text-SemiSeg: https://github.com/taozh2017/Text-SemiSeg/tree/main

## Contact

Yujiao Lan
Email: [your_email@163.com](mailto:your_email@163.com)

Yongjun Zhang
Email: [yjzhang1@gzu.edu.cn](mailto:yjzhang1@gzu.edu.cn)
