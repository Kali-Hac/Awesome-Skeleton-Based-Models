<!-- vscode-markdown-toc -->
- [Skeleton-Based Action Recognition](#skeleton-based-action-recognition)
	- [**70** Datasets](#70-datasets)
		- [Popular & New](#popular--new)
		- [Overview](#overview)
	- [Survey Papers](#survey-papers)
	- [**2022**](#2022)
	- [**2021**](#2021)
	- [**2020**](#2020)
	- [**2019**](#2019)
	- [**2018**](#2018)
	- [**2017**](#2017)
	- [Before 2017](#before-2017)
	- [arXiv papers](#arxiv-papers)
	- [Skeleton-based Action Recognition under Adversarial Attack](#skeleton-based-action-recognition-under-adversarial-attack)
	- [Leaderboards on NTU-RGB+D and NTU-RGB+D 120 Datasets](#leaderboards-on-ntu-rgbd-and-ntu-rgbd-120-datasets)
		- [NTU-RGB+D](#ntu-rgbd)
		- [NTU-RGB+D 120](#ntu-rgbd-120)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->




##  Skeleton-Based Action Recognition
###  **70** Datasets
#### Popular & New
- *(New! 2021)* **PoseC3D 2D Skeleton Dataset (FineGYM, NTURGB-D, Kinetics, Volleyball)** [[arxiv](https://arxiv.org/pdf/2104.13586.pdf), [Github](https://github.com/open-mmlab/mmaction2/tree/master/tools/data/skeleton)] ![](https://img.shields.io/github/stars/open-mmlab/mmaction2.svg?style=social)
- *(New! 2021)* **NTU60-X Dataset** [[arxiv](https://arxiv.org/pdf/2101.11529.pdf), [Github](https://github.com/skelemoa/ntu-x)] ![](https://img.shields.io/github/stars/skelemoa/ntu-x.svg?style=social)
- *(2019)* **NTU RGB+D 120 Dataset** [[Homepage](https://rose1.ntu.edu.sg/dataset/actionRecognition/),[Github](https://github.com/shahroudy/NTURGB-D)] ![](https://img.shields.io/github/stars/shahroudy/NTURGB-D.svg?style=social)
- NTU RGB+D Dataset [[Homepage](https://rose1.ntu.edu.sg/dataset/actionRecognition/),[Github](https://github.com/shahroudy/NTURGB-D)] ![](https://img.shields.io/github/stars/shahroudy/NTURGB-D.svg?style=social)
- (2018) VARYING-VIEW RGB-D ACTION DATASET [[arxiv](https://arxiv.org/pdf/1904.10681.pdf), [Github](https://github.com/HRI-UESTC/CFM-HRI-RGB-D-action-database)] ![](https://img.shields.io/github/stars/HRI-UESTC/CFM-HRI-RGB-D-action-database.svg?style=social)
- (2017) SYSU 3D Human-Object Interaction Dataset (**SYSU**)
- (2015) UWA3D Multiview Activity II Dataset (**UWA3D**) [[download](http://staffhome.ecm.uwa.edu.au/~00053650/databases.html)]
- (2014) Northwestern-UCLA Dataset (**N-UCLA**) [[donwload](https://users.eecs.northwestern.edu/~jwa368/my_data.html)]
<!-- - SBU Kinect Interaction Dataset (**SBU**) -->

#### Overview
Overview of **70** available datasets (2004-2022) for **action recognition** and their statistics, provided by the paper of (**TPAMI 2022**) [[arxiv](https://arxiv.org/abs/2012.11866)] (Human Action Recognition from Various Data Modalities: A Review). 

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
|  **37**  | [**NTU RGB+D**](https://rose1.ntu.edu.sg/dataset/actionRecognition/)          | **2016** |     **RGB,S,D,IR** |      **60** |        **40** |   **56,880** |             **80** |
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
|  **58**  | [**NTU RGB+D 120**](https://rose1.ntu.edu.sg/dataset/actionRecognition/)      | **2019** |     **RGB,S,D,IR** |     **120** |       **106** |  **114,480** |            **155** |
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



###  Survey Papers
- Human Action Recognition and Prediction: A Survey Recognition Algorithms (**IJCV 2022**) [[paper](https://doi.org/10.1007/s11263-022-01594-9)]

- Human Action Recognition from Various Data Modalities: A Review (**TPAMI 2022**) [[arxiv](https://arxiv.org/abs/2012.11866)]

- A Comparative Review of Recent Kinect-based Action Recognition Algorithms (**TIP 2019**) [[arxiv](https://arxiv.org/pdf/1906.09955.pdf)]


### **2022**
- Constructing Stronger and Faster Baselines for Skeleton-based Action Recognition (**TPAMI 2022**) [[paper](https://arxiv.org/pdf/2106.15125.pdf)] [[Github](https://github.com/yfsong0709/EfficientGCNv1)] ![](https://img.shields.io/github/stars/yfsong0709/EfficientGCNv1.svg?style=social) (Not uploaded) [[Gitee](https://gitee.com/yfsong0709/EfficientGCNv1)]

- **[Sym-GNN]** Symbiotic Graph Neural Networks for 3D Skeleton-Based Human Action Recognition and Motion Prediction (**TPAMI 2022**) [[paper](https://ieeexplore.ieee.org/document/9334430)] [[Github](https://github.com/LevelCA/Sym-GNN)] ![](https://img.shields.io/github/stars/LevelCA/Sym-GNN.svg?style=social) (Not uploaded)

- **[X-CAR]** X-Invariant Contrastive Augmentation and Representation Learning for Semi-Supervised Skeleton-Based Action Recognition (**TIP 2022**) [[paper](https://doi.org/10.1109/TIP.2022.3175605)]

- **[FGCN]** Feedback Graph Convolutional Network for Skeleton-Based Action Recognition (**TIP 2022**) [[paper](https://doi.org/10.1109/TIP.2021.3129117)]

- **[Multi-LiSAAL]** Multi-Localized Sensitive Autoencoder-Attention-LSTM For Skeleton-based Action Recognition (**TMM 2022**) [[paper](https://doi.org/10.1109/TMM.2021.3070127)]

- **[LAGA-Net]** LAGA-Net: Local-and-Global Attention Network for Skeleton Based Action Recognition (**TMM 2022**) [[paper](https://doi.org/10.1109/TMM.2021.3070127)]

- **[CIASA]** Adversarial Attack on Skeleton-Based Human Action Recognition (**TNNLS 2022**) [[paper](https://doi.org/10.1109/TNNLS.2020.3043002)]

- **[MTT]** MTT: Multi-Scale Temporal Transformer for Skeleton-Based Action Recognition (**IEEE Signal Process. Lett. 2022**) [[paper](https://doi.org/10.1109/LSP.2022.3142675)]

- **[Graph2Net]** Graph2Net: Perceptually-Enriched Graph Learning for Skeleton-Based Action Recognition (**IEEE Trans. Circuits Syst. Video Technol. 2022**) [[paper](https://doi.org/10.1109/TCSVT.2021.3085959)] [[Github](https://github.com/cong-wu/Graph2Net)] ![](https://img.shields.io/github/stars/cong-wu/Graph2Net.svg?style=social)


- A Cross View Learning Approach for Skeleton-Based Action Recognition (**IEEE Trans. Circuits Syst. Video Technol. 2022**) [[paper](https://doi.org/10.1109/TCSVT.2021.3100128)]

- Learning from Temporal Spatial Cubism for Cross-Dataset Skeleton-based Action Recognition (**ACM Trans. Multim. Comput. Commun. Appl. 2022**) [[paper](https://doi.org/10.1145/3472722)] [[Github](https://github.com/shanice-l/st-cubism)] ![](https://img.shields.io/github/stars/shanice-l/st-cubism.svg?style=social)

- Skeleton Sequence and RGB Frame Based Multi-Modality Feature Fusion Network for Action Recognition (**ACM Trans. Multim. Comput. Commun. Appl. 2022**) [[paper](https://doi.org/10.1145/3491228)]

- **[SparseShift-GCN]** SparseShift-GCN: High precision skeleton-based action recognition (**Pattern Recognit. Lett. 2022**) [[paper](https://doi.org/10.1016/j.patrec.2021.12.005)]

- **[FR-AGCN]** Forward-reverse adaptive graph convolutional networks for skeleton-based action recognition (**Neurocomputing 2022**) [[paper](https://doi.org/10.1016/j.neucom.2021.12.054)] [[Github](https://github.com/Nanasaki-Ai/FR-AGCN)] ![](https://img.shields.io/github/stars/Nanasaki-Ai/FR-AGCN.svg?style=social)

- **[ED-GCN]** Enhanced discriminative graph convolutional network with adaptive temporal modelling for skeleton-based action recognition (**Comput. Vis. Image Underst. 2022**) [[paper](https://doi.org/10.1016/j.cviu.2021.103348)]


### **2021**
- Quo Vadis, Skeleton Action Recognition ? (**IJCV 2021**) [[paper](https://arxiv.org/pdf/2007.02072.pdf)] [[Github](https://github.com/skelemoa/quovadis)] ![](https://img.shields.io/github/stars/skelemoa/quovadis.svg?style=social)


- **[CTR-GCN]** Channel-wise Topology Refinement Graph Convolution for Skeleton-Based Action Recognition (**ICCV 2021**) [[paper](https://arxiv.org/pdf/2107.12213.pdf)] [[Github](https://github.com/Uason-Chen/CTR-GCN)] ![](https://img.shields.io/github/stars/Uason-Chen/CTR-GCN.svg?style=social)

 - Spatio-Temporal Difference Descriptor for Skeleton-Based Action Recognition (**AAAI 2021**) [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/16210)]

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


### **2020**

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

### **2019**

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

### **2018**

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


### **2017**

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

### Before 2017

- **[Trust Gate ST-LSTM]** Spatio-temporal lstm with trust gates for 3d human action recognition (**ECCV 2016**) [[arxiv](https://arxiv.org/pdf/1607.07043.pdf)] [[Github](https://github.com/kinect59/Spatio-Temporal-LSTM)] ![](https://img.shields.io/github/stars/kinect59/Spatio-Temporal-LSTM.svg?style=social)
- **[Part-aware LSTM]** NTU RGB+D: A Large Scale Dataset for 3D Human Activity Analysis (**CVPR 2016**) [[arxiv](https://arxiv.org/pdf/1604.02808.pdf)]
- Rolling rotations for recognizing human actions from 3d skeletal data (**CVPR 2016**) [[paper](https://ieeexplore.ieee.org/document/7780853)]
- Co-occurrence feature learning for skeleton based action recognition using regularized deep lstm networks (**AAAI 2016**) [[paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/download/11989/12149)]
- Skeleton based action recognition with convolutional neural network (**ACPR 2015**) [[paper](https://ieeexplore.ieee.org/abstract/document/7486569)]
- **[H-RNN]** Hierarchical recurrent neural network for skeleton based action recognition (**CVPR 2015**) [[paper](https://ieeexplore.ieee.org/document/7298714)]
- Jointly learning heterogeneous features for rgb-d activity recognition (**CVPR 2015**) [[paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Hu_Jointly_Learning_Heterogeneous_2015_CVPR_paper.pdf)]
- **[LieGroup]** Human action recognition by representing 3d skeletons as points in a lie group (**CVPR 2014**) [[paper](https://openaccess.thecvf.com/content_cvpr_2014/papers/Vemulapalli_Human_Action_Recognition_2014_CVPR_paper.pdf)]
- Human action recognition using a temporal hierarchy of covariance descriptors on 3d joint locations (**IJCAI 2013**) [[paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.415.8032&rep=rep1&type=pdf)]


### arXiv papers

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




###  Leaderboards on NTU-RGB+D and NTU-RGB+D 120 Datasets

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



