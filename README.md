# Awesome-Papers

## 标签分布学习
| Title | Abbreviation | Venue | Code | aaa |
|-----|-----|-----|-----|-----|
| [Label Distribution Learning](https://ieeexplore.ieee.org/document/7439855) | LDL | TKDE 2016 | -- | 一种新的学习范式，为了解决标签形式非数值而是分布形式的问题，这种分布不是指概率分布，而是标签对样本的描述度，也就是0.2和0.8的标签都描绘了样本，但是描述程度不同 |


## 表征学习（鲁棒、泛化）
| Title | Abbreviation | Venue | Code | aaa |
|-----|-----|-----|-----|-----|
| [Generalized Cross Entropy Loss for Training Deep Neural Networks with Noisy Labels](https://proceedings.neurips.cc/paper/2018/hash/f2925f97bc13ad2852a7a551802feea0-Abstract.html) | GCE | NeurIPS 2018 | [code](https://github.com/AlanChou/Truncated-Loss) | 调整了损失梯度前的权重，弱化其对预测与标签之前不一致的惩罚 |
| [Can Cross Entropy Loss Be Robust to Label Noise?](https://www.ijcai.org/Proceedings/2020/0305.pdf) | TCE | IJCAI 2020 | - | 泰勒展开交叉熵，使其有界 |
| [mixup: BEYOND EMPIRICAL RISK MINIMIZATION](https://openreview.net/forum?id=r1Ddp1-Rb&;noteId=r1Ddp1-Rb) | mixup | ICLR 2018 | [code](https://github.com/facebookresearch/mixup-cifar10) | 线性插值，归纳偏置 |


## semi-supervised
| Title | Abbreviation | Venue | Code | aaa |
|-----|-----|-----|-----|-----|
| [Class-Distribution-Aware Pseudo-Labeling for Semi-Supervised Multi-Label Learning](https://proceedings.neurips.cc/paper_files/paper/2023/file/5195825ee60d7efc1e42b7f3f3137040-Paper-Conference.pdf) | CAP | NeurIPS 2023 | [code](https://github.com/xiemk/SSMLL-CAP) | 真实标签分布拟合伪标签分布 |
| [MixMatch: A Holistic Approach to Semi-Supervised Learning](https://proceedings.neurips.cc/paper_files/paper/2019/hash/1cd138d0499a68f4bb72bee04bbec2d7-Abstract.html) | MixMatch | NeurIPS 2019 | [code](https://github.com/google-research/mixmatch) | mixup+sharpening函数生成伪标签，用于半监督学习 |
| [FixMatch: Simplifying Semi-Supervised Learning with Consistency and Confidence](https://proceedings.neurips.cc/paper_files/paper/2020/file/06964dce9addb1c5cb5d6e3d9838f733-Paper.pdf) | FixMatch | NeurIPS 2020 | [code](https://github.com/google-research/fixmatch) | 弱增强图像的预测（高置信度）生成伪标签监督强增强图像 |
