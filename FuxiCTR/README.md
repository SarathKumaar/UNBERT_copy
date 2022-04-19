# FuxiCTR

Click-through rate (CTR) prediction is an critical task for many industrial applications such as online advertising, recommender systems, and sponsored search. FuxiCTR provides an open-source library for CTR prediction, with stunning features in configurability, tunability, and reproducibility. 

If you find FuxiCTR useful in your research, please kindly cite the following papers: 

+ Jieming Zhu, Jinyang Liu, Shuai Yang, Qi Zhang, Xiuqiang He. [Open Benchmarking for Click-Through Rate Prediction](https://arxiv.org/abs/2009.05794), in Proceedings of the 30th ACM International Conference on Information and Knowledge Management (CIKM), 2021.
+ Jieming Zhu, Kelong Mao, Quanyu Dai, Liangcai Su, Rong Ma, Jinyang Liu, Guohao Cai, Zhicheng Dou, Xi Xiao, Rui Zhang. [BARS: Towards Open Benchmarking for Recommender Systems](https://openbenchmark.github.io), in Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR), 2022.


## Model List

| Publication| Model  | Paper | Available | 
| :-----: | :-------: |:------------|:----------:|
| WWW'07| [LR](./fuxictr/pytorch/models/LR.py)  |[Predicting Clicks: Estimating the Click-Through Rate for New Ads](https://dl.acm.org/citation.cfm?id=1242643) | :heavy_check_mark: |
|ICDM'10 | [FM](./fuxictr/pytorch/models/FM.py)  | [Factorization Machines](https://www.csie.ntu.edu.tw/~b97053/paper/Rendle2010FM.pdf)| :heavy_check_mark: |
|CIKM'15| [CCPM](./fuxictr/pytorch/models/CCPM.py) | [A Convolutional Click Prediction Model](http://www.escience.cn/system/download/73676) | :heavy_check_mark: |
| RecSys'16 | [FFM](./fuxictr/pytorch/models/FFM.py) | [Field-aware Factorization Machines for CTR Prediction](https://dl.acm.org/citation.cfm?id=2959134) |:heavy_check_mark: |
| RecSys'16 | [YoutubeDNN](./fuxictr/pytorch/models/DNN.py) | [Deep Neural Networks for YouTube Recommendations](http://art.yale.edu/file_columns/0001/1132/covington.pdf) |:heavy_check_mark: |
| DLRS'16 | [Wide&Deep](./fuxictr/pytorch/models/WideDeep.py)  | [Wide & Deep Learning for Recommender Systems](https://arxiv.org/pdf/1606.07792.pdf) |:heavy_check_mark: |
| ICDM'16 | [IPNN](./fuxictr/pytorch/models/PNN.py) | [Product-based Neural Networks for User Response Prediction](https://arxiv.org/pdf/1611.00144.pdf) | :heavy_check_mark: |
| KDD'16 | [DeepCross](./fuxictr/pytorch/models/DeepCrossing.py) | [Deep Crossing: Web-Scale Modeling without Manually Crafted Combinatorial Features](https://www.kdd.org/kdd2016/papers/files/adf0975-shanA.pdf)  | :heavy_check_mark: |
| NIPS'16 | [HOFM](./fuxictr/pytorch/models/HOFM.py) | [Higher-Order Factorization Machines](https://papers.nips.cc/paper/6144-higher-order-factorization-machines.pdf) | :heavy_check_mark: |
| IJCAI'17 | [DeepFM](./fuxictr/pytorch/models/DeepFM.py) | [DeepFM: A Factorization-Machine based Neural Network for CTR Prediction](https://arxiv.org/abs/1703.04247) | :heavy_check_mark: |
|SIGIR'17 | [NFM](./fuxictr/pytorch/models/NFM.py) | [Neural Factorization Machines for Sparse Predictive Analytics](https://dl.acm.org/citation.cfm?id=3080777) | :heavy_check_mark: |
|IJCAI'17 | [AFM](./fuxictr/pytorch/models/AFM.py) | [Attentional Factorization Machines: Learning the Weight of Feature Interactions via Attention Networks](http://www.ijcai.org/proceedings/2017/0435.pdf) |:heavy_check_mark:|
| ADKDD'17 | [DCN](./fuxictr/pytorch/models/DCN.py)  | [Deep & Cross Network for Ad Click Predictions](https://arxiv.org/abs/1708.05123) | :heavy_check_mark:|
| WWW'18 | [FwFM](./fuxictr/pytorch/models/FwFM.py) | [Field-weighted Factorization Machines for Click-Through Rate Prediction in Display Advertising](https://arxiv.org/pdf/1806.03514.pdf)  | :heavy_check_mark: |
|KDD'18 | [xDeepFM](./fuxictr/pytorch/models/xDeepFM.py) | [xDeepFM: Combining Explicit and Implicit Feature Interactions for Recommender Systems](https://arxiv.org/pdf/1803.05170.pdf) | :heavy_check_mark: |
|KDD'18 | [DIN](./fuxictr/pytorch/models/DIN.py) | [Deep Interest Network for Click-Through Rate Prediction](https://www.kdd.org/kdd2018/accepted-papers/view/deep-interest-network-for-click-through-rate-prediction) | :heavy_check_mark: |
|CIKM'19 | [FiGNN](./fuxictr/pytorch/models/FiGNN.py) | [FiGNN: Modeling Feature Interactions via Graph Neural Networks for CTR Prediction](https://arxiv.org/abs/1910.05552) | :heavy_check_mark: |
|CIKM'19 | [AutoInt/AutoInt+](./fuxictr/pytorch/models/AutoInt.py) | [AutoInt: Automatic Feature Interaction Learning via Self-Attentive Neural Networks](https://arxiv.org/abs/1810.11921) | :heavy_check_mark: |
|RecSys'19 | [FiBiNET](./fuxictr/pytorch/models/FiBiNET.py) | [FiBiNET: Combining Feature Importance and Bilinear feature Interaction for Click-Through Rate Prediction](https://arxiv.org/abs/1905.09433) | :heavy_check_mark: |
|WWW'19 | [FGCNN](./fuxictr/pytorch/models/FGCNN.py) | [Feature Generation by Convolutional Neural Network for Click-Through Rate Prediction](https://arxiv.org/abs/1904.04447) | :heavy_check_mark: |
| AAAI'19| [HFM/HFM+](./fuxictr/pytorch/models/HFM.py) | [Holographic Factorization Machines for Recommendation](https://ojs.aaai.org//index.php/AAAI/article/view/4448)  | :heavy_check_mark: |
| Neural Networks'20 | [ONN](./fuxictr/pytorch/models/ONN.py)  | [Operation-aware Neural Networks for User Response Prediction](https://arxiv.org/pdf/1904.12579)  | :heavy_check_mark: |
| AAAI'20 | [AFN/AFN+](./fuxictr/pytorch/models/AFN.py) | [Adaptive Factorization Network: Learning Adaptive-Order Feature Interactions](https://ojs.aaai.org/index.php/AAAI/article/view/5768) | :heavy_check_mark: |
| AAAI'20  | [LorentzFM](./fuxictr/pytorch/models/LorentzFM.py) | [Learning Feature Interactions with Lorentzian Factorization](https://arxiv.org/abs/1911.09821) | :heavy_check_mark: |
| WSDM'20 | [InterHAt](./fuxictr/pytorch/models/InterHAt.py) | [Interpretable Click-through Rate Prediction through Hierarchical Attention](https://dl.acm.org/doi/10.1145/3336191.3371785) | :heavy_check_mark: |
| DLP-KDD'20 | [FLEN](./fuxictr/pytorch/models/FLEN.py) | [FLEN: Leveraging Field for Scalable CTR Prediction](https://arxiv.org/abs/1911.04690) | :heavy_check_mark: |
| WWW'21 | [FmFM](./fuxictr/pytorch/models/FmFM.py) | [FM^2: Field-matrixed Factorization Machines for Recommender Systems](https://arxiv.org/abs/2102.12994) | :heavy_check_mark: |
| IJCAI'21 | [UNBERT](./model_zoo/UNBERT) | [UNBERT: User-News Matching BERT for News Recommendation](https://www.ijcai.org/proceedings/2021/0462.pdf) | :heavy_check_mark: |

## Installation

Please follow [the guide for installation](./tutorials/v1.0/0_install_fuxictr.ipynb). In particular, FuxiCTR has the following dependent requirements. 

+ python 3.6
+ pytorch v1.0/v1.1
+ pyyaml >=5.1
+ scikit-learn
+ pandas
+ numpy
+ h5py
+ tqdm


## Get Started

1. [Run the demo to understand the overall workflow](./tutorials/v1.0/1_run_the_demo.ipynb)

2. [Run a model with dataset and model config files](./tutorials/v1.0/2_run_model_with_config_file.ipynb)

3. [How to make configurations?](./tutorials/v1.0/3_how_to_make_configurations.ipynb)

3. [Tune the model hyper-parameters via grid search](./tutorials/v1.0/4_tune_model_via_grid_search.ipynb)


## Code Structure
[Check an overview of code structure](./docs/FuxiCTR_overview.jpg) for more details on API design.


## Join Us
We have open positions for internships and full-time jobs. If you are interested in research and practice in recommender systems, please send your CV to jamie.zhu@huawei.com.


