# Awesome-Motion-Diffusion-Models

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/fengshiwest/Awesome-Motion-Diffusion-Models) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

A collection of resources and papers on Motion Diffusion Models. 

*The template and some of the components are referenced from [Awesome-Diffusion-Model](https://github.com/heejkoo/Awesome-Diffusion-Models).*


## Contents
- [Datasets](#datasets)
  - [Text to Motion](#text-to-motion)
    - [HumanML3D](#humanml3d)
    - [KIT-ML](#kit-ml)
    - [BABEL](#babel)
  - [Audio to Motion](#audio-to-motion)
    - [AIST++](#aist++)
  - [Motion Prediction](#motion-prediction)
    - [Human3.6M](#human3.6m)
    - [AMASS](#amass)
    - [HumanEva](#humaneva)

- [Papers](#papers)
  - [Survey](#survey)
  - [Text to Motion](#text-to-motion-1)
  - [Audio to Motion](#audio-to-motion-1)
  - [Speech to Motion](#speech-to-motion)
  - [Text & Audio to Motion](#text-and-audio-to-motion)
  - [Motion Prediction](#motion-prediction-1)


# Datasets

## Text to Motion

### HumanML3D

**Generating Diverse and Natural 3D Human Motions from Text** \
*Chuan Guo, Shihao Zou, Xinxin Zuo, Sen Wang, Wei Ji, Xingyu Li, Li Cheng* \
CVPR 2022. [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_Generating_Diverse_and_Natural_3D_Human_Motions_From_Text_CVPR_2022_paper.pdf)] [[Project](https://ericguo5513.github.io/text-to-motion/)] [[Code](https://github.com/EricGuo5513/text-to-motion)]

### KIT-ML

**The KIT Motion-Language Dataset** \
*Matthias Plappert, Christian Mandery, Tamim Asfour* \
Big Data 2016. [[Paper](https://matthiasplappert.com/publications/2016_Plappert_Big-Data.pdf)] [[Project](https://motion-annotation.humanoids.kit.edu/dataset/)]

### BABEL

**BABEL: Bodies, Action and Behavior with English Labels** \
*Abhinanda R. Punnakkal, Arjun Chandrasekaran, Nikos Athanasiou, Alejandra Quiros-Ramirez, Michael J. Black* \
CVPR 2021. [[Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Punnakkal_BABEL_Bodies_Action_and_Behavior_With_English_Labels_CVPR_2021_paper.html)] [[Project](https://babel.is.tue.mpg.de/)] [[Code](https://github.com/abhinanda-punnakkal/BABEL)]

## Audio to Motion

### AIST++

**AI Choreographer: Music Conditioned 3D Dance Generation with AIST++** \
*Ruilong Li, Shan Yang, David A. Ross, Angjoo Kanazawa* \
ICCV 2021. [[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_AI_Choreographer_Music_Conditioned_3D_Dance_Generation_With_AIST_ICCV_2021_paper.pdf)] [[Project](https://google.github.io/aichoreographer/)] [[Code](https://github.com/google/aistplusplus_api)]

## Motion Prediction

### Human3.6M

**Human3.6M: Large Scale Datasets and Predictive Methods for 3D Human Sensing in Natural Environments** \
*Catalin Ionescu, Dragos Papava, Vlad Olaru, Cristian Sminchisescu* \
TPAMI 2014. [[Paper](http://vision.imar.ro/human3.6m/pami-h36m.pdf)] [[Project](http://vision.imar.ro/human3.6m/description.php)]

### AMASS

**AMASS: Archive of Motion Capture As Surface Shapes** \
*Naureen Mahmood, Nima Ghorbani, Nikolaus F. Troje, Gerard Pons-Moll, Michael J. Black* \
ICCV 2019. [[Paper](https://files.is.tue.mpg.de/black/papers/amass.pdf)] [[Project](https://amass.is.tue.mpg.de/)] [[Code](https://github.com/nghorbani/amass)]

### HumanEva

**HUMANEVA: Synchronized Video and Motion Capture Dataset and Baseline Algorithm for Evaluation of Articulated Human Motion**
IJCV 2010. [[Paper](https://link.springer.com/article/10.1007/s11263-009-0273-6)] [[Project](http://humaneva.is.tue.mpg.de/)]

# Papers

## Survey

## Text to Motion

**Human Motion Diffusion Model** \
*Guy Tevet, Sigal Raab, Brian Gordon, Yonatan Shafir, Amit H. Bermano, Daniel Cohen-Or* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14916)] [[Project](https://guytevet.github.io/mdm-page/)] [[Code](https://github.com/GuyTevet/motion-diffusion-model)]

**SinMDM: Single Motion Diffusion** \
*Anonymous Authors* \
[[Paper](https://sinmdm.github.io/SinMDM-page/annonymous_paper.pdf)] [[Project](https://sinmdm.github.io/SinMDM-page/)] [[Code](https://github.com/SinMDM/SinMDM)]

**PhysDiff: Physics-Guided Human Motion Diffusion Model** \
*Ye Yuan, Jiaming Song, Umar Iqbal, Arash Vahdat, Jan Kautz* \
arXiv 2022. [[Paper](https://arxiv.org/pdf/2212.02500.pdf)] [[Project](https://nvlabs.github.io/PhysDiff/)]

**MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model** \
*Mingyuan Zhang, Zhongang Cai, Liang Pan, Fangzhou Hong, Xinying Guo, Lei Yang, Ziwei Liu* \
arXiv 2022. [[Paper](https://arxiv.org/pdf/2208.15001.pdf)] [[Project](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html)] [[Code](https://github.com/mingyuan-zhang/MotionDiffuse)]

**FLAME: Free-form Language-based Motion Synthesis & Editing** \
*Jihoon Kim, Jiseob Kim, Sungjoon Choi* \
arXiv 2022. [[Paper](https://arxiv.org/pdf/2209.00349.pdf)]

**Diffusion Motion: Generate Text-Guided 3D Human Motion by Diffusion Model** \
*Zhiyuan Ren, Zhihong Pan, Xin Zhou, Le Kang* \
arXiv 2022. [[Paper](https://arxiv.org/pdf/2210.12315.pdf)]


**Executing your Commands via Motion Diffusion in Latent Space** \
*Xin Chen, Biao Jiang, Wen Liu, Zilong Huang, Bin Fu,Tao Chen, Jingyi Yu, Gang Yu* \
CVPR 2023. [[Paper](https://arxiv.org/pdf/2212.04048.pdf)] [[Project](https://chenxin.tech/mld/)] [[Code](https://github.com/chenfengye/motion-latent-diffusion)]

**InterGen: Diffusion-based Multi-human Motion Generation under Complex Interactions** \
*Han Liang, Wenqian Zhang, Wenxuan Li, Jingyi Yu, Lan Xu* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2304.05684)]

**Human Motion Diffusion as a Generative Prior** \
*Yonatan Shafir, Guy Tevet, Roy Kapon, Amit H. Bermano* \
arXiv 2023. [[Paper](https://arxiv.org/pdf/2303.01418.pdf)] [[Project](https://priormdm.github.io/priorMDM-page/)] [[Code](https://github.com/priorMDM/priorMDM)]

**Text2Performer: Text-Driven Human Video Generation** \
*Yuming Jiang, Shuai Yang, Tong Liang Koh, Wayne Wu, Chen Change Loy, Ziwei Liu* \
arXiv 2023. [[Paper](https://arxiv.org/pdf/2304.08483.pdf)] [[Project](https://yumingj.github.io/projects/Text2Performer.html)] [[Code](https://github.com/yumingj/Text2Performer)]

**ReMoDiffuse: Retrieval-Augmented Motion Diffusion Model** \
*Mingyuan Zhang, Xinying Guo, Liang Pan, Zhongang Cai, Fangzhou Hong, Huirong Li, Lei Yang, Ziwei Liu* \
arXiv 2023. [[Paper](https://arxiv.org/pdf/2304.01116.pdf)] [[Project](https://mingyuan-zhang.github.io/projects/ReMoDiffuse.html)] [[Github](https://github.com/mingyuan-zhang/ReMoDiffuse)]


## Audio to Motion

**Listen, denoise, action! Audio-driven motion synthesis with diffusion models** \
*Simon Alexanderson, Rajmund Nagy, Jonas Beskow, Gustav Eje Henter* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09707)] [[Project](https://www.speech.kth.se/research/listen-denoise-action/)]

**EDGE: Editable Dance Generation From Music** \
*Jonathan Tseng, Rodrigo Castellon, C. Karen Liu* \
CVPR 2023. [[Paper](https://arxiv.org/pdf/2211.10658.pdf)] ][[Project](https://edge-dance.github.io/)] [[Code](https://github.com/Stanford-TML/EDGE)]


## Speech to Motion 

**DiffMotion: Speech-Driven Gesture Synthesis Using Denoising Diffusion Model** \
*Fan Zhang, Naye Ji, Fuxing Gao, Yongping Li* \
MMM 2023. [[Paper](https://arxiv.org/pdf/2301.10047.pdf)] [[Project](https://zf223669.github.io/DiffMotionWebsite/)] [[Code](https://github.com/zf223669/DiffmotionGG-beta)]


## Text & Audio to Motion

**UDE: A Unified Driving Engine for Human Motion Generation** \
*Zixiang Zhou, Baoyuan Wang* \
CVPR 2023. [[Paper](https://arxiv.org/pdf/2211.16016.pdf)] [[Project](https://zixiangzhou916.github.io/UDE/)] [[Code](https://github.com/zixiangzhou916/UDE)]

**MoFusion: A Framework for Denoising-Diffusion-based Motion Synthesis** \
*Rishabh Dabral, Muhammad Hamza Mughal, Vladislav Golyanik, Christian Theobalt* \
CVPR 2023. [[Paper](https://arxiv.org/pdf/2212.04495.pdf)] [[Project](https://vcai.mpi-inf.mpg.de/projects/MoFusion/)]


## Motion Prediction

**BeLFusion: Latent Diffusion for Behavior-Driven Human Motion Prediction** \
*German Barquero, Sergio Escalera, Cristina Palmero* \
arXiv 2022. [[Paper](https://arxiv.org/pdf/2211.14304.pdf)] [[Project](https://barquerogerman.github.io/BeLFusion/)] [[Code](https://github.com/BarqueroGerman/BeLFusion)]

**HumanMAC: Masked Motion Completion for Human Motion Prediction** \
*Ling-Hao Chen, Jiawei Zhang, Yewen Li, Yiren Pang, Xiaobo Xia, Tongliang Liu* \
arXiv 2023. [[Paper](https://arxiv.org/pdf/2302.03665.pdf)] [[Project](https://lhchen.top/Human-MAC/)] [[Code](https://github.com/LinghaoChan/HumanMAC)]

**Avatars Grow Legs: Generating Smooth Human Motion from Sparse Tracking Inputs with Diffusion Model** \
*Yuming Du, Robin Kips, Albert Pumarola, Sebastian Starke, Ali Thabet, Artsiom Sanakoyeu* \
CVPR 2023. [[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Du_Avatars_Grow_Legs_Generating_Smooth_Human_Motion_From_Sparse_Tracking_CVPR_2023_paper.pdf)] [[Project](https://dulucas.github.io/agrol/)] [[Code](https://github.com/facebookresearch/AGRoL)]

