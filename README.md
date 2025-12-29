# Oracle Bone Inscriptions Information Processing: A Comprehensive Survey

This repository accompanies the survey *Oracle Bone Inscriptions Information Processing: A Comprehensive Survey* and systematically organizes benchmarks and resources across oracle bone character recognition, fragment rejoining, classification and retrieval, decipherment, and related multimodal tasks. It aims to serve as a collection for reporting progress in the field of Oracle Bone Inscriptions Processing.

**We will continuously maintain and update this repository to ensure long-term value for the community.**

![Overview](image/overview.png)

**Paper:** *[Techrxiv](https://www.authorea.com/users/1009838/articles/1369823-oracle-bone-inscriptions-information-processing-a-comprehensive-survey)*  
**Project Page:** *This repository*

---

## Contributions

We warmly welcome pull requests (PRs)!

If you find this repository useful, please consider giving us a ⭐. Thank you for your support!

---

## Citation

If our work is helpful in your research, please cite our survey as:

```bibtex
@article{Chen_2025,
title={Oracle Bone Inscriptions Information Processing: A Comprehensive Survey},
url={http://dx.doi.org/10.22541/au.176616165.50988592/v1},
DOI={10.22541/au.176616165.50988592/v1},
publisher={Wiley},
author={Chen, Zijian and Hua, Wenjie and Li, Jinhao and Zhu, Yucheng and Zhi, Xiaona and Liu, Zhiji and Chen, Tingzhu and Zhang, Wenjun and Zhai, Guangtao},
year={2025}
```

## Table of Contents

1. [OBI-Dataset](#OBI-Dataset) 
   - [Recognition](#recognition)
   - [Rejoining](#rejoining)
   - [Classification and Retrieval](#classification-and-retrieval)
   - [Decipherment](#decipherment)
   - [Others](#others)
2. [Paper Index (Task-oriented)](#paper-index-task-oriented)
   - [OBI Preprocessing](#obi-preprocessing-data-augmentation--restoration)
   - [OBI Recognition](#obi-recognition)
   - [OBI Rejoining](#obi-rejoining)
   - [OBI Classification and Retrieval](#obi-classification-and-retrieval)
   - [OBI Deciphering](#obi-deciphering)


---
## OBI-Dataset 

## Recognition
|        Dataset         |                             Paper                              |                        Project Page                         |
| :--------------------: | :-------------------------------------------------------------: | :----------------------------------------------------------: |
|  YinQiWenYuan_detection  | YinQiWenYuan: Oracle Bone Character Detection Dataset | [Website](https://jgw.aynu.edu.cn/home/down/detail/index.html?sysid=3) |
|     OracleBone-8000     | [AI-Powered Oracle Bone Inscriptions Recognition and Fragments Rejoining](https://www.ijcai.org/proceedings/2020/779) | *N/A* |
|         ACCID          | [Toward Zero-shot Character Recognition: A Gold Standard Dataset with Radical-level Annotations](https://arxiv.org/abs/2308.00655) | *N/A* |
|          O2BR          | [OBI-Bench: Can LMMs Aid in Study of Ancient Script on Oracle Bones?](https://arxiv.org/abs/2412.01175) | [Github](https://github.com/zijianchen98/OBI-Bench) |


## Rejoining
|    Dataset     |                              Paper                              |                     Project Page                      |
| :------------: | :--------------------------------------------------------------: | :----------------------------------------------------: |
|   OB-Rejoin    | [Data-Driven Oracle Bone Rejoining: A Dataset and Practical Self-Supervised Learning Scheme](https://dl.acm.org/doi/10.1145/3534678.3539050) | *N/A* |
|      COBD      | [SFF-Siam: A New Oracle Bone Rejoining Method Based on Siamese Network](https://ieeexplore.ieee.org/document/10153461) | *N/A* |
|   OBI-rejoin   | [OBI-Bench: Can LMMs Aid in Study of Ancient Script on Oracle Bones?](https://arxiv.org/abs/2412.01175) | [Github](https://github.com/zijianchen98/OBI-Bench) |
|      OBFI      | [Deep Rejoining Model and Dataset of Oracle Bone Fragment Images](https://www.nature.com/articles/s40494-025-01651-9) | *N/A* |

## Classification and Retrieval

|      Dataset       |                             Paper                              |                        Project Page                         |
| :----------------: | :-------------------------------------------------------------: | :----------------------------------------------------------: |
|    Oracle-20k      | [Building Hierarchical Representations for Oracle Character and Sketch Recognition](https://ieeexplore.ieee.org/document/7327196) | *N/A* |
|      OBC306        | [OBC306: A Large-Scale Oracle Bone Character Recognition Dataset](https://ieeexplore.ieee.org/document/8978032) | [Website](https://jgw.aynu.edu.cn/home/down/detail/index.html?sysid=16) |
|    Oracle-AYNU     | [Oracle Character Recognition by Nearest Neighbor Classification with Deep Metric Learning](https://ieeexplore.ieee.org/document/8977960) | *N/A* |
|       HWOBC        | [HWOBC: A Handwriting Oracle Bone Character Recognition Database](https://iopscience.iop.org/article/10.1088/1742-6596/1651/1/012050) | [Website](https://jgw.aynu.edu.cn/home/down/detail/index.html?sysid=2) |
|    Oracle-50k      | [Self-supervised Learning of Orc-Bert Augmentor for Recognizing Few-Shot Oracle Characters](https://dl.acm.org/doi/10.1007/978-3-030-69544-6_39) | [Github](https://github.com/whhamber/Oracle-50K) |
|     OBI-IJDH       | OBI Dataset for IJDH and OBI Recognition Application | [Website](http://www.ihpc.se.ritsumei.ac.jp/obidataset.html) |
|    Oracle-250      | [Recognition of Oracle Radical based on the Capsule network](https://tis.hrbeu.edu.cn/en/oa/darticle.aspx?type=view&id=201904069) | *N/A* |
|   Radical-148      | [Recognition of Oracle Radical based on the Capsule network](https://tis.hrbeu.edu.cn/en/oa/darticle.aspx?type=view&id=201904069) | *N/A* |
|      OBI125        | [Dynamic Dataset Augmentation for Deep Learning-based Oracle Bone Inscriptions Recognition](https://dl.acm.org/doi/abs/10.1145/3532868) | [Website](http://www.ihpc.se.ritsumei.ac.jp/obidataset.html) |
|      OBI-100        | [Improvement of Oracle Bone Inscription Recognition Accuracy: A Deep Learning Perspective](https://www.mdpi.com/2220-9964/11/1/45) | *N/A* |
|    Oracle-241      | [Unsupervised Structure-Texture Separation Network for Oracle Character Recognition](https://ieeexplore.ieee.org/document/9757826) | [Github](https://github.com/wm-bupt/STSN) |
|       ORCD         | [Radical-based Extract and Recognition Networks for Oracle Character Recognition](https://link.springer.com/article/10.1007/s10032-021-00392-2) | *N/A* |
|       OCCD         | [Radical-based Extract and Recognition Networks for Oracle Character Recognition](https://link.springer.com/article/10.1007/s10032-021-00392-2) | *N/A* |
|     OracleRC       | [RZCR: Zero-shot Character Recognition via Radical-based Reasoning](https://dl.acm.org/doi/10.24963/ijcai.2023/73) | *N/A* |
|   Oracle-MNIST     | [Oracle-MNIST: a Dataset of Oracle Characters for Benchmarking Machine Learning Algorithms](https://www.nature.com/articles/s41597-024-02933-w) | [Github](https://github.com/wm-bupt/oracle-mnist) |
| OBI component 20   | [Component-Level Oracle Bone Inscription Retrieval](https://dl.acm.org/doi/10.1145/3652583.3658116) | [Github](https://github.com/hutt94/Component-Level-OBI-Retrieval) |

## Decipherment

|     Dataset      |                             Paper                              |                        Project Page                         |
| :--------------: | :-------------------------------------------------------------: | :----------------------------------------------------------: |
|     OBI-ECC      | [Study on the Evolution of Chinese Characters Based on Few-shot Learning: From Oracle Bone Inscriptions to Regular Script](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0272974) | *N/A* |
|      EVOBC       | [An Open Dataset for the Evolution of Oracle Bone Characters: EVOBC](https://arxiv.org/abs/2401.12467) | [Github](https://github.com/RomanticGodVAN/character-Evolution-Dataset) |
|     HUST-OBC     | [An Open Dataset for Oracle Bone Character Recognition and Decipherment](https://www.nature.com/articles/s41597-024-03807-x) | [Github](https://github.com/Pengjie-W/HUST-OBC) |
|     ACCP     | [Puzzle Pieces Picker: Deciphering Ancient Chinese Characters with Radical Reconstruction](https://arxiv.org/abs/2406.03019) | [Github](https://github.com/Pengjie-W/Puzzle-Pieces-Picker) |
|     OracleSem      | [OracleSage: Towards Unified Visual-Linguistic Understanding of Oracle Bone Scripts through Cross-Modal Knowledge Fusion](https://arxiv.org/abs/2411.17837) | *N/A* |
|      GEVOBC      | [A Graph-based Evolutionary Dataset for Oracle Bone Characters from Inscriptions to Modern Chinese Scripts](https://www.nature.com/articles/s40494-025-01951-0) | [Github](https://github.com/BrisksHan/GBEDOBC) |
|      PD-OBS       | [Interpretable Oracle Bone Script Decipherment through Radical and Pictographic Analysis with LVLMs](https://arxiv.org/abs/2508.10113) | [Github](https://github.com/PKXX1943/PD-OBS) |
|   PictOBI-20k    | [PictOBI-20k: Unveiling Large Multimodal Models in Visual Decipherment for Pictographic Oracle Bone Characters](https://arxiv.org/abs/2509.05773) | [Github](https://github.com/OBI-Future/PictOBI-20k) |

## Others
|     Dataset      |                             Paper                              |                        Project Page                         |
| :--------------: | :-------------------------------------------------------------: | :----------------------------------------------------------: |
|       RCRN       | [RCRN: Real-world Character Image Restoration Network via Skeleton Extraction](https://dl.acm.org/doi/10.1145/3503161.3548344) | [Github](https://github.com/daqians/Noisy-character-image-benchmark) |
|      OBIMD       | [Oracle Bone Inscriptions Multi-modal Dataset](https://arxiv.org/abs/2407.03900) | [Hugging Face](https://huggingface.co/datasets/KLOBIP/OBIMD) |
|     RMOBS      | [OracleFusion: Assisting the Decipherment of Oracle Bone Script with Structurally Constrained Semantic Typography](https://arxiv.org/abs/2506.21101) | *N/A* |
|    Oracle-P15k   | [Mitigating Long-tail Distribution in Oracle Bone Inscriptions: Dataset, Model, and Benchmark](https://dl.acm.org/doi/10.1145/3746027.3755067) | [Github](https://github.com/OBI-Future/Oracle-P15K) |

## Paper Index (Task-oriented)
This section provides a task-oriented index of **OBI Processing Tasks and Approaches** papers, aligned with the task taxonomy used in this survey (Section 4 of our [paper](https://www.authorea.com/users/1009838/articles/1369823-oracle-bone-inscriptions-information-processing-a-comprehensive-survey)).

### OBI Preprocessing: Data Augmentation & Restoration

| Paper | Venue & Year | Focus |
| :---: | :----------: | :---- |
| [Dynamic Dataset Augmentation for Deep Learning-based Oracle Bone Inscriptions Recognition](https://dl.acm.org/doi/10.1145/3532868) | ACM JOCCH 2022 | GAN-based dynamic augmentation |
| [Oracle Bone Heritage Data Augmentation Based on Two-stage Decomposition GANs](https://www.nature.com/articles/s40494-025-01774-z) | npj Heritage Science 2025 | Two-stage decomposition GAN |
| [Mitigating Long-tail Distribution in Oracle Bone Inscriptions: Dataset, Model, and Benchmark](https://dl.acm.org/doi/10.1145/3746027.3755067) | ACM MM 2025 | Diffusion-based synthesis, long-tail |
| [Large Kernel Convolutional Attention Based U-Net Network for Inpainting Oracle Bone Inscription](https://link.springer.com/chapter/10.1007/978-981-99-8552-4_10) | PRCV 2023 | U-Net based inpainting |
| [Coarse-to-Fine Generative Model for Oracle Bone Inscriptions Inpainting](https://aclanthology.org/2024.ml4al-1.12/) | ML4AL @ ACL 2024 | GAN-based coarse-to-fine inpainting |
| [Oracle Bone Inscription Image Restoration via Glyph Extraction](https://www.nature.com/articles/s40494-025-01795-8) | npj Heritage Science 2025 | Glyph-driven restoration |
| [OBIFormer: A Fast Attentive Denoising Framework for Oracle Bone Inscriptions](https://www.sciencedirect.com/science/article/abs/pii/S0141938225000964) | Displays 2025 | Attention-based denoising |
| [Orpaint: A Zero-shot Inpainting Model for Oracle Bone Inscription Rubbings with Visual Mamba Block](https://link.springer.com/article/10.1007/s11432-024-4493-4) | SCIS 2025 | Diffusion-based inpainting |
| [Multi-modal Ancient Scripts Recognition via Deep Learning with Data Homogenization and Augmentation](https://www.nature.com/articles/s40494-025-02095-x) | npj Heritage Science 2025 | Cross-modal data homogenization |
| [Generating Oracle Bone Inscriptions Based on the Structure-aware Diffusion Model](https://www.nature.com/articles/s40494-025-02000-6) | npj Heritage Science 2025 | Structure-aware diffusion |

### OBI Recognition

#### Traditional Pattern Recognition

| Paper | Venue & Year | Focus |
| :---: | :----------: | :---- |
| [A Method of Jia Gu Wen Recognition Based on a Two-level Classification](https://ieeexplore.ieee.org/document/602030/) | ICDAR 1995 | Two-level classification, topological structure |
| [Recognition of Oracular Bone Inscriptions Using Template Matching](https://www.ijcte.org/vol8/1019-C010.pdf) | IJCTE 2016 | Four-directional scanning, template matching |
| [Oracle-Bone Inscriptions Recognition Based on Topological Features](https://pdf.hanspub.org/csa20190600000_45957966.pdf) | CSA 2019 | Topological feature points, connected domains |


#### Deep Representation Learning-Based Recognition

| Paper | Venue & Year | Focus |
| :---: | :----------: | :---- |
| [Oracle Character Detection Based on Improved Faster R-CNN](https://ieeexplore.ieee.org/document/9526033/) | IEEE ICITBS 2021 | Two-stage detector with feature fusion |
| [Oracle Bone Inscription Detector Based on SSD](https://dl.acm.org/doi/10.1007/978-3-030-30754-7_13) | ICIAP 2019 | SSD-based small character detection |
| [Recognition of Oracle Bone Inscriptions by Using Two Deep Learning Models](https://link.springer.com/article/10.1007/s42803-022-00044-9) | IJDH 2023 | YOLO + MobileNet pipeline |
| [FDW-YOLO: An Improved YOLOv12 for Oracle Bone Inscriptions Detection](https://link.springer.com/chapter/10.1007/978-981-95-4378-6_18) | ICONIP 2025 | Feature diffusion pyramid, mixed convolution |
| [Oracle Character Prototype-Guided Cyclic Disentanglement for Oracle Bone Inscriptions Detection](https://link.springer.com/chapter/10.1007/978-981-97-8705-0_14) | ICPRAI 2024 | Prototype guidance, contrastive disentanglement |
| [Detecting Oracle Bone Inscriptions via Pseudo-category Labels](https://www.nature.com/articles/s40494-024-01221-5) | Heritage Science 2024 | Pseudo-label supervision, structural prior |
| [Clustering-based Feature Representation Learning for Oracle Bone Inscriptions Detection](https://www.nature.com/articles/s40494-025-01850-4) | npj Heritage Science 2025 | Clustering-based representation learning |
| [Radical-based Extract and Recognition Networks for Oracle Character Recognition](https://link.springer.com/article/10.1007/s10032-021-00392-2) | IJDAR 2022 | Radical-aware feature extraction |
| [Toward Zero-shot Character Recognition: A Gold Standard Dataset with Radical-level Annotations](https://dl.acm.org/doi/10.1145/3581783.3612201) | ACM MM 2023 | Radical-level supervision, zero-shot setting |


### OBI Rejoining

#### Contour Matching-Based Methods

| Paper | Venue & Year | Focus |
| :---: | :----------: | :---- |
| [The Research on Rejoining of the Oracle Bone Rubbings Based on Curve Matching](https://dl.acm.org/doi/10.1145/3460393) | TALLIP 2021 | Partial-to-global curve matching |
| [Research on Key Technologies of the Computer Aided Rejoining of Oracle Bone Inscriptions](https://ieeexplore.ieee.org/document/5609279) | ICIFE 2010 | Freeman chain code, contour matching |
| [System Design for Computer Aided Rejoining of Bones/Tortoise Shells with Inscriptions Based on Contour Matching](https://ieeexplore.ieee.org/document/5688700) | ICCCT 2010 | Shape function–based contour matching |
| [AI-powered Oracle Bone Inscriptions Recognition and Fragments Rejoining](https://www.ijcai.org/proceedings/2020/779) | IJCAI 2020 | Time-series modeling of contour curves |

#### Deep Learning–Assisted Methods

| Paper | Venue & Year | Focus |
| :---: | :----------: | :---- |
| [Internal Similarity Network for Rejoining Oracle Bone Fragment Images](https://www.mdpi.com/2073-8994/14/7/1464) | Symmetry 2022 | Internal similarity pooling network |
| [SFF-Siam: A New Oracle Bone Rejoining Method Based on Siamese Network](https://ieeexplore.ieee.org/document/10153461) | IEEE CG&A 2023 | Siamese network with similarity feature fusion |
| [Data-driven Oracle Bone Rejoining: A Dataset and Practical Self-supervised Learning Scheme](https://dl.acm.org/doi/10.1145/3534678.3539050) | KDD 2022 | Self-supervised learning, dataset-driven |
| [OBD-Finder: Explainable Coarse-to-Fine Text-Centric Oracle Bone Duplicates Discovery](https://arxiv.org/abs/2505.03836) | arXiv 2025 | Duplicate discovery, coarse-to-fine matching |


### OBI Classification and Retrieval

#### Supervised Deep Learning

| Paper | Venue & Year | Focus |
| :---: | :----------: | :---- |
| [Building Hierarchical Representations for Oracle Character and Sketch Recognition](https://ieeexplore.ieee.org/document/7327196/) | IEEE TIP 2016 | Hierarchical representation, early classification |
| [OBC306: A Large-scale Oracle Bone Character Recognition Dataset](https://ieeexplore.ieee.org/document/8978032/) | ICDAR 2019 | Large-scale dataset, CNN benchmarks |
| [Oracle Bone Inscriptions Recognition Based on Deep Convolutional Neural Network](https://www.joig.net/index.php?m=content&c=index&a=show&catid=66&id=249) | JOIG 2020 | CNN-based classification |
| [Improvement of Oracle Bone Inscription Recognition Accuracy: A Deep Learning Perspective](https://www.mdpi.com/2220-9964/11/1/45) | ISPRS IJGI 2022 | Deep learning baselines |
| [A Classification Method of Oracle Materials Based on Local Convolutional Neural Network Framework](https://ieeexplore.ieee.org/document/9004518/) | IEEE CG&A 2020 | Two-stage material classification |
| [Distinguishing Oracle Variants Based on Isomorphism and Symmetry Invariances of Oracle-bone Inscriptions](https://ieeexplore.ieee.org/document/9171826/) | IEEE Access 2020 | Symmetry and invariance modeling |
| [OraclePoints: A Hybrid Neural Representation for Oracle Character](https://dl.acm.org/doi/10.1145/3581783.3612534) | ACM MM 2023 | Image–point hybrid representation |
| [Oracle Character Image Retrieval by Combining Deep Neural Networks and Clustering Technology](https://www.iaeng.org/IJCS/issues_v47/issue_2/IJCS_47_2_08.pdf) | IAENG IJCS 2020 | DNN + clustering retrieval |
| [Oracle Bone Inscription Image Retrieval Based on Improved ResNet Network](https://link.springer.com/chapter/10.1007/978-3-031-78305-0_4) | ICPR 2024 | Siamese-style metric learning |
| [A Cross-Font Image Retrieval Network for Recognizing Undeciphered Oracle Bone Inscriptions](https://link.springer.com/chapter/10.1007/978-981-96-9794-6_17) | ICIC 2025 | Cross-font retrieval |

#### Zero-Shot and Few-Shot Learning

| Paper | Venue & Year | Focus |
| :---: | :----------: | :---- |
| [OracleGCD: Generalized Category Discovery for Oracle Bone Scripts](https://link.springer.com/chapter/10.1007/978-3-032-04624-6_27) | ICDAR 2025 | Generalized category discovery |
| [Ora-NSC: A Novel Semi-supervised Approach for Oracle Bone Fragment Classification with Imbalanced Classes](https://dl.acm.org/doi/10.1145/3743093.3770992) | ACM MM Asia 2025 | Semi-supervised learning |
| [OBI-CMF: Self-supervised Learning with Contrastive Masked Frequency Modeling for Oracle Bone Inscription Recognition](https://www.nature.com/articles/s40494-025-01644-8) | npj Heritage Science 2025 | Self-supervised contrastive learning |
| [Linking Unknown Characters via Oracle Bone Inscriptions Retrieval](https://link.springer.com/article/10.1007/s00530-024-01327-7) | Multimedia Systems 2024 | Unknown character retrieval |
| [RZCR: Zero-shot Character Recognition via Radical-based Reasoning](https://www.ijcai.org/proceedings/2023/73) | IJCAI 2023 | Radical-based zero-shot reasoning |
| [Component-level Oracle Bone Inscription Retrieval](https://dl.acm.org/doi/10.1145/3652583.3658116) | ICMR 2024 | Component-level retrieval |

#### Cross-Modal Learning

| Paper | Venue & Year | Focus |
| :---: | :----------: | :---- |
| [Unsupervised Structure-Texture Separation Network for Oracle Character Recognition](https://ieeexplore.ieee.org/document/9757826/) | IEEE TIP 2022 | Structure–texture disentanglement |
| [OracleAgent: A Multimodal Reasoning Agent for Oracle Bone Script Research](https://arxiv.org/abs/2510.26114) | arXiv 2025 | Vision–text retrieval, agentic system |

### OBI Deciphering

#### Modern Chinese Alignment-Based Deciphering

| Paper | Venue & Year | Focus |
| :---: | :----------: | :---- |
| [Sundial-GAN: A Cascade GAN Framework for Deciphering Oracle Bone Inscriptions](https://dl.acm.org/doi/10.1145/3503161.3547925) | ACM MM 2022 | GAN-based simulation of oracle-to-modern character evolution |
| [Deciphering Oracle Bone Language with Diffusion Models](https://aclanthology.org/2024.acl-long.831/) | ACL 2024 | Conditional diffusion for oracle–modern Chinese alignment |
| [A Text–Image Dual Conditional Stable Diffusion Model for Oracle Bone Inscription Decipherment](https://www.nature.com/articles/s40494-025-02019-9) | npj Heritage Science 2025 | Dual-condition diffusion with visual–semantic alignment |
| [Deciphering Ancient Chinese Oracle Bone Inscriptions Using Case-Based Reasoning](https://link.springer.com/chapter/10.1007/978-3-030-86957-1_21) | ICCBR 2021 | Auto-encoder–based multi-font feature retrieval |
| [Study on the Evolution of Chinese Characters Based on Few-Shot Learning](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0272974) | PLOS ONE 2022 | Few-shot Siamese learning for character evolution |
| [Puzzle Pieces Picker: Deciphering Ancient Chinese Characters with Radical Reconstruction](https://link.springer.com/chapter/10.1007/978-3-031-70533-5_11) | ICDAR 2024 | Radical/stroke reconstruction via Transformer |
| [Component-Level Segmentation for Oracle Bone Inscription Decipherment](https://ojs.aaai.org/index.php/AAAI/article/view/35030) | AAAI 2025 | Component-aware segmentation for decipherment |
| [A Cross-Font Image Retrieval Network for Recognizing Undeciphered Oracle Bone Inscriptions](https://link.springer.com/chapter/10.1007/978-981-96-9794-6_17) | ICIC 2025 | Historical font intermediaries for alignment |
| [A Graph-Based Evolutionary Dataset for Oracle Bone Characters](https://www.nature.com/articles/s40494-025-01951-0) | npj Heritage Science 2025 | Graph representations for oracle–modern character evolution |

#### Visual Content Alignment-Based Deciphering

| Paper | Venue & Year | Focus |
| :---: | :----------: | :---- |
| [Making Visual Sense of Oracle Bones for You and Me](https://openaccess.thecvf.com/content/CVPR2024/html/Qiao_Making_Visual_Sense_of_Oracle_Bones_for_You_and_Me_CVPR_2024_paper.html) | CVPR 2024 | Human study on visual grounding of oracle glyphs |
| [V-Oracle: Making Progressive Reasoning in Deciphering Oracle Bones](https://aclanthology.org/2025.acl-long.986/) | ACL 2025 | VQA-based progressive visual reasoning |
| [OracleFusion: Assisting the Decipherment of Oracle Bone Script with Structurally Constrained Semantic Typography](https://openaccess.thecvf.com/content/ICCV2025/papers/Li_OracleFusion_Assisting_the_Decipherment_of_Oracle_Bone_Script_with_Structurally_ICCV_2025_paper.pdf) | ICCV 2025 | LMM-based visual alignment with structure constraints |
| [PictOBI-20k: Unveiling Large Multimodal Models in Visual Decipherment](https://arxiv.org/abs/2509.05773) | arXiv 2025 | Visual perception benchmark for pictographic OBI |

#### Text Interpretation-Based Deciphering

| Paper | Venue & Year | Focus |
| :---: | :----------: | :---- |
| [OBI-Bench: Can LMMs Aid in Study of Ancient Script on Oracle Bones?](https://arxiv.org/abs/2412.01175) | ICLR 2025 | Systematic evaluation of LMM-based oracle interpretation |
| [OracleSage: Towards Unified Visual-Linguistic Understanding of Oracle Bone Scripts](https://arxiv.org/abs/2411.17837) | arXiv 2024 | Cross-modal reasoning with knowledge fusion |
| [Interpretable Oracle Bone Script Decipherment through Radical and Pictographic Analysis with LVLMs](https://arxiv.org/abs/2508.10113) | arXiv 2025 | LVLM-based interpretable decipherment |
| [OracleAgent: A Multimodal Reasoning Agent for Oracle Bone Script Research](https://arxiv.org/abs/2510.26114) | arXiv 2025 | Agentic system for structured oracle interpretation |

