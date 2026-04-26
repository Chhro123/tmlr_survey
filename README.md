# A Survey on Industrial Anomaly Synthesis

We discuss anomaly synthesis methods in detail. Welcome to read our paper and make comments.


## Taxonomy of Industrial Image Anomaly Synthesis


## Hand-Crafted Model

### Self-Contained

+ ADAFF: Anomaly Detection of GAN Industrial Image Based on Attention Feature Fusion [[Sensors 2023]](https://doi.org/10.3390/s23010355)
+ ADDLA: Self-Supervised Learning for Anomaly Detection With Dynamic Local Augmentation [[IEEE Access 2021]](https://doi.org/10.1109/ACCESS.2021.3124525)
+ ADSAS: Self-Supervised Learning for Industrial Image Anomaly Detection by Simulating Anomalous Samples [[IJCIS 2023]](https://link.springer.com/article/10.1007/s44196-023-00328-0)
+ CutPaste: Self-supervised learning for anomaly detection and localization [[CVPR 2021]](http://arxiv.org/pdf/2104.04015)[[unofficial code]](https://github.com/Runinho/pytorch-cutpaste)
+ FEGAN: A Feature Extraction Based Approach for GAN Anomaly Detection and Localization [[IEEE Access 2024]](https://doi.org/10.1109/ACCESS.2024.3406438)
+ NSA: Natural Synthetic Anomalies for Self-supervised Anomaly Detection and Localization [[ECCV 2022]](https://arxiv.org/pdf/2109.15222.pdf)[[code]](https://github.com/hmsch/natural-synthetic-anomalies)
+ REB: Reducing Biases in Representation for Industrial Anomaly Detection [[KBS 2024]](https://arxiv.org/abs/2308.12577)[[code]](https://github.com/ShuaiLYU/REB)
+ VDDM: A Study on Data Augmentation Techniques for Visual Defect Detection in Manufacturing [[BVAu 2023]](https://doi.org/10.1007/978-3-662-66769-9_6)


### External-Dependent

+ DeSTSeg: Segmentation Guided Denoising Student-Teacher for Anomaly Detection [[CVPR 2023]](https://arxiv.org/abs/2211.11317)[[code]](https://github.com/apple/ml-destseg)
+ DRAEM: A Discriminatively Trained Reconstruction Embedding for Surface Anomaly Detection [[ICCV 2021]](http://arxiv.org/pdf/2108.07610)[[code]](https://github.com/vitjanz/draem)
+ MemSeg: A Semi-supervised Method for Image Surface Defect Detection Using Differences and Commonalities [[EAAI 2023]](https://arxiv.org/pdf/2205.00908.pdf)[[unofficial code]](https://github.com/TooTouch/MemSeg)


### Inpainting-Based

+ AMI-Net: Adaptive Mask Inpainting Network for Industrial Anomaly Detection and Localization [[TASE 2024]](https://ieeexplore.ieee.org/abstract/document/10445116)
+ CACL: Cutout as Augmentation in Contrastive Learning for Detecting Burn Marks in Plastic Granules [[JSSS 2024]](https://doi.org/10.5194/jsss-13-63-2024)
+ CDO: Collaborative Discrepancy Optimization for Reliable Image Anomaly Localization [[TII 2023]](https://arxiv.org/abs/2302.08769)
+ I3AD: Iterative Image Inpainting with Structural Similarity Mask for Anomaly Detection [[WACVW 2021]](https://openreview.net/pdf?id=b4ach0lGuYO)
+ InTra: Inpainting Transformer for Anomaly Detection [[ICIAP 2022]](https://arxiv.org/pdf/2104.13897.pdf)
+ RD4AD: Revisiting Reverse Distillation for Anomaly Detection [[CVPR 2023]](https://openaccess.thecvf.com/content/CVPR2023/html/Tien_Revisiting_Reverse_Distillation_for_Anomaly_Detection_CVPR_2023_paper.html)
+ RIAD: Reconstruction by Inpainting for Visual Anomaly Detection [[PR 2021]](https://www.sciencedirect.com/science/article/pii/S0031320320305094)
+ SMAI: Superpixel Masking and Inpainting for Self-Supervised Anomaly Detection [[BMVC 2020]](https://www.bmvc2020-conference.com/assets/papers/0275.pdf)


## Distribution Hypothesis-Based Models

### Prior-Dependent

+ ADSPR: Anomaly Detection using Score-based Perturbation Resilience [[ICCV 2023]](https://openaccess.thecvf.com/content/ICCV2023/papers/Shin_Anomaly_Detection_using_Score-based_Perturbation_Resilience_ICCV_2023_paper.pdf)
+ GLASS: A Unified Anomaly Synthesis Strategy with Gradient Ascent for Industrial Anomaly Detection and Localization [[ECCV 2024]](https://arxiv.org/abs/2407.09359)[[code]](https://github.com/cqylunlun/GLASS)
+ PBAS: Progressive Boundary Guided Anomaly Synthesis for Industrial Anomaly Detection [[TCSVT 2024]](https://ieeexplore.ieee.org/document/10716437)[[code]](https://github.com/cqylunlun/PBAS)
+ SPVAE: Manifolds for Unsupervised Visual Anomaly Detection [[arXiv 2020]](https://arxiv.org/abs/2006.11364)


### Data-Driven

+ DSR: A Dual Subspace Re-projection Network for Surface Anomaly Detection [[ECCV 2022]](https://arxiv.org/pdf/2208.01521.pdf)[[code]](https://github.com/VitjanZ/DSR_anomaly_detection)
+ SimpleNet: A Simple Network for Image Anomaly Detection and Localization [[CVPR 2023]](https://github.com/DonaldRR/SimpleNet)[[code]](https://github.com/DonaldRR/SimpleNet)
+ SuperSimpleNet: Unifying Unsupervised and Supervised Learning for Fast and Reliable Surface Defect Detection [[ICPR 2025]](https://arxiv.org/abs/2408.03143)[[code]](https://github.com/blaz-r/SuperSimpleNet/tree/main)
+ UniAD: A Unified Model for Multi-class Anomaly Detection [[NeurIPS 2022]](https://arxiv.org/pdf/2206.03687.pdf)[[code]](https://github.com/zhiyuanyou/UniAD)


## GM-Based Models

### Full-Image Synthesis

+ Con-GAN: A New Contrastive GAN with Data Augmentation for Surface Defect Recognition under Limited Data [[TIM 2022]](https://ieeexplore.ieee.org/abstract/document/9999697/)
+ Defect Spectrum: A Granular Look of Large-Scale Defect Datasets with Rich Semantics [[ECCV 2025]](https://openreview.net/forum?id=RLhS1TrjK3)[[data]](https://github.com/EnVision-Research/Defect_Spectrum)
+ DFMGAN: Few-shot Defect Image Generation via Defect-aware Feature Manipulation [[AAAI 2023]](https://arxiv.org/abs/2303.02389)[[code]](https://github.com/Ldhlwh/DFMGAN)
+ Multistage GAN: Multistage GAN for Fabric Defect Detection [[TIP 2019]](https://pubmed.ncbi.nlm.nih.gov/31870985/)
+ RealNet: A Feature Selection Network with Realistic Synthetic Anomaly for Anomaly Detection [[CVPR 2024]](https://arxiv.org/abs/2403.05897)[[code]](https://github.com/cnulab/RealNet)


### Full-Image Translation

+ AttenCGAN: A New Cycle-consistent Adversarial Networks with Attention Mechanism for Surface Defect Classification with Small Samples [[TII 2022]](https://ieeexplore.ieee.org/abstract/document/9760037/)
+ CycleGAN: Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks [[ICCV 2017]](https://arxiv.org/abs/1703.10593)[[code]](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)
+ Defect-GAN: High-fidelity Defect Synthesis for Automated Defect Inspection [[WACV 2021]](https://openaccess.thecvf.com/content/WACV2021/html/Zhang_Defect-GAN_High-Fidelity_Defect_Synthesis_for_Automated_Defect_Inspection_WACV_2021_paper.html)
+ Pix2Pix: Image-to-Image Translation with Conditional Adversarial Networks [[CVPR 2017]](https://arxiv.org/abs/1611.07004)[[code]](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)
+ SDGAN: Defect Image Sample Generation with GAN for Improving Defect Recognition [[TASE 2020]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9000806)


### Local Anomaly Synthesis

+ DCDGANc: Diversified and Multi-Class Controllable Industrial Defect Synthesis for Data Augmentation and Transfer [[CVPRW 2023]](https://openaccess.thecvf.com/content/CVPR2023W/VISION/html/Wei_Diversified_and_Multi-Class_Controllable_Industrial_Defect_Synthesis_for_Data_Augmentation_CVPRW_2023_paper.html)
+ MDGAN: Mask-guided Generation Method for Industrial Defect Images with Non-uniform Structures [[Machines 2022]](https://www.mdpi.com/2075-1702/10/12/1239)
+ Open-set Fabric: Open-Set Fabric Defect Detection with Defect Generation and Transfer [[TIM 2025]](https://doi.org/10.1109/TIM.2025.3547485)
+ SARD: Segmentation-Aware Anomaly Synthesis via Region-Constrained Diffusion with Discriminative Mask Guidance [[MIND 2025]](https://doi.org/10.1109/MIND67540.2025.11351901)


## Vision-Language Models-Based Models

### Single-Stage Generation

+ AnoGen: Few-Shot Anomaly-Driven Generation for Anomaly Classification and Segmentation [[ECCV 2024]](https://csgaobb.github.io/Pub_files/ECCV2024_AnoGen_CR_0730_Mobile.pdf)[[code]](https://github.com/gaobb/AnoGen)
+ AnomalyAny: Unseen Visual Anomaly Generation [[CVPR 2025]](https://openaccess.thecvf.com/content/CVPR2025/html/Sun_Unseen_Visual_Anomaly_Generation_CVPR_2025_paper.html)[[code]](https://github.com/EPFL-IMOS/AnomalyAny)
+ AnomalyControl: Learning Cross-modal Semantic Features for Controllable Anomaly Synthesis [[arXiv 2024]](https://arxiv.org/abs/2412.06510)[[code]](https://github.com/DaniellaHe/AnomalyControl)
+ AnomalyXFusion: Multi-modal Anomaly Synthesis with Diffusion [[arXiv 2024]](https://arxiv.org/abs/2404.19444)[[code]](https://github.com/hujiecpp/MVTec-Caption)
+ CAGEN: Controllable Anomaly Generator using Diffusion Model [[ICASSP 2024]](https://ieeexplore.ieee.org/document/10447663)
+ CUT: A Controllable, Universal, and Training-Free Visual Anomaly Generation Framework [[arXiv 2024]](https://arxiv.org/abs/2406.01078)
+ DefectFill: Realistic Defect Generation with Inpainting Diffusion Model for Visual Inspection [[CVPR 2025]](https://openaccess.thecvf.com/content/CVPR2025/html/Song_DefectFill_Realistic_Defect_Generation_with_Inpainting_Diffusion_Model_for_Visual_Inspection_CVPR_2025_paper.html)
+ FAST: Foreground-aware Diffusion with Accelerated Sampling Trajectory for Segmentation-oriented Anomaly Synthesis [[NeurIPS 2025]](https://openreview.net/forum?id=qqEfm8tlCM)
+ TF-IDG: Training-Free Industrial Defect Generation with Diffusion Models [[ICCV 2025]](https://openaccess.thecvf.com/content/ICCV2025/html/Xu_Training-Free_Industrial_Defect_Generation_with_Diffusion_Models_ICCV_2025_paper.html)


### Multi-Stage Generation

+ AdaBLDM: A Novel Approach to Industrial Defect Generation through Blended Latent Diffusion Model with Online Adaptation [[arXiv 2024]](https://arxiv.org/abs/2402.19330)[[code]](https://github.com/GrandpaXun242/AdaBLDM)
+ AnomalyDiffusion: Few-Shot Anomaly Image Generation with Diffusion Model [[AAAI 2024]](https://ojs.aaai.org/index.php/AAAI/article/view/28696)[[code]](https://github.com/sjtuplayer/anomalydiffusion)
+ BeltDiff: Diffusion-based Self-labeled Generation System for Conveyor Belt Damage Detection [[EAAI 2025]](https://doi.org/10.1016/j.engappai.2025.112287)
+ DefectDiffu: Few-shot Defect Image Generation based on Consistency Modeling [[ECCV 2024]](https://arxiv.org/abs/2408.00372)[[code]](https://github.com/FFDD-diffusion/DefectDiffu)
+ DualAnoDiff: Dual-Interrelated Diffusion Model for Few-Shot Anomaly Image Generation [[arXiv 2024]](https://arxiv.org/abs/2408.13509)[[code]](https://github.com/yinyjin/DualAnoDiff)
+ GAA: Generate Aligned Anomaly: Region-Guided Few-Shot Anomaly Image-Mask Pair Synthesis for Industrial Inspection [[ACM MM 2025]](https://dl.acm.org/doi/10.1145/3746027.3755081)
+ SeaS: Few-shot Industrial Anomaly Image Generation with Separation and Sharing Fine-tuning [[ICCV 2025]](https://openaccess.thecvf.com/content/ICCV2025/papers/Dai_SeaS_Few-shot_Industrial_Anomaly_Image_Generation_with_Separation_and_Sharing_ICCV_2025_paper.pdf)
+ TDAD: Self-supervised Industrial Anomaly Detection with a Two-stage Diffusion Model [[Computers in Industry 2025]](https://doi.org/10.1016/j.compind.2024.104192)
