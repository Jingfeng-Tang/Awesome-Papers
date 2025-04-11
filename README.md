# Awesome-Papers

## 表征学习（鲁棒、泛化）
| Title | Abbreviation | Venue | Code | aaa |
|-----|-----|-----|-----|-----|
| [Can Cross Entropy Loss Be Robust to Label Noise?](https://www.ijcai.org/Proceedings/2020/0305.pdf) | TCE | IJCAI 2020 | - | 泰勒展开交叉熵，使其有界 |
| [mixup: BEYOND EMPIRICAL RISK MINIMIZATION](https://openreview.net/forum?id=r1Ddp1-Rb&;noteId=r1Ddp1-Rb) | mixup | ICLR 2018 | [code](https://github.com/facebookresearch/mixup-cifar10) | 线性插值，归纳偏置 |


## semi-supervised
| Title | Abbreviation | Venue | Code | aaa |
|-----|-----|-----|-----|-----|
| [Class-Distribution-Aware Pseudo-Labeling for Semi-Supervised Multi-Label Learning](https://proceedings.neurips.cc/paper_files/paper/2023/file/5195825ee60d7efc1e42b7f3f3137040-Paper-Conference.pdf) | CAP | NeurIPS 2023 | [code](https://github.com/xiemk/SSMLL-CAP) | 真实标签分布拟合伪标签分布 |
| [MixMatch: A Holistic Approach to Semi-Supervised Learning](https://proceedings.neurips.cc/paper_files/paper/2019/hash/1cd138d0499a68f4bb72bee04bbec2d7-Abstract.html) | MixMatch | NeurIPS 2019 | [code](https://github.com/google-research/mixmatch) | mixup+sharpening函数生成伪标签，用于半监督学习 |
| [FixMatch: Simplifying Semi-Supervised Learning with Consistency and Confidence](https://proceedings.neurips.cc/paper_files/paper/2020/file/06964dce9addb1c5cb5d6e3d9838f733-Paper.pdf) | FixMatch | NeurIPS 2020 | [code](https://github.com/google-research/fixmatch) | 弱增强图像的预测（高置信度）生成伪标签监督强增强图像 |
