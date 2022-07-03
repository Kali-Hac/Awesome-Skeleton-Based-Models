# Skeleton-Based Person Re-Identification (2012-2022) <!-- omit in toc --> 

<!-- vscode-markdown-toc -->
- [Skeleton-Based Person Re-Identification](#skeleton-based-person-re-identification)
  - [**6** Datasets](#6-datasets)
  - [**2022**](#2022)
  - [**2021**](#2021)
  - [**2020**](#2020)
  - [**2019**](#2019)
  - [Before 2019](#before-2019)
  - [Leaderboards](#leaderboards)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->



##  Skeleton-Based Person Re-Identification
### **6** Datasets
Overview of **6** available datasets for **skeleton-based person re-identification** and their statistics, mainly from the paper of (**TPAMI 2021**) [[paper](https://arxiv.org/abs/2009.03671)] (A Self-Supervised Gait Encoding Approach with Locality-Awareness for 3D Skeleton Based Person Re-Identification). 
```
Bold shows the most-frequently used datasets in the literature. CASIA-B and OUMVLP-Pose estimate 3D skeletons and 2D skeletons, respectively, from RGB images.
```
| **# Datasets**           | **Year** | **# ID** | **# Skeleton** |     **# View** | **# Clothes/Scenes**           |
|--------------------------|:--------:|---------:|---------------:|---------------:|--------------------------------|
| **IAS-Lab RGBD-ID**      | **2013** |   **11** |      **89.0K** | **Egocentric** | **Varying Clothes and Scenes** |
| **BIWI RGBD-ID**         | **2013** |   **50** |     **205.8K** | **Egocentric** | **Varying Clothes and Scenes** |
| **KGBD**                 | **2014** |  **164** |     **188.7K** | **Egocentric** | **——**                         |
| **KS20**                 | **2017** |   **20** |      **36.0K** |          **5** | **——**                         |
| **# Estimated Datasets** |          |          |                |                |                                |
| **CAISA-B (3D)**         | **2005** |  **124** |     **706.5K** |         **11** | **Varying Clothes**            |
| OUMVLP-Pose (2D)         |   2020   |   10,307 |         6,667K |             14 | ——                             |


### **2022**
- [SimMC: Simple Masked Contrastive Learning of Skeleton Representations for Unsupervised Person Re-Identification](https://doi.org/10.48550/arXiv.2204.09826) (IJCAI 2022) [[Github](https://github.com/Kali-Hac/SimMC)] ![](https://img.shields.io/github/stars/Kali-Hac/SimMC.svg?style=social)

### **2021**
 - [SM-SGE: A Self-Supervised Multi-Scale Skeleton Graph Encoding Framework for Person Re-Identification](https://doi.org/10.1145/3474085.3475330) (ACMMM 2021) [[Github](https://github.com/Kali-Hac/SM-SGE)] ![](https://img.shields.io/github/stars/Kali-Hac/SM-SGE.svg?style=social)

- [Multi-Level Graph Encoding with Structural-Collaborative Relation Learning for Skeleton-Based Person Re-Identification](https://doi.org/10.48550/arXiv.2204.09826) (IJCAI 2021) [[Github](https://github.com/Kali-Hac/MG-SCR)] ![](https://img.shields.io/github/stars/Kali-Hac/MG-SCR.svg?style=social)

- [A Self-Supervised Gait Encoding Approach with Locality-Awareness for 3D Skeleton Based Person Re-Identification](https://arxiv.org/abs/2009.03671) (TPAMI 2021) [[Github](https://github.com/Kali-Hac/Locality-Awareness-SGE)] ![](https://img.shields.io/github/stars/Kali-Hac/Locality-Awareness-SGE.svg?style=social)

### **2020**
- [Human skeleton mutual learning for person re-identification](https://doi.org/10.1016/j.neucom.2019.12.120) (Neurocomputing 2020)

- [Self-Supervised Gait Encoding with Locality-Aware Attention for Person Re-Identification](https://doi.org/10.24963/ijcai.2020/125) (IJCAI 2020) [[Github](https://github.com/Kali-Hac/SGE-LA)] ![](https://img.shields.io/github/stars/Kali-Hac/SGE-LA.svg?style=social)

### **2019**
- [SKEPRID: Pose and Illumination Change-Resistant Skeleton-Based Person Re-Identification](https://doi.org/10.1145/3243217) (ACM Trans. Multim. Comput. Commun. Appl. 2019)

- [Enhanced skeleton and face 3D data for person re-identification from depth cameras](https://doi.org/10.24963/ijcai.2020/125) (Comput. Graph. 2019)

### Before 2019
- [Person Identification Using Anthropometric and Gait Data from Kinect Sensor](http://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9680) (AAAI 2015)

- [3D reconstruction of freely moving persons for re-identification with a depth sensor](https://doi.org/10.24963/ijcai.2020/125) (ICRA 2014)

- [One-Shot Person Re-identification with a Consumer Depth Camera](https://doi.org/10.1007/978-1-4471-6296-4\_8) (Person Re-Identification 2014)

- [Re-identification with RGB-D Sensors](https://doi.org/10.1007/978-3-642-33863-2\_43) (ECCV Workshop 2012)

###  Leaderboards
The results are mainly from the paper of (**IJCAI 2021**) [[paper](https://doi.org/10.48550/arXiv.2204.09826)] (SimMC: Simple Masked Contrastive Learning of Skeleton Representations for Unsupervised Person Re-Identification). 
|                    |     KS20 |          |          |          |     KGBD |          |          |          |    IAS-A |          |          |          |
|--------------------|---------:|---------:|---------:|---------:|---------:|---------:|---------:|---------:|---------:|---------:|---------:|---------:|
| Methods            |    top-1 |    top-5 |   top-10 |      mAP |    top-1 |    top-5 |   top-10 |      mAP |    top-1 |    top-5 |   top-10 |      mAP |
| D-13 Descriptors   |     39.4 |     71.7 |     81.7 |     18.9 |     17.0 |     34.4 |     44.2 |      1.9 |     40.0 |     58.7 |     67.6 |     24.5 |
| D-16 Descriptors   |     51.7 |     77.1 |     86.9 |     24.0 |     31.2 |     50.9 |     59.8 |      4.0 |     42.7 |     62.9 |     70.7 |     25.2 |
| PoseGait           |     49.4 |     80.9 |     90.2 |     23.5 |     50.6 |     67.0 |     72.6 |     13.9 |     28.4 |     55.7 |     69.2 |     17.5 |
| [SGELA](https://github.com/Kali-Hac/Locality-Awareness-SGE) + DF         |     49.7 |     67.0 |     77.1 |     22.2 |     43.7 |     58.7 |     65.0 |      7.1 |     18.0 |     32.1 |     46.2 |     13.5 |
| [MG-SCR](https://github.com/Kali-Hac/MG-SCR)             |     46.3 |     75.4 |     84.0 |     10.4 |     44.0 |     58.7 |     64.6 |      6.9 |     36.4 |     59.6 |     69.5 |     14.1 |
| [SM-SGE](https://github.com/Kali-Hac/SM-SGE) + DF        |     49.8 |     78.1 |     85.2 |     11.7 |     43.2 |     58.6 |     64.6 |      7.5 |     38.5 |     63.2 |     73.9 |     15.0 |
| [AGE](https://github.com/Kali-Hac/SGE-LA)                |     43.2 |     70.1 |     80.0 |      8.9 |      2.9 |      5.6 |      7.5 |      0.9 |     31.1 |     54.8 |     67.4 |     13.4 |
| [SGELA](https://github.com/Kali-Hac/Locality-Awareness-SGE)              |     45.0 |     65.0 |     75.1 |     21.2 |     38.1 |     53.5 |     60.0 |      4.5 |     16.7 |     30.2 |     44.0 |     13.2 |
| [SM-SGE](https://github.com/Kali-Hac/SM-SGE)             |     45.9 |     71.9 |     81.2 |      9.5 |     38.2 |     54.2 |     60.7 |      4.4 |     34.0 |     60.5 |     71.6 |     13.6 |
| SimMC   | 66.4 | 80.7 | 87.0 | 22.3 | 54.9 | 66.2 | 70.6 | 11.7 | 44.8 | 65.3 | 72.9 | 18.7 |
| [SGELA](https://github.com/Kali-Hac/Locality-Awareness-SGE) + SimMC  |     47.3 |     69.7 |     79.3 |     20.1 |     51.7 |     62.7 |     67.9 |     15.1 |     16.8 |     33.3 |     48.7 |     12.0 |
| [MG-SCR](https://github.com/Kali-Hac/MG-SCR) + SimMC |     71.1 |     83.6 |     89.1 |     22.7 |     47.4 |     59.3 |     64.9 |     11.0 |     47.2 |     69.0 |     77.3 |     22.4 |
| [SM-SGE](https://github.com/Kali-Hac/SM-SGE) + SimMC |     67.2 |     82.2 |     88.5 |     23.0 |     47.1 |     59.2 |     64.9 |     10.8 |     51.3 |     69.9 |     75.6 |     27.3 |

|                    |    IAS-B |          |          |          |   BIWI-W |          |          |          |   BIWI-S |          |          |          |
|-------------------:|---------:|---------:|---------:|---------:|---------:|---------:|---------:|---------:|---------:|---------:|---------:|---------:|
| Methods            |    top-1 |    top-5 |   top-10 |      mAP |    top-1 |    top-5 |   top-10 |      mAP |    top-1 |    top-5 |   top-10 |      mAP |
| D-13 Descriptors   |     43.7 |     68.6 |     76.7 |     23.7 |     14.2 |     20.6 |     23.7 |     17.2 |     28.3 |     53.1 |     65.9 |     13.1 |
| D-16 Descriptors   |     44.5 |     69.1 |     80.2 |     24.5 |     17.0 |     25.3 |     29.6 |     18.8 |     32.6 |     55.7 |     68.3 |     16.7 |
| PoseGait           |     28.9 |     51.6 |     62.9 |     20.8 |      8.8 |     23.0 |     31.2 |     11.1 |     14.0 |     40.7 |     56.7 |      9.9 |
| [SGELA](https://github.com/Kali-Hac/Locality-Awareness-SGE) + DF         |     23.6 |     42.9 |     51.9 |     14.8 |     13.9 |     15.3 |     16.7 |     22.9 |     29.2 |     65.2 |     73.8 |     23.5 |
| [MG-SCR](https://github.com/Kali-Hac/MG-SCR)             |     32.4 |     56.5 |     69.4 |     12.9 |     10.8 |     20.3 |     29.4 |     11.9 |     20.1 |     46.9 |     64.1 |      7.6 |
| [SM-SGE](https://github.com/Kali-Hac/SM-SGE) + DF        |     44.3 |     68.2 |     77.5 |     14.9 |     16.7 |     31.0 |     40.2 |     18.7 |     34.8 |     60.6 |     71.5 |     12.8 |
| [AGE](https://github.com/Kali-Hac/SGE-LA)                |     31.1 |     52.3 |     64.2 |     12.8 |     11.7 |     21.4 |     27.3 |     12.6 |     25.1 |     43.1 |     61.6 |      8.9 |
| [SGELA](https://github.com/Kali-Hac/Locality-Awareness-SGE)             |     22.2 |     40.8 |     50.2 |     14.0 |     11.7 |     14.0 |     14.7 |     19.0 |     25.8 |     51.8 |     64.4 | 15.1 |
| [SM-SGE](https://github.com/Kali-Hac/SM-SGE)             |     38.9 |     64.1 |     75.8 |     13.3 |     13.2 |     25.8 |     33.5 |     15.2 |     31.3 |     56.3 |     69.1 |     10.1 |
| SimMC (Ours)   | 46.3 | 68.1 | 77.0 | 22.9 | 24.5 | 36.7 | 44.5 | 19.9 | 41.7 | 66.6 | 76.8 |     12.3 |
| [SGELA](https://github.com/Kali-Hac/Locality-Awareness-SGE) + SimMC  |     21.2 |     39.1 |     48.8 |     14.0 |     18.4 |     23.1 |     25.0 |     28.7 |     51.8 |     71.3 |     74.4 |     43.3 |
| [MG-SCR](https://github.com/Kali-Hac/MG-SCR) + SimMC |     52.4 |     72.0 |     78.8 |     29.1 |     25.1 |     37.5 |     46.4 |     20.3 |     28.3 |     51.6 |     64.8 |     10.9 |
| [SM-SGE](https://github.com/Kali-Hac/SM-SGE) + SimMC |     55.3 |     72.6 |     80.3 |     34.1 |     25.9 |     39.2 |     45.2 |     22.4 |     42.6 |     64.8 |     76.2 |     15.4 |
