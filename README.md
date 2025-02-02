# Awesome-Vision-Mamba-Models

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/Ruixxxx/Awesome-Vision-Mamba-Models?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/Ruixxxx/Awesome-Vision-Mamba-Models?style=flat-square)
[![Arxiv Page](https://img.shields.io/badge/Arxiv-2404.18861-red?style=flat-square)](https://arxiv.org/abs/2404.18861)

[NEWS.2024/04/29] **Our [paper](https://arxiv.org/abs/2404.18861) is released!**

📢**NOTE:** If you have any questions, please don't hesitate to contact us at any of the following emails: [rui.xu@whu.edu.cn](mailto:rui.xu@whu.edu.cn), [syangcw@connect.ust.hk](mailto:syangcw@connect.ust.hk), [ywangrm@connect.ust.hk](mailto:ywangrm@connect.ust.hk).

Mamba, a novel state space model, has gained recognition across diverse domains for its exceptional performance and efficient computational complexity. By addressing the limitations inherent in traditional visual foundation models, Mamba emerges as a promising contender poised to catalyze advancements in the field of computer vision.

:star: This repository hosts a curated collection of literature associated with Mamba models in computer vision. Feel free to star and fork. For further details, refer to the following paper:

**[A Survey on Vision Mamba: Models, Applications and Challenges](https://arxiv.org/abs/2404.18861)**<br/>
Rui Xu, Shu Yang, Yihui Wang, Bo Du, [Hao Chen](https://cse.hkust.edu.hk/~jhc/)<br/>
[SMART Lab](https://hkustsmartlab.netlify.app/), The Hong Kong University of Science and Technology<br/>
<br/>

If you find this repository is useful for you, please cite our paper:
```
@misc{2024vision_mamba,
      title={A Survey on Vision Mamba: Models, Applications and Challenges}, 
      author={Rui Xu and Shu Yang and Yihui Wang and Bo Du and Hao Chen},
      year={2024},
      eprint={},
      archivePrefix={arXiv 2404.18861},
      primaryClass={}
}
```

## Contents
- [Backbone](#backbone-for-representation-learning)
- [Related Survery](#related-survey)
- [Vision Application (Modality)](#vision-application)
  - [Image](#image)
    - [Natural Image](#natural-image)
    - [Remote Sensing Image](#remote-sensing-image)
    - [Medical Image](#medical-image)
  - [Video](#video)
  - [Multi-Modal](#multi-modal)
  - [Point Cloud](#point-cloud)
  - [Others](#others)
- [Other Domains](#other-domains)
  - [Reinforcement Learning](#reinforcement-learning)
  - [Graph Learning](#graph-learning)
  - [Mixture of Experts](#moe)

## Backbone for Representation Learning
<img width="361" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/555f0cf1-f909-4e62-b293-699e271cc45b">


[Detailed Performance Comparison](SOTA_Results.md)


| Date      | Paper | Figure    | Link | Code         |
| :-------- | :---- | :-------- | :--- | :----------- |
| Arxiv 24.01.17 | Vision Mamba: Efficient Visual Representation Learning with Bidirectional State Space Model|<img width="684" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/6d32c807-3d2f-457e-8927-fa4bbe595064"> |[link](https://arxiv.org/abs/2401.09417)|[code](https://github.com/hustvl/Vim)|
| Arxiv 24.01.18 | VMamba: Visual State Space Model | <img width="806" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/039e24f6-5f89-4772-bb84-7409aeef4da0"> <img width="833" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/75158bbf-18e9-45fc-93e0-7d84c062ed0d"> | [Link](https://arxiv.org/abs/2401.10166) | [code](https://github.com/MzeroMiko/VMamba) |
| Arxiv 24.02.08 | Mamba-ND: Selective State Space Modeling for Multi-Dimensional Data | <img width="712" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/0ee52771-63ec-4e1d-bd24-aff9fe83c8e6"> | [Link](https://arxiv.org/pdf/2402.05892) | [code](https://github.com/jacklishufan/Mamba-ND) |
| Arxiv 24.03.14 | LocalMamba: Visual State Space Model with Windowed Selective Scan| <img width="710" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/1c2bcfb8-72d0-4f33-b561-f926952455ff"> | [Link](https://arxiv.org/pdf/2403.09338) | [code](https://github.com/hunto/LocalMamba) |
| Arxiv 24.03.15 | EfficientVMamba: Atrous Selective Scan for Light Weight Visual Mamba | <img width="719" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/7e034c04-3359-456e-a2b3-720b4b37e975"> | [Link](https://arxiv.org/pdf/https://arxiv.org/pdf/2403.09977) | [code](https://github.com/TerryPei/EfficientVMamba) |
| Arxiv 24.03.22 | SiMBA: Simplified Mamba-based Architecture for Vision and Multivariate Time series | <img width="622" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/bef43ea0-0d1e-4c2f-93e1-231b41394195"> | [Link](https://arxiv.org/pdf/2403.15360) | [code](https://github.com/badripatro/Simba) |
| Arxiv 24.03.26 | PlainMamba: Improving Non-Hierarchical Mamba in Visual Recognition | <img width="713" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/d1170f9a-b9b2-4c4d-ab44-cd6c52a07c8d"> | [Link](https://arxiv.org/pdf/2403.17695) | [code](https://github.com/ChenhongyiYang/PlainMamba) |



## Related Survey

| Date      | Paper | Link | 
| :-------- | :---- | :-------- |
| Arxiv 24.04.15|State Space Model for New-Generation Network Alternative to Transformers: A Survey | [Link](https://arxiv.org/pdf/2404.09516) |
| Arxiv 24.04.24|A Survey on Visual Mamba | [Link](https://arxiv.org/pdf/2404.15956v2) | 
| Arxiv 24.04.24|Mamba-360: Survey of State Space Models as Transformer Alternative for Long Sequence Modelling: Methods, Applications, and Challenges | [Link](https://arxiv.org/pdf/2404.16112) | 

## Vision Application
### Image

#### Natural Image

| Date      | Paper | Figure    | Link | Code         | Task |
| :-------- | :---- | :-------- | :--- | :----------- | :--- |
| Arxiv 24.02.06| U-shaped Vision Mamba for Single Image Dehazing | <img width="848" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/3ca0831b-711c-4073-841e-2eba4f2e718d"> | [Link](https://arxiv.org/pdf/2402.04139) | [Code](https://github.com/zzr-idam) | Dehazing/Low Light Enhancement/Deraining |
| Arxiv 24.02.23| MambaIR: A Simple Baseline for Image Restoration with State-Space Model | <img width="708" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/22041ebc-cae7-4e72-a537-a7af3429b6d8"> | [Link](https://arxiv.org/pdf/2402.15648) | [Code](https://github.com/csguoh/MambaIR) | Super-resolution/Denoising |
| Arxiv 24.03.04| MiM-ISTD: Mamba-in-Mamba for Efficient Infrared Small Target Detection | <img width="847" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/c38ffac7-65b7-452c-b0ec-c3a17f8de860"> | [Link](https://arxiv.org/pdf/2403.02148) | [Code](https://github.com/txchen-USTC/MiM-ISTD) | Infrared Image Segmentation |
| Arxiv 24.03.07| InstructGIE: Towards Generalizable Image Editing | <img width="912" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/45b0c86f-f473-4eb7-a821-7be8e3be417d"> | [Link](https://arxiv.org/pdf/2403.05018) | | Image Editing |
| Arxiv 24.03.13| Activating Wider Areas in Image Super-Resolution | <img width="700" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/dfaf5b9a-19e0-4058-a4aa-a9af26df6334"> | [Link](https://arxiv.org/pdf/2403.08330) | | Super-resolution |
| Arxiv 24.03.20| ZigMa: A DiT-style Zigzag Mamba Diffusion Model | <img width="702" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/3a14b8da-188b-4c00-a054-c4cb47562f9e"> | [Link](https://arxiv.org/pdf/2403.13802) | [Code](https://taohu.me/zigma/) | Generation |
| Arxiv 24.03.27| Gamba: Marry Gaussian Splatting with Mamba for single view 3D reconstruction | <img width="564" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/361b14b9-6291-47d1-b8e0-ae667db5aa22"> | [Link](https://arxiv.org/pdf/2403.18795) | | 3D Reconstruction |
| Arxiv 24.04.09| MambaAD: Exploring State Space Models for Multi-class Unsupervised Anomaly Detection |<img width="793" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/0d601311-b0bf-48e1-b0d6-17ee9c3101d0">  | [Link](https://arxiv.org/pdf/2404.06564) | [code](https://lewandofskee.github.io/projects/MambaAD) | Anomaly Detection |
| Arxiv 24.04.11| DGMamba: Domain Generalization via Generalized State Space Model |<img width="720" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/50d5a8bb-d701-40a1-9f17-52a7d9c96221"> | [Link](https://arxiv.org/pdf/2404.07794) | [code](https://github.com/longshaocong/DGMamba) | Domain Generalization |
| Arxiv 24.04.15| FreqMamba: Viewing Mamba from a Frequency Perspective for Image Deraining | <img width="798" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/430aabed-9c3f-40f5-b062-d748829d20fa"> | [Link](https://arxiv.org/pdf/2404.09476) |  | Deraining |
| Arxiv 24.04.17| CU-Mamba: Selective State Space Models with Channel Learning for Image Restoration | <img width="1102" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/d4c0ac33-8541-4cf0-84aa-bd5b0958516f"> | [Link](https://arxiv.org/pdf/2404.11778) | | Denoising/Deblurring |
| Arxiv 24.04.22| MambaUIE: Unraveling the Ocean's Secrets with Only 2.8 FLOPs | <img width="687" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/7e84a297-ea0f-4e27-b9cc-cdb36b2b0e6f"> | [Link](https://arxiv.org/pdf/2404.13884) | [Code](https://github.com/1024AILab/MambaUIE) | Image Enhancement |

#### Remote Sensing Image

| Date      | Paper | Figure    | Link | Code         | Task |
| :-------- | :---- | :-------- | :--- | :----------- | :--- |
| Arxiv 24.02.19| Pan-Mamba: Effective pan-sharpening with State Space Model | <img width="716" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/9cead6ad-ce09-4597-a985-8181b407523d"> | [Link](https://arxiv.org/pdf/2402.12192) | [Code](https://github.com/alexhe101/Pan-Mamba) | Pan-sharpening |
| Arxiv 24.03.28| RSMamba: Remote Sensing Image Classification with State Space Model | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/5a8fd6df-ad6f-41fb-a0d7-7fce465566c1)  | [Link](https://arxiv.org/pdf/2403.19654) | [Code](https://github.com/KyanChen/RSMamba) | Remote Sensing Images Classification| 
| Arxiv 24.04.02| Samba: Semantic Segmentation of Remotely Sensed Images with State Space Model | <img width="402" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/c64ee6cc-ced1-4d27-b1af-27582f089fb0"> | [Link](https://arxiv.org/pdf/2404.01705) | [Code](https://github.com/zhuqinfeng1999/Samba) | Semantic Segmentation |
| Arxiv 24.04.03| RS3Mamba: Visual State Space Model for Remote Sensing Images Semantic Segmentation | <img width="502" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/1767d964-15ea-4085-a1f0-937cba3cf915"> | [Link](https://arxiv.org/pdf/2404.02457) | [Code](https://github.com/sstary/SSRS) | Semantic Segmentation |
| Arxiv 24.04.03| RS-Mamba for Large Remote Sensing Image Dense Prediction | <img width="942" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/4c47c3b7-5df8-4d77-93ba-d35263916f03"> | [Link](https://arxiv.org/pdf/2404.02668) | [Code](https://github.com/walking-shadow/Official_Remote_Sensing_Mamba) | Semantic Segmentation/Change Detection |
| Arxiv 24.04.04| ChangeMamba: Remote Sensing Change Detection with Spatio-Temporal State Space Model | <img width="1023" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/476bf8d5-625e-4e65-ad19-bc14817c9a58">  | [Link](https://arxiv.org/pdf/2404.03425) | [Code](https://github.com/ChenHongruixuan/MambaCD) | Change Detection/Building Damage Assessment |
| Arxiv 24.04.12| SpectralMamba: Efficient Mamba for Hyperspectral Image Classification | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/ed4437bb-a15b-4818-8dad-8fa7ac7c0213) | [Link](https://arxiv.org/pdf/2404.08489) | [Code](https://github.com/danfenghong/SpectralMamba) | Hyperspectral Image Classification |
| Arxiv 24.04.15| HSIDMamba: Exploring Bidirectional State-Space Models for Hyperspectral Denoising | <img width="947" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/91ebd913-ef36-400e-a83c-8d24fc5536b3"> | [Link](https://arxiv.org/pdf/2404.09697) | | Hyperspectral Denoising |

#### Medical Image

| Date      | Paper | Figure    | Link | Code         | Task |
| :-------- | :---- | :-------- | :--- | :----------- | :--- |
| Arxiv 24.01.09| U-Mamba: Enhancing Long-range Dependency for Biomedical Image Segmentation | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/0bb9063c-ee32-4269-a803-778f2c6f2d64) | [Link](https://arxiv.org/pdf/2401.04722) | [Code](https://wanglab.ai/u-mamba.html) | 2D Medical Segmentation/ </br> 3D Medical Segmentation |
| Arxiv 24.01.24| SegMamba: Long-range Sequential Modeling Mamba For 3D Medical Image Segmentation | <img width="635" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/690c8341-1f17-4f8f-929a-d7f31094ad64"> | [Link](https://arxiv.org/pdf/2401.13560) | [Code](https://github.com/ge-xing/SegMamba) |3D Medical Segmentation|
| Arxiv 24.02.04| VM-UNet: Vision Mamba UNet for Medical Image Segmentation | <img width="544" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/320dda01-12dc-4e37-992d-8551c99b475a"> | [Link](https://arxiv.org/pdf/2402.02491) | [Code](https://github.com/JCruan519/VM-UNet) | 2D Medical Segmentation |
| Arxiv 24.02.05| nnMamba: 3D Biomedical Image Segmentation, Classification and Landmark Detection with State Space Model | <img width="949" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/2b1669ec-d1f5-4c6c-a743-1620ab83fef3"> | [Link](https://arxiv.org/pdf/2402.03526) | [Code](https://github.com/lhaof/nnMamba) | 3D Medical Segmentation |
| Arxiv 24.02.05| Swin-UMamba: Mamba-based UNet with ImageNet-based pretraining | <img width="711" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/2b1c8b89-2b8c-4273-ae25-833f87fc97c2"> | [Link](https://arxiv.org/pdf/2402.03302) | [Code](https://github.com/JiarunLiu/Swin-UMamba) | 2D Medical Segmentation |
| Arxiv 24.02.07| Mamba-UNet: UNet-Like Pure Visual Mamba for Medical Image Segmentation | <img width="698" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/0a09dda6-986b-480d-8445-1db4a02f16f1"> | [Link](https://arxiv.org/pdf/2402.05079) | [Code](https://github.com/ziyangwang007/MambaUNet) | 2D Medical Segmentation |
| Arxiv 24.02.09| FD-Vision Mamba for Endoscopic Exposure Correction | <img width="666" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/f87cc9c6-efa9-40ca-bf76-af7dd19b2277"> | [Link](https://arxiv.org/pdf/2402.06378) | [Code](https://github.com/zzr-idam/FDVM-Net) | Endoscopic Exposure Correction |
| Arxiv 24.02.11| Semi-Mamba-UNet: Pixel-Level Contrastive Cross-Supervised Visual Mamba-based UNet for Semi-Supervised Medical Image Segmentation | <img width="623" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/e702b599-682b-42b0-8477-a72972843803"> | [Link](https://arxiv.org/pdf/2402.07245) | [Code](https://github.com/ziyangwang007/Mamba-UNet) | 2D Medical Segmentation |
| Arxiv 24.02.13| P-Mamba: Marrying Perona Malik Diffusion with Mamba for Efficient Pediatric Echocardiographic Left Ventricular Segmentation | <img width="717" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/cbbc8a01-b1bb-44bf-8954-4485605a8326"> | [Link](https://arxiv.org/pdf/2402.08506v2) | | 2D Medical Segmentation |
| Arxiv 24.02.16| Weak-Mamba-UNet: Visual Mamba Makes CNN and ViT Work Better for Scribble-based Medical Image Segmentation | <img width="706" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/909947ae-9ba2-47f9-b257-620663d55820"> | [Link](https://arxiv.org/pdf/2402.10887) | [Code](https://github.com/ziyangwang007/Mamba-UNet) | 2D Medical Segmentation|
| Arxiv 24.02.28| MambaMIR: An Arbitrary-Masked Mamba for Joint Medical Image Reconstruction and Uncertainty Estimation |<img width="733" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/ea55e5c2-27bb-4155-a1b3-769fbb46c1f3"> | [Link](https://arxiv.org/pdf/2402.18451v1) | [Code](https://github.com/ayanglab/MambaMIR) | Medical Image Reconstruction/Uncertainty Estimation |
| Arxiv 24.03.06| MedMamba: Vision Mamba for Medical Image Classification | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/40c97c50-9c24-41e2-b449-d1cf9a58c887) | [Link](https://arxiv.org/pdf/2403.03849) | [Code](https://github.com/YubiaoYue/MedMamba) | 2D Medical Classification |
| Arxiv 24.03.08| LightM-UNet: Mamba Assists in Lightweight UNet for Medical Image Segmentation | <img width="587" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/20237455-6ec6-49a1-81ba-05553c69910d"> | [Link](https://arxiv.org/pdf/2403.05246) | [Code](https://github.com/MrBlankness/LightM-UNet) | 2D Medical Segmentation/ </br> 3D Medical Segmentation |
| Arxiv 24.03.08| MamMIL: Multiple Instance Learning for Whole Slide Images with State Space Models | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/44567e8c-0cc8-4cc7-a4ed-a2376bfea6ae) | [Link](https://arxiv.org/pdf/2403.05160) | | Cancer Subtyping |
| Arxiv 24.03.11| MambaMIL: Enhancing Long Sequence Modeling with Sequence Reordering in Computational Pathology | <img width="516" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/fc147a4e-8a81-4862-b222-b52929def042"> | [Link](https://arxiv.org/pdf/2403.06800) | [Code](https://github.com/isyangshu/MambaMIL) | Cancer Subtyping/ </br> Survival Prediction |
| Arxiv 24.03.12| Large Window-based Mamba UNet for Medical Image Segmentation: Beyond Convolution and Self-attention | <img width="848" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/2e91f2b6-e13d-48b1-9012-91b8ce5f1f43"> | [Link](https://arxiv.org/pdf/2403.07332) | [Code](https://github.com/wjh892521292/LMa-UNet) | 2D Medical Segmentation/ </br> 3D Medical Segmentation |
| Arxiv 24.03.13| MD-Dose: A Diffusion Model based on the Mamba for Radiotherapy Dose Prediction | <img width="683" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/4440c5f1-1197-4295-b585-52314a144539"> | [Link](https://arxiv.org/pdf/2403.08479) | [Code](https://github.com/flj19951219/mamba_dose) | Radiation Dose Prediction (Segmentation) |
| Arxiv 24.03.14| VM-UNET-V2 Rethinking Vision Mamba UNet for Medical Image Segmentation | <img width="702" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/3f285231-30db-4737-a790-e69f0646d155"> | [Link](https://arxiv.org/pdf/2403.09157) | [Code](https://github.com/nobodyplayer1/VM-UNetV2) | 2D Medical Segmentation |
| Arxiv 24.03.20|H-vmunet: High-order Vision Mamba UNet for Medical Image Segmentation| <img width="748" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/88ae6463-46e9-4c84-a658-160bbbf4d9cf"> | [Link](https://arxiv.org/pdf/2403.13642) | [Code](https://github.com/wurenkai/H-vmunet) | 2D Medical Segmentation |
| Arxiv 24.03.20| ProMamba: Prompt-Mamba for polyp segmentation | <img width="741" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/56106afc-1d80-42db-bb9f-a6daaed7abc8"> | [Link](https://arxiv.org/pdf/2403.13660) | | 2D Medical Segmentation |
| Arxiv 24.03.25| CMViM: Contrastive Masked Vim Autoencoder for 3D Multi-modal Representation Learning for AD classification | <img width="707" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/c71f93de-e730-40b2-bb23-74a07c868ab7"> | [Link](https://arxiv.org/pdf/2403.16520) | | Alzheimer’s disease Classification (CT/MRI)|
| Arxiv 24.03.26| Integrating Mamba Sequence Model and Hierarchical Upsampling Network for Accurate Semantic Segmentation of Multiple Sclerosis Legion |  <img width="622" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/c0b134c5-f7e4-4794-86e2-b20ddca84469"> | [Link](https://arxiv.org/pdf/2403.17432) | | 2D Medical Segmentation（2D MRI） |
| Arxiv 24.03.29| UltraLight VM-UNet: Parallel Vision Mamba Significantly Reduces Parameters for Skin Lesion Segmentation | <img width="725" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/14d04b8b-cbe6-429d-984d-3ac7dd894bf3"> | [Link](https://arxiv.org/pdf/2403.20035) | [Code](https://github.com/wurenkai/UltraLight-VM-UNet) | 2D Medical Segmentation |
| Arxiv 24.03.26| Rotate to Scan: UNet-like Mamba with Triplet SSM Module for Medical Image Segmentation | <img width="830" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/100bc4e7-65e1-43d9-815d-99b394e12b4f"> | [Link](https://arxiv.org/pdf/2403.17701) |  | 2D Medical Segmentation |
| Arxiv 24.04.01| T-Mamba: Frequency-Enhanced Gated Long-Range Dependency for Tooth 3D CBCT Segmentation | <img width="603" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/b01c38ef-6623-4e9b-867b-ba6f39575b5c"> | [Link](https://arxiv.org/pdf/2404.01065) | [Code](https://github.com/isbrycee/T-Mamba) | 3D Medical Segmentation (Tooth) |
| Arxiv 24.04.10| ViM-UNet: Vision Mamba for Biomedical Segmentation | <img width="581" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/1c32deb4-7695-4cb6-bbc7-5912a69bed98"> | [Link](https://arxiv.org/pdf/2404.07705) | [Code](https://github.com/constantinpape/torch-em/blob/main/vimunet.md) | 2D Medical Segmentation (Cell/Neurite) |
| Arxiv 24.04.19| Vim4Path: Self-Supervised Vision Mamba for Histopathology Images | <img width="939" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/9e5d4ef7-89f5-47da-bf5e-38367997f54f"> | [Link](https://arxiv.org/pdf/2404.13222) | [Code](https://github.com/AtlasAnalyticsLab/Vim4Path) | Cancer Subtyping |
| Arxiv 24.04.26| Optimizing Universal Lesion Segmentation: State Space Model-Guided Hierarchical Networks with Feature Importance Adjustment | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/8677a439-1c4b-4b4e-8dc1-f0003167c855) | [Link](https://arxiv.org/pdf/2404.17235) |  | Universal Lesion Segmentation |
| Arxiv 24.04.26| Sparse Reconstruction of Optical Doppler Tomography Based on State Space Model | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/383012cc-e1f4-40b1-94f3-46156ae240ad) | [Link](https://arxiv.org/pdf/2404.17484) |  | ODT Sparse Reconstruction |


### Video

| Date      | Paper | Figure    | Link | Code         | Task |
| :-------- | :---- | :-------- | :--- | :----------- | :--- |
| Arxiv 24.01.25| Vivim: a Video Vision Mamba for Medical Video Object Segmentation | <img width="596" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/e30c0ceb-5399-44b5-99b7-65ada043c87c"> | [Link](https://arxiv.org/pdf/2401.14168) | [Code](https://github.com/scott-yjyang/Vivim) | Medical Video Segmentation |
| Arxiv 24.03.11| VideoMamba: State Space Model for Efficient Video Understanding | <img width="728" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/08797465-f93f-49ce-b724-91b67fabbabd"> | [Link](https://arxiv.org/pdf/2403.06977) | [Code](https://github.com/OpenGVLab/VideoMamba) | Action Recognition/Video Understanding/Text-to-video Retrieval |
| Arxiv 24.03.14| Video Mamba Suite: State Space Model as a Versatile Alternative for Video Understanding | <img width="704" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/70fb7829-d28e-4bbc-b326-fcb167dad979"> | [Link](https://arxiv.org/pdf/2403.09626) | [Code](https://github.com/OpenGVLab/video-mamba-suite) | Action Recognition/Action Localization/... |
| Arxiv 24.04.09| RhythmMamba: Fast Remote Physiological Measurement with Arbitrary Length Videos | <img width="881" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/f1b0f8a1-f10f-43c6-8203-701ae0376af2"> | [Link](https://arxiv.org/pdf/2404.06483) | [Code](https://github.com/zizhengguo/RhythmMamba) | Remote photoplethysmography  Prediction |
| Arxiv 24.04.11| Simba: Mamba augmented U-ShiftGCN for Skeletal Action Recognition in Videos | <img width="697" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/ea35cf6a-e2a6-4eab-8da7-2cb7cd098507"> | [Link](https://arxiv.org/pdf/2404.07645) | | Skeleton Action Recognition|

### Multi-Modal

| Date      | Paper | Figure    | Link | Code         | Task | Modality|
| :-------- | :---- | :-------- | :--- | :----------- | :--- | :--- | 
| Arxiv 24.01.25| MambaMorph: a Mamba-based Framework for Medical MR-CT Deformable Registration | <img width="705" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/0584bfee-1ed2-4d5b-984e-c374491adab9"> | [Link](https://arxiv.org/pdf/2401.13934) | [Code](https://github.com/Guo-Stone/MambaMorph) | Registration | MRI & CT| 
| Arxiv 24.03.12| Motion Mamba: Efficient and Long Sequence Motion Generation with Hierarchical and Bidirectional Selective SSM | <img width="910" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/9ef9c705-657d-4b6d-b229-6e2e4270682f"> | [Link](https://arxiv.org/pdf/2403.07487) | [Code](https://steve-zeyu-zhang.github.io/MotionMamba) | Text-to-Motion Generation | Motion & Text| 
| Arxiv 24.03.16| ReMamber: Referring Image Segmentation with Mamba Twister | <img width="715" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/08c3e6e4-49ca-4081-bea6-ed4c7b046c0b"> | [Link](https://arxiv.org/pdf/2403.17839) | | Referring Image Segmentation | Image & Text | 
| Arxiv 24.03.20| VL-Mamba: Exploring State Space Models for Multimodal Learning | <img width="718" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/aa912eb8-13a7-488f-9601-d298ed6796e2"> | [Link](https://arxiv.org/pdf/2403.13600) | [Code](https://yanyuanqiao.github.io/vl-mamba) | MLLM tasks | Image & Text | 
| Arxiv 24.03.21| Cobra: Extending Mamba to Multi-Modal Large Language Model for Efficient Inference | <img width="626" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/df845d03-3739-4b78-9328-6c2df2e98aad"> | [Link](https://arxiv.org/pdf/2403.14520) | [Code](https://sites.google.com/view/cobravlm) | MLLM tasks | Image & Text | 
| Arxiv 24.04.01| SpikeMba: Multi-Modal Spiking Saliency Mamba for Temporal Video Grounding| <img width="727" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/04cba5ac-b2f0-4357-b447-1e14a1d2617b"> | [Link](https://arxiv.org/pdf/2404.01174) | | Temporal Video Grounding | Video & Text | 
| Arxiv 24.04.05| Sigma: Siamese Mamba Network for Multi-Modal Semantic Segmentation | <img width="702" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/a972740b-774c-4e14-a914-791aa5f519b8"> | [Link](https://arxiv.org/pdf/2404.04256) | [Code](https://github.com/zifuwan/Sigma) | Semantic Segmentation | RGB Images & Depth/Thermal Images | 
| Arxiv 24.04.07| VMambaMorph: a Multi-Modality Deformable Image Registration Framework based on Visual State Space Model with Cross-Scan Module | <img width="711" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/6d47fc18-f044-49ed-8724-941a4fe46ebc"> | [Link](https://arxiv.org/pdf/2404.05105) | [Code](https://github.com/ziyangwang007/VMambaMorph) | Registration | MRI & CT| 
| Arxiv 24.04.11| SurvMamba: State Space Model with Multi-grained Multi-modal Interaction for Survival Prediction| <img width="813" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/c9307069-4672-47ed-9706-1003a5ad5eff"> | [Link](https://arxiv.org/pdf/2404.08027) | | Cancer Subtyping/Survival Prediction | WSIs & Gene| 
| Arxiv 24.04.11| FusionMamba: Efficient Image Fusion with State Space Model| <img width="816" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/2182cfb2-fa6f-4dea-ab2b-d21b906a683f"> | [Link](https://arxiv.org/pdf/2404.07932) | | Pansharpening | HISR Images & LRMS Images| 
| Arxiv 24.04.12| MambaDFuse: A Mamba-based Dual-phase Model for Multi-modality Image Fusion | <img width="1035" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/5921c2d4-d50d-48a3-928a-1dc69a60deb6"> | [Link](https://arxiv.org/pdf/2404.08406) | | Multi-modality Image Fusion  | RGB & Thermal Images, MRI & CT/PET/SPECT| 
| Arxiv 24.04.14|Fusion-Mamba for Cross-modality Object Detection | <img width="902" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/97b716a5-f647-43d9-a1fe-dc8b2b02670d"> | [Link](https://arxiv.org/pdf/2404.09146) | | Visible-infrared Images Fusion | RGB Images & Infrared Images| 
| Arxiv 24.04.14|A Novel State Space Model with Local Enhancement and State Sharing for Image Fusion| <img width="1013" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/df942cab-7802-4314-b7a7-549439b74f06"> | [Link](https://arxiv.org/pdf/2404.09293) | |  Pansharpening | HISR Images & LRMS Images| 
| Arxiv 24.04.15| FusionMamba: Dynamic Feature Enhancement for Multimodal Image Fusion with Mamba | <img width="906" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/87093676-286c-4e35-89b7-7e573679cc67"> | [Link](https://arxiv.org/pdf/2404.09498) | [Code](https://github.com/millieXie/FusionMamba) | Image Fusion | RGB & Infrared Images, MRI & CT/PET/SPECT, PC & GFP| 
| Arxiv 24.04.17| Text-controlled Motion Mamba: Text-Instructed Temporal Grounding of Human Motion | <img width="810" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/f27aa176-65e2-44db-a172-56712e789729"> | [Link](https://arxiv.org/pdf/2404.11375) | |  Temporal Grounding| Motion & Text |
| Arxiv 24.04.24| CFMW: Cross-modality Fusion Mamba for Multispectral Object Detection under Adverse Weather Conditions | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/5384d699-ed2f-46f5-bc56-2e61c03d2a51) | [Link](https://arxiv.org/pdf/2404.16302) | [Code](https://github.com/lhy-zjut/CFMW) |  Visible-infrared Images Fusion | RGB Images & Infrared Images| 


### Point Cloud

| Date      | Paper | Figure    | Link | Code         | Task | 
| :-------- | :---- | :-------- | :--- | :----------- | :--- |
| Arxiv 24.02.16| PointMamba: A Simple State Space Model for Point Cloud Analysis | <img width="718" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/e252e787-0189-4f94-bea1-2944d50b18f4"> | [Link](https://arxiv.org/pdf/2402.10739) | [Code](https://github.com/LMD0311/PointMamba) | Classification, Part Segmentation |
| Arxiv 24.03.01| Point Cloud Mamba: Point Cloud Learning via State Space Model|<img width="692" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/6a315d04-afe6-41d1-b8d5-d931a891a681"> | [Link](https://arxiv.org/pdf/2403.00762) | [Code](https://github.com/SkyworkAI/PointCloudMamba) | Classification, Part Segmentation, Semantic Segmentation |
| Arxiv 24.03.11| Point Mamba: A Novel Point Cloud Backbone Based on State Space Model with Octree-Based Ordering Strategy| <img width="882" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/c1c7c020-28cc-4ca6-b271-1d3cf665243f"> | [Link](https://arxiv.org/pdf/2403.06467) | [Code](https://github.com/IRMVLab/Point-Mamba) | Classification, Semantic Segmentation |
| Arxiv 24.04.08|3DMambaIPF: A State Space Model for Iterative Point Cloud Filtering via Differentiable Rendering | <img width="1028" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/ab137b17-85c1-4b6c-96d4-9ae5bfd45a1b"> | [Link](https://arxiv.org/pdf/2404.05522) | | Point Cloud Filtering |
| Arxiv 24.04.10|3DMambaComplete: Exploring Structured State Space Model for Point Cloud Completion | <img width="1020" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/da19fb01-52bd-4a55-b0ca-9681fdaef9ed"> | [Link](https://arxiv.org/pdf/2404.07106) |  | Point Cloud Completion |
| Arxiv 24.04.23| Mamba3D: Enhancing Local Features for 3D Point Cloud Analysis via State Space Model| <img width="959" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/6b565138-1c2d-4201-bd34-8b4343a62ec9"> | [Link](https://arxiv.org/pdf/2404.14966) | | Classification, Part Segmentation |

### Others
| Date      | Paper | Figure    | Link | Code         | Task |
| :-------- | :---- | :-------- | :--- | :----------- | :--- |
| Arxiv 24.02.24|Res-VMamba: Fine-Grained Food Category Visual Classification Using Selective State Space Models with Deep Residual Learning | <img width="683" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/e8ed3e23-e305-4b8a-a706-0601c1ef3b1b"> | [Link](https://arxiv.org/pdf/2402.15761) | [Code](https://github.com/ChiShengChen/ResVMamba) | Food Classification |
| Arxiv 24.03.08|Motion-Guided Dual-Camera Tracker for Low-Cost Skill Evaluation of Gastric Endoscopy | <img width="943" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/4cce4533-8d35-4acc-8cb3-6ad44603dc04"> | [Link](https://arxiv.org/pdf/2403.05146) | [Code](https://github.com/PieceZhang/MotionDCTrack) | Endoscope Tip Tracking |
| Arxiv 24.03.14| MambaTalk: Efficient Holistic Gesture Synthesis with Selective State Space Models| <img width="429" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/42ea6b78-cb43-401b-9f81-764a521cfa17"> | [Link](https://arxiv.org/pdf/2403.09471) |  | Gesture Synthesis |
| Arxiv 24.03.15| On the low-shot transferability of [V]-Mamba? | <img width="440" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/8e5c32ed-e499-44c5-9c33-ef5cd6873140"> | [Link](https://arxiv.org/pdf/2403.10696) | | Few-shot Learning |
| Arxiv 24.03.22| Music to Dance as Language Translation using Sequence Models | <img width="541" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/3e647680-22c7-4885-9ada-f32d9288f1ba"> | [Link](https://arxiv.org/pdf/2403.15569) | [Code](http://github.com/meowatthemoon/MDLT) | Music-to-Dance |



## Other Domains
coming soon
### Reinforcement Learning

### Graph Learning

### MOE

