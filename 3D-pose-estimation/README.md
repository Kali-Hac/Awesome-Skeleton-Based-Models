# 3D Pose Estimation (2000-2022)<!-- omit in toc --> 

<!-- vscode-markdown-toc -->
- [3D Pose Estimation](#3d-pose-estimation)
  - [**13** Datasets](#13-datasets)
  - [**2022**](#2022)
  - [**2021**](#2021)
  - [**2020**](#2020)
  - [**2019**](#2019)
  - [**2018**](#2018)
  - [**2017**](#2017)
  - [Before 2017](#before-2017)
  - [Real-Time 3D Pose Estimation](#real-time-3d-pose-estimation)
  - [Leaderboards](#leaderboards)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->



##  3D Pose Estimation
###  **13** Datasets
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

### **2022**
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
  


### **2021**
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
  

### **2020**
  
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
  
- [Multi-Person Absolute 3D Human Pose Estimation with Weak Depth Supervision](https://arxiv.org/abs/2004.03989) (Arxiv 2020) [[Github](https://github.com/vegesm/wdspose)] ![](https://img.shields.io/github/stars/vegesm/wdspose.svg?style=social)

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
  
- [Attention Mechanism Exploits Temporal Contexts: Real-Time 3D Human Pose Reconstruction](http://openaccess.thecvf.com/content_CVPR_2020/html/Liu_Attention_Mechanism_Exploits_Temporal_Contexts_Real-Time_3D_Human_Pose_Reconstruction_CVPR_2020_paper.html) (CVPR 2020) [[Github](https://github.com/lrxjason/Attention3DHumanPose)] ![](https://img.shields.io/github/stars/lrxjason/Attention3DHumanPose.svg?style=social)

- [Cascaded Deep Monocular 3D Human Pose Estimation With Evolutionary Training Data](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_Cascaded_Deep_Monocular_3D_Human_Pose_Estimation_With_Evolutionary_Training_CVPR_2020_paper.html)
 (CVPR 2020)

- [Deep Kinematics Analysis for Monocular 3D Human Pose Estimation](http://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Deep_Kinematics_Analysis_for_Monocular_3D_Human_Pose_Estimation_CVPR_2020_paper.pdf) (CVPR 2020)
  
- [Three-dimensional Reconstruction of Human Interactions](http://openaccess.thecvf.com/content_CVPR_2020/papers/Fieraru_Three-Dimensional_Reconstruction_of_Human_Interactions_CVPR_2020_paper.pdf) (CVPR 2020) [[Codes](http://vision.imar.ro/ci3d/)]
   
- [Coherent Reconstruction of Multiple Humans from a Single Image](http://openaccess.thecvf.com/content_CVPR_2020/papers/Jiang_Coherent_Reconstruction_of_Multiple_Humans_From_a_Single_Image_CVPR_2020_paper.pdf) (CVPR 2020) [[Github](https://github.com/JiangWenPL/multiperson)] ![](https://img.shields.io/github/stars/JiangWenPL/multiperson.svg?style=social)
  
- [Optical Non-Line-of-Sight Physics-based 3D Human Pose Estimation](https://arxiv.org/abs/2003.14414) (CVPR 2020) [[Codes](https://marikoisogawa.github.io/project/nlos_pose)]
  
- [Kinematic-Structure-Preserved Representation for Unsupervised 3D Human Pose Estimation](https://arxiv.org/abs/2006.14107) (AAAI 2020)
  
- [Inference Stage Optimization for Cross-scenario 3D Human Pose Estimation](https://arxiv.org/abs/2007.02054) (Arxiv 2020)
  
- [Predicting Camera Viewpoint Improves Cross-dataset Generalization for 3D Human Pose Estimation](https://arxiv.org/abs/2004.03143) (Arxiv 2020) [[Codes](http://wangzheallen.github.io/cross-dataset-generalization)]



### **2019**
  
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
  

### **2018**
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
  
  

### **2017**
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
  

### Before 2017
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

### Leaderboards
- [Human3.6M](https://paperswithcode.com/sota/3d-human-pose-estimation-on-human36m)
- [Human3.6M2](https://paperswithcode.com/task/3d-human-pose-estimation)
- [MuPoTS-3D](https://paperswithcode.com/sota/3d-multi-person-pose-estimation-absolute-on?p=camera-distance-aware-top-down-approach-for-1
)
- [MuPoTS-3D2](https://paperswithcode.com/sota/3d-multi-person-pose-estimation-root-relative?p=camera-distance-aware-top-down-approach-for-1
)
- [GPA(Geometric Pose Affordance dataset)](https://paperswithcode.com/sota/3d-human-pose-estimation-on-geometric-pose)
