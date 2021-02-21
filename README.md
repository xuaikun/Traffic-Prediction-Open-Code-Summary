# Deep learning models for traffic prediction

This is a summary for deep learning models with open code for traffic prediction.

These models are classified based on the following tasks.

- Traffic flow prediction

- Traffic speed prediction

- On-Demand service prediction

- Travel time prediction

- Traffic accident prediction

- Traffic Location Prediction

- Others


|             Task             |         Model         |                            Paper                             | Code           | Publication                               |
| :--------------------------: | :-------------------: | :----------------------------------------------------------: | ----------------------- | ------------------------------------------------------------ |
|   Traffic flow prediction    |      ST-MetaNet       | [Urban traffic prediction from spatio-temporal data using deep meta learning](https://dl.acm.org/doi/abs/10.1145/3292500.3330884) | [MXNet](https://github.com/panzheyi/ST-MetaNet) | SIGKDD2019/A                                                 |
|                              |         CRANN         | [A Spatio-Temporal Spot-Forecasting Framework forUrban Traffic Prediction](https://arxiv.org/abs/2003.13977) | [Pytorch](https://github.com/rdemedrano/crann_traffic) | Applied Soft Computing2020/none                              |
|                              |         ACFM         | [ACFM: A Dynamic Spatial-Temporal Network for Traffic Prediction](https://dl.acm.org/doi/10.1145/3240508.3240681) | [Pytorch](https://github.com/liulingbo918/ATFM) | ACM MM2018/A                                                 |
|                              |         STDN          | [Revisiting spatial-temporal similarity: A deep learning framework for traffic prediction](https://www.aaai.org/ojs/index.php/AAAI/article/view/4511) | [Keras](https://github.com/tangxianfeng/STDN) | AAAI2019/A                                                   |
|                              |        ASTGCN         | [Attention based spatial-temporal graph convolutional networks for traffic flow forecasting](https://www.aaai.org/ojs/index.php/AAAI/article/view/3881) | [Pytorch](https://github.com/guoshnBJTU/ASTGCN-r-Pytorch) | AAAI2019/A                                                  |
|                              |        STSGCN         | [Spatial-Temporal Synchronous Graph Convolutional Networks: A New Framework for Spatial-Temporal Network Data Forecasting](https://www.aaai.org/ojs/index.php/AAAI/article/view/5438) | [MXNet](https://github.com/Davidham3/STSGCN) | AAAI2020/A                                                  |
|                              |         AGCRN         | [Adaptive Graph Convolutional Recurrent Network for Traffic Forecasting](https://arxiv.org/abs/2007.02842) | [Pytorch](https://github.com/LeiBAI/AGCRN) | NIPS2020/A                                                |
| | STAG-GCN | [Spatiotemporal Adaptive Gated Graph Convolution Network for Urban Traffic Flow Forecasting](https://dl.acm.org/doi/abs/10.1145/3340531.3411894) | [Pytorch](https://github.com/RobinLu1209/STAG-GCN) | CIKM2020/B |
| | ST-CGA | [Spatial-Temporal Convolutional Graph Attention Networks for Citywide Traffic Flow Forecasting](https://dl.acm.org/doi/abs/10.1145/3340531.3411941) | [Keras](https://github.com/jillbetty001/ST-CGA) | CIKM2020/B |
| | DSAN | [Preserving Dynamic Attention for Long-Term Spatial-Temporal Prediction](https://dl.acm.org/doi/10.1145/3394486.3403046) | [tf2](https://github.com/hxstarklin/DSAN) | SIGKDD2020/A |
|                              |     Cluster_LSTM      | [Foreseeing Congestion using LSTM on Urban Traffic Flow Clusters](https://ieeexplore.ieee.org/abstract/document/9010150/) | [Keras](https://github.com/wangz315/ClusterPredictTrafficFlow) | ICSAI2019/none                                               |
|                              |       ST-ResNet       | [Deep Spatio-Temporal Residual Networks for Citywide Crowd Flows Prediction](https://arxiv.org/abs/1610.00081) | [tf](https://github.com/snehasinghania/STResNet)，[Pytorch](https://github.com/BruceBinBoxing/ST-ResNet-Pytorch)，[Keras](https://github.com/Snow-Dancing/DeepST-ResNet) | AAAI2017/A                                                   |
|                              |         STNN          | [Spatio-Temporal Neural Networks for Space-Time Series Forecasting and Relations Discovery](https://ieeexplore.ieee.org/document/8215543) | [Pytorch](https://github.com/edouardelasalles/stnn) | ICDM2017/B                                                   |
|                              |        MATGCN         | Multi-Attention Temporal Graph Convolution Network for Traffic Flow Forecasting | [Pytorch](https://github.com/lk485/matgcn) | 本科毕设                                                     |
|                              | Deep_Sedanion_Network | [Traffic flow prediction using Deep Sedenion Networks](https://arxiv.org/abs/2012.03874) | [Pytorch](https://github.com/bojesomo/Traffic4Cast2020-DeepSedanionNetwork) | arXiv2020                                                        |
|                              |       LSTM/GRU        | [Using LSTM and GRU neural network methods for traffic flow prediction](https://ieeexplore.ieee.org/abstract/document/7804912/) | [Keras](https://github.com/xiaochus/TrafficFlowPrediction) | YAC2016/none                                                 |
|                              |          SAE          | [Traffic Flow Prediction With Big Data: A Deep Learning Approach](https://ieeexplore.ieee.org/abstract/document/6894591/) | [Keras](https://github.com/xiaochus/TrafficFlowPrediction) | TITS2015/B                                                   |
| | ResLSTM | [Deep Learning Architecture for Short-Term Passenger Flow Forecasting in Urban Rail Transit](https://ieeexplore.ieee.org/abstract/document/9136910/) | [Keras](https://github.com/JinleiZhangBJTU/ResNet-LSTM-GCN) | TITS2020/B |
| | DGCN | [Dynamic Graph Convolution Network for Traffic Forecasting Based on Latent Network of Laplace Matrix Estimation](https://ieeexplore.ieee.org/abstract/document/9190068/) | [Pytorch](https://github.com/guokan987/DGCN) | TITS2020/B |
| | ToGCN | [Topological Graph Convolutional Network-Based Urban Traffic Flow and Density Prediction](https://ieeexplore.ieee.org/abstract/document/9247476/) | [Pytorch](https://github.com/Stanislas0/ToGCN-V2X) | TITS2020/B |
| | Multi-STGCnet | [Multi-STGCnet: A Graph Convolution Based Spatial-Temporal Framework for Subway Passenger Flow Forecasting](https://ieeexplore.ieee.org/abstract/document/9207049/) | [Keras](https://github.com/start2020/Multi-STGCnet) | IJCNN2020/C |
| | GNN-flow | [Learning Mobility Flows from Urban Features with Spatial Interaction Models and Neural Networks](https://arxiv.org/abs/2004.11924) | [Pytorch](https://github.com/FelixOpolka/Mobility-Flows-Neural-Networks) | IEEE SMARTCOMP2020/none |
| | TrGNN | [Traffic Flow Prediction with Vehicle Trajectories](https://wands.sg/publications/full_list/papers/AAAI_21_1.pdf) | [Pytorch](https://github.com/mingqian000/TrGNN) | AAAI2021/A |
| | ST-GDN | [Traffic Flow Forecasting with Spatial-Temporal Graph Diffusion Network](https://www.aaai.org/AAAI21Papers/AISI-9334.ZhangX.pdf) | [tf](https://github.com/jillbetty001/ST-GDN) | AAAI2021/A |
| | STFGNN | [Spatial-Temporal Fusion Graph Neural Networks for Traffic Flow Forecasting](https://arxiv.org/abs/2012.09641) | [MXNet](https://github.com/MengzhangLI/STFGNN) | AAAI2021/A |
| | TCC-LSTM-LSM | [A temporal-aware LSTM enhanced by loss-switch mechanism for traffic flow forecasting](https://www.sciencedirect.com/science/article/abs/pii/S0925231220318130) | [Keras](https://github.com/illumina7e/TCC-LSTM-LSM) | Neurocomputing2021/C |
|   Traffic speed prediction   |         DCRNN         | [Diffusion convolutional recurrent neural network: Data-driven traffic forecasting](https://arxiv.org/abs/1707.01926) | [tf](https://github.com/liyaguang/DCRNN)，[Pytorch](https://github.com/chnsh/DCRNN_PyTorch) | ICLR2018/none                                                |
|                              |         STGCN         | [Spatio-temporal graph convolutional networks: A deep learning framework for traffic forecasting](https://www.ijcai.org/Proceedings/2018/0505) | [tf](https://github.com/VeritasYin/STGCN_IJCAI-18)，[MXNet](https://github.com/Davidham3/STGCN)，[Pytorch](https://github.com/FelixOpolka/STGCN-PyTorch)，[Keras](https://github.com/Knowledge-Precipitation-Tribe/STGCN-Keras) | IJCAI2018/A                                                  |
|                              |         T-GCN         | [T-gcn: A temporal graph convolutional network for traffic prediction](https://ieeexplore.ieee.org/abstract/document/8809901/) | [tf](https://github.com/lehaifeng/T-GCN) | TITS2020/B                                                   |
|                              |         GMAN          | [Gman: A graph multi-attention network for traffic prediction](https://www.aaai.org/ojs/index.php/AAAI/article/view/5477) | [tf](https://github.com/zhengchuanpan/GMAN) | AAAI2020/A                                                   |
| | MRA-BGCN | [Multi-Range Attentive Bicomponent Graph Convolutional Network for Traffic Forecasting](https://arxiv.org/ftp/arxiv/papers/1911/1911.12093.pdf) | [Pytorch](https://github.com/wumingyao/MAR-BGCN_GPU_pytorch) | AAAI2020/A |
|                              |       TGC-LSTM        | [Traffic graph convolutional recurrent neural network: A deep learning framework for network-scale traffic learning and forecasting](https://ieeexplore.ieee.org/abstract/document/8917706/) | [Pytorch](https://github.com/zhiyongc/Graph_Convolutional_LSTM) | TITS2020/B                                                   |
|                              |     BaiduTraffic      | [Deep sequence learning with auxiliary information for traffic prediction](https://dl.acm.org/doi/abs/10.1145/3219819.3219895) | [tf](https://github.com/JingqingZ/BaiduTraffic) | SIGKDD2018/A                                                 |
|                              |     Graph WaveNet     | [Graph wavenet for deep spatial-temporal graph modeling](https://arxiv.org/abs/1906.00121) | [Pytorch](https://github.com/nnzhan/Graph-WaveNet) | IJCAI2019/A                                                  |
|                              |         GaAN          | [GaAN: Gated Attention Networks for Learning on Large and Spatiotemporal Graphs](https://arxiv.org/abs/1803.07294) | [MXNet](https://github.com/jennyzhang0215/GaAN) | UAI2018/B                                                    |
| | MTGNN | [Connecting the Dots: Multivariate Time Series Forecasting with Graph Neural Networks](https://arxiv.org/abs/2005.11650) | [Pytorch](https://github.com/nnzhan/MTGNN) | SIGKDD2020/A |
| | Curb-GAN | [Curb-GAN: Conditional Urban Traffic Estimation through Spatio-Temporal Generative Adversarial Networks](https://dl-acm-org-s.vpn.buaa.edu.cn:8118/doi/10.1145/3394486.3403127) | [Pytorch](https://github.com/Curb-GAN/Curb-GAN) | SIGKDD2020/A |
| | AF | [Stochastic origin-destination matrix forecasting using dual-stage graph convolutional, recurrent neural networks](https://ieeexplore.ieee.org/abstract/document/9101647) | [tf](https://github.com/hujilin1229/od-pred) | ICDE2020/A |
| | TL-DCRNN | [Transfer Learning with Graph Neural Networks for Short-Term Highway Traffic Forecasting](https://arxiv.org/abs/2004.08038) | [tf](https://github.com/tanwimallick/TL-DCRNN) | ICPR2020/C |
| | ST-MGAT | [ST-MGAT: Spatial-Temporal Multi-Head Graph Attention Networks for Traffic Forecasting](https://ieeexplore.ieee.org/abstract/document/9288309) | [Pytorch](https://github.com/Kelang-Tian/ST-MGAT) | ICTAI2020/C |
| | DGFN | [Dynamic Graph Filters Networks: A Gray-box Model for Multistep Traffic Forecasting](https://ieeexplore.ieee.org/abstract/document/9294627/) | [tf2](https://github.com/RomainLITUD/DGCN_traffic_forecasting) | ITSC2020/none |
| | DKFN | [Graph Convolutional Networks with Kalman Filtering for Traffic Prediction](https://people.cs.vt.edu/~ctlu/Publication/2020/GIS-2020-Chen.pdf) | [Pytorch](https://github.com/Fanglanc/DKFN) | Advances in Geographic Information Systems2020/none |
| | FC-GAGA | [FC-GAGA: Fully Connected Gated Graph Architecture for Spatio-Temporal Traffic Forecasting](https://arxiv.org/abs/2007.15531) | [tf](https://github.com/boreshkinai/fc-gaga) | AAAI2021/A |
| | HGCN | [Hierarchical Graph Convolution Networks for Traffic Forecasting](https://github.com/guokan987/HGCN/blob/main/paper/3399.GuoK.pdf) | [Pytorch](https://github.com/guokan987/HGCN) | AAAI2021/A |
| On-Demand service prediction |        STG2Seq        | [Stg2seq: Spatial-temporal graph to sequence model for multi-step passenger demand forecasting](https://arxiv.org/abs/1905.10069) | [tf](https://github.com/LeiBAI/STG2Seq) | IJCAL2019/A                                                  |
|                              |       DMVST-Net       | [Deep Multi-View Spatial-Temporal Network for Taxi Demand Prediction](https://arxiv.org/abs/1802.08714) | [Keras](https://github.com/huaxiuyao/DMVST-Net) | AAAI2018/A                                                   |
| | GraphLSTM | [Grids versus graphs: Partitioning space for improved taxi demand-supply forecasts](https://ieeexplore.ieee.org/abstract/document/9099450/) | [Pytorch](https://github.com/NDavisK/Grids-versus-Graphs) | TITS2020/B |
|                              |         DPFE          | [Estimating multi-year 24/7 origin-destination demand using high-granular multi-source traffic data](https://www.sciencedirect.com/science/article/abs/pii/S0968090X18302948) | [Pytorch](https://github.com/Lemma1/DPFE) | Transportation Research Part C: Emerging Technologies2018/none |
| | CCRNN | [Coupled Layer-wise Graph Convolution for Transportation Demand Prediction](https://arxiv.org/abs/2012.08080) | [Pytorch](https://github.com/Essaim/CGCDemandPrediction) | AAAI2021/A |
| | ST-ED-RMGC | [Predicting origin-destination ride-sourcing demand with a spatio-temporal encoder-decoder residual multi-graph convolutional network](https://www.sciencedirect.com/science/article/pii/S0968090X20307580) | [Keras](https://github.com/kejintao/ST-ED-RMGC) | Transportation Research Part C: Emerging Technologies2021/none |
|    Travel time prediction    |        DeepTTE        | [When will you arrive? estimating travel time based on deep neural networks](https://zhangjunbo.org/pdf/2018_AAAI_DeepTTE.pdf) | [Pytorch](https://github.com/UrbComp/DeepTTE) | AAAI2018/A                                                   |
|                              |        HetETA         | [HetETA: Heterogeneous Information Network Embedding for Estimating Time of Arrival](https://dl.acm.org/doi/abs/10.1145/3394486.3403294) | [tf](https://github.com/didi/heteta) | SIGKDD2020/A                                                 |
| | TTPNet | [TTPNet: A Neural Network for Travel Time Prediction Based on Tensor Decomposition and Graph Embedding]() | [TTPNet](https://github.com/YibinShen/TTPNet) | TKDE2020/A |
| Traffic accident prediction  |      RiskOracle       | [RiskOracle: A Minute-Level Citywide Traffic Accident Forecasting Framework](https://www.aaai.org/ojs/index.php/AAAI/article/view/5480) | [tf](https://github.com/zzyy0929/AAAI2020-RiskOracle) | AAAI2020/A                                                   |
|                              |        RiskSeq        | [Foresee Urban Sparse Traffic Accidents: A Spatiotemporal Multi-Granularity Perspective](https://ieeexplore.ieee.org/abstract/document/9242313/) | [tf](https://github.com/zzyy0929/Codes-for-RiskSeq-TKDE) | TKDE2020/A                                                   |
| | DSTGCN | [Deep Spatio-Temporal Graph Convolutional Network for Traffic Accident Prediction](https://www.sciencedirect.com/science/article/pii/S092523122031451X) | [Pytorch](https://github.com/yule-BUAA/DSTGCN) | Neurocomputing2020/C |
| | GSNet | [GSNet: Learning Spatial-Temporal Correlations from Geographical and Semantic Aspects for Traffic Accident Risk Forecasting](http://faculty.bjtu.edu.cn/media/rte/file/2021/2/1/1612146070.pdf) | [Pytorch](https://github.com/Echohhhhhh/GSNet) | AAAI2021/A |
| Traffic Location Prediction  |       DeepMove        | [DeepMove: Predicting Human Mobility with Attentional Recurrent Networks](https://dl.acm.org/doi/10.1145/3178876.3186058) | [Pytorch](https://github.com/vonfeng/DeepMove) | WWW2018/A                                                    |
|                              |         STRNN         | [Predicting the Next Location: A Recurrent Model with Spatial and Temporal Contexts](https://pdfs.semanticscholar.org/5bdf/0970034d0bb8a218c06ba3f2ddf97d29103d.pdf) | [Pytorch](https://github.com/yongqyu/STRNN) | AAAI2016/A                                                   |
|                              |        MALMCS         | [Dynamic Public Resource Allocation based on Human Mobility Prediction](https://dl.acm.org/doi/abs/10.1145/3380986) | [python](https://github.com/sjruan/malmcs) | UbiComp2020/A                                                |
|                              |         SERM          | [SERM: A Recurrent Model for Next Location Prediction in Semantic Trajectories](https://dl.acm.org/doi/abs/10.1145/3132847.3133056) | [Keras](https://github.com/yaodi833/serm) | CIKM2017/B                                                   |
|                              |       HST-LSTM        | [HST-LSTM: A Hierarchical Spatial-Temporal Long-Short Term Memory Network for Location Prediction](https://pdfs.semanticscholar.org/a1bf/ad98d6192b3fad42054b07ff8a5acc2a97c9.pdf) | [Pytorch](https://github.com/Logan-Lin/ST-LSTM_PyTorch) | IJCAI2018/A                                                  |
|                              |        VANext         | [Predciting Human Mobility via Variational Attention](https://dl.acm.org/doi/abs/10.1145/3308558.3313610) | [tf](https://github.com/gcooq/VANext) | WWW2019/A                                                    |
|                              |          FQA          | [Multi-agent Trajectory Prediction with Fuzzy Query Attention](https://arxiv.org/abs/2010.15891) | [Pytorch](https://github.com/nitinkamra1992/FQA) | NeurIPS2020/A                                                |
|            Others            |                       | [On the Inclusion of Spatial Information for Spatio-Temporal Neural Networks](https://arxiv.org/abs/2007.07559) | [Pytorch](https://github.com/rdemedrano/SANN) | arXiv2020                                                    |
|                              |        seq2seq        | [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks) | [Keras](https://github.com/farizrahman4u/seq2seq) | NeurIPS2014/A                                                |
| |  | [Learning Effective Road Network Representation with Hierarchical Graph Neural Networks](https://dl.acm.org/doi/abs/10.1145/3394486.3403043) | [Pytorch](https://gitee.com/solaris_wn/HRNR) | SIGKDD2020/A |
| | SHARE | [Semi-Supervised Hierarchical Recurrent Graph Neural Network for City-Wide Parking Availability Prediction](https://ojs.aaai.org/index.php/AAAI/article/download/5471/5327) | [Pytorch](https://github.com/Vvrep/SHARE-parking_availability_prediction-Pytorch) | AAAI2020 |
| | PVCGN | [Physical-Virtual Collaboration Modeling for Intra-and Inter-Station Metro Ridership Prediction](https://arxiv.org/abs/2001.04889) | [Pytorch](https://github.com/ivechan/PVCGN) | TITS2020/B |

