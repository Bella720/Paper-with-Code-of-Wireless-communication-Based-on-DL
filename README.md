For English reader,please refer to [English Version](https://github.com/IIT-Lab/Paper-with-Code-of-Wireless-communication-Based-on-DL/blob/master/English%20version.md).

随着深度学习的发展，使用深度学习解决相关通信领域问题的研究也越来越多。作为一名通信专业的研究生，如果实验室没有相关方向的代码积累，入门并深入一个新的方向会十分艰难。同时，大部分通信领域的论文不会提供开源代码，reproducible research比较困难。
<br>
基于深度学习的通信论文这几年飞速增加，明显能感觉这些论文的作者更具开源精神。本项目专注于整理在通信中应用深度学习，并公开了相关源代码的论文。
<br>
个人关注的领域和精力有限，这个列表不会那么完整。**如果你知道一些相关的开源论文，但不在此列表中，非常欢迎添加在issue当中**，为community贡献一份力量。欢迎交流^_^
<br>
**温馨提示:watch相较于star更容易得到更新通知 。**
<br>
TODO 

- [x] 按不同小方向分类
- [x] 论文添加下载链接
- [x] 增加更多相关论文代码
  * 在[daily_arxiv](https://github.com/zhuwenxing/daily_arxiv)这个repo下会以daily为尺度更新`eess.SP`和`cs.IT`分类下开源的代码论文
  * 该Repo通过爬虫+Github Action实现每日自动更新
- [ ] 传统通信论文代码列表
- [ ] “通信+DL”论文列表（引用较高，可以没有代码）


## 目录 （Contents)

- [Topics](#topics)
  + [Machine/deep learning for physical layer optimization](#physical-layer-optimization)
  + [Resource, power and network optimization using machine learning techniques](#resource-and-network-optimization)
  + [Distributed learning algorithms over communication networks](#distributed-learning-algorithms-over-communication-networks)
  + [Multiple access scheduling  and routing using machine learning techniques](#multiple-access-scheduling--and-routing-using-machine-learning-techniques)
  + [Machine learning for network slicing, network virtualization, and software-defined networking](#machine-learning-for--software-defined-networking)
  + [Machine learning for emerging communication systems and applications (e.g., IoT, edge computing, caching, smart cities, vehicular networks, and localization)](#machine-learning-for-emerging-communication-systems-and-applications)
  + [Secure machine learning over communication networks](#secure-machine-learning-over-communication-networks)




## Topics

### Physical layer optimization

| Paper                                                        | Code                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|[Online Meta-Learning For Hybrid Model-Based Deep Receivers](https://arxiv.org/abs/2203.14359)|[meta-deepsic](https://github.com/tomerraviv95/meta-deepsic)|
|[Gan-Based Joint Activity Detection and Channel Estimation For Grant-free Random Access](https://arxiv.org/abs/2204.01731)|[jadce](https://github.com/deeeeeeplearning/jadce)|
|[sionna: an open-source library for next-generation physical layer research](https://arxiv.org/abs/2203.11854)|[sionna](https://github.com/nvlabs/sionna)|
|[Deep Learning Aided Robust Joint Channel Classification, Channel Estimation, and Signal Detection for Underwater Optical Communication](https://ieeexplore.ieee.org/document/9302692)|[UWOC-JCCESD](https://github.com/Huaiyin-Lu/UWOC-JCCESD)|
|[LoRD-Net: Unfolded Deep Detection Network with Low-Resolution Receivers](https://arxiv.org/abs/2102.02993)|[LoRD-Net](https://github.com/skhobahi/LoRD-Net)|
|[Deep Diffusion Models for Robust Channel Estimation](https://arxiv.org/abs/2111.08177)|[diffusion-channels](https://github.com/utcsilab/diffusion-channels)|
|[A Channel Coding Benchmark for Meta-Learning](https://openreview.net/forum?id=DjzPaX8AT0z)|[MetaCC](https://github.com/ruihuili/MetaCC)|
|[On the Feasibility of Modeling OFDM Communication Signals with Unsupervised Generative Adversarial Networks](https://arxiv.org/abs/2109.05107)|[OFDM-GAN](https://github.com/usnistgov/OFDM-GAN)|
|[Robust Learning-Based ML Detection for Massive MIMO Systems with One-Bit Quantized Signals](https://ieeexplore.ieee.org/document/9013332)|[LearningML](https://github.com/Yunseong-Cho/LearningML)|
|[iterative error decimation for syndrome-based neural network decoders](https://arxiv.org/abs/2012.00089)|[ied](https://github.com/kamassury/ied)|
|[ko codes: inventing nonlinear encoding and decoding for reliable wireless communication via deep-learning](https://arxiv.org/abs/2108.12920)|[kocodes](https://github.com/deepcomm/kocodes)|
|[Deep Residual Learning for Channel Estimation in Intelligent Reflecting Surface-Assisted Multi-User Communications](https://arxiv.org/abs/2009.01423)|[CDRN-channel-estimation-IRS](https://github.com/XML124/CDRN-channel-estimation-IRS)|
|[Model-Driven Deep Learning for MIMO Detection](https://ieeexplore.ieee.org/document/9018199)|[OAMP-Net](https://github.com/hehengtao/OAMP-Net)|
|[Dilated Convolution based CSI Feedback Compression for Massive MIMO Systems](https://arxiv.org/abs/2106.04043)|[DCRNet](https://github.com/recusant7/DCRNet)|
|[Unsupervised Deep Learning for Massive MIMO Hybrid Beamforming](https://arxiv.org/abs/2007.00038)|[HBF-Net](https://github.com/HamedHojatian/HBF-Net)|
|[CLNet: Complex Input Lightweight Neural Network designed for Massive MIMO CSI Feedback](https://arxiv.org/abs/2102.07507)|[CLNet](https://github.com/SIJIEJI/CLNet)|
|[Block Deep Neural Network-Based Signal Detector for Generalized Spatial Modulation](https://arxiv.org/abs/2008.03612)|[B_DNN](https://github.com/hasanabs/B_DNN)|
|[Deep Active Learning Approach to Adaptive Beamforming for mmWave Initial Alignment](https://arxiv.org/abs/2012.13607)|[DL-ActiveLearning-BeamAlignment](https://github.com/foadsohrabi/DL-ActiveLearning-BeamAlignment)|
|[Data-Driven Deep Learning to Design Pilot and Channel Estimator for Massive MIMO](https://ieeexplore.ieee.org/document/9037126)|[Source-Code-X.Ma](https://github.com/gaozhen16/Source-Code-X.Ma)|
|[Deep Learning Predictive Band Switching in Wireless Networks](https://arxiv.org/abs/1910.05305)|[Bandswitch-DeepMIMO](https://github.com/farismismar/Bandswitch-DeepMIMO)|
|[RE-MIMO: Recurrent and Permutation Equivariant Neural MIMO Detection](https://arxiv.org/abs/2007.00140)|[RE-MIMO](https://github.com/krpratik/RE-MIMO)|
|[NOLD: A Neural-Network Optimized Low-Resolution Decoder for LDPC Codes](https://github.com/Leo-Chu/NOLD/blob/master/JCN20-DIV2-067.R2.pdf)|[NOLD](https://github.com/Leo-Chu/NOLD)|
|[A MIMO detector with deep learning in the presence of correlated interference](https://ieeexplore.ieee.org/abstract/document/8990045)|[project_dcnnmld](https://github.com/skypitcher/project_dcnnmld)|
|[Deep Learning Driven Non-Orthogonal Precoding for Millimeter Wave Communications](https://ieeexplore.ieee.org/document/9082619)|[Deep-Learning-Driven-Non-Orthogonal-Precoding-for-Millimeter-Wave-Communications](https://github.com/JKLinUESTC/Deep-Learning-Driven-Non-Orthogonal-Precoding-for-Millimeter-Wave-Communications)|
|[Iterative Algorithm Induced Deep-Unfolding Neural Networks: Precoding Design for Multiuser MIMO Systems](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9246287)|[DeepUnfolding_WMMSE](https://github.com/hqyyqh888/DeepUnfolding_WMMSE)|
| [Power of Deep Learning for Channel Estimation and Signal Detection in OFDM Systems](https://arxiv.org/pdf/1708.08514.pdf)| [haoyye/OFDM_DNN](https://github.com/haoyye/OFDM_DNN)        |
| [Automatic Modulation Classification: A Deep Learning Enabled Approach](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8454504) | [mengxiaomao](https://github.com/mengxiaomao)/[CNN_AMC](https://github.com/mengxiaomao/CNN_AMC) |
| [Deep Architectures for Modulation Recognition](https://arxiv.org/pdf/1703.09197.pdf)              | [qieaaa / Deep-Architectures-for-Modulation-Recognition](https://github.com/qieaaa/Deep-Architectures-for-Modulation-Recognition) |
| [Deep-Waveform: A Learned OFDM Receiver Based on Deep Complex-Valued Convolutional Networkss](https://ieeexplore.ieee.org/document/9448141) | [zhongyuanzhao / dl_ofdm](https://github.com/zhongyuanzhao/dl_ofdm) |
| [Joint Transceiver Optimization for Wireless Communication PHY with Convolutional NeuralNetwork](https://arxiv.org/abs/1808.03242) | [hlz1992/RadioCNN](https://github.com/hlz1992/RadioCNN)      |
| [5G MIMO Data for Machine Learning: Application to Beam-Selection using Deep Learning](https://par.nsf.gov/servlets/purl/10112564)| [lasseufpa](https://github.com/lasseufpa)/[5gm-data](https://github.com/lasseufpa/5gm-data) |
|[A Two-Fold Group Lasso Based Lightweight Deep Neural Network for Automatic Modulation Classification](https://ieeexplore.ieee.org/abstract/document/9145050)|[Group-Sparse-DNN-for-AMC](https://github.com/tjuxiaofeng/Group-Sparse-DNN-for-AMC)|
|[Recursive CSI Quantization of Time-Correlated MIMO Channels by Deep Learning Classification](https://arxiv.org/abs/2009.13560)|[MultiStage-Grassmannian-DNN](https://github.com/StefanSchwarzTUW/MultiStage-Grassmannian-DNN)|
| [Deep Learning for Massive MIMO CSI Feedback](https://arxiv.org/pdf/1712.08919.pdf)                  | [sydney222 / Python_CsiNet](https://github.com/sydney222/Python_CsiNet) |
| [Beamforming Design for Large-Scale Antenna Arrays Using Deep Learning](http://arxiv.org/abs/1904.03657) | [TianLin0509/BF-design-with-DL](https://github.com/TianLin0509/BF-design-with-DL)|
| [An Introduction to Deep Learning for the Physical Layer](https://arxiv.org/pdf/1702.00832.pdf)     | [yashcao / RTN-DL-for-physical-layer](https://github.com/yashcao/RTN-DL-for-physical-layer)<br />[musicbeer / Deep-Learning-for-the-Physical-Layer](https://github.com/musicbeer/Deep-Learning-for-the-Physical-Layer)<br />[helloMRDJ / autoencoder-for-the-Physical-Layer](https://github.com/helloMRDJ/autoencoder-for-the-Physical-Layer)|
| [Deep MIMO Detection](https://arxiv.org/pdf/1706.01151.pdf)                                          | [neevsamuel](https://github.com/neevsamuel)/[DeepMIMODetection](https://github.com/neevsamuel/DeepMIMODetection) |
| [Learning to Detect](https://arxiv.org/pdf/1805.07631.pdf)                                         | [neevsamuel](https://github.com/neevsamuel)/[LearningToDetect](https://github.com/neevsamuel/LearningToDetect) |
| [An iterative BP-CNN architecture for channel decoding](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8259241)        | [liangfei-info](https://github.com/liangfei-info)/[Iterative-BP-CNN](https://github.com/liangfei-info/Iterative-BP-CNN) |
| [On Deep Learning-Based Channel Decoding](https://arxiv.org/pdf/1701.07738.pdf)| [gruberto/DL-ChannelDecoding](https://github.com/gruberto/DL-ChannelDecoding) <br/>[Decoder-using-deep-learning](https://github.com/VivekRamalingamK/Decoder-using-deep-learning)|
| [Deep learning-based channel estimation for beamspace mmWave massive MIMO systems](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8353153)| [hehengtao](https://github.com/hehengtao)/[LDAMP_based-Channel-estimation](https://github.com/hehengtao/LDAMP_based-Channel-estimation) |
| [Fast Deep Learning for Automatic Modulation Classification](https://arxiv.org/pdf/1901.05850.pdf)   | [dl4amc](https://github.com/dl4amc)/[source](https://github.com/dl4amc/source) |
| [Deep Learning-Based Channel Estimation](https://arxiv.org/pdf/1810.05893.pdf)| [Mehran-Soltani](https://github.com/Mehran-Soltani)/[ChannelNet](https://github.com/Mehran-Soltani/ChannelNet) |
|[Sparsely Connected Neural Network for Massive MIMO Detection](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8780959)|[MIMO_Detection](https://github.com/NobleLee/MIMO_Detection)|
| [Deepcode: Feedback Codes via Deep Learning](https://arxiv.org/pdf/1807.00801.pdf)                | https://github.com/hyejikim1/Deepcode<br>https://github.com/yihanjiang/feedback_code |
|[MIST: A Novel Training Strategy for Low-latency Scalable Neural Net Decoders](https://arxiv.org/pdf/1905.08990.pdf)|[MIST_CNN_Decoder](https://github.com/kryashashwi/MIST_CNN_Decoder)|
|[Deep Learning Models for Wireless Signal Classification With Distributed Low-Cost Spectrum Sensors](https://ieeexplore.ieee.org/abstract/document/8357902)|[modulation_classif](https://github.com/zeroXzero/modulation_classif)|
|[Learning Physical-Layer Communication with Quantized Feedback](https://arxiv.org/pdf/1904.09252.pdf)|[quantizedfeedback](https://github.com/henkwymeersch/quantizedfeedback)|
|[Reinforcement Learning for Channel Coding: Learned Bit-Flipping Decoding](https://arxiv.org/pdf/1906.04448.pdf)|[RLdecoding](https://github.com/fabriziocarpi/RLdecoding)|
|[Adaptive Neural Signal Detection for Massive MIMO](https://arxiv.org/abs/1906.04610)|[mehrdadkhani/MMNet](https://github.com/mehrdadkhani/MMNet)|
|[CNN-based Precoder and Combiner Design in mmWave MIMO Systems](https://ieeexplore.ieee.org/document/8710287)|[Deep_HybridBeamforming](https://github.com/meuseabe/Deep_HybridBeamforming)|
|[Sequential Convolutional Recurrent Neural Networks for Fast Automatic Modulation Classification](https://arxiv.org/pdf/1909.03050.pdf)|[coming soon](https://github.com/kython)|
|[Low-Precision Neural Network Decoding of Polar Codes](https://ieeexplore.ieee.org/abstract/document/8815542)|[low-precision-nnd](https://github.com/IgWod/low-precision-nnd)|
|[Low-rank mmWave MIMO channel estimation in one-bit receivers](https://arxiv.org/abs/1910.09141)|[Low-rank-MIMO-channel-estimation-from-one-bit-measurements](https://github.com/nitinjmyers/Low-rank-MIMO-channel-estimation-from-one-bit-measurements)|
|[Deep Learning for Massive MIMO with 1-Bit ADCs: When More Antennas Need Fewer Pilots](https://arxiv.org/abs/1910.06960)|[1-Bit-ADCs](https://github.com/YuZhang-GitHub/1-Bit-ADCs)|
|[Deep Learning for Direct Hybrid Precoding in Millimeter Wave Massive MIMO Systems](https://arxiv.org/abs/1905.13212)|[DL-hybrid-precoder](https://github.com/lxf8519/DL-hybrid-precoder)|
|[Deep Learning-Based Detector for OFDM-IM](https://ieeexplore.ieee.org/document/8684894)|[DeepIM](https://github.com/ThienVanLuong/DeepIM)|
|[Deep Learning for Channel Coding via Neural Mutual Information Estimation](https://ieeexplore.ieee.org/document/8815464)|[Wireless_encoding_with_MI_estimation](https://github.com/Fritschek/Wireless_encoding_with_MI_estimation)|
|[Learning the MMSE Channel Estimator](https://arxiv.org/pdf/1707.05674v3.pdf)|[learning-mmse-est](https://github.com/tum-msv/learning-mmse-est)|
|[Neural Network Aided SC Decoder for Polar Codes](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8780605)|[1_NND](https://github.com/BruceGaoo/1_NND)|
|[Exploiting Bi-Directional Channel Reciprocity in Deep Learning for Low Rate Massive MIMO CSI Feedback](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8638509)|[Bi-Directional-Channel-Reciprocity](https://github.com/DLinWL/Bi-Directional-Channel-Reciprocity)|
|[Performance Evaluation of Channel Decoding With Deep Neural Networks](https://arxiv.org/pdf/1711.00727.pdf)|[deep-neural-network-decoder](https://github.com/levylv/deep-neural-network-decoder)|
|[Decoder-in-the-Loop: Genetic Optimization-based LDPC Code Design](https://arxiv.org/abs/1903.03128)|[Genetic-Algorithm-based-LDPC-Code-Design](https://github.com/AhmedElkelesh/Genetic-Algorithm-based-LDPC-Code-Design)|
|[Benchmarking End-to-end Learning of MIMO Physical-Layer Communication](https://arxiv.org/abs/2005.09718)|[DeepLearning_MIMO](https://github.com/JSChalmers/DeepLearning_MIMO)|
|[Learned Conjugate Gradient Descent Network for Massive MIMO Detection](https://arxiv.org/abs/1906.03814)|[LcgNet](https://github.com/YiWei0129/LcgNet)|
|[Trainable Projected Gradient Detector for Massive Overloaded MIMO Channels: Data-driven Tuning Approach](https://arxiv.org/abs/1812.10044)|[overloaded_MIMO](https://github.com/wadayama/overloaded_MIMO)|
|[Deep Soft Interference Cancellation for MIMO Detection](https://ieeexplore.ieee.org/document/9054732)|[DeepSIC](https://github.com/nirshlezinger1/DeepSIC)|
|[Deep unfolding of the weighted MMSE algorithm](https://arxiv.org/pdf/2006.08448.pdf)|[WMMSE-deep-unfolding](https://github.com/lpkg/WMMSE-deep-unfolding)|
|[Deep Learning for Direction of Arrival Estimation via Emulation of Large Antenna Arrays](https://arxiv.org/abs/2007.13824)|[DoA with DNN via Emulation of Antenna Arrays](https://gitlab.com/miriyugl/doa-with-dnn-via-emulation-of-antenna-arrays)|
|[Acquiring Measurement Matrices via Deep Basis Persuit for Sparse Channel Estimation in mmWave Massive MIMO Systems](https://arxiv.org/abs/2007.05177)|[DeepBP-AE](https://github.com/Pengxia-Wu/DeepBP-AE)|
|[Deep Learning for SVD and Hybrid Beamforming](https://ieeexplore.ieee.org/abstract/document/9130130)|[DL_SVD_BF](https://www.dropbox.com/sh/v0gs7ba0qq5x168/AACyqRoCz5m3fhpF-azkbn3Qa?dl=0)|
|[Neural Mutual Information Estimation for Channel Coding: State-of-the-Art Estimators, Analysis, and Performance Comparison](https://arxiv.org/abs/2006.16015)|[Reverse-Jensen_MI_estimation](https://github.com/Fritschek/Reverse-Jensen_MI_estimation)|
|[Deep Transfer Learning Based Downlink Channel Prediction for FDD Massive MIMO Systems](https://arxiv.org/abs/1912.12265)|[Codes-for-Deep-Transfer-Learning-Based-Downlink-Channel-Prediction-for-FDD-Massive-MIMO-Systems](https://github.com/yangyuwenyang/Codes-for-Deep-Transfer-Learning-Based-Downlink-Channel-Prediction-for-FDD-Massive-MIMO-Systems)|
|[Channel Estimation for One-Bit Multiuser Massive MIMO Using Conditional GAN](https://arxiv.org/abs/2006.11435)|[Channel_Estimation_cGAN](https://github.com/YudiDong/Channel_Estimation_cGAN)|
|[A Model-Driven Deep Learning Method for Normalized Min-Sum LDPC Decoding](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9145237)|[A-Model-Driven-Deep-Learning-Method-for-Normalized-Min-Sum-LDPC-Decoding](https://github.com/tjuxiaofeng/A-Model-Driven-Deep-Learning-Method-for-Normalized-Min-Sum-LDPC-Decoding)|
|[Complex-Valued Convolutions for Modulation Recognition using Deep Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9145469)|[Complex_Convolutions](https://github.com/JakobKrzyston/Complex_Convolutions)|
|[Generative Adversarial Estimation of Channel Covariance in Vehicular Millimeter Wave Systems](https://arxiv.org/abs/1808.02208)|[GAN-cov-matrix](https://github.com/lxf8519/GAN-cov-matrix)|
|[Deep Learning for Beamspace Channel Estimation in Millimeter-Wave Massive MIMO Systems](https://ieeexplore.ieee.org/document/9207745)|[Simulation Codes](http://oa.ee.tsinghua.edu.cn/dailinglong/publications/publications.html)|
|[Deep Learning for Polar Codes over Flat Fading Channels](https://ieeexplore.ieee.org/document/8669025)|[polarOverFlatFading](https://github.com/ade-irawan/polarOverFlatFading)|
|[Aggregated Network for Massive MIMO CSI Feedback](https://arxiv.org/abs/2101.06618)|[ACRNet](https://github.com/Kylin9511/ACRNet)|
| [Convolutional Radio Modulation Recognition Networks](https://arxiv.org/pdf/1602.04105.pdf)          | [chrisruk](https://github.com/chrisruk)/[cnn](https://github.com/chrisruk/cnn)<br />[qieaaa / Singal-CNN](https://github.com/qieaaa/Singal-CNN) |
| [Turbo Autoencoder: Deep learning based channel code for point-to-point communication channels](https://arxiv.org/pdf/1911.03038.pdf)  | [yihanjiang](https://github.com/yihanjiang)/[turboae](https://github.com/yihanjiang/turboae) |
|[Multi-resolution CSI Feedback with deep learning in Massive MIMO System](https://arxiv.org/abs/1910.14322)|[CRNet](https://github.com/Kylin9511/CRNet)|
|[Spatio-Temporal Representation with Deep Recurrent Network in MIMO CSI Feedback](https://ieeexplore.ieee.org/document/8951228)|[ConvlstmCsiNet](https://github.com/Aries-LXY/ConvlstmCsiNet)|
|[Learn to Compress CSI and Allocate Resources in Vehicular Networks](https://arxiv.org/abs/1908.04685)|[Learn-CompressCSI-RA-V2X-Code](https://github.com/CooperLWang/Learn-CompressCSI-RA-V2X-Code)|
|[Deep Learning for TDD and FDD Massive MIMO: Mapping Channels in Space and Frequency](https://arxiv.org/pdf/1905.03761.pdf)|[DL-Massive-MIMO](https://github.com/malrabeiah/DL-Massive-MIMO)|
|[Deep UL2DL: Channel Knowledge Transfer from Uplink to Downlink](https://arxiv.org/abs/1812.07518)|[UL2DL](https://github.com/safarisadegh/UL2DL)|
|[Towards Optimally Efficient Tree Search with Deep Temporal Difference Learning](https://arxiv.org/abs/2101.02420)|[hats](https://github.com/skypitcher/hats)|
|[Enabling Large Intelligent Surfaces with Compressive Sensing and Deep Learning](https://arxiv.org/abs/1904.10136)|[LIS-DeepLearning](https://github.com/Abdelrahman-Taha/LIS-DeepLearning)|
|[A CNN-Based End-to-End Learning Framework Towards Intelligent Communication Systems](https://ieeexplore.ieee.org/document/8755977)|[Deepcom](https://github.com/ZhangKaiyao/Deepcom)|
| [Communication Algorithms via Deep Learning](https://arxiv.org/abs/1805.09317) | [yihanjiang](https://github.com/yihanjiang)/[commviadl](https://github.com/yihanjiang/Sequential-RNN-Decoder) |
|[Learning to Communicate in a Noisy Environment](https://arxiv.org/abs/1910.09630)|[echo](https://github.com/ml4wireless/echo)|
|[Meta-Learning to Communicate: Fast End-to-End Training for Fading Channels](https://arxiv.org/abs/1910.09945)|[meta-autoencoder](https://github.com/kclip/meta-autoencoder)|
|[Deep energy autoencoder for noncoherent multicarrier MU-SIMO systems](https://ieeexplore.ieee.org/document/9036067)|[energy_autoencoder](https://github.com/ThienVanLuong/energy_autoencoder)|
|[Deep Channel Learning For Large Intelligent Surfaces Aided mm-Wave Massive MIMO Systems](https://arxiv.org/abs/2001.11085)|[deepChannelLearning4RIS](https://github.com/meuseabe/deepChannelLearning4RIS)|
|[Deep learning based end-to-end wireless communication systems with conditional GAN as unknown channel](https://arxiv.org/pdf/1903.02551.pdf)|[End2End_GAN](https://github.com/haoyye/End2End_GAN)|
|[RadioUNet: Fast Radio Map Estimation with Convolutional Neural Networks](https://arxiv.org/abs/1911.09002)|[RadioUNet](https://github.com/RonLevie/RadioUNet)|
|[Deep learning aided multicarrier systems](https://ieeexplore.ieee.org/abstract/document/9271932)|[multicarrier_autoencoder](https://github.com/ThienVanLuong/multicarrier_autoencoder)|

### Resource and network optimization 
| Paper                                                        | Code                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|[Resource Allocation based on Graph Neural Networks in Vehicular Communications](https://ieeexplore.ieee.org/document/9322537)|[Globecom2020-ResourceAllocationGNN](https://github.com/Coolzyh/Globecom2020-ResourceAllocationGNN)|
|[An Unsupervised Deep Unrolling Framework for Constrained Optimization Problems in Wireless Networks](https://arxiv.org/abs/2201.08994)|[USRMNet-HWGCN](https://github.com/soulven/usrmnet-hwgcn)|
|[Power Allocation for Wireless Federated Learning using Graph Neural Networks](https://arxiv.org/abs/2111.07480)|[WirelessFL-PDGNet](https://github.com/bl166/wirelessfl-pdgnet)|
|[Delay-Oriented Distributed Scheduling Using Graph Neural Networks](https://arxiv.org/abs/2111.07017)|[gcn-dql](https://github.com/zhongyuanzhao/gcn-dql)|
|[Deep Learning Based MAC via Joint Channel Access and Rate Adaptation](https://arxiv.org/abs/2106.10307)|[Wireless-Signal-Strength-on-2.4GHz-WSS24-dataset](https://github.com/postman511/Wireless-Signal-Strength-on-2.4GHz-WSS24-dataset)|
|[wireless link scheduling via graph representation learning: a comparative study of different supervision levels](https://arxiv.org/abs/2110.01722)|[LinkSchedulingGNNs_SupervisionStudy](https://github.com/navid-naderi/LinkSchedulingGNNs_SupervisionStudy)|
|[Distributed Scheduling using Graph Neural Networks](https://arxiv.org/abs/2011.09430)|[distgcn](https://github.com/zhongyuanzhao/distgcn)|
|[DeepBeam: Deep Waveform Learning for Coordination-Free Beam Management in mmWave Networks](https://arxiv.org/abs/2012.14350)|[deepbeam](https://github.com/wineslab/deepbeam)|
|[Graph Embedding-Based Wireless Link Scheduling With Few Training Samples](https://arxiv.org/abs/1906.02871)|[graph_embedding_link_scheduling](https://github.com/mengyuan-lee/graph_embedding_link_scheduling)|
| [Energy Efficiency in Reinforcement Learning for Wireless Sensor Networks](https://arxiv.org/pdf/1812.02538.pdf)| [mkoz71 / Energy-Efficiency-in-Reinforcement-Learning](https://github.com/mkoz71/Energy-Efficiency-in-Reinforcement-Learning) |
| [Learning to optimize: Training deep neural networks for wireless resource management](https://arxiv.org/abs/1705.09412)| [Haoran-S / DNN_WMMSE](https://github.com/Haoran-S/DNN_WMMSE) |
| [Implications of Decentralized Q-learning Resource Allocation in Wireless Networks](https://arxiv.org/pdf/1705.10508.pdf) | [wn-upf / decentralized_qlearning_resource_allocation_in_wns](https://github.com/wn-upf/decentralized_qlearning_resource_allocation_in_wns) |
| [Deep Q-Learning for Self-Organizing Networks Fault Management and Radio Performance Improvement](https://arxiv.org/abs/1707.02329) | [farismismar / Deep-Q-Learning-SON-Perf-Improvement](https://github.com/farismismar/Deep-Q-Learning-SON-Perf-Improvement) |
| [Q-Learning Algorithm for VoLTE Closed-Loop Power Control in Indoor Small Cells](https://arxiv.org/pdf/1707.03269.pdf) | [farismismar / Q-Learning-Power-Control](https://github.com/farismismar/Q-Learning-Power-Control) |
| [Deep Learning for Optimal Energy-Efficient Power Control in Wireless Interference Networks](https://arxiv.org/pdf/1812.06920.pdf) | [bmatthiesen / deep-EE-opt](https://github.com/bmatthiesen/deep-EE-opt) |
| [Actor-Critic-Based Resource Allocation for Multi-modal Optical Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8644190) | [BoyuanYan / Actor-Critic-Based-Resource-Allocation-for-Multimodal-Optical-Networks](https://github.com/BoyuanYan/Actor-Critic-Based-Resource-Allocation-for-Multimodal-Optical-Networks)|
| [Transmit Power Control Using Deep Neural Network for Underlay Device-to-Device Communication](https://ieeexplore.ieee.org/document/8428396) | [seotaijiya](https://github.com/seotaijiya)/[TPC_D2D](https://github.com/seotaijiya/TPC_D2D) |
|[Power Allocation in Multi-Cell Networks Using Deep Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/8690757)|[qfnet](https://github.com/kangcp/qfnet)|
|[Deep Learning in Downlink Coordinated Multipoint in New Radio Heterogeneous Networks](https://arxiv.org/pdf/1812.03421.pdf)|[DL-CoMP-Machine-Learning](https://github.com/farismismar/DL-CoMP-Machine-Learning)|
|[Deep Reinforcement Learning for Resource Allocation in V2V Communications](https://arxiv.org/abs/1711.00968)|https://github.com/haoyye/ResourceAllocationReinforcementLearning|
| [AIF: An Artificial Intelligence Framework for Smart Wireless Network Management](http://ieeexplore.ieee.org/document/8119495/metrics) | [caogang](https://github.com/caogang)/[WlanDqn](https://github.com/caogang/WlanDqn) |
| [Deep-Learning-Power-Allocation-in-Massive-MIMO](https://arxiv.org/abs/1812.03640)              | [lucasanguinetti / Deep-Learning-Power-Allocation-in-Massive-MIMO](https://github.com/lucasanguinetti/Deep-Learning-Power-Allocation-in-Massive-MIMO) |
|[Machine Learning meets Stochastic Geometry: Determinantal Subset Selection for Wireless Networks](https://arxiv.org/abs/1905.00504)|[DPPL](https://github.com/stochastic-geometry/DPPL)|
|[Learning Based Power Control for mmWave Massive MIMO against Jamming](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8647173)|[Learning-Based-Power-Control-for-mmWave-Massive-MIMO-against-Jamming](https://github.com/xiaozhch5/Learning-Based-Power-Control-for-mmWave-Massive-MIMO-against-Jamming)|
|[Towards Optimal Power Control via Ensembling Deep Neural Networks](https://arxiv.org/abs/1807.10025)|[PCNet-ePCNet](https://github.com/ShenGroup/PCNet-ePCNet)|
|[A Graph Neural Network Approach for Scalable Wireless Power Control](https://arxiv.org/pdf/1907.08487.pdf)|[Globecom2019](https://github.com/yshenaw/Globecom2019)|
|[Mobility-Aware Centralized Reinforcement Learning for Dynamic Resource Allocation in HetNets](https://www.researchgate.net/publication/335159543_Mobility-Aware_Centralized_Reinforcement_Learning_for_Dynamic_Resource_Allocation_in_HetNets)|[UARA](https://github.com/LiuJieShane/UARA)|
|[Intelligent Resource Allocation in Wireless Communications Systems](https://ieeexplore.ieee.org/document/8961912)|[IRAWCS](https://github.com/seotaijiya/IRAWCS)|
|[Learning Combinatorial Optimization Algorithms over Graphs](https://arxiv.org/abs/1704.01665)|[graph_comb_opt](https://github.com/Hanjun-Dai/graph_comb_opt.git)|
|[Extending the RISC-V ISA for Efficient RNN-based 5G Radio Resource Management](https://arxiv.org/abs/2002.12877)|[RNNASIP](https://github.com/andrire/RNNASIP)|
|[Power Allocation in Multi-user Cellular Networks With Deep Q Learning Approach](https://arxiv.org/abs/1812.02979)|[PA_ICC](https://github.com/mengxiaomao/PA_ICC)|
|[Power Allocation in Multi-User Cellular Networks: Deep Reinforcement Learning Approaches](https://arxiv.org/abs/1901.07159)|[PA_TWC](https://github.com/mengxiaomao/PA_TWC)|
|[Unfolding WMMSE using Graph Neural Networks for Efficient Power Allocation](https://arxiv.org/abs/2009.10812)|[Unrolled-WMMSE](https://github.com/ArCho48/Unrolled-WMMSE)|
|[Deep Actor-Critic Learning for Distributed Power Control in Wireless Mobile Networks](https://arxiv.org/abs/2009.06681)|[Power-Control-asilomar](https://github.com/sinannasir/Power-Control-asilomar)|
|[Graph Neural Networks for Scalable Radio Resource Management: Architecture Design and Theoretical Analysis](https://arxiv.org/abs/2007.07632)|[GNN-Resource-Management](https://github.com/yshenaw/GNN-Resource-Management)|
|[Contrastive Self-Supervised Learning for Wireless Power Control](https://arxiv.org/abs/2010.11909)|[ContrastiveSSL_WirelessPowerControl](https://github.com/navid-naderi/ContrastiveSSL_WirelessPowerControl)|
|[No-Pain No-Gain: DRL Assisted Optimization in Energy-Constrained CR-NOMA Networks](https://github.com/zhiguo-ding/CRNOMA_DDPG/blob/main/paper.pdf)|[CRNOMA_DDPG](https://github.com/zhiguo-ding/CRNOMA_DDPG)|
|[Multicell Power Control under Rate Constraints with Deep Learning](https://arxiv.org/abs/2012.03655)|[SRnet-and-SRNet-Heu-for-power-control](https://github.com/Leeyyhh/SRnet-and-SRNet-Heu-for-power-control)|
|[Deep Learning for mmWave Beam and Blockage Prediction Using Sub-6GHz Channels](https://arxiv.org/abs/1910.02900)|[Sub6-Preds-mmWave](https://github.com/malrabeiah/Sub6-Preds-mmWave)|
|[Wireless link adaptation - a hybrid data-driven and model-based approach](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9154263)|[LinkAdaptationCSI](https://github.com/lpkg/LinkAdaptationCSI)|
|[Learning to Continuously Optimize Wireless Resource In Episodically Dynamic Environment](https://arxiv.org/abs/2011.07782)|[ICASSP2021](https://github.com/Haoran-S/ICASSP2021)|
| [DeepNap: Data-Driven Base Station Sleeping Operations through Deep Reinforcement Learning](http://network.ee.tsinghua.edu.cn/niulab/wp-content/uploads/2018/10/deepnap_CCN.pdf) | [zaxliu](https://github.com/zaxliu)/[deepnap](https://github.com/zaxliu/deepnap) | 
|[No-Pain No-Gain: DRL Assisted Optimization in Energy-Constrained CR-NOMA Networks](https://arxiv.org/pdf/2104.06007.pdf)|[CRNOMA_DDPG](https://github.com/zhiguo-ding/CRNOMA_DDPG)|

### Distributed learning algorithms over communication networks
| Paper                                                        | Code                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|[A Scalable Federated Multi-agent Architecture for Networked Connected Communication Network](https://arxiv.org/abs/2108.00506)|[Fed-MF-MAL](https://github.com/paperflight/Fed-MF-MAL)|
|[Reconfigurable Intelligent Surface Enabled Federated Learning: A Unified Communication-Learning Design Approach](https://arxiv.org/abs/2011.10282)|[RIS-FL](https://github.com/liuhang1994/RIS-FL)|
|[Decentralized Statistical Inference with Unrolled Graph Neural Networks](https://arxiv.org/abs/2104.01555)|[Learning-based-DOP-Framework](https://github.com/IrisWangHe/Learning-based-DOP-Framework)|
|[Decentralized Scheduling for Cooperative Localization with Deep Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/8701533)|[DeepRLVehicularLocalization](https://github.com/henkwymeersch/DeepRLVehicularLocalization)|
|[Deep Reinforcement Learning for Distributed Dynamic MISO Downlink-Beamforming Coordination](https://ieeexplore.ieee.org/abstract/document/9123956)|[DRL_for_DDBC](https://github.com/JungangGe/DRL_for_DDBC)|
| [Decentralized Computation Offloading for Multi-User Mobile Edge Computing: A Deep Reinforcement Learning Approach](https://arxiv.org/abs/1812.07394) | [swordest](https://github.com/swordest)/[mec_drl](https://github.com/swordest/mec_drl) |
|[Federated Learning over Wireless Networks: Convergence Analysis and Resource Allocation](https://arxiv.org/pdf/1910.13067.pdf)|[FEDL](https://github.com/nhatminh/FEDL)|
|[Federated Learning over Wireless Networks: Optimization Model Design and Analysis](https://ieeexplore.ieee.org/document/8737464)|[OnDevAI](https://github.com/nhatminh/OnDevAI)|
|[Deep Deterministic Policy Gradient (DDPG)-Based Energy Harvesting Wireless Communications](https://ieeexplore.ieee.org/document/8731635)|[Energy-Harvesting-DDPG](https://github.com/CrQiu/Energy-Harvesting-DDPG-)|
[A joint learning and communications framework for federated learning over wireless networks](https://arxiv.org/pdf/1909.07972.pdf)|[Wireless-FL](https://github.com/mzchen0/Wireless-FL)|

### Multiple access scheduling  and routing using machine learning techniques
| Paper                                                        | Code                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|[Distributive Dynamic Spectrum Access Through Deep Reinforcement Learning: A Reservoir Computing-Based Approach](https://ieeexplore.ieee.org/document/8474348)|[DQN_RC_DSA_IOT2019](https://github.com/haohsuan2918/DQN_RC_DSA_IOT2019)|
|[Deep Reinforcement Learning for Dynamic Multichannel Access in Wireless Networks](https://ieeexplore.ieee.org/document/8303773)|[DynamicMultiChannelRL](https://github.com/GulatiAditya/DynamicMultiChannelRL)|
| [Deep multi-user reinforcement learning for dynamic spectrum access in multichannel wireless networks](https://ieeexplore.ieee.org/document/8254101)| [shkrwnd](https://github.com/shkrwnd)/[Deep-Reinforcement-Learning-for-Dynamic-Spectrum-Access](https://github.com/shkrwnd/Deep-Reinforcement-Learning-for-Dynamic-Spectrum-Access) |
|[Deep Reinforcement Learning for Dynamic Multichannel Access in Wireless Networks](https://ieeexplore.ieee.org/document/8303773)|[DynamicMultiChannelRL](https://github.com/GulatiAditya/DynamicMultiChannelRL)|
|[Reinforcement Learning Based Scheduling Algorithm for Optimizing Age of Information in Ultra Reliable Low Latency Networks](https://ieeexplore.ieee.org/document/8969641)|[AoI_RL](https://github.com/aelgabli/AoI_RL)|
|[Enhancing WiFi Multiple Access Performance with Federated Deep Reinforcement Learning](https://arxiv.org/abs/2102.07019)|[FLDRL-in-Wireless-Communication](https://github.com/Mauriyin/FLDRL-in-Wireless-Communication)|
|[A Clustering Approach to Wireless Scheduling](https://ieeexplore.ieee.org/abstract/document/9154271)|[A_Clustering_Approach_to_Wireless_Scheduling](https://github.com/willtop/A_Clustering_Approach_to_Wireless_Scheduling)|
|[Deep-Reinforcement Learning Multiple Access for Heterogeneous Wireless Networks](https://ieeexplore.ieee.org/document/8665952)|[DLMA](https://github.com/YidingYu/DLMA)|
| [A deep-reinforcement learning approach for software-defined networking routing optimization](https://arxiv.org/abs/1709.07080) | [knowledgedefinednetworking / a-deep-rl-approach-for-sdn-routing-optimization](https://github.com/knowledgedefinednetworking/a-deep-rl-approach-for-sdn-routing-optimization) |
| [Spatial deep learning for wireless scheduling](https://arxiv.org/abs/1808.01486)               | [willtop](https://github.com/willtop)/[Spatial_DeepLearning_Wireless_Scheduling](https://github.com/willtop/Spatial_DeepLearning_Wireless_Scheduling) |
| [Transformer based Online Bayesian Neural Networks for Grant Free Uplink Access in CRAN with Streaming Variational Inference](https://ieeexplore.ieee.org/document/9540910)               | [CRAN_MIMO_VI](https://github.com/jhanilesh96/CRAN_MIMO_VI) |

### Machine learning for  software-defined networking
| Paper                                                        | Code                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [DELMU: A Deep Learning Approach to Maximising the Utility of Virtualised Millimetre-Wave Backhauls](https://link.springer.com/chapter/10.1007/978-3-030-19945-6_10)| [ruihuili / DELMU](https://github.com/ruihuili/DELMU)        |
|[ns-3 meets OpenAI Gym: The Playground for Machine Learning in Networking Research](https://arxiv.org/pdf/1810.03943.pdf)|[ns3-gym](https://github.com/tkn-tub/ns3-gym)|

### Machine learning for emerging communication systems and applications
| Paper                                                        | Code                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
|[Deep Reinforcement Learning with Communication Transformer for Adaptive Live Streaming in Wireless Edge Networks](https://ieeexplore.ieee.org/document/9605672)|[SACCT](https://github.com/wsyCUHK/SACCT)|
|[Dependent Task Offloading for Edge Computing based on Deep Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/9627763)|[RLTaskOffloading](https://github.com/linkpark/RLTaskOffloading)|
|[Fast Adaptive Computation Offloading in Edge Computing based on Meta Reinforcement Learning](https://arxiv.org/abs/2008.02033)|[metarl-offloading](https://github.com/linkpark/metarl-offloading)|
|[Lyapunov-guided Deep Reinforcement Learning for Stable Online Computation Offloading in Mobile-Edge Computing Networks](https://ieeexplore.ieee.org/document/9449944)|[LyDROO](https://github.com/revenol/LyDROO)|
|[Proactive and AoI-aware Failure Recovery for Stateful NFV-enabled Zero-Touch 6G Networks: Model-Free DRL Approach](https://arxiv.org/abs/2103.03817)|[ZT-PFR](https://github.com/wildsky95/ZT-PFR)|
|[Multi-UAV Path Planning for Wireless Data Harvesting with Deep Reinforcement Learning](https://arxiv.org/abs/2010.12461)|[uav_data_harvesting](https://github.com/hbayerlein/uav_data_harvesting)|
|[Spectrum sharing in vehicular networks based on multi-agent reinforcement learning](https://arxiv.org/abs/1905.02910)|[MARLspectrumSharingV2X](https://github.com/AlexVic/MARLspectrumSharingV2X)|
|[An Open-Source Framework for Adaptive Traffic Signal Control](https://arxiv.org/pdf/1909.00395.pdf)|[docwza/sumolights](https://github.com/docwza/sumolights)|
|[CSI-based Positioning in Massive MIMO systems using Convolutional Neural Networks](https://arxiv.org/abs/1911.11523)|[MaMIMO_CSI_with_CNN_positioning](https://github.com/sibrendebast/MaMIMO_CSI_with_CNN_positioning)|
|[BottleNet++: An End-to-End Approach for Feature Compression in Device-Edge Co-Inference Systems](https://ieeexplore.ieee.org/abstract/document/9145068)|[BottleNetPlusPlus](https://github.com/shaojiawei07/BottleNetPlusPlus)|
|[Deep reinforcement learning for online computation offloading in wireless powered mobile-edge computing networks](https://ieeexplore.ieee.org/abstract/document/8771176/)|[DROO](https://github.com/revenol/DROO)|
|[MaMIMO CSI-based positioning using CNNs: Peeking inside the black box](https://arxiv.org/abs/2003.04581)|[inside-the-black-box](https://github.com/sibrendebast/inside-the-black-box)|
|[Graph Neural Network for Large-Scale Network Localization](https://arxiv.org/abs/2010.11653)|[GNN-For-localization](https://github.com/Yanzongzi/GNN-For-localization)|
|[Fast Adaptive Task Offloading in Edge Computing based on Meta Reinforcement Learning](https://arxiv.org/abs/2008.02033)|[metarl-offloading](https://github.com/linkpark/metarl-offloading)|
|[RF-based Direction Finding of UAVs Using DNN](https://arxiv.org/abs/1712.01154)|https://github.com/LahiruJayasinghe/DeepDOA|
### Secure machine learning over communication networks
| Paper                                                        | Code                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Physical Adversarial Attacks Against End-to-End Autoencoder Communication Systems](https://arxiv.org/abs/1902.08391)| https://github.com/meysamsadeghi/Security-and-Robustness-of-Deep-Learning-in-Wireless-Communication-Systems |
|[Deep Learning for the Gaussian Wiretap Channel](https://ieeexplore.ieee.org/abstract/document/8761681)|[NN_GWTC](https://github.com/Fritschek/NN_GWTC)|



# "通信+DL"论文（无代码)/Paper List Without Code
说明：论文主要来源于arxiv中[Signal Processing](https://arxiv.org/list/eess.SP/recent)和[Information Theory](https://arxiv.org/list/cs.IT/recent)
* [Robust Data Detection for MIMO Systems with One-Bit ADCs: A Reinforcement Learning Approach](https://arxiv.org/pdf/1903.12546.pdf)
* [Distributed Power Control for Large Energy Harvesting Networks: A Multi-Agent Deep Reinforcement Learning Approach](https://arxiv.org/pdf/1904.00601.pdf)
* [Machine Learning for Wireless Communication Channel Modeling: An Overview](https://link.springer.com/article/10.1007/s11277-019-06275-4)
* [Sum Spectral Efficiency Maximization in Massive MIMO Systems: Benefits from Deep Learning](https://arxiv.org/pdf/1903.08163.pdf)

# 数据集/Database
* [Wireless-Signal-Strength-on-2.4GHz-WSS24-dataset](https://github.com/postman511/Wireless-Signal-Strength-on-2.4GHz-WSS24-dataset):A Dataset For RSSI Analysis
* [MetaCC](https://github.com/ruihuili/MetaCC):[A Channel Coding Benchmark for Meta-Learning](https://openreview.net/forum?id=DjzPaX8AT0z)
* [thymio-radio-map](https://github.com/arthurgassner/thymio-radio-map): [OpenCSI: An Open-Source Dataset for Indoor Localization Using CSI-Based Fingerprinting](https://arxiv.org/abs/2104.07963)
* [The DeepMIMO Dataset](http://deepmimo.net/) and  the corresponding paper [DeepMIMO: A Generic Deep Learning Dataset for Millimeter Wave and Massive MIMO Applications](https://arxiv.org/abs/1902.06435)
* [RAYMOBTIME](https://www.lasse.ufpa.br/raymobtime/):Raymobtime is a methodology for collecting realistic datasets for simulating wireless communications. It uses ray-tracing and 3D scenarios with mobility and time evolution, for obtaining consistency over time, frequency and space. 
* [MASSIVE MIMO CSI MEASUREMENTS](https://homes.esat.kuleuven.be/~sdebast/csi_measurements.html)
* [SM-CsiNet+ and PM-CsiNet+](https://drive.google.com/drive/folders/1_lAMLk_5k1Z8zJQlTr5NRnSD6ACaNRtj?usp=sharing):来自论文[Convolutional Neural Network based Multiple-Rate Compressive Sensing for Massive MIMO CSI Feedback: Design, Simulation, and Analysis](https://arxiv.org/pdf/1906.06007.pdf)
* [An open online real modulated dataset](https://pan.baidu.com/s/1biDooH6E81Toxa2u4D3p2g):来自论文[Deep Learning for Signal Demodulation in Physical Layer Wireless Communications: Prototype Platform, Open Dataset, and Analytics](https://arxiv.org/pdf/1903.04297.pdf)。
  > To the best of our knowledge,this is the first open dataset of real modulated signals
  > for wireless communication systems.
* [RF DATASETS FOR MACHINE LEARNING](https://www.deepsig.io/datasets)
* [open datase](https://pan.baidu.com/s/1rS143bEDaOTEiCneXE67dg#list/path=%2F):来自论文[Signal Demodulation With Machine Learning
Methods for Physical Layer Visible Light
Communications: Prototype Platform,
Open Dataset, and Algorithms](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8661606&tag=1)
  >The dataset is collected in real physical environment, and the channel suffers from many factors such as limited LED bandwidth, multi-reflection,spurious or continuous jamming, etc.
# 学者个人主页/Researcher Homepage
* [Dr. Zhen Gao ( 高 镇 )](https://gaozhen16.eu.org/):
  - Wireless Communications
  - Channel Estimation of mmWave/THz Hybrid Massive MIMO
  - Sparse Signal Processing
  - Deep Learning based Solutions in Wireless Systems
* [Ahmed Alkhateeb](http://www.aalkhateeb.net/index.html):Research Interests
  - Millimeter Wave and Massive MIMO Communication
  - Vehicular and Drone Communication Systems
  - Applications of Machine Learning in Wireless Communication
  - Building Mobile Communication Systems that Work in Reality!
* [Emil Björnson](https://ebjornson.com/research/):
  He performs research on multi-antenna communications, Massive MIMO, radio resource allocation, energy-efficient communications, and network design. 
* [Leo-Chu](https://github.com/Leo-Chu):His research interests are in the theoretical and algorithmic studies in random matrix theory, nonconvex optimization, deep learning, as well as their applications in wireless communications, bioengineering, and smart grid.
# 有用的网页和材料/Useful Websites and Materials
* [Graph-based Deep Learning for Communication Networks: A Survey](https://arxiv.org/abs/2106.02533): [GNN-Communication-Networks](https://github.com/jwwthu/GNN-Communication-Networks)
* [机器学习和通信结合论文列表/Research Library ](https://mlc.committees.comsoc.org/research-library/)
* [Best Readings in Machine Learning in Communications](https://www.comsoc.org/publications/best-readings/machine-learning-communications)
* [Communication Systems, Linköping University, LIU](https://www.youtube.com/channel/UCOrjRoYJPqGiR1SZvU3xcYQ/videos)
* [Codes for Intelligent reflecting surface (IRS)](https://github.com/ken0225/RIS_Codes_Collection)
* [awesome-ml4co](https://github.com/Thinklab-SJTU/awesome-ml4co):a list of papers that utilize machine learning technologies to solve combinatorial optimization problems.
* [Simulation Code from comsoc](https://mlc.committees.comsoc.org/papers-with-code/)

<br>贡献者/Contributors：
* WxZhu:
  - [Github](https://github.com/zhuwenxing)  
  - Email:wenxingzhu@shu.edu.cn
* [LinTian](https://github.com/TianLin0509)
* [HongtaiChen](https://github.com/HongtaiChen)
* [yihanjiang](https://github.com/yihanjiang)
* wu huaming:
  - Email:whming@tju.edu.cn

<br>版本更新/Version Update：

1. 第一版完成/First Version：2019-02-21
2. 分类整理及链接补全/First Version: 2021-04-14 via [Yokoxue](https://github.com/yokoxue)
