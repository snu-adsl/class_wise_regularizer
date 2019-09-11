# Utilizing Class Information for Deep Network Representation Shaping

This repo contains code accompaning the paper, [Utilizing Class Information for Deep Network Representation Shaping](https://www.aaai.org/ojs/index.php/AAAI/article/view/4214)  

## Abstract

Statistical characteristics of deep network representations, such as sparsity and correlation, are known to be relevant to the performance and interpretability of deep learning. When a statistical characteristic is desired, often an adequate regularizer can be designed and applied during the training phase. Typically, such a regularizer aims to manipulate a statistical characteristic over all classes together. For classification tasks, however, it might be advantageous to enforce the desired characteristic per class such that different classes can be better distinguished. Motivated by the idea, we design two class-wise regularizers that explicitly utilize class information: class-wise Covariance Regularizer (cw-CR) and classwise Variance Regularizer (cw-VR). cw-CR targets to reduce the covariance of representations calculated from the same class samples for encouraging feature independence. cw-VR is similar, but variance instead of covariance is targeted to improve feature compactness. For the sake of completeness, their counterparts without using class information, Covariance Regularizer (CR) and Variance Regularizer (VR), are considered together. The four regularizers are conceptually simple and computationally very efficient, and the visualization shows that the regularizers indeed perform distinct representation shaping. In terms of classification performance, significant improvements over the baseline and L1/L2 weight regularization methods were found for 21 out of 22 tasks over popular benchmark datasets. In particular, cw-VR achieved the best performance for 13 tasks including ResNet-32/110.

## Citation

If you are use of any material in this repository, we ask to cite:

```

@inproceedings{choi2019utilizing,
  title={Utilizing Class Information for Deep Network Representation Shaping},
  author={Choi, Daeyoung and Rhee, Wonjong},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={33},
  pages={3396--3403},
  year={2019}
}
```

-------

