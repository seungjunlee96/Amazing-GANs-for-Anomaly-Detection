# Amazing-GANs-For-Anomaly-Detection

## What is anomaly detection?
Anomaly detection is a technique used to identify unusual patterns that do not conform to expected behavior, called outliers. Typically, this is treated as an unsupervised learning problem where the anomalous samples are not known a priori and it is assumed that the majority of the training dataset consists of “normal” data (here and elsewhere the term “normal” means *not anomalous* and is unrelated to the Gaussian distribution). [Lukas Ruff et al., 2018; Deep One-Class Classification]

In general, Anomaly detection is also called `Novelty Detection` or `Outlier Detection`, `Forgery Detection` and `Out-of-distribution Detection`.   

Each term has slightly different meanings. Mostly, on the assumption that you do not have unusual data, this problem is especially called `One Class Classification`, `One Class Segmentation`.  

and `Novelty Detection` and `Outlier Detection` have slightly different meanings. Figure below shows the differences of two terms.

Also, there are two types of target data. (`time-series data`, and `image data`)  
In time-series data, it is aimed to detect a abnormal sections or frames in input data. (ex, videos, signal, etc)  
In image data, it is aimed to classify abnormal images or to segment abnormal regions, for example, defect in some manufacturing data.  

[Reference](https://github.com/hoya012/awesome-anomaly-detection)

## Lists of GANs for Anomaly Detection
|Conference|Year|Paper|Github|
|:--------:|:---:|:---:|:----:|
|Medical Image Analysis|2017|[AnoGAN:Unsupervised Anomaly Detection with Generative Adversarial Networks to Guide Marker Discovery](https://arxiv.org/abs/1703.05921)|[Unofficial](https://github.com/LeeDoYup/AnoGAN-tf)|
|IEEE ICDM|2018|[Adversarially Learned Anomaly Detection](https://arxiv.org/abs/1812.02288)|[Official](https://github.com/houssamzenati/Adversarially-Learned-Anomaly-Detection)|
|ICLRW|2018|[EGBAD: Efficient GAN-Based Anomaly Detection](https://arxiv.org/abs/1802.06222)|[Official](https://github.com/houssamzenati/Efficient-GAN-Anomaly-Detection)|
|Asian Conference on Computer Vision|2018|[GANomaly: Semi-Supervised Anomaly Detection via Adversarial Training](http://arxiv.org/abs/1805.06725)||
|arXiv|2019|[Fence GAN: Towards Better Anomaly Detection](https://arxiv.org/abs/1904.01209)|[Official](https://github.com/phuccuongngo99/Fence_GAN)|
|Medical Image Analysis|2019|[f-AnoGAN](https://github.com/tSchlegl/f-AnoGAN/tree/master/paper)|[Official](https://github.com/tSchlegl/f-AnoGAN)|
|arXiv|2019|[Unsupervised Learning of Anomaly Detection from Contaminated Image Data using Simultaneous Encoder Training](https://arxiv.org/pdf/1905.11034.pdf)|-|


## Survey Papers
| |Year|Paper|
|:--:|:---:|:---:|
|arXiv|2019|[A Survey on GANs for Anomaly Detection](https://arxiv.org/pdf/1906.11632)|
|arXiv|2019|[A study on Anomaly Detection GAN-based methods on image data]|
|arXiv|2019|[Deep Learning for Anomaly Detection: A Survey](https://arxiv.org/pdf/1901.03407.pdf)|
|arXiv|2019|[Anomalous Instance Detection in Deep Learning: A Survey](https://arxiv.org/pdf/2003.06979.pdf)|
