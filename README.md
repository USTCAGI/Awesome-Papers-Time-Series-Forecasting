
<div align="center">
  <h2><b> A Comprehensive Survey of Time Series Forecasting: Concepts, Challenges, and Future Directions (Preprint, ArXiv 2025) </b></h2>
</div>

<div align="center">

![](https://img.shields.io/github/last-commit/USTCAGI/Awesome-Papers-Time-Series-Forecasting
?color=green)![](https://img.shields.io/github/stars/USTCAGI/Awesome-Papers-Time-Series-Forecasting
?color=yellow)![](https://img.shields.io/github/forks/USTCAGI/Awesome-Papers-Time-Series-Forecasting
?color=lightblue)![](https://img.shields.io/badge/PRs-Welcome-green)

</div>


> 🙋 Please let us know if you notice any mistakes or have any suggestions!
If you find this resource helpful, please consider starring this repository.

## Updates/News:

🚩 **News** (Mar. 2025): We have created this repository.

## Abstract 🚀
Time series forecasting (TSF) has become an increasingly vital tool in various decision-making applications, including business intelligence and scientific discovery, in today’s rapidly evolving digital landscape. Over the years, a wide range of methods for TSF has been proposed, spanning from traditional static-based models to more recent machine learning-driven, data-intensive approaches. Despite the extensive body of research, there is still no universally accepted, unified problem statement or systematic elaboration of the core challenges and characteristics of TSF. The extent to which deep TSF models can address fundamental issues—such as data sparsity and non-stationarity—remains unclear, and the broader TSF research landscape continues to evolve, shaped by diverse methodological trends. This comprehensive survey aims to address these gaps by examining the key entities in TSF (e.g., covariates) and their characteristics (e.g., frequency, length, missing values). We introduce a general problem formulation and challenge analysis for TSF, propose a taxonomy that classifies representative methodologies from the preprocessing and forecasting perspectives, and highlight emerging topics like transfer learning and trustworthy forecasting. Finally, we discuss promising research directions that are poised to drive innovation in this dynamic and rapidly advancing field.


<p align="center">
<img src="./figures/definition.png" height = "360" alt="" align=center />
</p>

<p align="center">
<img src="./figures/content.png" height = "720" alt="" align=center />
</p>

## Static-based Approaches
- [Some  properties of a simple moving average when applied to fore casting a time series](https://www.tandfonline.com/doi/abs/10.1057/palgrave.jors.2600823) [Journal of the Operational Research Society, 1999]
- [Forecasting seasonals and trends by exponentially  weighted moving averages](https://www.sciencedirect.com/science/article/pii/S0169207003001134) [International journal of forecasting, 2004]
- [Time series analysis: forecasting and control](https://books.google.com/books?hl=zh-CN&lr=&id=rNt5CgAAQBAJ&oi=fnd&pg=PR7&dq=+Time++series+analysis:+forecasting+and+control.&ots=DL50wMjZSy&sig=DC0qn_Ru3mD1uSYWcvgJFhNB6CA) [books.google.com, 2025]
- [Automatic time series forecasting: the forecast package for R](https://www.jstatsoft.org/article/view/v027i03/0) [Journal of statistical software, 2008]
- [Exponential smoothing: The state of the art](https://onlinelibrary.wiley.com/doi/abs/10.1002/for.3980040103) [Journal of forecasting, 1985]
- [Forecasting using simple exponential smoothing method](https://search.proquest.com/openview/0a65a0cecf057c6f8e84e9189ad71b2d/1?pq-origsite=gscholar&cbl=2016346) [Acta Electrotechnica et Informatica, 2012]
- [A new look at models for exponential smoothing](https://rss.onlinelibrary.wiley.com/doi/abs/10.1111/1467-9884.00267) [Journal of the Royal Statistical Society, 2001]
- [Time series forecasting using holt-winters exponential smoothing](https://c.mql5.com/forextsd/forum/69/exponentialsmoothing.pdf) [Kanwal Rekhi school of information Technology, 2004]
- [The markov-switching multifractal model of asset re turns: Gmm estimation and linear forecasting of volatility](https://www.tandfonline.com/doi/abs/10.1198/073500107000000403) [Journal of business & economic statistics, 2008]

## Machine Learning Models
- [Support vector regression machines](https://proceedings.neurips.cc/paper/1996/hash/d38901788c533e8286cb6400b40b386d-Abstract.html) [NeurIPS 1996]
- [Support-Vector Networks](https://link.springer.com/article/10.1007/BF00994018) [Machine Learning 1995]
- [A tutorial on support vector regression](https://link.springer.com/article/10.1023/B:STCO.0000035301.49549.88) [Statistics and Computing 2004]
- [Time series prediction using support vector machines: a survey](https://ieeexplore.ieee.org/document/4840324) [IEEE 2009]
- [Support vector machine with adaptive parameters in financial time series forecasting](https://ieeexplore.ieee.org/abstract/document/1257413) [IEEE 2003]
- [Air pollutant parameter forecasting using support vector machinesn](https://ieeexplore.ieee.org/document/1005545) [IEEE 2002]
- [Time series forecasting by a seasonal support vector regression model](https://www.sciencedirect.com/science/article/abs/pii/S0957417409010185) [Expert Systems with Applications 2010]
- [Iterated time series prediction with multiple support vector regression models](https://www.sciencedirect.com/science/article/abs/pii/S0925231212005863) [Neurocomputing 2013]
- [Classification and regression trees](https://www.nature.com/articles/nmeth.4370) [Nature Methods 2017]
- [Random forests](https://link.springer.com/article/10.1023/A:1010933404324) [Machine Learning 2001]
- [Greedy function approximation: a gradient boosting machine]() []
- [Forecasting with trees](https://www.sciencedirect.com/science/article/pii/S0169207021001679) [International Journal of Forecasting 2022]
- [A hybrid method using exponential smoothing and gradient boosting for electrical short-term load forecasting](https://www.sciencedirect.com/science/article/abs/pii/S0169207019301153) [International Journal of Forecasting 2020]
- [Nearest neighbor pattern classification](https://ieeexplore.ieee.org/document/1053964) [IEEE 1967]
- [A methodology for applying k-nearest neighbor to time series forecastin](https://link.springer.com/article/10.1007/s10462-017-9593-z) [Artificial Intelligence Review 2019]
- [Dealing with seasonality by narrowing the training set in time series forecasting with kNN](Expert systems with applications) [Expert systems with applications 2018]
- [A k-nearest-neighbor simulator for daily precipitation and other weather variable](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/1999WR900028) [Water resources research 1999]
- [Multivariate k-nearest neighbour regression for time series data—A novel algorithm for forecasting UK electricity demand](https://ieeexplore.ieee.org/document/6706742) [IEEE 2013]


## Deep Learning Models
### RNNs
- [Modeling Long- and Short-Term Temporal Patterns with Deep Neural Networks](https://arxiv.org/abs/1703.07015) [SIGIR 2018]
- [A Dual-Stage Attention-Based Recurrent Neural Network for Time Series Prediction](https://arxiv.org/abs/1704.02971) [IJCAI 2017]
- [DeepAR: Probabilistic Forecasting with Autoregressive Recurrent Networks](https://arxiv.org/abs/1704.04110) [IJoF 2019]
- [A Multi-Horizon Quantile Recurrent Forecaster](https://arxiv.org/abs/1711.11053) [NIPSW 2017]
- [Deep Factors for Forecasting](https://arxiv.org/abs/1905.12417) [ICML 2019]
- [A hybrid method of exponential smoothing and recurrent neural networks for time series forecasting](https://www.sciencedirect.com/science/article/pii/S0169207019301153) [IJoF 2020]
- [Multi-Horizon Time Series Forecasting with Temporal Attention Learning](https://dl.acm.org/doi/abs/10.1145/3292500.3330662) [KDD 2019]
- [Modeling Irregular Time Series with Continuous Recurrent Units](https://arxiv.org/abs/2111.11344) [ICML 2022]
- [SegRNN: Segment Recurrent Neural Network for Long-Term Time Series Forecasting](https://arxiv.org/abs/2308.11200) [Arxiv 2023]
### CNNs
- [Towards Better Forecasting by Fusing Near and Distant Future Visions](https://arxiv.org/abs/1912.05122) [AAAI 2020]
- [MICN: Multi-scale Local and Global Context Modeling for Long-term Series Forecasting](https://openreview.net/pdf?id=zt53IDUR1U) [ICLR 2023]
- [ConvTimeNet: A Deep Hierarchical Fully Convolutional Model for Multivariate Time Series Analysis](https://arxiv.org/abs/2403.01493) [WWW 2025]
- [SCINet: Time Series Modeling and Forecasting with Sample Convolution and Interaction](https://arxiv.org/abs/2106.09305) [NIPS 2022]
- [FTMixer: Frequency and Time Domain Representations Fusion for Time Series Modeling](https://arxiv.org/abs/2405.15256) [Arxiv 2024]
- [TimesNet: Temporal 2D-Variation Modeling for General Time Series Analysis](https://arxiv.org/abs/2210.02186) [ICLR 2023]
- [ModernTCN: A Modern Pure Convolution Structure for General Time Series Analysis](https://openreview.net/pdf?id=vpJMJerXHU) [ICLR 2024]
- [Ts2vec: Towards universal representation of time series](https://ojs.aaai.org/index.php/AAAI/article/view/20881/20640) [AAAI 2022]
### Attention
- [Enhancing the Locality and Breaking the Memory Bottleneck of Transformer on Time Series Forecasting](https://arxiv.org/abs/1907.00235) [NIPS 2019]
- [Informer: Beyond Efficient Transformer for Long Sequence Time-Series Forecasting](https://arxiv.org/abs/2012.07436) [AAAI 2021]
- [Autoformer: Decomposition Transformers with Auto-Correlation for Long-Term Series Forecasting](https://arxiv.org/abs/2106.13008) [NIPS 2021]
- [FEDformer: Frequency Enhanced Decomposed Transformer for Long-term Series Forecasting](https://arxiv.org/abs/2201.12740) [ICML 2022]
- [Crossformer: Transformer Utilizing Cross-Dimension Dependency for Multivariate Time Series Forecasting](https://openreview.net/forum?id=vSVLM2j9eie) [ICLR 2023]
- [A Time Series is Worth 64 Words: Long-term Forecasting with Transformers](https://arxiv.org/abs/2211.14730) [ICLR 2023]
- [iTransformer: Inverted Transformers Are Effective for Time Series Forecasting](https://arxiv.org/abs/2310.06625) [ICLR 2024]
### MLPs
- [N-BEATS: Neural Basis Expansion Analysis For Interpretable Time Series Forecasting](https://arxiv.org/abs/1905.10437) [ICLR 2020]
- [N-HiTS: Neural Hierarchical Interpolation for Time Series Forecasting](https://arxiv.org/abs/2201.12886) [AAAI 2023]
- [Are Transformers Effective for Time Series Forecasting?](https://arxiv.org/abs/2205.13504) [AAAI 2023]
- [Koopa: Learning Non-stationary Time Series Dynamics with Koopman Predictors](https://arxiv.org/abs/2305.18803) [NIPS 2023]
- [FITS: Modeling Time Series with 10k Parameters](https://arxiv.org/abs/2307.03756) [ICLR 2024]
- [SparseTSF: Modeling Long-term Time Series Forecasting with 1k Parameters](https://arxiv.org/abs/2405.00946) [ICML 2024]
- [TimeMixer: Decomposable Multiscale Mixing for Time Series Forecasting](https://openreview.net/forum?id=7oLshfEIC2) [ICLR 2024]
### SSMs
- [Deep State Space Models for Time Series Forecasting](https://papers.nips.cc/paper/8004-deep-state-space-models-for-time-series-forecasting) [NIPS 2018]
- [Effectively Modeling Time Series with Simple Discrete State Spaces](https://arxiv.org/abs/2303.09489) [ICLR 2023]
- [TimeMachine: A Time Series is Worth 4 Mambas for Long-term Forecasting](https://arxiv.org/abs/2303.09489) [ECAI 2024]
- [Is Mamba Effective for Time Series Forecasting?](https://arxiv.org/abs/2403.11144) [Arxiv 2024]
### KANs
- [Kan: Kolmogorov-arnold networks](https://arxiv.org/abs/2404.19756) [Arxiv 2024]  
- [Kolmogorov-Arnold Networks (KANs) for Time Series Analysis](https://arxiv.org/abs/2405.08790) [Arxiv 2024]
- [A Temporal Kolmogorov-Arnold Transformer for Time Series Forecasting](https://arxiv.org/abs/2406.02486) [Arxiv 2024]

## Generative Models
### Autoregressive Models
- [Timer: generative pre-trained transformers are large time series models](https://arxiv.org/pdf/2402.02368) [ICML 2024]
- [Instructime: Advancing time series classification with multimodal language modeling](https://dl.acm.org/doi/10.1145/3701551.3703499) [WSDM 2025]
- [Generative pretrained hierarchical transformer for time series forecasting](https://dl.acm.org/doi/10.1145/3637528.3671855) [KDD 2024]
- [Autotimes: Autoregressive time series forecasters via large language models](https://arxiv.org/pdf/2402.02370) [NeurIPS 2024]
### VAEs
- [Timevae: A variational auto-encoder for multivariate time series generation](https://arxiv.org/pdf/2111.08095) [Arxiv 2021]
- [Hybrid variational autoencoder for time series forecasting](https://arxiv.org/pdf/2303.07048) [KBS 2023]
### GANs
- [Time-series generative adversarial networks](https://dl.acm.org/doi/abs/10.5555/3454287.3454781) [NeurIPS 2019]
- [Context-aware traffic flow forecasting in new roads](https://dl.acm.org/doi/10.1145/3511808.3557566) [CIKM 2022]
- [Curb-gan: Conditional urban traffic estimation through spatio-temporal generative adversarial networks](https://dl.acm.org/doi/10.1145/3394486.3403127) [SIGKDD 2020]
### Flow-based Models
- [Conditional flow matching for time series modelling](https://openreview.net/pdf?id=Hqn4Aj7xrQ) [ICML 2024 Workshop]
- [Trajectory flow matching with applications to clinical time series modelling](https://arxiv.org/pdf/2410.21154) [NeurIPS 2024]
- [Fm-ts: Flow matching for time series generation](https://arxiv.org/pdf/2411.07506) [Arxiv 2024]
### Diffusion Models
- [Autoregressive denoising diffusion models for multivariate probabilistic time series forecasting](https://arxiv.org/abs/2101.12072) [ICML 2021]
- [Predict, refine, synthesize: Self-guiding diffusion models for probabilistic time series forecasting](https://dl.acm.org/doi/10.5555/3666122.3667354) [NeurIPS 2023]
- [Score-grad: Multivariate probabilistic time series forecasting with continuous energy-based generative models](https://arxiv.org/pdf/2106.10121) [Arxiv 2021]
- [Non-autoregressive conditional diffusion models for time series prediction](https://arxiv.org/pdf/2306.05043) [ICML 2023]
- [Modeling temporal data as continuous functions with stochastic process diffusion](https://arxiv.org/pdf/2211.02590) [ICML 2023]
- [Fdf: Flexible decoupled framework for time series forecasting with conditional denoising and polynomial modeling](https://arxiv.org/pdf/2410.13253) [Arxiv 2024]


## Transferring Learning Methods
- [Learning Transferable Time Series Classifier with Cross-Domain Pre-training from Language Model](https://arxiv.org/abs/2403.12372) [WSDM 2025]
- [Advancing Time Series Classification with Multimodal  Language Modeling](https://arxiv.org/pdf/2403.12371) [WSDM 2025]
- [Soft Contrastive Learning for Time Series](https://arxiv.org/pdf/2312.16424) [ICLR 2024]
- [Learning to Embed Time Series Patches Independently](https://arxiv.org/abs/2312.16427) [ICLR 2024]
- [Timer: Generative Pre-trained Transformers Are Large Time Series Models](https://arxiv.org/pdf/2402.02368) [ICML 2024]
- [TimeSiam: A Pre-Training Framework for Siamese Time-Series Modeling](https://arxiv.org/pdf/2402.02475) [ICML 2024]
- [UniST: A Prompt-Empowered Universal Model for Urban Spatio-Temporal Prediction](https://arxiv.org/abs/2402.11838) [KDD 2024]
- [SimMTM: A Simple Pre-Training Framework for Masked Time-Series Modeling](https://arxiv.org/abs/2302.00861) [NeurIPS 2023]
- [Self-Supervised Contrastive Pre-Training for Time  Series via Time-Frequency Consistency](https://arxiv.org/pdf/2206.08496) [NeurIPS 2022]
- [CoST: Contrastive Learning of Disentangled Seasonal-Trend Representations for Time Series Forecasting](https://openreview.net/pdf?id=PilZY3omXV2) [ICLR 2022]
- [Domain Adaptation for Time Series Forecasting via Attention Sharing](https://arxiv.org/pdf/2102.06828) [ICML 2022]
- [Time-Series Representation Learning via Temporal and Contextual Contrasting](https://arxiv.org/abs/2106.14112) [IJCAI 2022]
- [Transfer learning for time series classification](https://arxiv.org/abs/1811.01533) [IEEE Big Data 2018]
- [VisionTS: Visual Masked Autoencoders Are Free-Lunch Zero-Shot Time Series Forecasters](https://arxiv.org/pdf/2408.17253) [Arxiv 2024]


## Time Series Foundation Models
- [Unsupervised Representation Learning for Time Series with Temporal Neighborhood Coding](https://arxiv.org/abs/2106.00750) [ICLR 2021]
- [Time-Series Representation Learning via Temporal and Contextual Contrasting](https://arxiv.org/abs/2106.14112) [IJCAI 2021]
- [TS2Vec: Towards Universal Representation of Time Series](https://arxiv.org/abs/2106.10466) [AAA 2022]
- [Self-supervised contrastive pre-training for time series via time-frequency consistency](https://proceedings.neurips.cc/paper_files/paper/2022/file/194b8dac525581c346e30a2cebe9a369-Paper-Conference.pdf) [neurips 2022]
- [A transformer-based framework for multivariate time series representation learning](https://dl.acm.org/doi/pdf/10.1145/3447548.3467401) [SIGKDD 2021]
- [A time series is worth 64 words: Long-term forecasting with transformers](https://arxiv.org/pdf/2211.14730) [ICLR 2023]
- [Timemae: Self-supervised representations of time series with decoupled masked autoencoders](https://arxiv.org/pdf/2303.00320) [arXiv]
- [Cross-Domain Pre-training with Language Models for Transferable Time Series Representations](https://arxiv.org/abs/2403.12372) [WSDM 2025]
- [Simmtm: A simple pre-training framework for masked time-series modeling](https://proceedings.neurips.cc/paper_files/paper/2023/file/5f9bfdfe3685e4ccdbc0e7fb29cccf2a-Paper-Conference.pdf) [neurips 2023]
- [Diffusion Auto-regressive Transformer for Effective Self-supervised Time Series Forecasting](https://arxiv.org/abs/2410.05711) [arXiv]
- [Generative pretrained hierarchical transformer for time series forecasting](https://arxiv.org/pdf/2402.16516) [SIGKDD 2024]
- [Timer: Generative Pre-trained Transformers Are Large Time Series Models](https://arxiv.org/pdf/2402.02368) [PMLR 2024]


## Trustworthy Time Series Forecasting
- [SeqLink: A Robust Neural-ODE Architecture for Modelling Partially Observed Time Series](https://openreview.net/forum?id=2KMAsJ5h7B) [TMLR 2024]
- [Physics-informed neural ode for post-disaster mobility recovery](https://dl.acm.org/doi/10.1145/3637528.3672027)[KDD 2024]
- [Physics-informed neural networks for modeling physiological time series for cuffless blood pressure estimation](https://www.nature.com/articles/s41746-023-00853-4)[npj digital medicine 2023]
- [Machine learning for the physics of climate](https://www.nature.com/articles/s42254-024-00776-3)[Nature Reviews Physics 2024]
- [Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations](https://www.sciencedirect.com/science/article/pii/S0021999118307125)[Journal of Computational physics 2019]
- [Applications of physics-informed neural networks in power systems-a review](https://ieeexplore.ieee.org/document/9743327)[IEEE Transactions on Power Systems 2022]
- [Causal inference meets machine learning](https://dl.acm.org/doi/10.1145/3394486.3406460)[KDD 2020]
- [Causal effect inference with deep latent-variable models](https://proceedings.neurips.cc/paper_files/paper/2017/file/94b5bde6de888ddf9cde6748ad2523d1-Paper.pdf)[NeurIPS 2017]
- [Time-series classification using mixed-state dynamic Bayesian networks](https://ieeexplore.ieee.org/document/784983)[CVPR 1999]
- [Time-varying dynamic bayesian networks](https://papers.nips.cc/paper_files/paper/2009/hash/a67f096809415ca1c9f112d96d27689b-Abstract.html)[NeurIPS 2009]
- [Estimation and hypothesis testing of cointegration vectors in Gaussian vector autoregressive models](https://www.jstor.org/stable/2938278)

## Benchmark Evaluation
- [Deep Time Series Models: A Comprehensive Survey and Benchmark](https://openreview.net/forum?id=tL42Spa6cg)[CoRR 2024]
- [Machine Learning Based Short-Term Load Forecasting for Smart Meter Energy Consumption Data in London Households](https://ieeexplore.ieee.org/abstract/document/9501104)(IEEE 2021)
- [Sdwpf: A dataset for spatial dynamic wind power forecasting challenge at kdd cup 2022](https://arxiv.org/abs/2208.04360)(arXiv)
- [Modeling long-and short-term temporal patterns with deep neural networks](https://dl.acm.org/doi/abs/10.1145/3209978.3210006)(SIGIR 2018)
- [Informer: Beyond Efficient Transformer for Long Sequence Time-Series Forecasting](https://ojs.aaai.org/index.php/AAAI/article/view/17325)(AAAI 2021)
- [Autoformer: Decomposition transformers with auto-correlation for long-term series forecasting](https://proceedings.neurips.cc/paper/2021/hash/bcc0d400288793e8bdcd7c19a8ac0c2b-Abstract.html)[NeurIPS 2021]
- [Gluonts: Probabilistic and neural time series modeling in python](https://www.jmlr.org/papers/v21/19-820.html)[JMLR 2020]
- [Libcity: An open library for traffic prediction](https://dl.acm.org/doi/abs/10.1145/3474717.3483923)[SIGSPATIAL '21]
- [Big data and its technical challenges](https://dl.acm.org/doi/fullHtml/10.1145/2611567)[ACM 2014]
- [SubseasonalClimateUSA: a dataset for subseasonal forecasting and benchmarking](https://proceedings.neurips.cc/paper_files/paper/2023/hash/18ef499ee57c4822e1e3ea9b9948af18-Abstract-Datasets_and_Benchmarks.html)[NeurIPS 2023]
- [TFB: Towards Comprehensive and Fair Benchmarking of Time Series Forecasting Methods](https://openreview.net/forum?id=vIsYeoFG9m)[CoRR 2024]
- [Forecasting Fine-Grained Air Quality Based on Big Data](https://dl.acm.org/doi/abs/10.1145/2783258.2788573)[KDD '15]
- - [Smart*: An Open Data Set and Tools for Enabling Research in Sustainable Homes](https://none.cs.umass.edu/papers/pdf/sustkdd12-smart.pdf)(KDD 2012)
- [Unified Training of Universal Time Series Forecasting Transformers](https://ink.library.smu.edu.sg/sis_research/9906/)[(ICML 2024]
- [Chronos: Learning the Language of Time Series](https://openreview.net/forum?id=gerNCVqqtR)[TMLR 2024]
- [The Building Data Genome Project 2, energy meter data from the ASHRAE Great Energy Predictor III competition](https://www.nature.com/articles/s41597-020-00712-x)[Scientific Data]
- [Project Tycho 2.0: a repository to improve the integration and reuse of data for global population health](https://academic.oup.com/jamia/article/25/12/1608/5132125?login=false)[JAMIA 2018]

## Contact:
If you have any questions or suggestions, feel free to contact our team:

Current:
- Mingyue Cheng (mycheng@ustc.edu.cn,)
- Zhiding Liu (zhiding@mail.ustc.edu.cn,)
- Xiaoyu Tao (txytiny@mail.ustc.edu.cn,)
- Jintao Zhang (zjttt@mail.ustc.edu.cn,)
- Tingyue Pan (pty12345@mail.ustc.edu.cn,)
- Daoyu Wang (wdy030428@mail.ustc.edu.cn,)
- Shilong Zhang (zhangshilong@mail.ustc.edu.cn,)
- Panjing He (hepanjing@mail.ustc.edu.cn,)
- Xiaohan Zhang (zxh2519826485@mail.ustc.edu.cn,)
- Jiahao Wang (SA24229078@mail.ustc.edu.cn)



## All Thanks To Our Contributors

<a href="https://github.com/USTCAGI/Awesome-Papers-Time-Series-Forecasting/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=USTCAGI/Awesome-Papers-Time-Series-Forecasting" />
</a>
