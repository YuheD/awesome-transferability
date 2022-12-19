
# awesome-transferability

This repo is a collection of AWESOME things about model transferability, including papers, code, etc. 

## Shallow methods
- **[2016]** Learning to Select Pre-trained Deep Representations with Bayesian Evidence Framework [[CVPR]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Kim_Learning_to_Select_CVPR_2016_paper.pdf)


## Deep methods

### 2019
- **[NCE]** Transferability and Hardness of Supervised Classification Tasks [[ICCV]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Tran_Transferability_and_Hardness_of_Supervised_Classification_Tasks_ICCV_2019_paper.pdf) 
> The conditional entropy of label sequences
- **[H-Score]** An informationtheoretic approach to transferability in task transfer learning [[ICIP]](https://ieeexplore.ieee.org/document/8803726)
> a high H-score implies the inter-class variance of f is large, while feature redundancy is small.

### 2020
- **LEEP**: A New Measure to Evaluate Transferability of Learned Representations [[ICML]](https://arxiv.org/pdf/2002.12462) [[Slides]](https://dev.icml.cc/media/icml-2020/Slides/6289.pdf) [[PyTorch]](https://github.com/thuml/LogME)
>The conditional entropy of label sequences
- Model Reuse with Reduced Kernel Mean Embedding Specification [[ArXiv]](https://arxiv.org/abs/2001.07135)
- Boosting-based reliable model reuse [[ACML]](https://proceedings.mlr.press/v129/ding20a.html)

### 2021
- **[NLeep]** Ranking Neural Checkpoints [[CVPR]](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Ranking_Neural_Checkpoints_CVPR_2021_paper.pdf)
> replacing θ(x)z, the probability of classifying an input x to the class z, in equations (4–5) by the posterior distribution P (v|x).
- **LogME**: Practical Assessment of Pre-trained Models for Transfer Learning [[ICML]](http://arxiv.org/abs/2211.16299) [[PyTorch]](https://github.com/thuml/LogME)
- A linearized framework and a new benchmark for model selection for fine-tuning [[CoRR]](https://openreview.net/forum?id=ZsT82LZ8Xkc)
> Label-Gradient Correlation.& Label-Feature Correlation.
- Scalable Diverse Model Selection for Accessible Transfer Learning [[NeurIPS]](https://proceedings.neurips.cc/paper/2021/file/a1140a3d0df1c81e24ae954d935e8926-Paper.pdf) [[PyTorch]](https://github.com/dbolya/parc)
> pairwise Pearson product-moment correlation & Spearman correlation
- A Mathematical Framework for Quantifying Transferability in Multi-source Transfer Learning [[NeurIPS]](https://proceedings.neurips.cc/paper/2021/hash/db9ad56c71619aeed9723314d1456037-Abstract.html)
- Practical Transferability Estimation for Image Classification Tasks [[ArXiv]](https://arxiv.org/abs/2106.10479)
- Newer is not always better: Rethinking transferability metrics, their peculiarities, stability and performance [[ArXiv]](https://arxiv.org/abs/2110.06893)
- Transferability Estimation for Semantic Segmentation Task [[ArXiv]](https://arxiv.org/abs/2109.15242)
- OTCE: A Transferability Metric for Cross-Domain Cross-Task Representations [[CVPR]](https://openaccess.thecvf.com/content/CVPR2021/papers/Tan_OTCE_A_Transferability_Metric_for_Cross-Domain_Cross-Task_Representations_CVPR_2021_paper.pdf) [[Poster]](https://www.tbsi.edu.cn/wolt/tbsi_wolt2020/posters/tanyang.pdf)


### 2022
- Frustratingly Easy Transferability Estimation [[ICML]](https://proceedings.mlr.press/v162/huang22d.html) [[Slides]](https://icml.cc/media/icml-2022/Slides/17386.pdf)
> Mutual Information between the feature extracted by the pre-trained model and the labels.
- Rethinking Two Consensuses of the Transferability in Deep Learning [[ArXiv]](http://arxiv.org/abs/2212.00399)
> $D(\theta_r,\theta_B)/D(\theta_A,\theta_B)$
- Transferability Estimation Using Bhattacharyya Class Separability [[CVPR]](https://openaccess.thecvf.com/content/CVPR2022/html/Pandy_Transferability_Estimation_Using_Bhattacharyya_Class_Separability_CVPR_2022_paper.html)
> inter-class distance larger, transferability higher.
- Transferability Metrics for Selecting Source Model Ensembles [[CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Agostinelli_Transferability_Metrics_for_Selecting_Source_Model_Ensembles_CVPR_2022_paper.pdf)
- **How stable are Transferability Metrics evaluations?** [[ECCV]](https://arxiv.org/abs/2204.01403) [[TensorFlow]](https://github.com/google-research/google-research/tree/master/stable_transfer)
- Pre-Trained Model Reusability Evaluation for Small-Data Transfer Learning [[NeurIPS]](https://openreview.net/forum?id=XY5g3mkVge) [[Codes]](https://github.com/candytalking/SynLearn.)
- Neural Transferability: Current Pitfalls and Striving for Optimal Scores [[SSRN Under Review]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4196999)
- Transferability Estimation Based On Principal Gradient Expectation [[ArXiv]](http://arxiv.org/abs/2211.16299)
> gradient expectation
- Ranking and Tuning Pre-trained Models: A New Paradigm for Exploiting Model Hubs [[JMLR]](https://www.jmlr.org/papers/volume23/21-1251/21-1251.pdf)
- PACTran: PAC-Bayesian Metrics for Estimating the Transferability of Pretrained Models to Classification Tasks [[ECCV]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136940244.pdf) [[Codes]](https://github.com/google-research/pactran_metrics)
- Which Model to Transfer? Finding the Needle in the Growing Haystack [[CVPR]](https://openaccess.thecvf.com/content/CVPR2022/html/Renggli_Which_Model_To_Transfer_Finding_the_Needle_in_the_Growing_CVPR_2022_paper.html)
- Transfer how much: a fine-grained measure of the knowledge transferability of user behavior sequences in social network [[Data Mining and Knowledge Discovery]](https://link.springer.com/article/10.1007/s10618-022-00857-w)
- Evidence > Intuition: Transferability Estimation for Encoder Selection [[EMNLP]](https://arxiv.org/abs/2210.11255)
