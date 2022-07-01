# Awesome-Skeleton-Based-Models <!-- omit in toc --> [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

We collect existing **(3D) skeleton-based models** of *all categaories* published in prominent conferences (*CVPR, ICCV, ECCV, AAAI, IJCAI, ACMMM, ICLR, ICML, NeurIPS, etc*) and journals (*TPAMI, TIP, TMM, TNNLS, PMLR, Pattern Recognition, etc*).

If you have any problems, suggestions or improvements, please feel free to contact me (haocong001@ntu.edu.sg). Welcome to discuss together.

## TODO <!-- omit in toc -->

- [ ] Paper List
  - [x] Skeleton-Based Action Recognition
  - [x] 3D Pose Estimation
  - [x] Skeleton-Based Person Re-Identification *(New!)*
  - [ ] Gesture Recognition
  - [ ] Gait Recognition
  - [ ] Others (Motion Prediction, Interaction Recognition, etc)

## Contents <!-- omit in toc -->

- [Skeleton Tracking](#skeleton-tracking)
  - [Microsoft Kinect](#microsoft-kinect)
  - [Other Tracking Devices](#other-tracking-devices)
- [Skeleton-Based Action Recognition](#skeleton-based-action-recognition)
  - [Popular Datasets with Skeletons](#popular-datasets-with-skeletons)
  - [Action Recognition Survey](#action-recognition-survey)
  - [2022 (Action Recognition)](#2022-action-recognition)
  - [2021 (Action Recognition)](#2021-action-recognition)
  - [2020 (Action Recognition)](#2020-action-recognition)
  - [2019 (Action Recognition)](#2019-action-recognition)
  - [2018 (Action Recognition)](#2018-action-recognition)
  - [2017 (Action Recognition)](#2017-action-recognition)
  - [Before 2017 (Action Recognition)](#before-2017-action-recognition)
  - [arXiv papers (Action Recognition)](#arxiv-papers-action-recognition)
  - [Skeleton-based Action Recognition under Adversarial Attack](#skeleton-based-action-recognition-under-adversarial-attack)
  - [Leaderboards on NTU-RGB+D and NTU-RGB+D 120 Datasets](#leaderboards-on-ntu-rgbd-and-ntu-rgbd-120-datasets)
    - [NTU-RGB+D](#ntu-rgbd)
    - [NTU-RGB+D 120](#ntu-rgbd-120)
- [3D Pose Estimation](#3d-pose-estimation)
  - [Datasets](#datasets)
  - [2022 (3D Pose Estimation)](#2022-3d-pose-estimation)
  - [2021 (3D Pose Estimation)](#2021-3d-pose-estimation)
  - [2020 (3D Pose Estimation)](#2020-3d-pose-estimation)
  - [2019 (3D Pose Estimation)](#2019-3d-pose-estimation)
  - [2018 (3D Pose Estimation)](#2018-3d-pose-estimation)
  - [2017 (3D Pose Estimation)](#2017-3d-pose-estimation)
  - [Before 2017 (3D Pose Estimation)](#before-2017-3d-pose-estimation)
  - [Real-Time 3D Pose Estimation](#real-time-3d-pose-estimation)
  - [Leaderboards (3D Pose Estimation)](#leaderboards-3d-pose-estimation)
- [Skeleton-Based Person Re-Identification (S-reID)](#skeleton-based-person-re-identification-s-reid)
  - [Popular Datasets](#popular-datasets)
  - [2022 (S-reID)](#2022-s-reid)
  - [2021 (S-reID)](#2021-s-reid)
  - [2020 (S-reID)](#2020-s-reid)
  - [2019 (S-reID)](#2019-s-reid)
  - [2018 (S-reIDn)](#2018-s-reidn)
  - [2017 (S-reID)](#2017-s-reid)
  - [Before 2017 (S-reID)](#before-2017-s-reid)
  - [Leaderboards on](#leaderboards-on)
- [Acknowledge](#acknowledge)





## Skeleton Tracking

### Microsoft Kinect
- Microsoft Kinect sensor and its effect (**IEEE Multimedia 2012**) [[paper](https://ieeexplore.ieee.org/document/6190806)]
- Real-time human pose recognition in parts from single depth images (**CVPR 2011**) [[paper](https://doi.org/10.1109/CVPR.2011.5995316)]
- Enhanced Computer Vision With Microsoft Kinect Sensor: A Review (**IEEE Trans. Cybern. 2013**) [[paper](https://ieeexplore.ieee.org/abstract/document/6547194)]

### Other Tracking Devices
- [Intel RealSense](https://www.intelrealsense.com/skeletal-tracking/)
- [Astra Pro](https://pterneas.com/2018/04/30/orbbec-astra-nuitrack/)

## Skeleton-Based Action Recognition
### Popular Datasets with Skeletons
- *(New! 2021)* **PoseC3D 2D Skeleton Dataset (FineGYM, NTURGB-D, Kinetics, Volleyball)** [[arxiv](https://arxiv.org/pdf/2104.13586.pdf), [Github](https://github.com/open-mmlab/mmaction2/tree/master/tools/data/skeleton)] ![](https://img.shields.io/github/stars/open-mmlab/mmaction2.svg?style=social)
- *(New! 2021)* **NTU60-X Dataset** [[arxiv](https://arxiv.org/pdf/2101.11529.pdf), [Github](https://github.com/skelemoa/ntu-x)] ![](https://img.shields.io/github/stars/skelemoa/ntu-x.svg?style=social)
- *(2019)* **NTU RGB+D 120 Dataset** [[Homepage](http://rose1.ntu.edu.sg/datasets/actionrecognition.asp),[Github](https://github.com/shahroudy/NTURGB-D)] ![](https://img.shields.io/github/stars/shahroudy/NTURGB-D.svg?style=social)
- NTU RGB+D Dataset [[Homepage](http://rose1.ntu.edu.sg/datasets/actionrecognition.asp),[Github](https://github.com/shahroudy/NTURGB-D)] ![](https://img.shields.io/github/stars/shahroudy/NTURGB-D.svg?style=social)
- (2018) VARYING-VIEW RGB-D ACTION DATASET [[arxiv](https://arxiv.org/pdf/1904.10681.pdf), [Github](https://github.com/HRI-UESTC/CFM-HRI-RGB-D-action-database)] ![](https://img.shields.io/github/stars/HRI-UESTC/CFM-HRI-RGB-D-action-database.svg?style=social)
- (2017) SYSU 3D Human-Object Interaction Dataset (**SYSU**)
- (2015) UWA3D Multiview Activity II Dataset (**UWA3D**) [[download](http://staffhome.ecm.uwa.edu.au/~00053650/databases.html)]
- (2014) Northwestern-UCLA Dataset (**N-UCLA**) [[donwload](https://users.eecs.northwestern.edu/~jwa368/my_data.html)]
<!-- - SBU Kinect Interaction Dataset (**SBU**) -->

Overview of available datasets (2004-2022) for **action recognition** and their statistics, provided by the paper of (**TPAMI 2022**) [[arxiv](https://arxiv.org/abs/2012.11866)] (Human Action Recognition from Various Data Modalities: A Review). 

```
S: Skeleton, D: Depth, IR: Infrared, PC: Point Cloud, ES: Event Stream, Au: Audio, Ac: Acceleration, Gyr: Gyroscope, EMG: Electromyography. Bold shows the most-frequently used datasets in the literature.
```

<!-- ![datasets](./AR-datasets.jpg) -->

| **# Id** | **Dataset**            | **Year** |       **Modality** | **# Class** | **# Subject** | **# Sample** |         **# View** |
|:--------:|------------------------|---------:|-------------------:|------------:|--------------:|-------------:|-------------------:|
|     1    | [KTH](https://www.csc.kth.se/cvap/actions/)                  |     2004 |                RGB |           6 |            25 |        2,391 |                  1 |
|     2    | Weizmann               |     2005 |                RGB |          10 |             9 |           90 |                  1 |
|     3    | IXMAS                  |     2006 |                RGB |          11 |            10 |          330 |                  5 |
|     4    | [HDM05](http://resources.mpi-inf.mpg.de/HDM05/)                  |     2007 |              RGB,S |         130 |             5 |        2,337 |                  1 |
|     5    | [Hollywood](http://cvssp.org/Hollywood3D/)              |     2008 |                RGB |           8 |             — |          430 |                  — |
|     6    | Hollywood2             |     2009 |                RGB |          12 |             — |        3,669 |                  — |
|   **7**  | [**MSR-Action3D**](https://sites.google.com/view/wanqingli/data-sets/msr-action3d)      | **2010** |            **S,D** |      **20** |        **10** |      **567** |              **1** |
|     8    | Olympic                |     2010 |                RGB |          16 |             — |          783 |                  — |
|   **9**  | [**CAD-60**](http://pr.cs.cornell.edu/humanactivities/)            | **2011** |        **RGB,S,D** |      **12** |         **4** |       **60** |              **—** |
|    10    | [HMDB51](https://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database)                 |     2011 |                RGB |          51 |             — |        6,766 |                  — |
|  **11**  | [**RGB-HuDaAct**](http://www.ifp.illinois.edu/~moulin/Papers/RGBD-HuDaAct.pdf)        | **2011** |          **RGB,D** |      **13** |        **30** |    **1,189** |              **1** |
|  **12**  | [**ACT4^{2}**](https://sites.google.com/site/qinleisite/Home/dataset)         | **2012** |          **RGB,D** |      **14** |        **24** |    **6,844** |              **4** |
|    13    | DHA                    |     2012 |              RGB,D |          17 |            21 |          357 |                  1 |
|  **14**  | [**MSRDailyActivity3D**](http://research.microsoft.com/%E2%88%BCzliu/ActionRecoRsrc) | **2012** |        **RGB,S,D** |      **16** |        **10** |      **320** |              **1** |
|    15    | UCF101                 |     2012 |                RGB |         101 |             — |       13,320 |                  — |
|  **16**  | [**UTKinect**](https://cvrc.ece.utexas.edu/KinectDatasets/HOJ3D.html)           | **2012** |        **RGB,S,D** |      **10** |        **10** |      **200** |              **1** |
|    17    | [Berkeley MHAD](https://tele-immersion.citris-uc.org/)          |     2013 |      RGB,S,D,Au,Ac |          12 |            12 |          660 |                  4 |
|  **18**  | [**CAD-120**](https://www.re3data.org/repository/r3d100012216)            | **2013** |        **RGB,S,D** |      **10** |         **4** |      **120** |              **—** |
|    19    | IAS-lab                |     2013 |         RGB,S,D,PC |          15 |            12 |          540 |                  1 |
|    20    | J-HMDB                 |     2013 |              RGB,S |          21 |             — |       31,838 |                  — |
|  **21**  | [**MSRAction-Pair**](http://www.cs.ucf.edu/~oreifej/HON4D.html)     | **2013** |        **RGB,S,D** |      **12** |        **10** |      **360** |              **1** |
|    22    | UCFKinect              |     2013 |                  S |          16 |            16 |        1,280 |                  1 |
|    23    | Multi-View TJU         |     2014 |            RGB,S,D |          20 |            22 |        7,040 |                  2 |
|  **24**  | [**Northwestern-UCLA**](http://wangjiangb.github.io/my_data.html)  | **2014** |        **RGB,S,D** |      **10** |        **10** |    **1,475** |              **3** |
|    25    | [Sports-1M](https://cs.stanford.edu/people/karpathy/deepvideo/)              |     2014 |                RGB |         487 |             — |  $1,113,158$ |                  — |
|    26    | UPCV                   |     2014 |                  S |          10 |            20 |          400 |                  1 |
|  **27**  | [**UWA3D Multiview**](http://staffhome.ecm.uwa.edu.au/~00053650/databases.html)    | **2014** |        **RGB,S,D** |      **30** |        **10** |     **~900** |              **4** |
|    28    | [ActivityNet](http://activity-net.org/)            |     2015 |                RGB |         203 |             — |       27,801 |                  — |
|    **29**    | [**SYSU 3D HOI**](http://isee.sysu.edu.cn/resource)            |     **2015** |            **RGB,S,D** |          **12** |            **40** |          **480** |                  **1** |
|    30    | [THUMOS Challenge 15](http://www.thumos.info/)    |     2015 |                RGB |         101 |             — |       24,017 |                  — |
|    31    | TJU                    |     2015 |            RGB,S,D |          15 |            20 |        1,200 |                  1 |
|  **32**  | [**UTD-MHAD**](https://www.utdallas.edu/~kehtar/UTD-MHAD.html)           | **2015** | **RGB,S,D,Ac,Gyr** |      **27** |         **8** |      **861** |              **1** |
|  **33**  | [**UWA3D Multiview II**](http://staffhome.ecm.uwa.edu.au/~00053650/databases.html) | **2015** |        **RGB,S,D** |      **30** |        **10** |    **1,075** |              **4** |
|  **34**  | [**M^{2}I**](https://pubmed.ncbi.nlm.nih.gov/27429453/)           | **2015** |        **RGB,S,D** |      **22** |        **22** |    **~1800** |              **2** |
|    35    | [Charades](http://vuchallenge.org/charades.html)               |     2016 |                RGB |         157 |           267 |        9,848 |                  — |
|    36    | InfAR                  |     2016 |                 IR |          12 |            40 |          600 |                  2 |
|  **37**  | [**NTU RGB+D**](http://rose1.ntu.edu.sg/datasets/actionrecognition.asp)          | **2016** |     **RGB,S,D,IR** |      **60** |        **40** |   **56,880** |             **80** |
|    38    | [YouTube-8M](https://research.google.com/youtube8m/)             |     2016 |                RGB |       4,800 |             — |    8,264,650 |                  — |
|    39    | [AVA](http://research.google.com/ava/)                    |     2017 |                RGB |          80 |             — |          437 |                  — |
|    40    | DvsGesture             |     2017 |                 ES |          17 |            29 |            — |                  — |
|    41    | FCVID                  |     2017 |                RGB |         239 |             — |       91,233 |                  — |
|    42    | [Kinetics-400](https://deepmind.com/research/open-source/kinetics)           |     2017 |                RGB |         400 |             — |      306,245 |                  — |
|    43    | NEU-UB                 |     2017 |              RGB,D |           6 |            20 |          600 |                  — |
|    44    | [PKU-MMD](https://www.icst.pku.edu.cn/struct/Projects/PKUMMD.html)                |     2017 |         RGB,S,D,IR |          51 |            66 |        1,076 |                  3 |
|    45    | [Something-Something-v1](https://20bn.com/datasets/something-something/v1) |     2017 |                RGB |         174 |             — |      108,499 |                  — |
|    46    | [UniMiB SHAR](http://www.sal.disco.unimib.it/technologies/unimib-shar/)            |     2017 |                 Ac |          17 |            30 |       11,771 |                  — |
|    47    | [EPIC-KITCHENS-55](https://epic-kitchens.github.io/2019)       |     2018 |             RGB,Au |           — |            32 |       39,594 |         Egocentric |
|    48    | [Kinetics-600](https://paperswithcode.com/dataset/kinetics-600)           |     2018 |                RGB |         600 |             — |      495,547 |                  — |
|    49    | [RGB-D Varying-view](https://github.com/HRI-UESTC/CFM-HRI-RGB-D-action-database)     |     2018 |            RGB,S,D |          40 |           118 |       25,600 | 8+1(360$^{\circ}$) |
|    50    | [DHP19](https://sites.google.com/view/dhp19/home)                  |     2019 |               ES,S |          33 |            17 |            — |                  4 |
|    51    | [Drive&Act](https://www.driveandact.com/)              |     2019 |         RGB,S,D,IR |          83 |            15 |            — |                  6 |
|    52    | Hemangomez *et al.*      |     2019 |              Radar |           8 |            11 |        1,056 |                  — |
|    53    | [Kinetics-700](https://deepmind.com/research/open-source/kinetics)           |     2019 |                RGB |         700 |             — |      650,317 |                  — |
|    54    | Kitchen20              |     2019 |                 Au |          20 |             — |          800 |                  — |
|    55    | [MMAct](https://mmact19.github.io/2019/)                  |     2019 |  RGB,S,Ac,Gyr,etc. |          37 |            20 |       36,764 |       4+Egocentric |
|    56    | [Moments in Time](http://moments.csail.mit.edu/)        |     2019 |                RGB |         339 |             — |   ~1,000,000 |                  — |
|    57    | Wang *et al.*            |     2019 |           WiFi CSI |           6 |             1 |        1,394 |                  — |
|  **58**  | [**NTU RGB+D 120**](http://rose1.ntu.edu.sg/Datasets/actionRecognition.asp)      | **2019** |     **RGB,S,D,IR** |     **120** |       **106** |  **114,480** |            **155** |
|    59    | ETRI-Activity3D        |     2020 |            RGB,S,D |          55 |           100 |      112,620 |                  — |
|    60    | EV-Action              |     2020 |        RGB,S,D,EMG |          20 |            70 |        7,000 |                  9 |
|    61    | [IKEA ASM](https://ikeaasm.github.io/)               |     2020 |            RGB,S,D |          33 |            48 |       16,764 |                  3 |
|    62    | [RareAct](https://github.com/antoine77340/RareAct)                |     2020 |                RGB |         122 |             — |          905 |                  — |
|    63    | [BABEL](https://babel.is.tue.mpg.de/)                  |     2021 |              Mocap |         252 |             — |       13,220 |                  — |
|    64    | [HAA500](https://www.cse.ust.hk/haa/)                 |     2021 |                RGB |         500 |             — |       10,000 |                  — |
|    65    | HOMAGE                 |     2021 | RGB,IR,Ac,Gyr,etc. |          75 |            27 |        1,752 |                2~5 |
|    66    | [MultiSports](https://deeperaction.github.io/datasets/multisports.html)            |     2021 |                RGB |          66 |             — |       37,701 |                  — |
|    67    | [UAV-Human](https://github.com/SUTDCV/UAV-Human)              |     2021 |    RGB,S,D,IR,etc. |         155 |           119 |       67,428 |                  — |
|    68    | [Ego4D](https://ego4d-data.org/)                  |     2022 |     RGB,Au,Ac,etc. |           — |           923 |            — |         Egocentric |
|    69    | [EPIC-KICHENS-100](https://epic-kitchens.github.io/2021)       |     2022 |          RGB,Au,Ac |           — |            45 |       89,979 |         Egocentric |
|    70    | [JRDB-Act](https://jrdb.stanford.edu/)               |     2022 |             RGB,PC |          26 |             — |        3,625 |      360$^{\circ}$ |



### Action Recognition Survey
- Human Action Recognition and Prediction: A Survey Recognition Algorithms (**IJCV 2022**) [[paper](https://doi.org/10.1007/s11263-022-01594-9)]

- Human Action Recognition from Various Data Modalities: A Review (**TPAMI 2022**) [[arxiv](https://arxiv.org/abs/2012.11866)]

- A Comparative Review of Recent Kinect-based Action Recognition Algorithms (**TIP 2019**) [[arxiv](https://arxiv.org/pdf/1906.09955.pdf)]


### 2022 (Action Recognition)
- Constructing Stronger and Faster Baselines for Skeleton-based Action Recognition (**TPAMI 2022**) [[paper](https://arxiv.org/pdf/2106.15125.pdf)] [[Github](https://github.com/yfsong0709/EfficientGCNv1)] ![](https://img.shields.io/github/stars/yfsong0709/EfficientGCNv1.svg?style=social) (Not uploaded) [[Gitee](https://gitee.com/yfsong0709/EfficientGCNv1)]

- **[Sym-GNN]** Symbiotic Graph Neural Networks for 3D Skeleton-Based Human Action Recognition and Motion Prediction (**TPAMI 2022**) [[paper](https://ieeexplore.ieee.org/document/9334430)] [[Github](https://github.com/LevelCA/Sym-GNN)] ![](https://img.shields.io/github/stars/LevelCA/Sym-GNN.svg?style=social) (Not uploaded)

- **[X-CAR]** X-Invariant Contrastive Augmentation and Representation Learning for Semi-Supervised Skeleton-Based Action Recognition(**TIP 2022**) [[paper](https://doi.org/10.1109/TIP.2022.3175605)]

- **[FGCN]** Feedback Graph Convolutional Network for Skeleton-Based Action Recognition
(**TIP 2022**) [[paper](https://doi.org/10.1109/TIP.2021.3129117)]

- **[Multi-LiSAAL]** Multi-Localized Sensitive Autoencoder-Attention-LSTM For Skeleton-based Action Recognition(**TMM 2022**) [[paper](https://doi.org/10.1109/TMM.2021.3070127)]

- **[LAGA-Net]** LAGA-Net: Local-and-Global Attention Network for Skeleton Based Action Recognition
(**TMM 2022**) [[paper](https://doi.org/10.1109/TMM.2021.3070127)]

- **[CIASA]** Adversarial Attack on Skeleton-Based Human Action Recognition
(**TNNLS 2022**) [[paper](https://doi.org/10.1109/TNNLS.2020.3043002)]

- **[MTT]** MTT: Multi-Scale Temporal Transformer for Skeleton-Based Action Recognition(**IEEE Signal Process. Lett. 2022**) [[paper](https://doi.org/10.1109/LSP.2022.3142675)]

- **[Graph2Net]** Graph2Net: Perceptually-Enriched Graph Learning for Skeleton-Based Action Recognition(**IEEE Trans. Circuits Syst. Video Technol. 2022**) [[paper](https://doi.org/10.1109/TCSVT.2021.3085959)] [[Github](https://github.com/cong-wu/Graph2Net)] ![](https://img.shields.io/github/stars/cong-wu/Graph2Net.svg?style=social)


- A Cross View Learning Approach for Skeleton-Based Action Recognition(**IEEE Trans. Circuits Syst. Video Technol. 2022**) [[paper](https://doi.org/10.1109/TCSVT.2021.3100128)]

- Learning from Temporal Spatial Cubism for Cross-Dataset Skeleton-based Action Recognition(**ACM Trans. Multim. Comput. Commun. Appl. 2022**) [[paper](https://doi.org/10.1145/3472722)] [[Github](https://github.com/shanice-l/st-cubism)] ![](https://img.shields.io/github/stars/shanice-l/st-cubism.svg?style=social)

- Skeleton Sequence and RGB Frame Based Multi-Modality Feature Fusion Network for Action Recognition(**ACM Trans. Multim. Comput. Commun. Appl. 2022**) [[paper](https://doi.org/10.1145/3491228)]

- **[SparseShift-GCN]** SparseShift-GCN: High precision skeleton-based action recognition(**Pattern Recognit. Lett. 2022**) [[paper](https://doi.org/10.1016/j.patrec.2021.12.005)]

- **[FR-AGCN]** Forward-reverse adaptive graph convolutional networks for skeleton-based action recognition(**Neurocomputing 2022**) [[paper](https://doi.org/10.1016/j.neucom.2021.12.054)] [[Github](https://github.com/Nanasaki-Ai/FR-AGCN)] ![](https://img.shields.io/github/stars/Nanasaki-Ai/FR-AGCN.svg?style=social)

- **[ED-GCN]** Enhanced discriminative graph convolutional network with adaptive temporal modelling for skeleton-based action recognition(**Comput. Vis. Image Underst. 2022**) [[paper](https://doi.org/10.1016/j.cviu.2021.103348)]


### 2021 (Action Recognition)
- Quo Vadis, Skeleton Action Recognition ? (**IJCV 2021**) [[paper](https://arxiv.org/pdf/2007.02072.pdf)] [[Github](https://github.com/skelemoa/quovadis)] ![](https://img.shields.io/github/stars/skelemoa/quovadis.svg?style=social)


- **[CTR-GCN]** Channel-wise Topology Refinement Graph Convolution for Skeleton-Based Action Recognition (**ICCV 2021**) [[paper](https://arxiv.org/pdf/2107.12213.pdf)] [[Github](https://github.com/Uason-Chen/CTR-GCN)] ![](https://img.shields.io/github/stars/Uason-Chen/CTR-GCN.svg?style=social)

 - Spatio-Temporal Difference Descriptor for Skeleton-Based Action Recognition
 (**AAAI 2021**) [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/16210)]

- **[AdaSGN]** AdaSGN: Adapting Joint Number and Model Size for Efficient Skeleton-Based Action Recognition (**ICCV 2021**) [[paper](https://doi.org/10.1109/ICCV48922.2021.01316)] [[Github](https://github.com/lshiwjx/AdaSGN)] ![](https://img.shields.io/github/stars/lshiwjx/AdaSGN.svg?style=social)
  
- Self-supervised 3D Skeleton Action Representation Learning with Motion Consistency and Continuity (**ICCV 2021**) [[paper](https://doi.org/10.1109/ICCV48922.2021.01308
)]

- Skeleton Cloud Colorization for Unsupervised 3D Action Representation Learning (**ICCV 2021**) [[paper](https://doi.org/10.1109/ICCV48922.2021.01317)]

- 3D Human Action Representation Learning via Cross-View Consistency Pursuit (**CVPR 2021**) [[arxiv](https://arxiv.org/pdf/2104.14466.pdf)][[Github](https://github.com/LinguoLi/CrosSCLR)] ![](https://img.shields.io/github/stars/LinguoLi/CrosSCLR.svg?style=social)

- **[MST-GCN]** Multi-Scale Spatial Temporal Graph Convolutional Network for Skeleton-Based Action Recognition (**AAAI 2021**) [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/16197)] [[Github](https://github.com/czhaneva/MST-GCN)] ![](https://img.shields.io/github/stars/czhaneva/MST-GCN.svg?style=social)


- Learning Multi-Granular Spatio-Temporal Graph Network for Skeleton-based Action Recognition (**ACMMM 2021**) [[paper](https://doi.org/10.1145/3474085.3475574)] [[Github](https://github.com/tailin1009/DualHead-Network)] ![](https://img.shields.io/github/stars/tailin1009/DualHead-Network.svg?style=social) (Not uploaded)

-  Modeling the Uncertainty for Self-supervised 3D Skeleton Action Representation Learning (**ACMMM 2021**) [[paper](https://doi.org/10.1145/3474085.3475248)]

- Skeleton-Contrastive 3D Action Representation Learning (**ACMMM 2021**) [[paper](https://doi.org/10.1109/TMM.2020.2974323)] [[Github](https://github.com/fmthoker/skeleton-contrast)] ![](https://img.shields.io/github/stars/fmthoker/skeleton-contrast.svg?style=social) (Not uploaded)

- **[STST]** STST: Spatial-Temporal Specialized Transformer for Skeleton-based Action Recognition (**ACMMM 2021**) [[paper](https://doi.org/10.1145/3474085.3475473)] [[Github](https://github.com/HanzoZY/STST)] ![](https://img.shields.io/github/stars/HanzoZY/STST.svg?style=social) (Not uploaded)

- **[CP-STN]** Spatial Temporal Enhanced Contrastive and Pretext Learning for Skeleton-based Action Representation (**PMLR 2021**) [[paper](https://proceedings.mlr.press/v157/zhan21a.html)]



- Tripool: Graph triplet pooling for 3D skeleton-based action recognition (**Pattern Recognit. 2021**) [[paper](https://doi.org/10.1016/j.patcog.2021.107921)]
  
- Structural Knowledge Distillation for Efficient Skeleton-Based Action Recognition (**TIP 2021**) [[paper](https://doi.org/10.1109/TIP.2021.3056895)] [[Github](https://github.com/xiaochehe/SKD)] ![](https://img.shields.io/github/stars/xiaochehe/SKD.svg?style=social)

- **[ShiftGCN++]** Extremely Lightweight Skeleton-Based Action Recognition With ShiftGCN++ (**TIP 2021**) [[paper](https://doi.org/10.1109/TIP.2021.3104182)] [[Github](https://github.com/kchengiva/Shift-GCN-plus)] ![](https://img.shields.io/github/stars/kchengiva/Shift-GCN-plus.svg?style=social)

- **[Hyper-GNN]** Hypergraph Neural Network for Skeleton-Based Action Recognition (**TIP 2021**) [[paper](https://doi.org/10.1109/TIP.2021.3051495)]

- **[GCN-HCRF]** A Multi-Stream Graph Convolutional Networks-Hidden Conditional Random Field Model for Skeleton-Based Action Recognition (**TMM 2021**) [[paper](https://doi.org/10.1109/TMM.2020.2974323)]

- Hierarchical Soft Quantization for Skeleton-Based Human Action Recognition (**TMM 2021**) [[paper](https://doi.org/10.1109/TMM.2020.2990082)]

- Pose Refinement Graph Convolutional Network for Skeleton-Based Action Recognition (**{IEEE} Robotics Autom. Lett. 2021**) [[paper](https://doi.org/10.1109/LRA.2021.3056361)] [[Github](https://github.com/sj-li/PR-GCN)] ![](https://img.shields.io/github/stars/sj-li/PR-GCN.svg?style=social)

- **[FDGCN]** Skeleton-Based Action Recognition With Focusing-Diffusion Graph Convolutional Networks (**IEEE Signal Process. Lett. 2021**) [[paper](https://doi.org/10.1109/LSP.2021.3116513)]

- **[ST-GDN]** Spatial Temporal Graph Deconvolutional Network for Skeleton-Based Human Action Recognition (**IEEE Trans. Circuits Syst. Video Technol. 2021**) [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9312608)]

- Fuzzy Integral-Based {CNN} Classifier Fusion for 3D Skeleton Action Recognition (**IEEE Trans. Circuits Syst. Video Technol. 2021**) [[paper](https://doi.org/10.1109/TCSVT.2020.3019293
)] [[Github](https://github.com/theavicaster/fuzzy-integral-cnn-fusion-3d-har)] ![](https://img.shields.io/github/stars/theavicaster/fuzzy-integral-cnn-fusion-3d-har.svg?style=social)

- **[SEFN]** Symmetrical Enhanced Fusion Network for Skeleton-Based Action Recognition (**IEEE Trans. Circuits Syst. Video Technol. 2021**) [[paper](https://doi.org/10.1109/TCSVT.2021.3050807)]

- **[RA-GCN]** Richly Activated Graph Convolutional Network for Robust Skeleton-Based Action Recognition (**IEEE Trans. Circuits Syst. Video Technol. 2021**) [[paper](https://doi.org/10.1109/TCSVT.2020.3015051)] [[Github](https://github.com/amira-mira/RA-GCNv22)] ![](https://img.shields.io/github/stars/amira-mira/RA-GCNv22.svg?style=social)

- Dual-Stream Structured Graph Convolution Network for Skeleton-Based Action Recognition (**ACM Trans. Multim. Comput. Commun. Appl. 2021**) [[paper](https://doi.org/10.1145/3450410)]

- Action recognition using kinematics posture feature on 3D skeleton joint locations (**Pattern Recognit. Lett. 2021**) [[paper](https://doi.org/10.1016/j.patrec.2021.02.013)]
  
- Scene image and human skeleton-based dual-stream human action recognition (**Pattern Recognit. Lett. 2021**) [[paper](https://doi.org/10.1016/j.patrec.2021.06.003)]

- Skeleton-based action recognition using sparse spatio-temporal GCN with edge effective resistance (**Neurocomputing 2021**) [[paper](https://doi.org/10.1016/j.neucom.2020.10.096)]

- **[VE-GCN]** Integrating vertex and edge features with Graph Convolutional Networks for skeleton-based action recognition (**Neurocomputing 2021**) [[paper](https://doi.org/10.1016/j.neucom.2021.09.034)]

- **[AMV-GCNs]** Adaptive multi-view graph convolutional networks for skeleton-based action recognition (**Neurocomputing 2021**) [[paper](https://doi.org/10.1016/j.neucom.2020.03.126)]

- Rethinking the ST-GCNs for 3D skeleton-based human action recognition (**Neurocomputing 2021**) [[paper](https://doi.org/10.1016/j.neucom.2021.05.004)] [[Github](https://github.com/apenbol/ST-GGN)] ![](https://img.shields.io/github/stars/apenbol/ST-GGN.svg?style=social)

- **[AAM-GCN]** Attention adjacency matrix based graph convolutional networks for skeleton-based action recognition (**Neurocomputing 2021**) [[paper](https://doi.org/10.1016/j.neucom.2021.02.001)]

- **[ST-TR]** Skeleton-based action recognition via spatial and temporal transformer networks (**Comput. Vis. Image Underst. 2021**) [[paper](https://doi.org/10.1016/j.cviu.2021.103219)] [[Github](https://github.com/Anuj040/ST-TR)] ![](https://img.shields.io/github/stars/Anuj040/ST-TR.svg?style=social)

- **[AS-CAL]** Augmented Skeleton Based Contrastive Action Learning with Momentum LSTM for Unsupervised Action Recognition (**Inf. Sci. 2021**) [[paper](https://doi.org/10.1016/j.ins.2021.04.023)] [[Github](https://github.com/LZU-SIAT/AS-CAL)] ![](https://img.shields.io/github/stars/LZU-SIAT/AS-CAL.svg?style=social)


### 2020 (Action Recognition) 

- (Mainly from [[Github](https://github.com/niais/Awesome-Skeleton-based-Action-Recognition)], adding latest status)

- **[MV-IGNET]** Learning Multi-View Interactional Skeleton Graph for Action Recognition (**TPAMI 2020**) [[paper](https://ieeexplore.ieee.org/abstract/document/9234715)][[Github](https://github.com/niais/mv-ignet)] ![](https://img.shields.io/github/stars/niais/mv-ignet.svg?style=social)
- **[MS-AAGCN]** Skeleton-Based Action Recognition with Multi-Stream Adaptive Graph Convolutional Networks (**TIP 2020**) [[paper](https://arxiv.org/pdf/1912.06971.pdf)]
- **[P&C FW-AEC]** PREDICT & CLUSTER: Unsupervised Skeleton Based Action Recognition (**CVPR 2020**) [[paper](http://openaccess.thecvf.com/content_CVPR_2020/papers/Su_PREDICT__CLUSTER_Unsupervised_Skeleton_Based_Action_Recognition_CVPR_2020_paper.pdf)]
- **[CA-GC]** Context Aware Graph Convolution for Skeleton-Based Action Recognition (**CVPR 2020**) [[paper](http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_Context_Aware_Graph_Convolution_for_Skeleton-Based_Action_Recognition_CVPR_2020_paper.pdf)]
- **[Shift-GCN]** Skeleton-Based Action Recognition With Shift Graph Convolutional Network (**CVPR 2020**) [[paper](http://openaccess.thecvf.com/content_CVPR_2020/papers/Cheng_Skeleton-Based_Action_Recognition_With_Shift_Graph_Convolutional_Network_CVPR_2020_paper.pdf)][[Github](https://github.com/kchengiva/Shift-GCN)] ![](https://img.shields.io/github/stars/kchengiva/Shift-GCN.svg?style=social)
- **[DMGNN]** Dynamic Multiscale Graph Neural Networks for 3D Skeleton Based Human Motion Prediction (**CVPR 2020**) [[paper](http://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Dynamic_Multiscale_Graph_Neural_Networks_for_3D_Skeleton_Based_Human_CVPR_2020_paper.pdf)]
- **[SGN]** Semantics-Guided Neural Networks for Efficient Skeleton-Based Human Action Recognition (**CVPR 2020**) [[arxiv](https://arxiv.org/pdf/1904.01189.pdf)][[Github](https://github.com/microsoft/SGN)] ![](https://img.shields.io/github/stars/microsoft/SGN.svg?style=social)
- **[MS-G3D]** Disentangling and Unifying Graph Convolutions for Skeleton-Based Action Recognition (**CVPR 2020**) [[arxiv](https://arxiv.org/pdf/2003.14111.pdf)] [[Github](https://github.com/kenziyuliu/ms-g3d)] ![](https://img.shields.io/github/stars/kenziyuliu/ms-g3d.svg?style=social)

- Adversarial Self-Supervised Learning for Semi-Supervised 3D Action Recognition (**ECCV 2020**) [[arxiv](https://arxiv.org/pdf/2007.05934.pdf)]

- Unsupervised 3D Human Pose Representation with Viewpoint and Pose Disentanglement (**ECCV 2020**) [[arxiv](https://arxiv.org/pdf/2007.07053.pdf)] [[Github](https://github.com/NIEQiang001/unsupervised-human-pose)] ![](https://img.shields.io/github/stars/NIEQiang001/unsupervised-human-pose.svg?style=social)

- **[DecoupleGCN-DropGraph]** Decoupling GCN with DropGraph Module for Skeleton-Based Action Recognition (**ECCV 2020**) [[arxiv](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123690528.pdf)] [[Github](https://github.com/kchengiva/DecoupleGCN-DropGraph)] ![](https://img.shields.io/github/stars/kchengiva/DecoupleGCN-DropGraph.svg?style=social)

- Ms2l: Multi-task self-supervised learning for skeleton based action recognition (**ACMMM 2020**) [[arxiv](https://arxiv.org/pdf/2010.05599.pdf)]

- **[Dynamic GCN]** Dynamic GCN: Context-enriched Topology Learning for Skeleton-based Action Recognition (**ACM-MM 2020**)[[arxiv](https://arxiv.org/pdf/2007.14690.pdf)]

- **[GCN-NAS]** Learning Graph Convolutional Network for Skeleton-based Human Action Recognition by Neural Searching (**AAAI 2020**) [[arxiv](https://arxiv.org/pdf/1911.04131v1.pdf)] [[Github](https://github.com/xiaoiker/GCN-NAS)] ![](https://img.shields.io/github/stars/xiaoiker/GCN-NAS.svg?style=social)

- **[PA-ResGCN]** Stronger, Faster and More Explainable: A Graph Convolutional Baseline for Skeleton-based Action Recognition (**ACM-MM 2020**) [[arxiv](https://arxiv.org/pdf/2010.09978.pdf)] [[Github](https://github.com/yfsong0709/ResGCNv1)] ![](https://img.shields.io/github/stars/yfsong0709/ResGCNv1.svg?style=social)
- **[Poincare-GCN]** Mix Dimension in Poincaré Geometry for 3D Skeleton-based Action Recognition (**ACM-MM 2020**) [[arxiv](https://arxiv.org/pdf/2007.15678.pdf)]
- **[STIGCN]** Spatio-Temporal Inception Graph Convolutional for Skeleton-Based Action Recognition (**ACM-MM 2020**) [[arxiv](https://dl.acm.org/doi/pdf/10.1145/3394171.3413666)]
- **[JOLO-GCN]** JOLO-GCN: Mining Joint-Centered Light-Weight Information for Skeleton-Based Action Recognition (**WACV 2021**) [[arxiv](https://arxiv.org/abs/2011.07787)]
- **[ST-TR-AGCN]** Spatial Temporal Transformer Network for Skeleton-based Action Recognition (**Under submission at Computer Vision and Image Understanding (CVIU)**) [[arxiv](https://arxiv.org/pdf/2008.07404.pdf)] [[Github](https://github.com/Chiaraplizz/ST-TR)] ![](https://img.shields.io/github/stars/Chiaraplizz/ST-TR.svg?style=social)
- **[PCRP]** Prototypical Contrast and Reverse Prediction: Unsupervised Skeleton Based Action Recognition [[arxiv](https://arxiv.org/pdf/2011.07236.pdf)] [[Github](https://github.com/Mikexu007/PCRP)] ![](https://img.shields.io/github/stars/Mikexu007/PCRP.svg?style=social)

### 2019 (Action Recognition)

- NTU-RGB+D 120: A Large-Scale Benchmark for 3D Human Activity Understanding (***TPAMI 2019***) [[arxiv](https://arxiv.org/pdf/1905.04757.pdf)] [[Homepage](http://rose1.ntu.edu.sg/datasets/actionrecognition.asp)] [[Github](https://github.com/shahroudy/NTURGB-D)] ![](https://img.shields.io/github/stars/shahroudy/NTURGB-D.svg?style=social)
- **[VA-NN]** View Adaptive Neural Networks for High Performance Skeleton-based Human Action Recognition (**TPAMI 2019**) [[arxiv](https://arxiv.org/pdf/1804.07453.pdf)] [[Github](https://github.com/microsoft/View-Adaptive-Neural-Networks-for-Skeleton-based-Human-Action-Recognition)] ![](https://img.shields.io/github/stars/microsoft/View-Adaptive-Neural-Networks-for-Skeleton-based-Human-Action-Recognition.svg?style=social)
- Bayesian Graph Convolutional LSTM for Skeleton Based Action Recognition (**ICCV 2019**) [[arxiv](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhao_Bayesian_Graph_Convolution_LSTM_for_Skeleton_Based_Action_Recognition_ICCV_2019_paper.pdf)]
- **[2s-SDGCN]** Spatial Residual Layer and Dense Connection Block Enhanced Spatial Temporal Graph Convolutional Network for Skeleton-Based Action Recognition (*ICCV Workshop 2019*) [[paper](http://openaccess.thecvf.com/content_ICCVW_2019/papers/SGRL/Wu_Spatial_Residual_Layer_and_Dense_Connection_Block_Enhanced_Spatial_Temporal_ICCVW_2019_paper.pdf)]
- **[DGNN]** Skeleton-Based Action Recognition With Directed Graph Neural Networks (**CVPR 2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shi_Skeleton-Based_Action_Recognition_With_Directed_Graph_Neural_Networks_CVPR_2019_paper.pdf)] [[unofficial PyTorch implementation](https://github.com/kenziyuliu/DGNN-PyTorch)] ![](https://img.shields.io/github/stars/kenziyuliu/DGNN-PyTorch.svg?style=social)
- **[2s-AGCN]** Two-Stream Adaptive Graph Convolutional Networks for Skeleton-Based Action Recognition (**CVPR 2019**) [[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shi_Two-Stream_Adaptive_Graph_Convolutional_Networks_for_Skeleton-Based_Action_Recognition_CVPR_2019_paper.pdf)] [[Github](https://github.com/lshiwjx/2s-AGCN)] ![](https://img.shields.io/github/stars/lshiwjx/2s-AGCN.svg?style=social)
- **[AS-GCN]** Actional-Structural Graph Convolutional Networks for Skeleton-based Action Recognition (**CVPR 2019**) [[arxiv](https://arxiv.org/pdf/1904.12659.pdf)] [[Github](https://github.com/limaosen0/AS-GCN)] ![](https://img.shields.io/github/stars/limaosen0/AS-GCN.svg?style=social)
- **[AGC-LSTM]** An Attention Enhanced Graph Convolutional LSTM Network for Skeleton-Based Action Recognition (**CVPR 2019**) [[arxiv](https://arxiv.org/pdf/1902.09130.pdf)]
- Optimized Skeleton-based Action Recognition via Sparsified Graph Regression (**ACMMM 2019**) [[paper](https://arxiv.org/pdf/1811.12013.pdf)]
- **[Motif-STGCN]** Graph CNNs with Motif and Variable Temporal Block for Skeleton-based Action Recognition (**AAAI 2019**) [[arxiv](http://geometrylearning.com/paper/Graph_CNN.pdf)] [[Github](https://github.com/wenyh1616/motif-stgcn)] ![](https://img.shields.io/github/stars/wenyh1616/motif-stgcn.svg?style=social)
- Richly Activated Graph Convolutional Network for Action Recognition with Incomplete Skeletons (**ICIP 2019**) [[arxiv](https://arxiv.org/pdf/1905.06774.pdf)] [[Github](https://github.com/yfsong0709/RA-GCNv1)] ![](https://img.shields.io/github/stars/yfsong0709/RA-GCNv1.svg?style=social)
- **[TSRJI]** Skeleton Image Representation for 3D Action Recognition based on Tree Structure and Reference Joints (**SIBGRAPI**) [[arxiv](https://arxiv.org/pdf/1909.05704v1.pdf)] [[Github](https://github.com/carloscaetano/skeleton-images#skeleton-images-representation-SkeleMotion-and-SRJI)] ![](https://img.shields.io/github/stars/carloscaetano/skeleton-images#skeleton-images-representation-SkeleMotion-and-SRJI.svg?style=social)
- **[SkeleMotion]** SkeleMotion: A New Representation of Skeleton Joint Sequences Based on Motion Information for 3D Action Recognition (**AVSS**) [[arxiv](https://arxiv.org/pdf/1907.13025v1.pdf)] [[Github](https://github.com/carloscaetano/skeleton-images#skeleton-images-representation-SkeleMotion-and-SRJI)] ![](https://img.shields.io/github/stars/carloscaetano/skeleton-images#skeleton-images-representation-SkeleMotion-and-SRJI.svg?style=social)

### 2018 (Action Recognition)

- **Beyond Joints:** Learning Representations from Primitive Geometries for Skeleton-based Action Recognition and Detection (***TIP 2018***) [[paper](https://ieeexplore.ieee.org/document/8360391)] [[Github](https://github.com/hongsong-wang/Beyond-Joints)] ![](https://img.shields.io/github/stars/hongsong-wang/Beyond-Joints.svg?style=social)
- **[DPRL]** Deep progressive reinforcement learning for skeleton-based action recognition (**CVPR 2018**) [[paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Tang_Deep_Progressive_Reinforcement_CVPR_2018_paper.pdf)]
- **[SR-TSL]** Skeleton based action recognition with spatial reasoning and temporal stack learning (**ECCV 2018**) [[arxiv](https://arxiv.org/pdf/1805.02335.pdf)]
- **[HCN]** Co-occurrence feature learning from skeleton data for action recognition and detection with hierarchical aggregation (**IJCAI 2018**) [[arxiv](https://arxiv.org/pdf/1804.06055.pdf)] [[Reimplementation](https://github.com/huguyuehuhu/HCN-pytorch)] ![](https://img.shields.io/github/stars/huguyuehuhu/HCN-pytorch.svg?style=social)
- **[MAN]** Memory attention networks for skeleton-based action recognition (**IJCAI 2018**) [[arxiv](https://arxiv.org/pdf/1804.08254.pdf)] [[Github](https://github.com/memory-attention-networks/MANs)] ![](https://img.shields.io/github/stars/memory-attention-networks/MANs.svg?style=social)
- **[ST-GCN]** Spatial temporal graph convolutional networks for skeleton-based action recognition (**AAAI 2018**) [[arxiv](https://arxiv.org/pdf/1801.07455.pdf)] [[Github](https://github.com/yysijie/st-gcn)] ![](https://img.shields.io/github/stars/yysijie/st-gcn.svg?style=social)
- Unsupervised representation learning with long-term dynamics for skeleton based action recognition (**AAAI 2018**) [[arxiv](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16341/15984)] [[Github](https://github.com/jungel2star/Unsupervised-Representation-Learning-with-Long-Term-Dynamics-for-Skeleton-Based-Action-Recognition)] ![](https://img.shields.io/github/stars/jungel2star/Unsupervised-Representation-Learning-with-Long-Term-Dynamics-for-Skeleton-Based-Action-Recognition.svg?style=social)
- Spatio-temporal graph convolution for skeleton based action recognition (**AAAI 2018**) [[arxiv](https://arxiv.org/pdf/1802.09834.pdf)]
- Part-based Graph Convolutional Network for Action Recognition (**BMVC 2018**) [[arxiv](https://arxiv.org/pdf/1809.04983.pdf)] [[Github](https://github.com/kalpitthakkar/pb-gcn)] ![](https://img.shields.io/github/stars/kalpitthakkar/pb-gcn.svg?style=social)
- A Fine-to-Coarse Convolutional Neural Network for 3D Human Action Recognition (**BMVC 2018**) [[arxiv](https://arxiv.org/pdf/1805.11790.pdf)]
- A Large-scale Varying-view RGB-D Action Dataset for Arbitrary-view Human Action Recognition (**ACMMM 2018**) [[arxiv](https://arxiv.org/pdf/1904.10681.pdf)]
- Unsupervised feature learning of human actions as trajectories in pose embedding manifold (**WACV 2018**) [[arxiv](https://arxiv.org/abs/1812.02592)]


### 2017 (Action Recognition)

- Jointly learning heterogeneous features for RGB-D activity recognition (***TPAMI 2017***) [[paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Hu_Jointly_Learning_Heterogeneous_2015_CVPR_paper.pdf)]
- **[Visualization CNN]** Enhanced skeleton visualization for view invariant human action recognition (***Pattern Recognition 2017***) [[paper](https://www.utdallas.edu/~cxc123730/PR_2017.pdf)]
- Global context-aware attention lstm networks for 3d action recognition (**CVPR 2017**) [[paper](https://ieeexplore.ieee.org/document/8099874)]
- **[Two-stream RNN]** Modeling temporal dynamics and spatial configurations of actions using two-stream recurrent neural networks (**CVPR 2017**) [[arxiv](https://arxiv.org/pdf/1704.02581.pdf)] [[Github](https://github.com/hongsong-wang/RNN-for-skeletons)] ![](https://img.shields.io/github/stars/Mikexu007/PCRP.svg?style=social)
- **[C-CNN + MTLN]** A new representation of skeleton sequences for 3d action recognition (**CVPR 2017**) [[arxiv](https://arxiv.org/pdf/1703.03492.pdf)]
- **[Ensemble TS-LSTM]** Ensemble deep learning for skeleton-based action recognition using temporal sliding lstm networks (**ICCV 2017**) [[paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Lee_Ensemble_Deep_Learning_ICCV_2017_paper.pdf)] [[Github](https://github.com/InwoongLee/TS-LSTM)] ![](https://img.shields.io/github/stars/InwoongLee/TS-LSTM.svg?style=social)
- **[VA-LSTM]** View adaptive recurrent neural networks for high performance human action recognition from skeleton data (**ICCV 2017**) [[arxiv](https://arxiv.org/pdf/1703.08274.pdf)]
- Learning action recognition model from depth and skeleton videos (**ICCV 2017**) [[paper](https://ieeexplore.ieee.org/document/8237883)]
- **[STA-LSTM]** An end-to-end spatio-temporal attention model for human action recognition from skeleton data (**AAAI 2017**) [[arxiv](https://arxiv.org/pdf/1611.06067.pdf)]
- Skeleton-based action recognition using LSTM and CNN (*ICME Workshop 2017*) [[arxiv](https://arxiv.org/pdf/1707.02356.pdf)]
- Skeleton-based action recognition with convolutional neural networks (*ICME Workshop 2017*) [[arxiv](https://arxiv.org/pdf/1704.07595.pdf)]
- PKU-MMD: A large scale benchmark for continuous multi-modal human action understanding (*ACMMM Workshop 2017*) [[arxiv](https://arxiv.org/pdf/1703.07475.pdf)]
- **[Temporal Conv]** Interpretable 3d human action analysis with temporal convolutional networks (*CVPR Workshop 2017*) [[arxiv](https://arxiv.org/pdf/1704.04516.pdf)]

### Before 2017 (Action Recognition)

- **[Trust Gate ST-LSTM]** Spatio-temporal lstm with trust gates for 3d human action recognition (**ECCV 2016**) [[arxiv](https://arxiv.org/pdf/1607.07043.pdf)] [[Github](https://github.com/kinect59/Spatio-Temporal-LSTM)] ![](https://img.shields.io/github/stars/kinect59/Spatio-Temporal-LSTM.svg?style=social)
- **[Part-aware LSTM]** NTU RGB+D: A Large Scale Dataset for 3D Human Activity Analysis (**CVPR 2016**) [[arxiv](https://arxiv.org/pdf/1604.02808.pdf)]
- Rolling rotations for recognizing human actions from 3d skeletal data (**CVPR 2016**) [[paper](https://ieeexplore.ieee.org/document/7780853)]
- Co-occurrence feature learning for skeleton based action recognition using regularized deep lstm networks (**AAAI 2016**) [[paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/download/11989/12149)]
- Skeleton based action recognition with convolutional neural network (**ACPR 2015**) [[paper](https://ieeexplore.ieee.org/abstract/document/7486569)]
- **[H-RNN]** Hierarchical recurrent neural network for skeleton based action recognition (**CVPR 2015**) [[paper](https://ieeexplore.ieee.org/document/7298714)]
- Jointly learning heterogeneous features for rgb-d activity recognition (**CVPR 2015**) [[paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Hu_Jointly_Learning_Heterogeneous_2015_CVPR_paper.pdf)]
- **[LieGroup]** Human action recognition by representing 3d skeletons as points in a lie group (**CVPR 2014**) [[paper](https://openaccess.thecvf.com/content_cvpr_2014/papers/Vemulapalli_Human_Action_Recognition_2014_CVPR_paper.pdf)]
- Human action recognition using a temporal hierarchy of covariance descriptors on 3d joint locations (**IJCAI 2013**) [[paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.415.8032&rep=rep1&type=pdf)]


### arXiv papers (Action Recognition)

- Skeleton-DML: Deep Metric Learning for Skeleton-Based One-Shot Action Recognition [[arxiv](https://arxiv.org/abs/2012.13823)][[Github](https://github.com/raphaelmemmesheimer/skeleton-dml)] ![](https://img.shields.io/github/stars/raphaelmemmesheimer/skeleton-dml.svg?style=social) (Accepted at **WACV 2022**)
- Sparse Semi-Supervised Action Recognition with Active Learning [[arxiv](https://arxiv.org/abs/2012.01740#:~:text=Sparse%20Semi%2DSupervised%20Action%20Recognition%20with%20Active%20Learning,-Jingyuan%20Li%2C%20Eli&text=Current%20state%2Dof%2Dthe%2D,in%20annotation%20and%20mislabeled%20data.)]
- STAR: Sparse Transformer-based Action Recognition [[arxiv](https://arxiv.org/abs/2107.07089)] [[Github](https://github.com/imj2185/STAR)] ![](https://img.shields.io/github/stars/imj2185/STAR.svg?style=social)
- **[DenseIndRNN]** Deep Independently Recurrent Neural Network (**Preprint**) [[arxiv](https://arxiv.org/pdf/1910.06251v1.pdf)] [[Github](https://github.com/Sunnydreamrain/IndRNN_pytorch)]
- Skeleton-Based Action Recognition with Synchronous Local and Non-local Spatio-temporal Learning and Frequency Attention [[arxiv](https://arxiv.org/pdf/1811.04237.pdf)] (Accepted at **ICME 2019**)
- **[DSTA-Net]** Decoupled Spatial-Temporal Attention Network for Skeleton-Based Action Recognition [[arxiv](https://arxiv.org/abs/2007.03263#:~:text=Decoupled%20Spatial%2DTemporal%20Attention%20Network%20for%20Skeleton%2DBased%20Action%20Recognition,-Lei%20Shi%2C%20Yifan&text=It%20involves%20solely%20the%20attention,their%20positions%20or%20mutual%20connections.)] (Accepted at **ACCV 2020**)
- SynSE: Syntactically Guided Generative Embeddings for Zero Shot Skeleton Action Recognition [[arxiv](https://arxiv.org/pdf/2101.11530.pdf)] [[Github](https://github.com/skelemoa/synse-zsl)] (Accepted at **ICIP 2021**)
- **[PoseC3D]** Revisiting Skeleton-based Action Recognition [[arxiv](https://arxiv.org/pdf/2104.13586.pdf)][[Github](https://github.com/open-mmlab/mmaction2/tree/master/configs/skeleton/posec3d)]
- Leveraging Third-Order Features in Skeleton-Based Action Recognition [[arxiv](https://arxiv.org/pdf/2105.01563.pdf)][[Github](https://github.com/ZhenyueQin/Angular-Skeleton-Encoding)] 


### Skeleton-based Action Recognition under Adversarial Attack

- Understanding the Robustness of Skeleton-based Action Recognition under Adversarial Attack (**CVPR 2021**) [[arxiv](https://arxiv.org/pdf/2103.05347.pdf)]
- BASAR:Black-box Attack on Skeletal Action Recognition (**CVPR 2021**) [[arxiv](https://arxiv.org/pdf/2103.05266.pdf)]




### Leaderboards on NTU-RGB+D and NTU-RGB+D 120 Datasets

#### NTU-RGB+D

| Year | Methods               | Cross-Subject | Cross-View |
| ---- | --------------------- | :-----------: | :--------: |
| 2014 | Lie Group             |     50.1      |    52.8    |
| 2015 | H-RNN                 |     59.1      |    64.0    |
| 2016 | Part-aware LSTM       |     62.9      |    70.3    |
| 2016 | Trust Gate ST-LSTM    |     69.2      |    77.7    |
| 2017 | Two-stream RNN        |     71.3      |    79.5    |
| 2017 | STA-LSTM              |     73.4      |    81.2    |
| 2017 | Ensemble TS-LSTM      |     74.6      |    81.3    |
| 2017 | Visualization CNN     |     76.0      |    82.6    |
| 2017 | C-CNN + MTLN          |     79.6      |    84.8    |
| 2017 | Temporal Conv         |     74.3      |    83.1    |
| 2017 | VA-LSTM               |     79.4      |    87.6    |
| 2018 | Beyond Joints         |     79.5      |    87.6    |
| 2018 | ST-GCN                |     81.5      |    88.3    |
| 2018 | DPRL                  |     83.5      |    89.8    |
| 2019 | Motif-STGCN           |     84.2      |    90.2    |
| 2018 | HCN                   |     86.5      |    91.1    |
| 2018 | SR-TSL                |     84.8      |    92.4    |
| 2018 | MAN                   |     82.7      |    93.2    |
| 2019 | RA-GCN                |     85.9      |    93.5    |
| 2019 | DenseIndRNN           |     86.7      |    93.7    |
| 2018 | PB-GCN                |     87.5      |    93.2    |
| 2019 | AS-GCN                |     86.8      |    94.2    |
| 2019 | VA-NN (fusion)        |     89.4      |    95.0    |
| 2019 | AGC-LSTM (Joint&Part) |     89.2      |    95.0    |
| 2019 | 2s-AGCN               |     88.5      |    95.1    |
| 2020 | SGN                   |     89.0      |    94.5    |
| 2020 | GCN-NAS               |     89.4      |    95.7    |
| 2019 | 2s-SDGCN              |     89.6      |    95.7    |
| 2019 | DGNN                  |     89.9      |    96.1    |
| 2020 | MV-IGNET              |     89.2      |    96.3    |
| 2020 | 4s Shift-GCN          |     90.7      |    96.5    |
| 2020 | DecoupleGCN-DropGraph |     90.8      |    96.6    |  
| 2020 | PA-ResGCN-B19         |     90.9      |    96.0    |
| 2020 | MS-G3D                |     91.5      |    96.2    |
| 2021 | EfficientGCN-B4       |     91.7      |    95.7    |
| 2021 | CTR-GCN               |     92.4      |    96.8    |



#### NTU-RGB+D 120

| Year | Methods                             | Cross-Subject | Cross-Setup |
| ---- | ----------------------------------- | :-----------: | :---------: |
| 2019 | SkeleMotion (Magnitude-Orientation) |     62.9      |    63.0     |
| 2019 | SkeleMotion + Yang *et al*          |     67.7      |    66.9     |
| 2019 | TSRJI                               |     67.9      |    59.7     |
| 2020 | SGN                                 |     79.2      |    81.5     |
| 2020 | MV-IGNET                            |     83.9      |    85.6     |
| 2020 | 4s Shift-GCN                        |     85.9      |    87.6     |
| 2020 | DecoupleGCN-DropGraph               |     86.5      |    88.1     |
| 2020 | MS-G3D                              |     86.9      |    88.4     |
| 2020 | PA-ResGCN-B19                       |     87.3      |    88.3     |
| 2021 | EfficientGCN-B4                     |     88.3      |    89.1     |
| 2021 | CTR-GCN                             |     88.9      |    90.6     |




## 3D Pose Estimation
### Datasets
Overview of available datasets for **3D pose estimation** and their statistics, provided by the paper of (**Comput. Vis. Image Underst. 2021**) [[paper](https://www.sciencedirect.com/science/article/pii/S1077314221000692)] (Deep 3D human pose estimation: A review). 
```
Bold shows the most-frequently used datasets in the literature.
```

| **# Id** | **Dataset**                  | **Year** | **# Images**     | **# Subject**              |
|:--------:|------------------------------|----------|------------------|----------------------------|
|   **1**  | [**HumanEva-I**](http://humaneva.is.tue.mpg.de/)               | **2010** | **12 sequences** | **4 subject, 6 actions**   |
|   **2**  | [**Human3.6M**](http://vision.imar.ro/human3.6m/)                | **2013** | **3.6M**         | **11 (5 female + 6 male)** |
|     3    | Shelf                        | 2014     | ——               | 4                          |
|     4    | Campus                       | 2014     | ——               | 3                          |
|     5    | MARCONnI                     | 2016     | 12 sequences     | 1 or 2 per sequence        |
|     6    | [CMU Panoptic](http://domedb.perception.cs.cmu.edu/)                 | 2016     | 1.5M             | Up to 8 subjects           |
|   **7**  | [**MPI-INF-3DHP**](http://gvv.mpi-inf.mpg.de/3dhp-dataset/)             | **2016** | **1.3M frames**  | **8 (4 female + 4 male)**  |
|   **8**  | [**MuCo-3DHP<br>(MuPoTS-3D)**](http://gvv.mpi-inf.mpg.de/projects/SingleShotMultiPerson/) | **2017** | **——**           | **8 (4 female + 4 male)**  |
|     9    | [Total Capture](https://cvssp.org/data/totalcapture/)                | 2017     | 1.892M frames    | 5 (4 male + 1 female)      |
|    10    | [SURREAL](https://www.di.ens.fr/willow/research/surreal/data/)                      | 2017     | 6M frames        | 145                        |
|  **11**  | [**Unite the People**](http://up.is.tuebingen.mpg.de/)         | **2017** | **8515 images**  |                            |
|    12    | [JTA](http://imagelab.ing.unimore.it/jta)                          | 2018     | 500K frames      | > 21                       |
|    13    | [3DPW](http://virtualhumans.mpi-inf.mpg.de/3DPW)                         | 2018     | 60 sequences     | 7                          |

### 2022 (3D Pose Estimation)
- [Consensus-Based Optimization for 3D Human Pose Estimation in Camera Coordinates](https://doi.org/10.1007/s11263-021-01570-9) (IJCV 2022) [[Github](https://github.com/dluvizon/3d-pose-consensus)] ![](https://img.shields.io/github/stars/dluvizon/3d-pose-consensus.svg?style=social)
        
- [Object-Based Visual Camera Pose Estimation From Ellipsoidal Model and 3D-Aware Ellipse Prediction](https://doi.org/10.1007/s11263-022-01585-w) (IJCV 2022)
    
- [Locally Connected Network for Monocular 3D Human Pose Estimation](https://doi.org/10.1109/TPAMI.2020.3019139) (TPAMI 2022)

- [HEMlets PoSh: Learning Part-Centric Heatmap Triplets for 3D Human Pose and Shape Estimation](https://doi.org/10.1109/TPAMI.2021.3051173) (TPAMI 2022)

- [Limb Pose Aware Networks for Monocular 3D Pose Estimation](https://doi.org/10.1109/TIP.2021.3136613) (TIP 2022)

- [Differentiable Spatial Regression: A Novel Method for 3D Hand Pose Estimation](https://doi.org/10.1109/TIP.2021.3136613) (TMM 2022)
  
- [3D hand pose and shape estimation from RGB images for keypoint-based hand gesture recognition](https://doi.org/10.1016/j.patcog.2022.108762) (Pattern Recognit. 2022)

- [3D pose estimation and future motion prediction from 2D images](https://doi.org/10.1016/j.patcog.2021.108439) (Pattern Recognit. 2022)

- [Learning Monocular 3D Human Pose Estimation With Skeletal Interpolation](https://doi.org/10.1109/ICASSP43922.2022.9746410) (ICASSP 2022)

- [Adversarial Learning Enhancement for 3D Human Pose and Shape Estimation](https://doi.org/10.1109/ICASSP43922.2022.9746244) (ICASSP 2022)

- [3D-Augmented Contrastive Knowledge Distillation for Image-based Object Pose Estimation](https://doi.org/10.1145/3512527.3531359) (ICMR 2022)
  


### 2021 (3D Pose Estimation)
- [Enhanced 3D Human Pose Estimation from Videos by Using Attention-Based Neural Network with Dilated Convolutions](https://doi.org/10.1007/s11263-021-01436-0) (IJCV 2021)
        
- [3D Hand Pose Estimation Using Synthetic Data and Weakly Labeled RGB Images](https://doi.org/10.1109/TPAMI.2020.2993627) (TPAMI 2021)
    
- [Multi-Task Deep Learning for Real-Time 3D Human Pose Estimation and Action Recognition](https://arxiv.org/pdf/1803.09722.pdf) (TPAMI 2021) [[Github](https://github.com/IMAGINE-Paris/deephar)] ![](https://img.shields.io/github/stars/IMAGINE-Paris/deephar.svg?style=social)
    
- [Learning Dynamical Human-Joint Affinity for 3D Pose Estimation in Videos](https://doi.org/10.1109/TIP.2021.3109517) (TIP 2021)
    
- [TransPose: real-time 3D human translation and pose estimation with six inertial sensors](https://doi.org/10.1145/3450626.3459786) (ACM Trans. Graph. 2021)  [[Github](https://github.com/Xinyu-Yi/TransPose)] ![](https://img.shields.io/github/stars/Xinyu-Yi/TransPose.svg?style=social)
    
- [Deductive Learning for Weakly-Supervised 3D Human Pose Estimation via Uncalibrated Cameras](https://ojs.aaai.org/index.php/AAAI/article/view/16194) (AAAI 2021)
    
- [Graph and Temporal Convolutional Networks for 3D Multi-person Pose Estimation in Monocular Videos](https://ojs.aaai.org/index.php/AAAI/article/view/16202) (AAAI 2021)
    
- [Invariant Teacher and Equivariant Student for Unsupervised 3D Human Pose Estimation](https://ojs.aaai.org/index.php/AAAI/article/view/16409) (AAAI 2021) [[Github](https://github.com/MediaBrain-SJTU/ITES)] ![](https://img.shields.io/github/stars/MediaBrain-SJTU/ITES.svg?style=social)
    
- [SimPoE: Simulated Character Control for 3D Human Pose Estimation](https://openaccess.thecvf.com/content/CVPR2021/html/Yuan\_SimPoE\_Simulated\_Character\_Control\_for\_3D\_Human\_Pose\_Estimation\_CVPR\_2021\_paper.html) (CVPR 2021)
    
- [Monocular 3D Multi-Person Pose Estimation by Integrating Top-Down and Bottom-Up Networks](https://openaccess.thecvf.com/content/CVPR2021/html/Cheng\_Monocular\_3D\_Multi-Person\_Pose\_Estimation\_by\_Integrating\_Top-Down\_and\_Bottom-Up\_CVPR\_2021\_paper.html) (CVPR 2021) [[Github](https://github.com/VIML-CVDL/3D-Multi-Person-Pose)] ![](https://img.shields.io/github/stars/VIML-CVDL/3D-Multi-Person-Pose.svg?style=social)
    
- [PoseAug: A Differentiable Pose Augmentation Framework for 3D Human Pose Estimation](https://openaccess.thecvf.com/content/CVPR2021/html/Gong\_PoseAug\_A\_Differentiable\_Pose\_Augmentation\_Framework\_for\_3D\_Human\_Pose\_CVPR\_2021\_paper.html) (CVPR 2021)  [[Github](https://github.com/jfzhang95/PoseAug)] ![](https://img.shields.io/github/stars/jfzhang95/PoseAug.svg?style=social)
    
- [Human POSEitioning System (HPS): 3D Human Pose Estimation and Self-Localization in Large Scenes From Body-Mounted Sensors](https://openaccess.thecvf.com/content/CVPR2021/html/Guzov\_Human\_POSEitioning\_System\_HPS\_3D\_Human\_Pose\_Estimation\_and\_Self-Localization\_CVPR\_2021\_paper.html) (CVPR 2021) [[Github](https://github.com/aymenmir1/hps)] ![](https://img.shields.io/github/stars/aymenmir1/hps.svg?style=social)
    
- [HybrIK: A Hybrid Analytical-Neural Inverse Kinematics Solution for 3D Human Pose and Shape Estimation](https://openaccess.thecvf.com/content/CVPR2021/html/Li\_HybrIK\_A\_Hybrid\_Analytical-Neural\_Inverse\_Kinematics\_Solution\_for\_3D\_Human\_CVPR\_2021\_paper.html) (CVPR 2021) [[Github](https://github.com/Jeff-sjtu/HybrIK)] ![](https://img.shields.io/github/stars/Jeff-sjtu/HybrIK.svg?style=social)
    
- [Multi-View Multi-Person 3D Pose Estimation With Plane Sweep Stereo](https://openaccess.thecvf.com/content/CVPR2021/html/Lin\_Multi-View\_Multi-Person\_3D\_Pose\_Estimation\_With\_Plane\_Sweep\_Stereo\_CVPR\_2021\_paper.html) (CVPR 2021) [[Github](https://github.com/jiahaoLjh/PlaneSweepPose)] ![](https://img.shields.io/github/stars/jiahaoLjh/PlaneSweepPose.svg?style=social)
    
- [Semi-Supervised 3D Hand-Object Poses Estimation With Interactions in Time](https://openaccess.thecvf.com/content/CVPR2021/html/Liu\_Semi-Supervised\_3D\_Hand-Object\_Poses\_Estimation\_With\_Interactions\_in\_Time\_CVPR\_2021\_paper.html) (CVPR 2021)
    
- [Context Modeling in 3D Human Pose Estimation: A Unified Perspective](https://openaccess.thecvf.com/content/CVPR2021/html/Ma\_Context\_Modeling\_in\_3D\_Human\_Pose\_Estimation\_A\_Unified\_Perspective\_CVPR\_2021\_paper.html) (CVPR 2021) [[Github](https://github.com/ShirleyMaxx/ContextPose-PyTorch-release)] ![](https://img.shields.io/github/stars/ShirleyMaxx/ContextPose-PyTorch-release.svg?style=social)
    
- [Probabilistic 3D Human Shape and Pose Estimation From Multiple Unconstrained Images in the Wild](https://openaccess.thecvf.com/content/CVPR2021/html/Sengupta\_Probabilistic\_3D\_Human\_Shape\_and\_Pose\_Estimation\_From\_Multiple\_Unconstrained\_CVPR\_2021\_paper.html) (CVPR 2021)
    
- [CanonPose: Self-Supervised Monocular 3D Human Pose Estimation in the Wild](https://openaccess.thecvf.com/content/CVPR2021/html/Wandt\_CanonPose\_Self-Supervised\_Monocular\_3D\_Human\_Pose\_Estimation\_in\_the\_Wild\_CVPR\_2021\_paper.html) (CVPR 2021) [[Github](https://github.com/bastianwandt/CanonPose)] ![](https://img.shields.io/github/stars/bastianwandt/CanonPose.svg?style=social)
    
- [Graph Stacked Hourglass Networks for 3D Human Pose Estimation](https://openaccess.thecvf.com/content/CVPR2021/html/Xu\_Graph\_Stacked\_Hourglass\_Networks\_for\_3D\_Human\_Pose\_Estimation\_CVPR\_2021\_paper.html) (CVPR 2021)
    
- [HandFoldingNet: A 3D Hand Pose Estimation Network Using Multiscale-Feature Guided Folding of a 2D Hand Skeleton](https://doi.org/10.1109/ICCV48922.2021.01107) (ICCV 2021) [[Github](https://github.com/cwc1260/HandFold)] ![](https://img.shields.io/github/stars/cwc1260/HandFold.svg?style=social)
    
- [Camera Distortion-aware 3D Human Pose Estimation in Video with Optimization-based Meta-Learning](https://doi.org/10.1109/ICCV48922.2021.01098) (ICCV 2021) [[Github](https://github.com/hanbyel0105/CamDistHumanPose3D)] ![](https://img.shields.io/github/stars/hanbyel0105/CamDistHumanPose3D.svg?style=social)
    
- [Revitalizing Optimization for 3D Human Pose and Shape Estimation: A Sparse Constrained Formulation](https://doi.org/10.1109/ICCV48922.2021.01126) (ICCV 2021)
    
- [Unsupervised 3D Pose Estimation for Hierarchical Dance Video Recognition](https://doi.org/10.1109/ICCV48922.2021.01083) (ICCV 2021)
    
- [EM-POSE: 3D Human Pose Estimation from Sparse Electromagnetic Trackers](https://doi.org/10.1109/ICCV48922.2021.01129) (ICCV 2021) [[Github](https://github.com/facebookresearch/em-pose)] ![](https://img.shields.io/github/stars/facebookresearch/em-pose.svg?style=social)
    
- [HuMoR: 3D Human Motion Model for Robust Pose Estimation](https://arxiv.org/pdf/1803.09722.pdf) (ICCV 2021) [[Github](https://github.com/davrempe/humor)] ![](https://img.shields.io/github/stars/davrempe/humor.svg?style=social)
    
- [EventHands: Real-Time Neural 3D Hand Pose Estimation from an Event Stream](https://doi.org/10.1109/ICCV48922.2021.01216) (ICCV 2021) [[Github](https://github.com/r00tman/EventHands)] ![](https://img.shields.io/github/stars/r00tman/EventHands.svg?style=social)
    
- [Hierarchical Kinematic Probability Distributions for 3D Human Shape and Pose Estimation from Images in the Wild](https://doi.org/10.1109/ICCV48922.2021.01103) (ICCV 2021) [[Github](https://github.com/akashsengupta1997/HierarchicalProbabilistic3DHuman)] ![](https://img.shields.io/github/stars/akashsengupta1997/HierarchicalProbabilistic3DHuman.svg?style=social)
    
- [PeCLR: Self-Supervised 3D Hand Pose Estimation from monocular RGB via Contrastive Learning](https://doi.org/10.1109/ICCV48922.2021.01104) (ICCV 2021) [[Github](https://github.com/dahiyaaneesh/peclr)] ![](https://img.shields.io/github/stars/dahiyaaneesh/peclr.svg?style=social)
    
- [Encoder-decoder with Multi-level Attention for 3D Human Shape and Pose Estimation](https://doi.org/10.1109/ICCV48922.2021.01279) (ICCV 2021) [[Github](https://github.com/ziniuwan/maed)] ![](https://img.shields.io/github/stars/ziniuwan/maed.svg?style=social)
  
- [Probabilistic Monocular 3D Human Pose Estimation with Normalizing Flows](https://doi.org/10.1109/ICCV48922.2021.01101) (ICCV 2021) [[Github](https://github.com/twehrbein/Probabilistic-Monocular-3D-Human-Pose-Estimation-with-Normalizing-Flows)] ![](https://img.shields.io/github/stars/twehrbein/Probabilistic-Monocular-3D-Human-Pose-Estimation-with-Normalizing-Flows.svg?style=social)
    
- [Graph-Based 3D Multi-Person Pose Estimation Using Multi-View Images](https://doi.org/10.1109/ICCV48922.2021.01096) (ICCV 2021) [[Github](https://github.com/IbrahimL/gb3mppe)] ![](https://img.shields.io/github/stars/IbrahimL/gb3mppe.svg?style=social)

- [Towards Alleviating the Modeling Ambiguity of Unsupervised Monocular 3D Human Pose Estimation](https://doi.org/10.1109/ICCV48922.2021.00853) (ICCV 2021)
    
- [Learning Skeletal Graph Neural Networks for Hard 3D Pose Estimation](https://doi.org/10.1109/ICCV48922.2021.01124) (ICCV 2021)  [[Github](https://github.com/ailingzengzzz/Skeletal-GNN)] ![](https://img.shields.io/github/stars/ailingzengzzz/Skeletal-GNN.svg?style=social)

- [EventHPE: Event-based 3D Human Pose and Shape Estimation](https://doi.org/10.1109/ICCV48922.2021.01081) (ICCV 2021) [[Github](https://github.com/JimmyZou/EventHPE)] ![](https://img.shields.io/github/stars/JimmyZou/EventHPE.svg?style=social)
    
- [3D Human Pose Estimation with Spatial and Temporal Transformers](https://doi.org/10.1109/ICCV48922.2021.01128) (ICCV 2021) [[Github](https://github.com/zczcwh/PoseFormer)] ![](https://img.shields.io/github/stars/zczcwh/PoseFormer.svg?style=social)
    
- [Modulated Graph Convolutional Network for 3D Human Pose Estimation](https://arxiv.org/pdf/1803.09722.pdf) (ICCV 2021) [[Github](https://github.com/ZhimingZo/Modulated-GCN)] ![](https://img.shields.io/github/stars/ZhimingZo/Modulated-GCN.svg?style=social)
  
- [Sequential 3D Human Pose Estimation Using Adaptive Point Cloud Sampling Strategy](https://arxiv.org/pdf/1803.09722.pdf) (IJCAI 2021) [[Github](https://github.com/Hmslab/Adapose)] ![](https://img.shields.io/github/stars/Hmslab/Adapose.svg?style=social)

- [PoseGTAC: Graph Transformer Encoder-Decoder with Atrous Convolution for 3D Human Pose Estimation](https://doi.org/10.24963/ijcai.2021/188) (IJCAI 2021)   

- [U-CondDGCN: Conditional Directed Graph Convolution for 3D Human Pose Estimation](https://doi.org/10.1145/3474085.3475219) (ACMMM 2021) [[Github](https://github.com/tamasino52/U-CondDGCN)] ![](https://img.shields.io/github/stars/tamasino52/U-CondDGCN.svg?style=social)
    
- [Multi-initialization Optimization Network for Accurate 3D Human Pose and Shape Estimation](https://doi.org/10.1145/3474085.3475355) (ACMMM 2021)   
  
- [Multi-view 3D Smooth Human Pose Estimation based on Heatmap Filtering and Spatio-temporal Information](https://doi.org/10.1145/3474085.3475185) (ACMMM 2021)   

- [Improving Robustness and Accuracy via Relative Information Encoding in 3D Human Pose Estimation](https://doi.org/10.1145/3474085.3475504) (ACMMM 2021) [[Github](https://github.com/paTRICK-swk/Pose3D-RIE)] ![](https://img.shields.io/github/stars/paTRICK-swk/Pose3D-RIE.svg?style=social)

- [Non-local Latent Relation Distillation for Self-Adaptive 3D Human Pose Estimation](https://proceedings.neurips.cc/paper/2021/hash/018b59ce1fd616d874afad0f44ba338d-Abstract.html) (NeurIPS 2021)
    
- [Direct Multi-view Multi-person 3D Pose Estimation](https://proceedings.neurips.cc/paper/2021/hash/6da9003b743b65f4c0ccd295cc484e57-Abstract.html) (NeurIPS 2021) [[Github](https://github.com/sail-sg/mvp)] ![](https://img.shields.io/github/stars/sail-sg/mvp.svg?style=social)   
  

### 2020 (3D Pose Estimation)
  
- [Learning Graph Convolutional Network for Skeleton-based Human Action Recognition by Neural Searching](https://arxiv.org/abs/1911.04131) (Arxiv 2020)
  
- [DeepFuse: An IMU-Aware Network for Real-Time 3D Human Pose Estimation from Multi-View Image](https://arxiv.org/abs/1912.04071) (WACV 2020)
  
- [From Kinematics To Dynamics: Estimating Center of Pressure and Base of Support from Video Frames of Human Motion](https://arxiv.org/abs/2001.00657) (arxiv 2020)
  
- [Synergetic Reconstruction from 2D Pose and 3D Motion for Wide-Space Multi-Person Video Motion Capture in the Wild](https://arxiv.org/abs/2001.05613) (Arxiv 2020) [[Codes](http://www.ynl.t.u-tokyo.ac.jp/research/vmocap-syn/)]
  
- [Deep Reinforcement Learning for Active Human Pose Estimation](https://arxiv.org/abs/2001.02024) (AAAI 2020)
  
- [Deep NRSfM++: Towards 3D Reconstruction in the Wild](https://arxiv.org/abs/2001.10090) (Arxiv 2020)
  
- [Anatomy-aware 3D Human Pose Estimation in Videos](https://arxiv.org/abs/2002.10322) (Arxiv 2020)
  
- [PoseNet3D: Unsupervised 3D Human Shape and Pose Estimation](https://arxiv.org/abs/2003.03473) (Arxiv 2020)
  
- [EllipBody: A Light-weight and Part-based Representation for Human Pose and Shape Recovery](https://arxiv.org/pdf/2003.10873.pdf) (CVPR 2020)
  
- [Weakly-Supervised 3D Human Pose Learning via Multi-view Images in the Wild](https://arxiv.org/abs/2003.07581) (CVPR 2020)
  
- [Fusing Wearable IMUs with Multi-View Images for Human Pose Estimation: A Geometric Approach](https://arxiv.org/abs/2003.11163) (CVPR 2020)
  
- [MetaFuse: A Pre-trained Fusion Model for Human Pose Estimation](https://arxiv.org/abs/2003.13239) (CVPR 2020)
  
- [Optical Non-Line-of-Sight Physics-based 3D Human Pose Estimation](https://arxiv.org/abs/2003.14414)(CVPR 2020)
  
- [Compressed Volumetric Heatmaps for Multi-Person 3D Pose Estimation](https://arxiv.org/abs/2004.00329)(CVPR 2020)
  
- [Bodies at Rest: 3D Human Pose and Shape Estimation from a Pressure Image using Synthetic Data](https://arxiv.org/abs/2004.01166) (CVPR 2020) [[Github](https://github.com/Healthcare-Robotics/bodies-at-rest)] ![](https://img.shields.io/github/stars/Healthcare-Robotics/bodies-at-rest.svg?style=social)
  
- [Lightweight Multi-View 3D Pose Estimation through Camera-Disentangled Representation](https://arxiv.org/abs/2004.02186) (CVPR 2020)
  
- [Multi-Person Absolute 3D Human Pose Estimation with Weak Depth Supervision
](https://arxiv.org/abs/2004.03989) (Arxiv 2020) [[Github](https://github.com/vegesm/wdspose)] ![](https://img.shields.io/github/stars/vegesm/wdspose.svg?style=social)

- [Exemplar Fine-Tuning for 3D Human Pose Fitting Towards In-the-Wild 3D Human Pose Estimation](https://arxiv.org/abs/2004.03686) (Arxiv 2020)
  
- [Self-Supervised 3D Human Pose Estimation via Part Guided Novel Image Synthesis](https://arxiv.org/abs/2004.04400)  (CVPR 2020)
  
- [Multimodal and multiview distillation for real-time player detection on a football field](https://arxiv.org/abs/2004.07544) (CVPRW 2020)
  
- [End-to-End Estimation of Multi-Person 3D Poses from Multiple Cameras](https://arxiv.org/abs/2004.06239) (Arxiv 2020)
  
- [Motion Guided 3D Pose Estimation from Videos](https://arxiv.org/abs/2004.13985) (Arxiv 2020)
  
- [View Invariant Human Body Detection and Pose Estimation from Multiple Depth Sensors](https://arxiv.org/abs/2005.04258)  (Arxiv 2020)
  
- [MEBOW: Monocular Estimation of Body Orientation In the Wild ](http://infolab.stanford.edu/~wangz/project/imsearch/BODY/CVPR20/wu.pdf) (CVPR 2020)
  
- [Epipolar Transformers](https://arxiv.org/abs/2005.04551) (CVPR 2020) [[Github](https://github.com/yihui-he/epipolar-transformers)] ![](https://img.shields.io/github/stars/yihui-he/epipolar-transformers.svg?style=social)
  
- [Cross-View Tracking for Multi-Human 3D Pose Estimation at over 100 FPS](https://arxiv.org/abs/2003.03972) (CVPR 2020)
  
- [Multiview-Consistent Semi-Supervised Learning for 3D Human Pose Estimation](https://arxiv.org/abs/1908.05293) (CVPR 2020)
  
- [Attention Mechanism Exploits Temporal Contexts: Real-Time 3D Human Pose Reconstruction
](http://openaccess.thecvf.com/content_CVPR_2020/html/Liu_Attention_Mechanism_Exploits_Temporal_Contexts_Real-Time_3D_Human_Pose_Reconstruction_CVPR_2020_paper.html) (CVPR 2020) [[Github](https://github.com/lrxjason/Attention3DHumanPose)] ![](https://img.shields.io/github/stars/lrxjason/Attention3DHumanPose.svg?style=social)

- [Cascaded Deep Monocular 3D Human Pose Estimation With Evolutionary Training Data](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_Cascaded_Deep_Monocular_3D_Human_Pose_Estimation_With_Evolutionary_Training_CVPR_2020_paper.html)
 (CVPR 2020)

- [Deep Kinematics Analysis for Monocular 3D Human Pose Estimation](http://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Deep_Kinematics_Analysis_for_Monocular_3D_Human_Pose_Estimation_CVPR_2020_paper.pdf) (CVPR 2020)
  
- [Three-dimensional Reconstruction of Human Interactions](http://openaccess.thecvf.com/content_CVPR_2020/papers/Fieraru_Three-Dimensional_Reconstruction_of_Human_Interactions_CVPR_2020_paper.pdf) (CVPR 2020) [[Codes](http://vision.imar.ro/ci3d/)]
   
- [Coherent Reconstruction of Multiple Humans from a Single Image](http://openaccess.thecvf.com/content_CVPR_2020/papers/Jiang_Coherent_Reconstruction_of_Multiple_Humans_From_a_Single_Image_CVPR_2020_paper.pdf) (CVPR 2020) [[Github](https://github.com/JiangWenPL/multiperson)] ![](https://img.shields.io/github/stars/JiangWenPL/multiperson.svg?style=social)
  
- [Optical Non-Line-of-Sight Physics-based 3D Human Pose Estimation](https://arxiv.org/abs/2003.14414) (CVPR 2020) [[Codes](https://marikoisogawa.github.io/project/nlos_pose)]
  
- [Kinematic-Structure-Preserved Representation for Unsupervised 3D Human Pose Estimation](https://arxiv.org/abs/2006.14107) (AAAI 2020)
  
- [Inference Stage Optimization for Cross-scenario 3D Human Pose Estimation](https://arxiv.org/abs/2007.02054) (Arxiv 2020)
  
- [Predicting Camera Viewpoint Improves Cross-dataset Generalization for 3D Human Pose Estimation](https://arxiv.org/abs/2004.03143) (Arxiv 2020) [[Codes](http://wangzheallen.github.io/cross-dataset-generalization)]



### 2019 (3D Pose Estimation)
  
- [3D Human Pose Machines with Self-supervised Learning](https://arxiv.org/pdf/1901.03798.pdf) (TPAMI 2019) [[Codes](http://www.sysu-hcp.net/3d_pose_ssl/)]
  
- [3D Human Pose Estimation with 2D Marginal Heatmaps](https://arxiv.org/abs/1806.01484) (WACV 2019) [[Github](https://github.com/anibali/margipose)] ![](https://img.shields.io/github/stars/anibali/margipose.svg?style=social)
  
- [Fast and Robust Multi-Person 3D Pose Estimation from Multiple Views](https://arxiv.org/abs/1901.04111) (CVPR 2019) [[Codes](https://zju-3dv.github.io/mvpose)]
  
- [Learning the Depths of Moving People by Watching Frozen People](https://arxiv.org/abs/1904.11111) (CVPR 2019)

- [Monocular Total Capture: Posing Face, Body and Hands in the Wild ](https://arxiv.org/abs/1812.01598) (CVPR 2019) [[Codes](http://domedb.perception.cs.cmu.edu/monototalcapture.html)]
  
- [RepNet: Weakly Supervised Training of an Adversarial Reprojection Network for 3D Human Pose Estimation](https://arxiv.org/abs/1902.09868) (CVPR 2019)
  
- [In the Wild Human Pose Estimation Using Explicit 2D Features and Intermediate 3D Representations](https://arxiv.org/abs/1904.03289) (CVPR 2019)
  
- [Semantic Graph Convolutional Networks for 3D Human Pose Regression](https://arxiv.org/abs/1904.03345) (CVPR 2019) [[Github](https://github.com/garyzhao/SemGCN)] ![](https://img.shields.io/github/stars/garyzhao/SemGCN.svg?style=social)
  
- [ON THE CONTINUITY OF ROTATION REPRESENTATIONS IN NEURAL NETWORKS ](https://arxiv.org/pdf/1812.07035.pdf) (CVPR 2019)
  
- [Self-Supervised Learning of 3D Human Pose using Multi-view Geometry](https://arxiv.org/abs/1903.02330) (CVPR 2019) [[Github](https://github.com/mkocabas/EpipolarPose)] ![](https://img.shields.io/github/stars/mkocabas/EpipolarPose.svg?style=social)
  
- [Generating Multiple Hypotheses for 3D Human Pose Estimation with Mixture Density Network](https://arxiv.org/abs/1904.05547) (CVPR 2019) [[Github](https://github.com/chaneyddtt/Generating-Multiple-Hypotheses-for-3D-Human-Pose-Estimation-with-Mixture-Density-Network)] ![](https://img.shields.io/github/stars/chaneyddtt/Generating-Multiple-Hypotheses-for-3D-Human-Pose-Estimation-with-Mixture-Density-Network.svg?style=social)
  
- [Neural Scene Decomposition for Multi-Person Motion Capture](https://arxiv.org/abs/1903.05684) (CVPR 2019)
  
- [Weakly-Supervised Discovery of Geometry-Aware Representationfor 3D Human Pose Estimation](https://128.84.21.199/pdf/1903.08839.pdf) (CVPR 2019)
  
- [IGE-Net: Inverse Graphics Energy Networksfor Human Pose Estimation and Single-View Reconstruction](http://openaccess.thecvf.com/content_CVPR_2019/papers/Jack_IGE-Net_Inverse_Graphics_Energy_Networks_for_Human_Pose_Estimation_and_CVPR_2019_paper.pdf) (CVPR 2019)
  
- [Monocular 3D Human Pose Estimation by Generation and Ordinal Ranking](https://arxiv.org/abs/1904.01324) (Arxiv 2019) [[Github](https://github.com/ssfootball04/generative_pose)] ![](https://img.shields.io/github/stars/ssfootball04/generative_pose.svg?style=social)
  
- [Estimating 3D Motion and Forces of Person-Object Interactions from Monocular Video](https://arxiv.org/abs/1904.02683) (Arxiv 2019)
  
- [Context-aware Human Motion Prediction](https://arxiv.org/abs/1904.03419) (Arxiv 2019)
  
- [Unsupervised 3D Pose Estimation with Geometric Self-Supervision](https://arxiv.org/abs/1904.04812)(Arxiv 2019)
  
- [Generalizing Monocular 3D Human Pose Estimation in the Wild](https://arxiv.org/abs/1904.05512) (Arxiv 2019) [[Github](https://github.com/llcshappy/Monocular-3D-Human-Pose)] ![](https://img.shields.io/github/stars/llcshappy/Monocular-3D-Human-Pose.svg?style=social)
  
- [Absolute Human Pose Estimation with Depth Prediction Network](https://arxiv.org/abs/1904.05947) (IJCNN 2019)
  
- [You2Me: Inferring Body Pose in Egocentric Video via First and Second Person Interactions](https://arxiv.org/abs/1904.09882) (Arxiv 2019) [[Codes](http://vision.cs.utexas.edu/projects/you2me/)]
  
- [Learnable Triangulation of Human Pose](https://arxiv.org/abs/1905.05754) (ICCV 2019) [[Codes](https://saic-violet.github.io/learnable-triangulation/)]
  
- [Not All Parts Are Created Equal: 3D Pose Estimation by Modelling Bi-directional Dependencies of Body Parts](https://arxiv.org/abs/1905.07862) (Arxiv 2019)
  
- [Feature Boosting Network For 3D Pose Estimation](https://arxiv.org/abs/1901.04877) (TPAMI 2019)

- [Ego-Pose Estimation and Forecasting as Real-Time PD Control](https://arxiv.org/abs/1906.03173) (ICCV 2019) [[Codes](https://www.ye-yuan.com/ego-pose/)]
  
- [Understanding Human Context in 3D Scenes by Learning Spatial Affordances with Virtual Skeleton Models](https://arxiv.org/abs/1906.05498) (Arxiv 2019)

- [XNect: Real-time Multi-person 3D Human Pose Estimation with a Single RGB Camera](https://arxiv.org/abs/1907.00837) (Arxiv 2019) [[Github](https://github.com/mehtadushy/SelecSLS-Pytorch)] ![](https://img.shields.io/github/stars/mehtadushy/SelecSLS-Pytorch.svg?style=social)

- [Camera Distance-aware Top-down Approach for 3D Multi-person Pose Estimation from a Single RGB Image](https://arxiv.org/abs/1907.11346) (ICCV 2019) [[Github](https://github.com/mks0601/3DMPPE_ROOTNET_RELEASE)] ![](https://img.shields.io/github/stars/mks0601/3DMPPE_ROOTNET_RELEASE.svg?style=social)
 
- [xR-EgoPose: Egocentric 3D Human Pose from an HMD Camera](https://arxiv.org/abs/1907.10045) (ICCV 2019) [[Github](https://github.com/facebookresearch/xR-EgoPose)] ![](https://img.shields.io/github/stars/facebookresearch/xR-EgoPose.svg?style=social)
  
- [Semantic Estimation of 3D Body Shape and Pose using Minimal Cameras](https://arxiv.org/abs/1908.03030) (Arxiv 2019)
  
- [Resolving 3D Human Pose Ambiguities with 3D Scene Constraints](https://arxiv.org/abs/1908.06963) (ICCV 2019) [[Data]](https://prox.is.tue.mpg.de/) [[Github](https://github.com/MohameHassan/prox)] ![](https://img.shields.io/github/stars/MohameHassan/prox.svg?style=social)
  
- [Distill Knowledge from NRSfM for Weakly Supervised 3D Pose Learning](https://arxiv.org/abs/1908.06377) (ICCV 2019)
  
- [Single-Stage Multi-Person Pose Machines](https://arxiv.org/abs/1908.09220) (ICCV 2019)
  
- [A2J: Anchor-to-Joint Regression Network for 3D Articulated Pose Estimation from a Single Depth Image](https://arxiv.org/abs/1908.09999) (ICCV 2019) [[Github](https://github.com/zhangboshen/A2J)] ![](https://img.shields.io/github/stars/zhangboshen/A2J.svg?style=social)
  
- [Cross View Fusion for 3D Human Pose Estimation](https://chunyuwang.netlify.com/img/ICCV_Cross_view_camera_ready.pdf) (ICCV 2019) [[Github](https://github.com/microsoft/multiview-human-pose-estimation-pytorch)] ![](https://img.shields.io/github/stars/microsoft/multiview-human-pose-estimation-pytorch.svg?style=social)
  
- [Optimizing Network Structure for 3D Human Pose Estimation](https://chunyuwang.netlify.com/) (ICCV 2019)
  
- [Motion Capture from Pan-Tilt Cameras with Unknown Orientation](https://arxiv.org/pdf/1908.11676.pdf) (3DV 2019)
  
- [C3DPO: Canonical 3D Pose Networks for Non-Rigid Structure From Motion](https://arxiv.org/abs/1909.02533) (ICCV 2019)
  
- [MonoLoco: Monocular 3D Pedestrian Localization and Uncertainty Estimation](https://arxiv.org/abs/1906.06059) (ICCV 2019) [[Github](https://github.com/vita-epfl/monoloco)] ![](https://img.shields.io/github/stars/vita-epfl/monoloco.svg?style=social)
  
- [Multi-Person 3D Human Pose Estimation from Monocular Images](https://arxiv.org/abs/1909.10854) (3DV 2019)
  
- [Human Synthesis and Scene Compositing](https://arxiv.org/abs/1909.10307) (Arxiv 2019)
  
- [MocapNET: Ensemble of SNN Encoders for 3D Human Pose Estimation in RGB Images](http://users.ics.forth.gr/~argyros/mypapers/2019_09_BMVC_mocapnet.pdf) (BMVC 2019) [[Github](https://github.com/FORTH-ModelBasedTracker/MocapNET)] ![](https://img.shields.io/github/stars/FORTH-ModelBasedTracker/MocapNET.svg?style=social)
  
- [Adversarial Attack on Skeleton-based HumanAction Recognition](https://arxiv.org/pdf/1909.06500.pdf)  (Arxiv 2019)
  
- [Learning to Reconstruct 3D Human Pose and Shape via Model-fitting in the Loop](https://arxiv.org/abs/1909.12828)  (ICCV 2019) [[Codes](https://www.seas.upenn.edu/~nkolot/projects/spin/)]
  
- [DenseRaC: Joint 3D Pose and Shape Estimation by Dense Render-and-Compare](https://arxiv.org/abs/1910.00116) (ICCV 2019)
  
- [Chirality Nets for Human Pose Regression](https://arxiv.org/abs/1911.00029) (NeurIPS 2019)
  
- [A Neural Network for Detailed Human Depth Estimation from a Single Image](https://arxiv.org/abs/1910.01275) (ICCV 2019)
  
- [HEMlets Pose: Learning Part-Centric Heatmap Triplets for Accurate 3D Human Pose Estimation](https://arxiv.org/abs/1910.01275) (ICCV 2019)
  
- [Convex Optimisation for Inverse Kinematics](https://arxiv.org/abs/1910.11016) (Arxiv 2019)
  
- [AbsPoseLifter: Absolute 3D Human Pose Lifting Network from a Single Noisy 2D Human Pose](https://arxiv.org/abs/1910.12029) (Arxiv 2019)
  
- [SMART: Skeletal Motion Action Recognition aTtack](https://arxiv.org/abs/1911.07107) (Arxiv 2019)
  
- [Markerless Outdoor Human Motion Capture Using Multiple Autonomous Micro Aerial Vehicles](http://openaccess.thecvf.com/content_ICCV_2019/papers/Saini_Markerless_Outdoor_Human_Motion_Capture_Using_Multiple_Autonomous_Micro_Aerial_ICCV_2019_paper.pdf) (ICCV 2019) [[Github](https://github.com/robot-perception-group/Aircap_Pose_Estimator)] ![](https://img.shields.io/github/stars/robot-perception-group/Aircap_Pose_Estimator.svg?style=social)
  
- [Exploiting Spatial-temporal Relationships for 3D Pose Estimation via Graph Convolutional Networks](https://cse.buffalo.edu/~jsyuan/papers/2019/Exploiting_Spatialtemporal_Relationships_for_3D_Pose_Estimation_via_Graph_Convolutional_Networks.pdf) (ICCV 2019)
  
- [Occlusion-Aware Networks for 3D Human Pose Estimation in Video](http://openaccess.thecvf.com/content_ICCV_2019/papers/Cheng_OcclusionAware_Networks_for_3D_Human_Pose_Estimation_in_Video_ICCV_2019_paper.pdf) (ICCV 2019)
  
- [On Boosting Single-Frame 3D Human Pose Estimation via Monocular Videos](http://openaccess.thecvf.com/content_ICCV_2019/papers/Li_On_Boosting_SingleFrame_3D_Human_Pose_Estimation_via_Monocular_Videos_ICCV_2019_paper.pdf) (ICCV 2019)
  
- [Monocular 3D Human Pose Estimation by Generation and Ordinal Ranking](https://arxiv.org/abs/1904.01324) (ICCV 2019) [[Github](https://github.com/ssfootball04/generative_pose)] ![](https://img.shields.io/github/stars/ssfootball04/generative_pose.svg?style=social)
  
- [Consensus-based Optimization for 3D Human Pose Estimation in Camera Coordinates](https://arxiv.org/abs/1911.09245) (Arxiv 2019)
  
- [Domes to Drones: Self-Supervised Active Triangulation for 3D Human Pose Reconstruction](https://arxiv.org/abs/1912.02923) (NeurIPS 2019)

- [Generating 3D People in Scenes without People](https://arxiv.org/abs/1912.02923) (Arxiv 2019)
  
- [ActiveMoCap: Optimized Drone Flight for Active Human Motion Capture](https://arxiv.org/abs/1912.08568) (Arxiv 2019)
 
- [Geometric Pose Affordance: 3D Human Pose with Scene Constraints](https://arxiv.org/abs/1905.07718) - [[Page]](http://wangzheallen.github.io/GPA) (Arxiv 2019)
  

### 2018 (3D Pose Estimation)
- [3D Human Pose Estimation in the Wild by Adversarial Learning](https://arxiv.org/pdf/1803.09722.pdf) (CVPR 2018)
  
- [Ordinal Depth Supervision for 3D Human Pose Estimation](https://arxiv.org/pdf/1805.04095.pdf) (CVPR 2018) [[Github](https://github.com/geopavlakos/ordinal-pose3d)] ![](https://img.shields.io/github/stars/geopavlakos/ordinal-pose3d.svg?style=social)
  
- [V2V-PoseNet: Voxel-to-Voxel Prediction Network for Accurate 3D Hand and Human Pose Estimation From a Single Depth Map](https://arxiv.org/abs/1711.07399) (CVPR 2018) [[Github](https://github.com/mks0601/V2V-PoseNet_RELEASE)] ![](https://img.shields.io/github/stars/mks0601/V2V-PoseNet_RELEASE.svg?style=social)
  
- [DRPose3D: Depth Ranking in 3D Human Pose Estimation](https://arxiv.org/pdf/1805.08973.pdf) (IJCAI 2018)
  
- [Human Motion Capture Using a Drone](https://arxiv.org/abs/1804.06112) (ICRA 2018)
- 
- [End-to-end Recovery of Human Shape and Pose](https://arxiv.org/pdf/1712.06584.pdf) (CVPR 2018) [[Github](https://github.com/akanazawa/hmr)] ![](https://img.shields.io/github/stars/akanazawa/hmr.svg?style=social)
  
- [Learning to Estimate 3D Human Pose and Shape from a Single Color Image](http://openaccess.thecvf.com/content_cvpr_2018/papers/Pavlakos_Learning_to_Estimate_CVPR_2018_paper.pdf) (CVPR 2018)
  
- [Monocular 3D Pose and Shape Estimation of Multiple People in Natural Scenes](http://www.maths.lth.se/sminchisescu/media/papers/Zanfir_Monocular_3D_Pose_CVPR_2018_paper.pdf) (CVPR 2018)
  
- [Dense Human Pose Estimation In The Wild](https://arxiv.org/pdf/1802.00434.pdf) (CVPR 2018) [[Github](https://github.com/facebookresearch/Densepose)] ![](https://img.shields.io/github/stars/facebookresearch/Densepose.svg?style=social)
  
- [Learning Monocular 3D Human Pose Estimation from Multi-View Images](https://arxiv.org/pdf/1803.04775.pdf) (CVPR 2018)
  
- [3D Human Sensing, Action and Emotion Recognition inRobot Assisted Therapy of Children with Autism](http://www.maths.lth.se/sminchisescu/media/papers/Marinoiu_3D_Human_Sensing_CVPR_2018_paper.pdf) (CVPR 2018)
  
- [Neural Body Fitting: Unifying Deep Learning and Model-Based Human Pose and Shape Estimation](https://arxiv.org/pdf/1808.05942.pdf) (3DV 2018) [[Github](https://github.com/mohomran/neural_body_fitting)] ![](https://img.shields.io/github/stars/mohomran/neural_body_fitting.svg?style=social)
  
- [Learning 3D Human Pose from Structure and Motion](http://openaccess.thecvf.com/content_ECCV_2018/papers/Rishabh_Dabral_Learning_3D_Human_ECCV_2018_paper.pdf) (ECCV 2018)
  
- [Unsupervised Learning of View-invariant Action Representations](http://papers.nips.cc/paper/7401-unsupervised-learning-of-view-invariant-action-representations.pdf) (NeurIPS 2018)
  
- [Deep Network for the Integrated 3D Sensing ofMultiple People in Natural Images](http://www.maths.lth.se/sminchisescu/media/papers/integrated-3d-sensing-of-multiple-people-in-natural-images_neurips2018.pdf) (NeurIPS 2018)
  
- [Integral Human Pose Regression](https://arxiv.org/pdf/1711.08229.pdf) (ECCV 2018) [[Github](https://github.com/JimmySuen/integral-human-pose)] ![](https://img.shields.io/github/stars/JimmySuen/integral-human-pose.svg?style=social)
  
- [Dense Pose Transfer](https://arxiv.org/pdf/1809.01995.pdf) (ECCV 2018)
  
- [Deformable Pose Traversal Convolutionfor 3D Action and Gesture Recognition](http://openaccess.thecvf.com/content_ECCV_2018/papers/Junwu_Weng_Deformable_Pose_Traversal_ECCV_2018_paper.pdf) (ECCV 2018)
  
- [Deep Autoencoder for Combined Human Pose Estimation and Body Model Upscaling](https://cvssp.org/projects/totalcapture/ECCV1UpscalePoseAutoencoder//FinalPaper.pdf) (ECCV 2018)
  
- [Unsupervised Geometry-Aware Representation for 3D Human Pose Estimation](http://openaccess.thecvf.com/content_ECCV_2018/papers/Helge_Rhodin_Unsupervised_Geometry-Aware_Representation_ECCV_2018_paper.pdf) (ECCV 2018) [[Github](https://github.com/hrhodin/UnsupervisedGeometryAwareRepresentationLearning)] ![](https://img.shields.io/github/stars/hrhodin/UnsupervisedGeometryAwareRepresentationLearning.svg?style=social)
  
- [Monocap: Monocular human motion capture using a CNN coupled with a geometric prior](https://arxiv.org/abs/1701.02354) (TPAMI 2018) [[Github](https://github.com/daniilidis-group/monocap)] ![](https://img.shields.io/github/stars/daniilidis-group/monocap.svg?style=social)
  
- [Single-Shot Multi-Person 3D Pose Estimation From Monocular RGB](https://arxiv.org/pdf/1712.03453.pdf) (3DV 2018) [[Github](https://github.com/Daniil-Osokin/lightweight-human-pose-estimation-3d-demo.pytorch)] ![](https://img.shields.io/github/stars/Daniil-Osokin/lightweight-human-pose-estimation-3d-demo.pytorch.svg?style=social)
  
- [HUMBI 1.0: HUman Multiview Behavioral Imaging Dataset](https://arxiv.org/pdf/1812.00281.pdf) (Arxiv 2018)
  
- [Explicit Pose Deformation Learning for Tracking Human Poses](https://arxiv.org/abs/1811.07123) (Arxiv 2018)
  
    
- [MONET: Multiview Semi-supervised Keypoint via Epipolar Divergence](https://arxiv.org/abs/1806.00104)  (Arxiv 2018)

- [Video Motion Capture from the Part Confidence Maps of Multi-Camera Images by Spatiotemporal Filtering Using the Human Skeletal Model](https://arxiv.org/abs/1912.03880) (IROS 2018)
  
  

### 2017 (3D Pose Estimation)
- [VNect: Real-time 3D Human Pose Estimation with a Single RGB Camera](http://gvv.mpi-inf.mpg.de/projects/VNect/content/VNect_SIGGRAPH2017.pdf) (SIGGRAPH 2017) [[Github](https://github.com/timctho/VNect-tensorflow)] ![](https://img.shields.io/github/stars/timctho/VNect-tensorflow.svg?style=social)
  
- [Recurrent 3D Pose Sequence Machines](https://arxiv.org/pdf/1707.09695.pdf) (CVPR 2017)
  
- [Lifting from the Deep: Convolutional 3D Pose Estimation from a Single Image](https://arxiv.org/pdf/1701.00295.pdf) (CVPR 2017)
  
- [3D Human Pose Estimation from a Single Image via Distance Matrix Regression](https://arxiv.org/abs/1611.09010) (CVPR 2017)
  
- [3D Human Pose Estimation = 2D Pose Estimation + Matching](https://arxiv.org/pdf/1612.06524.pdf) (CVPR 2017) [[Github](https://github.com/flyawaychase/3DHumanPose)] ![](https://img.shields.io/github/stars/flyawaychase/3DHumanPose.svg?style=social)
  
- [Coarse-to-Fine Volumetric Prediction for Single-Image 3D Human Pose](https://arxiv.org/pdf/1611.07828.pdf) (CVPR 2017) [[Github](https://github.com/geopavlakos/c2f-vol-demo)] ![](https://img.shields.io/github/stars/geopavlakos/c2f-vol-demo.svg?style=social)
  
  
- [LCR-Net: Localization-Classification-Regression for Human Pose](https://www.researchgate.net/publication/315867122_LCR-Net_Localization-Classification-Regression_for_Human_Pose) (CVPR 2017) [[Codes](https://thoth.inrialpes.fr/src/LCR-Net/)]
  
- [Deep Learning on Lie Groups for Skeleton-based Action Recognition](https://github.com/zzhiwu/LieNet) (CVPR 2017) [[Github](https://github.com/zzhiwu/LieNet)] ![](https://img.shields.io/github/stars/zzhiwu/LieNet.svg?style=social)
  
- [Seeing invisible poses: Estimating3d body pose from egocentric video.](https://arxiv.org/abs/1603.07763) (CVPR 2017)
  
- [Harvesting Multiple Views for Marker-less 3D Human Pose Annotations](https://www.seas.upenn.edu/~pavlakos/projects/harvesting/files/harvesting.pdf) (CVPR 2017) [[Github](https://github.com/geopavlakos/harvesting)] ![](https://img.shields.io/github/stars/geopavlakos/harvesting.svg?style=social)
  
- [Towards 3D Human Pose Estimation in the Wild: a Weakly-supervised Approach](https://arxiv.org/pdf/1704.02447.pdf) (ICCV 2017) [[Github](https://github.com/xingyizhou/Pytorch-pose-hg-3d)] ![](https://img.shields.io/github/stars/xingyizhou/Pytorch-pose-hg-3d.svg?style=social)
  

- [Adversarial Inverse Graphics Networks: Learning 2D-to-3D Lifting and Image-to-Image Translation from Unpaired Supervision](https://arxiv.org/abs/1705.11166) (ICCV 2017)
  
- [A Simple Yet Effective Baseline for 3d Human Pose Estimation](https://arxiv.org/pdf/1705.03098.pdf) (ICCV 2017) [[Github](https://github.com/xingyizhou/weigq/3d_pose_baseline_pytorc)] ![](https://img.shields.io/github/stars/weigq/3d_pose_baseline_pytorch.svg?style=social)
  
- [Sparse Representation for 3D Shape Estimation: A Convex Relaxation Approach](http://arxiv.org/abs/1509.04309) (TPAMI 2017) [[Codes](http://www.cad.zju.edu.cn/home/xzhou/code/shapeconvex.zip)]
  
- [Compositional Human Pose Regression](https://arxiv.org/pdf/1704.00159.pdf) (ICCV 2017)
  
- [Monocular 3D Human Pose Estimation In The Wild Using Improved CNN Supervision](http://gvv.mpi-inf.mpg.de/3dhp-dataset/) (3DV 2017)
  

### Before 2017 (3D Pose Estimation)
- [Reconstruction of Articulated Objects from Point Correspondences in a Single Uncalibrated Image](https://pdfs.semanticscholar.org/4034/943de699dd4d672d3d59b408459168785e9c.pdf) (CVIU 2000)

- [Covariance-Scaled Sampling for Monocular 3D Body Tracking](http://www.maths.lth.se/sminchisescu/media/papers/css_cvpr01.pdf) (CVPR 2001)
  
- [Improving the Scope of Deformable Model Shape and Motion Estimation](http://www.maths.lth.se/sminchisescu/media/papers/deform_cvpr01.pdf) (CVPR 2001)
  
- [Recovering 3D Human Posefrom Monocular Images](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/agarwal-triggs-pami06.pdf) (TPAMI 2006)
  
- [3D Human Pose Estimation from Monocular Images with Deep Convolutional Neural Network](http://visal.cs.cityu.edu.hk/static/pubs/conf/accv14-3dposecnn.pdf)  (ACCV 2014)
  
- [3D Pictorial Structures for Multiple Human Pose Estimation](http://campar.in.tum.de/pub/belagiannis2014cvpr/belagiannis2014cvpr.pdf) (CVPR 2014)
  
- [3D Human pose estimation: A review of the literature and analysis of covariates](http://cbl.uh.edu/pub_files/nsarafianos_CVIU.pdf) (CVIU 2016)
  
- [Sparseness Meets Deepness: 3D Human Pose Estimation from Monocular Video](http://arxiv.org/abs/1511.09439) (CVPR 2016)  [[Github](https://github.com/daniilidis-group/monocap)] ![](https://img.shields.io/github/stars/daniilidis-group/monocap.svg?style=social)
  
- [Structured Prediction of 3D Human Pose with Deep Neural Networks](https://arxiv.org/pdf/1605.05180.pdf) (BMVC 2016)
  


### Real-Time 3D Pose Estimation
 - [Realtime Multi-person 2D Pose Estimation Using Part Affinity Fields](https://arxiv.org/pdf/1611.08050.pdf) (CVPR 2017) [[Github](https://github.com/ZheC/Realtime_Multi-Person_Pose_Estimation)] ![](https://img.shields.io/github/stars/ZheC/Realtime_Multi-Person_Pose_Estimation.svg?style=social)
  
- [VNect: Real-time 3D Human Pose Estimation with a Single RGB Camera](http://gvv.mpi-inf.mpg.de/projects/VNect/content/VNect_SIGGRAPH2017.pdf) (SIGGRAPH 2017) [[Github](https://github.com/timctho/VNect-tensorflow)] ![](https://img.shields.io/github/stars/timctho/VNect-tensorflow.svg?style=social)
  
- [RMPE: Regional Multi-person Pose Estimation](https://arxiv.org/pdf/1612.00137.pdf) (ICCV 2017) [[Github](https://github.com/Fang-Haoshu/RMPE)] ![](https://img.shields.io/github/stars/Fang-Haoshu/RMPE.svg?style=social)


- [VNect: Real-time 3D Human Pose Estimation with a Single RGB Camera](http://gvv.mpi-inf.mpg.de/projects/VNect/content/VNect_SIGGRAPH2017.pdf) (SIGGRAPH 2017) [[Github](https://github.com/timctho/VNect-tensorflow)] ![](https://img.shields.io/github/stars/timctho/VNect-tensorflow.svg?style=social)
  
- [Dense Human Pose Estimation In The Wild](https://arxiv.org/pdf/1802.00434.pdf) (ArXiv 2018) [[Github](https://github.com/facebookresearch/Densepose)] ![](https://img.shields.io/github/stars/facebookresearch/Densepose.svg?style=social)
  
- [Real-time 2D Multi-Person Pose Estimation on CPU: Lightweight OpenPose](https://arxiv.org/pdf/1811.12004.pdf) (ArXiv 2018) [[Github](https://github.com/Daniil-Osokin/lightweight-human-pose-estimation.pytorch)] ![](https://img.shields.io/github/stars/Daniil-Osokin/lightweight-human-pose-estimation.pytorch.svg?style=social)
  - Extension to 3D pose estimation (based on [Single-Shot Multi-Person 3D Pose Estimation From Monocular RGB](https://arxiv.org/pdf/1712.03453.pdf) - Mehta, D., et al.) [[Github](https://github.com/Daniil-Osokin/lightweight-human-pose-estimation-3d-demo.pytorch)] ![](https://img.shields.io/github/stars/Daniil-Osokin/lightweight-human-pose-estimation-3d-demo.pytorch.svg?style=social)

- [XNect: Real-time Multi-person 3D Human Pose Estimation with a Single RGB Camera](https://arxiv.org/abs/1907.00837) (Arxiv 2019) [[Github](https://github.com/mehtadushy/SelecSLS-Pytorch)] ![](https://img.shields.io/github/stars/mehtadushy/SelecSLS-Pytorch.svg?style=social)

- [DeepFuse: An IMU-Aware Network for Real-Time 3D Human Pose Estimation from Multi-View Image](https://arxiv.org/abs/1912.04071) (WACV 2020)

- [Multimodal and multiview distillation for real-time player detection on a football field](https://arxiv.org/abs/2004.07544) (CVPRW 2020)

- [Attention Mechanism Exploits Temporal Contexts: Real-Time 3D Human Pose Reconstruction
](http://openaccess.thecvf.com/content_CVPR_2020/html/Liu_Attention_Mechanism_Exploits_Temporal_Contexts_Real-Time_3D_Human_Pose_Reconstruction_CVPR_2020_paper.html) (CVPR 2020) [[Github](https://github.com/lrxjason/Attention3DHumanPose)] ![](https://img.shields.io/github/stars/lrxjason/Attention3DHumanPose.svg?style=social)

- [Multi-Task Deep Learning for Real-Time 3D Human Pose Estimation and Action Recognition](https://arxiv.org/pdf/1803.09722.pdf) (TPAMI 2021)

- [TransPose: real-time 3D human translation and pose estimation with six inertial sensors](https://doi.org/10.1145/3450626.3459786) (ACM Trans. Graph. 2021)  [[Github](https://github.com/Xinyu-Yi/TransPose)] ![](https://img.shields.io/github/stars/Xinyu-Yi/TransPose.svg?style=social)

- [EventHands: Real-Time Neural 3D Hand Pose Estimation from an Event Stream](https://doi.org/10.1109/ICCV48922.2021.01216) (ICCV 2021) [[Github](https://github.com/r00tman/EventHands)] ![](https://img.shields.io/github/stars/r00tman/EventHands.svg?style=social)

### Leaderboards (3D Pose Estimation)
- [Human3.6M](https://paperswithcode.com/sota/3d-human-pose-estimation-on-human36m)
- [Human3.6M2](https://paperswithcode.com/task/3d-human-pose-estimation)
- [MuPoTS-3D](https://paperswithcode.com/sota/3d-multi-person-pose-estimation-absolute-on?p=camera-distance-aware-top-down-approach-for-1
)
- [MuPoTS-3D2](https://paperswithcode.com/sota/3d-multi-person-pose-estimation-root-relative?p=camera-distance-aware-top-down-approach-for-1
)
- [GPA(Geometric Pose Affordance dataset)](https://paperswithcode.com/sota/3d-human-pose-estimation-on-geometric-pose)

## Skeleton-Based Person Re-Identification (S-reID)
### Popular Datasets

### 2022 (S-reID)

### 2021 (S-reID)

### 2020 (S-reID)

### 2019 (S-reID)

### 2018 (S-reIDn)

### 2017 (S-reID)

### Before 2017 (S-reID)

### Leaderboards on 



<!-- ## Skeleton-Based Person Re-Identification (S-reID)
### Popular Datasets

### 2022 (S-reID)

### 2021 (S-reID)

### 2020 (S-reID)

### 2019 (S-reID)

### 2018 (S-reIDn)

### 2017 (S-reID)

### Before 2017 (S-reID)

### Leaderboards on  -->

## Acknowledge

Thanks for the awesome repositories from [Niais](https://github.com/niais/Awesome-Skeleton-based-Action-Recognition), [Wangzheallen](https://github.com/wangzheallen/awesome-human-pose-estimation) etc. 

I will appreacite much if you help re-organize and refine current taxonomy (e.g., add more works related to 3D skeletons) and archive uncategoried papers or anything to enrich this repository. 

If you have any problems, suggestions or improvements, please feel free to contact me (haocong001@ntu.edu.sg). Welcome to discuss together.
