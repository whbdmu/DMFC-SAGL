# ACM MM-2025-Dual-Constraint Multi-view Fuzzy Clustering with Scalable Anchor Graph Learning (DMFC-SAGL)
## Paper
This repository is the official matlab implementation for the paper "Dual-Constraint Multi-view Fuzzy Clustering with Scalable Anchor Graph Learning" by Luyan Cui (cuiluyan@dlmu.edu.cn), Huibing Wang (huibing.wang@dlmu.edu.cn), Yawei Chen, Mingze Yao, Xianping Fu, Jiqing Zhang. Proceedings of the 33rd ACM International Conference on Multimedia, ACM MM-25.
## Introduction
In this paper, we present a Dual-Constraint Multi-view Fuzzy Clustering with Scalable Anchor Graph Learning (DMFC-SAGL) that explores the anchor graphs of different magnitudes and directly derives the clustering labels via fuzzy clustering. In particular, DMFC-SAGL first learns the multi-scale anchor graphs based different quantity of anchors to accommodate the distinct data distributions and extract more comprehensive information. Then, by carrying out fuzzy clustering for anchor graphs, the soft labels can be generated directly without additional post-processing. Moreover, DMFC-SAGL imposes the dual-constraint of low-rank tensor and orthogonality during label learning to ensure the information of consistency and diversity among multi-scale anchor graphs. Experiments with advanced baselines on the seven multi-view datasets indicate the superiority of the proposed method.
<img width="1408" height="460" alt="image" src="https://github.com/user-attachments/assets/5b1f0454-6792-4ab8-82b4-a5deffa1ebee" />
## Dependencies
* OS: Windows 10
* Matlab 2020b
* Related measure can be obtained in .\functions
## Usage
* Conduct clustering run demo_BDGP.m and demo_CCV.m. The relevant hyperparameter settings have been provided in the code.
