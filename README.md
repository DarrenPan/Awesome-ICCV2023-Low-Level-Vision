# Awesome-ICCV2023-Low-Level-Vision
A Collection of Papers and Codes in ICCV2023 related to Low-Level Vision

**[In Construction]** If you find some missing papers or typos, feel free to pull issues or requests.

## Related collections for low-level vision
- [Awesome-ICCV2021-Low-Level-Vision](https://github.com/DarrenPan/Awesome-ICCV2023-Low-Level-Vision/blob/main/ICCV2021-Low-Level-Vision.md)
- [Awesome-CVPR2023/2022-Low-Level-Vision](https://github.com/DarrenPan/Awesome-CVPR2023-Low-Level-Vision)
- [Awesome-NeurIPS2022/2021-Low-Level-Vision](https://github.com/DarrenPan/Awesome-NeurIPS2022-Low-Level-Vision)
- [Awesome-ECCV2022-Low-Level-Vision](https://github.com/DarrenPan/Awesome-ECCV2022-Low-Level-Vision)
- [Awesome-AAAI2022-Low-Level-Vision](https://github.com/DarrenPan/Awesome-AAAI2022-Low-Level-Vision)
- [Awesome-CVPR2021/2020-Low-Level-Vision](https://github.com/Kobaayyy/Awesome-CVPR2021-CVPR2020-Low-Level-Vision)
- [Awesome-ECCV2020-Low-Level-Vision](https://github.com/Kobaayyy/Awesome-ECCV2020-Low-Level-Vision)



## Overview

- [Image Restoration](#image-restoration)
  - [Video Restoration](#video-restoration)

- [Super Resolution](#super-resolution)
  - [Image Super Resolution](#image-super-resolution)
  - [Video Super Resolution](#video-super-resolution)
- [Image Rescaling](#image-rescaling)

- [Denoising](#denoising)
  - [Image Denoising](#image-denoising)

- [Deblurring](#deblurring)
  - [Image Deblurring](#image-deblurring)
  - [Video Deblurring](#video-deblurring)

- [Deraining](#deraining)

- [Dehazing](#dehazing)

- [Demosaicing](#demosaicing)

- [HDR Imaging / Multi-Exposure Image Fusion](#hdr-imaging--multi-exposure-image-fusion)

- [Frame Interpolation](#frame-interpolation)

- [Image Enhancement](#image-enhancement)
  - [Low-Light Image Enhancement](#low-light-image-enhancement)

- [Image Harmonization](#image-harmonizationcomposition)

- [Image Completion/Inpainting](#image-completioninpainting)

- [Image Stitching](#image-stitching)

- [Image Compression](#image-compression)

- [Image Quality Assessment](#image-quality-assessment)

- [Style Transfer](#style-transfer)

- [Image Editing](#image-editing)

- [Image Generation/Synthesis/ Image-to-Image Translation](#image-generationsynthesis--image-to-image-translation)
  - [Video Generation](#video-generation)

- [Others](#others)


# Image Restoration

**DiffIR: Efficient Diffusion Model for Image Restoration**
- Paper: https://arxiv.org/abs/2303.09472
- Code: https://github.com/Zj-BinXia/DiffIR
- Tags: Diffusion

**PIRNet: Privacy-Preserving Image Restoration Network via Wavelet Lifting**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Deng_PIRNet_Privacy-Preserving_Image_Restoration_Network_via_Wavelet_Lifting_ICCV_2023_paper.html
- Code: https://github.com/gclonghorn/PIRNet

**Focal Network for Image Restoration**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Cui_Focal_Network_for_Image_Restoration_ICCV_2023_paper.html
- Code: https://github.com/c-yn/FocalNet

**Learning Image-Adaptive Codebooks for Class-Agnostic Image Restoration**
- Paper: https://arxiv.org/abs/2306.06513

**Under-Display Camera Image Restoration with Scattering Effect**
- Paper: https://arxiv.org/abs/2308.04163
- Code: https://github.com/NamecantbeNULL/SRUDC
- Tags: Under-Display Camera

**FSI: Frequency and Spatial Interactive Learning for Image Restoration in Under-Display Cameras**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Liu_FSI_Frequency_and_Spatial_Interactive_Learning_for_Image_Restoration_in_ICCV_2023_paper.html
- Tags: Under-Display Camera

**Multi-weather Image Restoration via Domain Translation**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Patil_Multi-weather_Image_Restoration_via_Domain_Translation_ICCV_2023_paper.html
- Code: https://github.com/pwp1208/Domain_Translation_Multi-weather_Restoration
- Tags: Multi-weather

**Adverse Weather Removal with Codebook Priors**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Ye_Adverse_Weather_Removal_with_Codebook_Priors_ICCV_2023_paper.html
- Tags: Adverse Weather Removal

**Towards Authentic Face Restoration with Iterative Diffusion Models and Beyond**
- Paper: https://arxiv.org/abs/2307.08996
- Tags: Authentic Face Restoration, Diffusion

**Improving Lens Flare Removal with General Purpose Pipeline and Multiple Light Sources Recovery**
- Paper: https://arxiv.org/abs/2308.16460
- Code: https://github.com/YuyanZhou1/Improving-Lens-Flare-Removal
- Tags: Flare Removal 

**High-Resolution Document Shadow Removal via A Large-Scale Real-World Dataset and A Frequency-Aware Shadow Erasing Net**
- Paper: https://arxiv.org/abs/2308.14221
- Code: https://github.com/CXH-Research/DocShadow-SD7K
- Tags: Document Shadow Removal

**Boundary-Aware Divide and Conquer: A Diffusion-Based Solution for Unsupervised Shadow Removal**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Guo_Boundary-Aware_Divide_and_Conquer_A_Diffusion-Based_Solution_for_Unsupervised_Shadow_ICCV_2023_paper.html
- Tags: Shadow Removal

**Leveraging Inpainting for Single-Image Shadow Removal**
- Paper: https://arxiv.org/abs/2302.05361
- Tags: Shadow Removal

**Fine-grained Visible Watermark Removal**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Niu_Fine-grained_Visible_Watermark_Removal_ICCV_2023_paper.html
- Tags: Watermark Removal

**Physics-Driven Turbulence Image Restoration with Stochastic Refinement**
- Paper: https://arxiv.org/abs/2307.10603
- Code: https://github.com/VITA-Group/PiRN
- Tags: Turbulence Image

**Building Bridge Across the Time: Disruption and Restoration of Murals In the Wild**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Shao_Building_Bridge_Across_the_Time_Disruption_and_Restoration_of_Murals_ICCV_2023_paper.html
- Code: https://github.com/Shaocr/Building-Bridge-Across-the-Time-Disruption-and-Restoration-of-Murals-In-the-Wild
- Tags: Murals Restoration

**DDS2M: Self-Supervised Denoising Diffusion Spatio-Spectral Model for Hyperspectral Image Restoration**
- Paper: https://arxiv.org/abs/2303.06682
- Code: https://github.com/miaoyuchun/DDS2M
- Tags: Diffusion, Hyperspectral

**Fingerprinting Deep Image Restoration Models**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Quan_Fingerprinting_Deep_Image_Restoration_Models_ICCV_2023_paper.html

**Self-supervised Monocular Underwater Depth Recovery, Image Restoration, and a Real-sea Video Dataset**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Varghese_Self-supervised_Monocular_Underwater_Depth_Recovery_Image_Restoration_and_a_Real-sea_ICCV_2023_paper.html
- Code: https://github.com/nishavarghese15/DRUVA

## Image Reconstruction

**Pixel Adaptive Deep Unfolding Transformer for Hyperspectral Image Reconstruction**
- Paper: https://arxiv.org/abs/2308.10820
- Code: https://github.com/MyuLi/PADUT

## Video Restoration

**Snow Removal in Video: A New Dataset and A Novel Method**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Chen_Snow_Removal_in_Video_A_New_Dataset_and_A_Novel_ICCV_2023_paper.html
- Code: https://github.com/haoyuc/VideoDesnowing
- Tags: Desnowing

**Video Adverse-Weather-Component Suppression Network via Weather Messenger and Adversarial Backpropagation**
- Paper: https://arxiv.org/abs/2309.13700
- Code: https://github.com/scott-yjyang/ViWS-Net

**Fast Full-frame Video Stabilization with Iterative Optimization**
- Paper: https://arxiv.org/abs/2307.12774
- Code: https://github.com/zwyking/Fast-Stab
- Tags: Video Stabilization

**Minimum Latency Deep Online Video Stabilization**
- Paper: https://arxiv.org/abs/2212.02073
- Code: https://github.com/liuzhen03/NNDVS
- Tags: Video Stabilization

**Task Agnostic Restoration of Natural Video Dynamics**
- Paper: https://arxiv.org/abs/2206.03753
- Code: https://github.com/MKashifAli/TARONVD

[[Back-to-Overview](#overview)]

# Super Resolution
## Image Super Resolution

**On the Effectiveness of Spectral Discriminators for Perceptual Quality Improvement**
- Paper: https://arxiv.org/abs/2307.12027
- Code: https://github.com/Luciennnnnnn/DualFormer

**SRFormer: Permuted Self-Attention for Single Image Super-Resolution**
- Paper: https://arxiv.org/abs/2303.09735 
- Code: https://github.com/HVision-NKU/SRFormer

**DLGSANet: Lightweight Dynamic Local and Global Self-Attention Network for Image Super-Resolution**
- Paper: https://arxiv.org/abs/2301.02031
- Code: https://github.com/NeonLeexiang/DLGSANet

**Dual Aggregation Transformer for Image Super-Resolution**
- Paper: https://arxiv.org/abs/2308.03364
- Code: https://github.com/zhengchen1999/DAT

**MSRA-SR: Image Super-resolution Transformer with Multi-scale Shared Representation Acquisition**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Zhou_MSRA-SR_Image_Super-resolution_Transformer_with_Multi-scale_Shared_Representation_Acquisition_ICCV_2023_paper.html

**Content-Aware Local GAN for Photo-Realistic Super-Resolution**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Park_Content-Aware_Local_GAN_for_Photo-Realistic_Super-Resolution_ICCV_2023_paper.html
- Code: https://github.com/jkpark0825/CAL
- Tags: GAN

**Boosting Single Image Super-Resolution via Partial Channel Shifting**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Zhang_Boosting_Single_Image_Super-Resolution_via_Partial_Channel_Shifting_ICCV_2023_paper.html
- Code: https://github.com/OwXiaoM/_PCS

**Feature Modulation Transformer: Cross-Refinement of Global Representation via High-Frequency Prior for Image Super-Resolution**
- Paper: https://arxiv.org/abs/2308.05022
- Code: https://github.com/AVC2-UESTC/CRAFT-SR

**Spatially-Adaptive Feature Modulation for Efficient Image Super-Resolution**
- Paper: https://arxiv.org/abs/2302.13800
- Code: https://github.com/sunny2109/SAFMN
- Tags: Efficient

**Lightweight Image Super-Resolution with Superpixel Token Interaction**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Zhang_Lightweight_Image_Super-Resolution_with_Superpixel_Token_Interaction_ICCV_2023_paper.html
- Code: https://github.com/ArcticHare105/SPIN
- Tags: Lightweight

**Reconstructed Convolution Module Based Look-Up Tables for Efficient Image Super-Resolution**
- Paper: https://arxiv.org/abs/2307.08544
- Code: https://github.com/liuguandu/RC-LUT
- Tags: Efficient

**Iterative Soft Shrinkage Learning for Efficient Image Super-Resolution**
- Paper: https://arxiv.org/abs/2211.13654
- Code: https://github.com/Jiamian-Wang/Iterative-Soft-Shrinkage-SR
- Tags: Efficient
  
**MetaF2N: Blind Image Super-Resolution by Learning Efficient Model Adaptation from Faces**
- Paper: https://arxiv.org/abs/2309.08113
- Code: https://github.com/yinzhicun/MetaF2N
- Tags: Blind

**Learning Correction Filter via Degradation-Adaptive Regression for Blind Single Image Super-Resolution**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Zhou_Learning_Correction_Filter_via_Degradation-Adaptive_Regression_for_Blind_Single_Image_ICCV_2023_paper.html
- Code: https://github.com/edbca/DARSR
- Tags: Blind

**LMR: A Large-Scale Multi-Reference Dataset for Reference-Based Super-Resolution**
- Paper: https://arxiv.org/abs/2303.04970
- Tags: Reference-Based 

**Real-CE: A Benchmark for Chinese-English Scene Text Image Super-resolution**
- Paper: https://arxiv.org/abs/2308.03262
- Code: https://github.com/mjq11302010044/Real-CE
- Tags: Text SR

**Learning Non-Local Spatial-Angular Correlation for Light Field Image Super-Resolution**
- Paper: https://arxiv.org/abs/2302.08058
- Code: https://github.com/ZhengyuLiang24/EPIT
- Tags: Light Field

**Spherical Space Feature Decomposition for Guided Depth Map Super-Resolution**
- Paper: https://arxiv.org/abs/2303.08942
- Code: https://github.com/Zhaozixiang1228/GDSR-SSDNet
- Tags: Depth Map

**HSR-Diff: Hyperspectral Image Super-Resolution via Conditional Diffusion Models**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Wu_HSR-Diff_Hyperspectral_Image_Super-Resolution_via_Conditional_Diffusion_Models_ICCV_2023_paper.html
- Tags: Hyperspectral, Diffusion

**ESSAformer: Efficient Transformer for Hyperspectral Image Super-resolution**
- Paper: https://arxiv.org/abs/2307.14010
- Code: https://github.com/Rexzhan/ESSAformer
- Tags: Hyperspectral

**Rethinking Multi-Contrast MRI Super-Resolution: Rectangle-Window Cross-Attention Transformer and Arbitrary-Scale Upsampling**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Li_Rethinking_Multi-Contrast_MRI_Super-Resolution_Rectangle-Window_Cross-Attention_Transformer_and_Arbitrary-Scale_Upsampling_ICCV_2023_paper.html
- Tags: MRI

**Decomposition-Based Variational Network for Multi-Contrast MRI Super-Resolution and Reconstruction**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Lei_Decomposition-Based_Variational_Network_for_Multi-Contrast_MRI_Super-Resolution_and_Reconstruction_ICCV_2023_paper.html
- Code: https://github.com/lpcccc-cv/MC-VarNet
- Tags: MRI

**CuNeRF: Cube-Based Neural Radiance Field for Zero-Shot Medical Image Arbitrary-Scale Super Resolution**
- Paper: https://arxiv.org/abs/2303.16242
- Code: https://github.com/NarcissusEx/CuNeRF
- Tags: Medical, NeRF

## Burst Super Resolution

**Towards Real-World Burst Image Super-Resolution: Benchmark and Method**
- Paper: https://arxiv.org/abs/2309.04803
- Code: https://github.com/yjsunnn/FBANet
- Tag: Real-World

**Self-Supervised Burst Super-Resolution**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Bhat_Self-Supervised_Burst_Super-Resolution_ICCV_2023_paper.html
- Tags: Self-Supervised

## Video Super Resolution

**Learning Data-Driven Vector-Quantized Degradation Model for Animation Video Super-Resolution**
- Paper: https://arxiv.org/abs/2303.09826
- Code: https://github.com/researchmm/VQD-SR

**Multi-Frequency Representation Enhancement with Privilege Information for Video Super-Resolution**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Li_Multi-Frequency_Representation_Enhancement_with_Privilege_Information_for_Video_Super-Resolution_ICCV_2023_paper.html

## Spatial-Temporal Video Super-Resolution

**MoTIF: Learning Motion Trajectories with Local Implicit Neural Functions for Continuous Space-Time Video Super-Resolution**
- Paper: https://arxiv.org/abs/2307.07988
- Code: https://github.com/sichun233746/MoTIF

[[Back-to-Overview](#overview)]

# Image Rescaling

**Downscaled Representation Matters: Improving Image Rescaling with Collaborative Downscaled Images**
- Paper: https://arxiv.org/abs/2211.10643

[[Back-to-Overview](#overview)]

# Denoising
## Image Denoising

**Random Sub-Samples Generation for Self-Supervised Real Image Denoising**
- Paper: https://arxiv.org/abs/2307.16825
- Code: https://github.com/p1y2z3/SDAP
- Tags: Self-Supervised

**Score Priors Guided Deep Variational Inference for Unsupervised Real-World Single Image Denoising**
- Paper: https://arxiv.org/abs/2308.04682
- Tags: Unsupervised

**Unsupervised Image Denoising in Real-World Scenarios via Self-Collaboration Parallel Generative Adversarial Branches**
- Paper: https://arxiv.org/abs/2308.06776
- Tags: Unsupervised

**Self-supervised Image Denoising with Downsampled Invariance Loss and Conditional Blind-Spot Network**
- Paper: https://arxiv.org/abs/2304.09507
- Code: https://github.com/jyicu/CBSN
- Tags: Self-supervised

**Multi-view Self-supervised Disentanglement for General Image Denoising**
- Paper: https://arxiv.org/abs/2309.05049
- Tags: Self-supervised

**Iterative Denoiser and Noise Estimator for Self-Supervised Image Denoising**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Zou_Iterative_Denoiser_and_Noise_Estimator_for_Self-Supervised_Image_Denoising_ICCV_2023_paper.html
- Tags: Self-Supervised

**Noise2Info: Noisy Image to Information of Noise for Self-Supervised Image Denoising**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Noise2Info_Noisy_Image_to_Information_of_Noise_for_Self-Supervised_Image_ICCV_2023_paper.html
- Tags: Self-Supervised

**The Devil is in the Upsampling: Architectural Decisions Made Simpler for Denoising with Deep Image Prior**
- Paper: https://arxiv.org/abs/2304.11409
- Code: https://github.com/YilinLiu97/FasterDIP-devil-in-upsampling

**Lighting Every Darkness in Two Pairs: A Calibration-Free Pipeline for RAW Denoising**
- Paper: https://arxiv.org/abs/2308.03448
- Code: https://github.com/Srameo/LED

**ExposureDiffusion: Learning to Expose for Low-light Image Enhancement**
- Paper: https://arxiv.org/abs/2307.07710
- Code: https://github.com/wyf0912/ExposureDiffusion

**Towards General Low-Light Raw Noise Synthesis and Modeling**
- Paper: https://arxiv.org/abs/2307.16508
- Code: https://github.com/fengzhang427/LRD
- Tags: Noise Modeling

**Hybrid Spectral Denoising Transformer with Guided Attention**
- Paper: https://arxiv.org/abs/2303.09040
- Code: https://github.com/Zeqiang-Lai/HSDT
- Tags: hyperspectral image denoising

[[Back-to-Overview](#overview)]

# Deblurring
## Image Deblurring

**Multiscale Structure Guided Diffusion for Image Deblurring**
- Paper: https://arxiv.org/abs/2212.01789
 
**Multi-Scale Residual Low-Pass Filter Network for Image Deblurring**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Dong_Multi-Scale_Residual_Low-Pass_Filter_Network_for_Image_Deblurring_ICCV_2023_paper.html

**Single Image Defocus Deblurring via Implicit Neural Inverse Kernels**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Quan_Single_Image_Defocus_Deblurring_via_Implicit_Neural_Inverse_Kernels_ICCV_2023_paper.html

**Single Image Deblurring with Row-dependent Blur Magnitude**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Ji_Single_Image_Deblurring_with_Row-dependent_Blur_Magnitude_ICCV_2023_paper.html

**Non-Coaxial Event-Guided Motion Deblurring with Spatial Alignment**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Cho_Non-Coaxial_Event-Guided_Motion_Deblurring_with_Spatial_Alignment_ICCV_2023_paper.html
- Tags: Event-Based

**Generalizing Event-Based Motion Deblurring in Real-World Scenarios**
- Paper: https://arxiv.org/abs/2308.05932
- Code: https://github.com/XiangZ-0/GEM
- Tags: Event-Based

## Video Deblurring

**Exploring Temporal Frequency Spectrum in Deep Video Deblurring**
- Paper：https://openaccess.thecvf.com/content/ICCV2023/html/Zhu_Exploring_Temporal_Frequency_Spectrum_in_Deep_Video_Deblurring_ICCV_2023_paper.html

[[Back-to-Overview](#overview)]

# Deraining

**From Sky to the Ground: A Large-scale Benchmark and Simple Baseline Towards Real Rain Removal**
- Paper: https://arxiv.org/abs/2308.03867
- Code: https://github.com/yunguo224/LHP-Rain

**Learning Rain Location Prior for Nighttime Deraining**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Zhang_Learning_Rain_Location_Prior_for_Nighttime_Deraining_ICCV_2023_paper.html
- Code: https://github.com/zkawfanx/RLP

**Sparse Sampling Transformer with Uncertainty-Driven Ranking for Unified Removal of Raindrops and Rain Streaks**
- Paper: https://arxiv.org/abs/2308.14153
- Code: https://github.com/Ephemeral182/UDR-S2Former_deraining

**Unsupervised Video Deraining with An Event Camera**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Unsupervised_Video_Deraining_with_An_Event_Camera_ICCV_2023_paper.html

[[Back-to-Overview](#overview)]

# Dehazing

**MB-TaylorFormer: Multi-branch Efficient Transformer Expanded by Taylor Formula for Image Dehazing**
- Paper: https://arxiv.org/abs/2308.14036
- Code: https://github.com/FVL2020/ICCV-2023-MB-TaylorFormer

[[Back-to-Overview](#overview)]

# Demosaicing

**Efficient Unified Demosaicing for Bayer and Non-Bayer Patterned Image Sensors**
- Paper: https://arxiv.org/abs/2307.10667

[[Back-to-Overview](#overview)]

# HDR Imaging / Multi-Exposure Image Fusion

**Alignment-free HDR Deghosting with Semantics Consistent Transformer**
- Paper: https://arxiv.org/abs/2305.18135
- Code: https://github.com/Zongwei97/SCTNet

**MEFLUT: Unsupervised 1D Lookup Tables for Multi-exposure Image Fusion**
- Paper: https://arxiv.org/abs/2309.11847
- Code: https://github.com/Hedlen/MEFLUT

**RawHDR: High Dynamic Range Image Reconstruction from a Single Raw Image**
- Paper: https://arxiv.org/abs/2309.02020
- Code: https://github.com/jackzou233/RawHDR

**Learning Continuous Exposure Value Representations for Single-Image HDR Reconstruction** 
- Paper: https://arxiv.org/abs/2309.03900

**LAN-HDR: Luminance-based Alignment Network for High Dynamic Range Video Reconstruction**
- Paper: https://arxiv.org/abs/2308.11116

**Joint Demosaicing and Deghosting of Time-Varying Exposures for Single-Shot HDR Imaging**
- Paper: https://vclab.kaist.ac.kr/iccv2023/iccv2023-single-shot-hdr-imaging.pdf
- Code: https://github.com/KAIST-VCLAB/singshot-hdr-demosaicing

**GlowGAN: Unsupervised Learning of HDR Images from LDR Images in the Wild**
- Paper: https://arxiv.org/abs/2211.12352

**Beyond the Pixel: a Photometrically Calibrated HDR Dataset for Luminance and Color Prediction**
- Paper: https://arxiv.org/abs/2304.12372
- Code: https://github.com/lvsn/beyondthepixel

[[Back-to-Overview](#overview)]

# Frame Interpolation

**Video Object Segmentation-aware Video Frame Interpolation**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Yoo_Video_Object_Segmentation-aware_Video_Frame_Interpolation_ICCV_2023_paper.html
- Code: https://github.com/junsang7777/VOS-VFI

**Rethinking Video Frame Interpolation from Shutter Mode Induced Degradation**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Ji_Rethinking_Video_Frame_Interpolation_from_Shutter_Mode_Induced_Degradation_ICCV_2023_paper.html

[[Back-to-Overview](#overview)]

# Image Enhancement

**Iterative Prompt Learning for Unsupervised Backlit Image Enhancement**
- Paper: https://arxiv.org/abs/2303.17569
- Code: https://github.com/ZhexinLiang/CLIP-LIT

## Low-Light Image Enhancement

**ExposureDiffusion: Learning to Expose for Low-light Image Enhancement**
- Paper: https://arxiv.org/abs/2307.07710
- Code: https://github.com/wyf0912/ExposureDiffusion
  
**Implicit Neural Representation for Cooperative Low-light Image Enhancement**
- Paper: https://arxiv.org/abs/2303.11722
- Code: https://github.com/Ysz2022/NeRCo

**Low-Light Image Enhancement with Illumination-Aware Gamma Correction and Complete Image Modelling Network**
- Paper:  https://arxiv.org/abs/2308.08220

**Diff-Retinex: Rethinking Low-light Image Enhancement with A Generative Diffusion Model**
- Paper: https://arxiv.org/abs/2308.13164

**Retinexformer: One-stage Retinex-based Transformer for Low-light Image Enhancement**
- Paper: https://arxiv.org/abs/2303.06705
- Code: https://github.com/caiyuanhao1998/Retinexformer

**Low-Light Image Enhancement with Multi-Stage Residue Quantization and Brightness-Aware Attention**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Liu_Low-Light_Image_Enhancement_with_Multi-Stage_Residue_Quantization_and_Brightness-Aware_Attention_ICCV_2023_paper.html

**Dancing in the Dark: A Benchmark towards General Low-light Video Enhancement**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Fu_Dancing_in_the_Dark_A_Benchmark_towards_General_Low-light_Video_ICCV_2023_paper.html
- Code: https://github.com/ciki000/DID

**NIR-assisted Video Enhancement via Unpaired 24-hour Data**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Niu_NIR-assisted_Video_Enhancement_via_Unpaired_24-hour_Data_ICCV_2023_paper.html
- Code: https://github.com/MyNiuuu/NVEU

**Coherent Event Guided Low-Light Video Enhancement**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Liang_Coherent_Event_Guided_Low-Light_Video_Enhancement_ICCV_2023_paper.html
- Code: https://github.com/sherrycattt/EvLowLight

[[Back-to-Overview](#overview)]

# Image Harmonization/Composition

**Deep Image Harmonization with Learnable Augmentation**
- Paper: https://arxiv.org/abs/2308.00376
- Code: https://github.com/bcmi/SycoNet-Adaptive-Image-Harmonization

**Deep Image Harmonization with Globally Guided Feature Transformation and Relation Distillation**
- Paper: https://arxiv.org/abs/2308.00356
- Code: https://github.com/bcmi/Image-Harmonization-Dataset-ccHarmony

**TF-ICON: Diffusion-Based Training-Free Cross-Domain Image Composition**
- Paper: https://arxiv.org/abs/2307.12493
- Code: https://github.com/Shilin-LU/TF-ICON

[[Back-to-Overview](#overview)]

# Image Completion/Inpainting

**Diverse Inpainting and Editing with GAN Inversion**
- Paper: https://arxiv.org/abs/2307.15033

**Rethinking Fast Fourier Convolution in Image Inpainting**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Chu_Rethinking_Fast_Fourier_Convolution_in_Image_Inpainting_ICCV_2023_paper.html

**Continuously Masked Transformer for Image Inpainting**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Ko_Continuously_Masked_Transformer_for_Image_Inpainting_ICCV_2023_paper.html
- Code: https://github.com/keunsoo-ko/CMT

**MI-GAN: A Simple Baseline for Image Inpainting on Mobile Devices**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Sargsyan_MI-GAN_A_Simple_Baseline_for_Image_Inpainting_on_Mobile_Devices_ICCV_2023_paper.html
- Code: https://github.com/Picsart-AI-Research/MI-GAN

**PATMAT: Person Aware Tuning of Mask-Aware Transformer for Face Inpainting**
- Paper: https://arxiv.org/abs/2304.06107
- Code: https://github.com/humansensinglab/PATMAT

## Video Inpainting

**ProPainter: Improving Propagation and Transformer for Video Inpainting**
- Paper: https://arxiv.org/abs/2309.03897
- Code: https://github.com/sczhou/ProPainter

**Semantic-Aware Dynamic Parameter for Video Inpainting Transformer**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Lee_Semantic-Aware_Dynamic_Parameter_for_Video_Inpainting_Transformer_ICCV_2023_paper.html

**CIRI: Curricular Inactivation for Residue-aware One-shot Video Inpainting**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Zheng_CIRI_Curricular_Inactivation_for_Residue-aware_One-shot_Video_Inpainting_ICCV_2023_paper.html
- Code: https://github.com/Arise-zwy/CIRI

[[Back-to-Overview](#overview)]

# Image Stitching

**Parallax-Tolerant Unsupervised Deep Image Stitching**
- Paper: https://arxiv.org/abs/2302.08207
- Code: https://github.com/nie-lang/UDIS2

[[Back-to-Overview](#overview)]

# Image Compression

**RFD-ECNet: Extreme Underwater Image Compression with Reference to Feature Dictionary**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Li_RFD-ECNet_Extreme_Underwater_Image_Compression_with_Reference_to_Feature_Dictionary_ICCV_2023_paper.html
- Code: https://github.com/lilala0/RFD-ECNet

**COMPASS: High-Efficiency Deep Image Compression with Arbitrary-scale Spatial Scalability**
- Paper: https://arxiv.org/abs/2309.07926
- Code: https://github.com/ImJongminPark/COMPASS

**Computationally-Efficient Neural Image Compression with Shallow Decoders**
 - Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Yang_Computationally-Efficient_Neural_Image_Compression_with_Shallow_Decoders_ICCV_2023_paper.html
 - Code: https://github.com/mandt-lab/shallow-ntc

**Dec-Adapter: Exploring Efficient Decoder-Side Adapter for Bridging Screen Content and Natural Image Compression**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Shen_Dec-Adapter_Exploring_Efficient_Decoder-Side_Adapter_for_Bridging_Screen_Content_and_ICCV_2023_paper.html

**Semantically Structured Image Compression via Irregular Group-Based Decoupling**
- Paper: https://arxiv.org/abs/2305.02586

**TransTIC: Transferring Transformer-based Image Compression from Human Perception to Machine Perception**
- Paper: https://arxiv.org/abs/2306.05085
- Code: https://github.com/NYCU-MAPL/TransTIC

**AdaNIC: Towards Practical Neural Image Compression via Dynamic Transform Routing**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Tao_AdaNIC_Towards_Practical_Neural_Image_Compression_via_Dynamic_Transform_Routing_ICCV_2023_paper.html

**COOL-CHIC: Coordinate-based Low Complexity Hierarchical Image Codec**
- Paper: https://openaccess.thecvf.com/content/ICCV2023/html/Ladune_COOL-CHIC_Coordinate-based_Low_Complexity_Hierarchical_Image_Codec_ICCV_2023_paper.html
- Code: https://github.com/Orange-OpenSource/Cool-Chic

## Video Compression

**Scene Matters: Model-based Deep Video Compression**
- Paper: https://arxiv.org/abs/2303.04557

[[Back-to-Overview](#overview)]

# Image Quality Assessment

**Thinking Image Color Aesthetics Assessment: Models, Datasets and Benchmarks**
- Paper: [ICCV Open Access Version](https://openaccess.thecvf.com/content/ICCV2023/html/He_Thinking_Image_Color_Aesthetics_Assessment_Models_Datasets_and_Benchmarks_ICCV_2023_paper.html)
- Code: https://github.com/woshidandan/Image-Color-Aesthetics-Assessment/tree/main

**Test Time Adaptation for Blind Image Quality Assessment**
- Paper: https://arxiv.org/abs/2307.14735

**Troubleshooting Ethnic Quality Bias with Curriculum Domain Adaptation for Face Image Quality Assessment**
- Paper: [ICCV Open Access Version](https://openaccess.thecvf.com/content/ICCV2023/html/Ou_Troubleshooting_Ethnic_Quality_Bias_with_Curriculum_Domain_Adaptation_for_Face_ICCV_2023_paper.html)
- Code: https://github.com/oufuzhao/EQBM

**SQAD: Automatic Smartphone Camera Quality Assessment and Benchmarking**
- Paper: [ICCV Open Access Version](https://openaccess.thecvf.com/content/ICCV2023/html/Fang_SQAD_Automatic_Smartphone_Camera_Quality_Assessment_and_Benchmarking_ICCV_2023_paper.html)
- Code: https://github.com/aiff22/SQAD

**Exploring Video Quality Assessment on User Generated Contents from Aesthetic and Technical Perspectives**
- Paper https://arxiv.org/abs/2211.04894
- Code: https://github.com/VQAssessment/DOVER

[[Back-to-Overview](#overview)]

# Style Transfer

**AesPA-Net: Aesthetic Pattern-Aware Style Transfer Networks**
- Paper: https://arxiv.org/abs/2307.09724
- Code: https://github.com/Kibeom-Hong/AesPA-Net

**Two Birds, One Stone: A Unified Framework for Joint Learning of Image and Video Style Transfers**
- Paper: https://arxiv.org/abs/2304.11335
- Code: https://github.com/NevSNev/UniST

**All-to-key Attention for Arbitrary Style Transfer**
- Paper:
- Code: https://github.com/LearningHx/StyA2K

**StyleDiffusion: Controllable Disentangled Style Transfer via Diffusion Models**
- Paper: https://arxiv.org/abs/2308.07863

**StylerDALLE: Language-Guided Style Transfer Using a Vector-Quantized Tokenizer of a Large-Scale Generative Model**
- Paper: https://arxiv.org/abs/2303.09268
- Code: https://github.com/zipengxuc/StylerDALLE

[[Back-to-Overview](#overview)]

# Image Editing

**Adaptive Nonlinear Latent Transformation for Conditional Face Editing**
- Paper: https://arxiv.org/abs/2307.07790
- Code: https://github.com/Hzzone/AdaTrans

**Multimodal Garment Designer: Human-Centric Latent Diffusion Models for Fashion Image Editing**
- Paper: https://arxiv.org/abs/2304.02051
- Code: https://github.com/aimagelab/multimodal-garment-designer 

**MasaCtrl: Tuning-Free Mutual Self-Attention Control for Consistent Image Synthesis and Editing**
- Paper: https://arxiv.org/abs/2304.08465
- Code: https://github.com/TencentARC/MasaCtrl

**Not All Steps are Created Equal: Selective Diffusion Distillation for Image Manipulation**
- Paper: https://arxiv.org/abs/2307.08448
- Code: https://github.com/AndysonYs/Selective-Diffusion-Distillation

**HairCLIPv2: Unifying Hair Editing via Proxy Feature Blending**
- Paper: 
- Code: https://github.com/wty-ustc/HairCLIPv2

**StyleGANEX: StyleGAN-Based Manipulation Beyond Cropped Aligned Faces**
- Paper: https://arxiv.org/abs/2303.06146
- Code: https://github.com/williamyang1991/StyleGANEX

**Diverse Inpainting and Editing with GAN Inversion**
- Paper: https://arxiv.org/abs/2307.15033

**Effective Real Image Editing with Accelerated Iterative Diffusion Inversion**
- Paper: https://arxiv.org/abs/2309.04907

[[Back-to-Overview](#overview)]

# Image Generation/Synthesis / Image-to-Image Translation
## Text-to-Image / Text Guided / Multi-Modal

**MagicFusion: Boosting Text-to-Image Generation Performance by Fusing Diffusion Models**
- Paper: https://arxiv.org/abs/2303.13126
- Code: https://github.com/MagicFusion/MagicFusion.github.io

**ELITE: Encoding Visual Concepts into Textual Embeddings for Customized Text-to-Image Generation**
- Paper: https://arxiv.org/abs/2302.13848
- Code: https://github.com/csyxwei/ELITE

**Better Aligning Text-to-Image Models with Human Preference**
- Paper: https://arxiv.org/abs/2303.14420
- Code: https://github.com/tgxs002/align_sd

**Unleashing Text-to-Image Diffusion Models for Visual Perception**
- Paper: https://arxiv.org/abs/2303.02153
- Code: https://github.com/wl-zhao/VPD

**Unsupervised Compositional Concepts Discovery with Text-to-Image Generative Models**
- Paper: https://arxiv.org/abs/2306.05357
- Code: https://github.com/nanlliu/Unsupervised-Compositional-Concepts-Discovery

**BoxDiff: Text-to-Image Synthesis with Training-Free Box-Constrained Diffusion**
- Paper: https://arxiv.org/abs/2307.10816
- Code: https://github.com/Sierkinhane/BoxDiff

**Ablating Concepts in Text-to-Image Diffusion Models**
- Paper: https://arxiv.org/abs/2303.13516
- Code: https://github.com/nupurkmr9/concept-ablation

**Learning to Generate Semantic Layouts for Higher Text-Image Correspondence in Text-to-Image Synthesis**
- Paper: https://arxiv.org/abs/2308.08157
- Code: https://github.com/pmh9960/GCDP

**HumanSD: A Native Skeleton-Guided Diffusion Model for Human Image Generation**
- Paper: https://arxiv.org/abs/2304.04269
- Code: https://github.com/IDEA-Research/HumanSD

**Story Visualization by Online Text Augmentation with Context Memory**
- Paper: https://arxiv.org/abs/2308.07575

**DiffCloth: Diffusion Based Garment Synthesis and Manipulation via Structural Cross-modal Semantic Alignment**
- Paper: https://arxiv.org/abs/2308.11206

**Dense Text-to-Image Generation with Attention Modulation**
- Paper: https://arxiv.org/abs/2308.12964
- Code: https://github.com/naver-ai/DenseDiffusion``

**ITI-GEN: Inclusive Text-to-Image Generation**
- Paper: https://arxiv.org/abs/2309.05569
- Project: https://czhang0528.github.io/iti-gen


## Image-to-Image / Image Guided

**Reinforced Disentanglement for Face Swapping without Skip Connection**
- Paper: https://arxiv.org/abs/2307.07928

**BlendFace: Re-designing Identity Encoders for Face-Swapping**
- Paper: https://arxiv.org/abs/2307.10854
- Code: https://github.com/mapooon/BlendFace

**General Image-to-Image Translation with One-Shot Image Guidance**
- Paper: https://arxiv.org/abs/2307.14352
- Code: https://github.com/CrystalNeuro/visual-concept-translator

**GaFET: Learning Geometry-aware Facial Expression Translation from In-The-Wild Images**
- Paper: https://arxiv.org/abs/2308.03413

**Scenimefy: Learning to Craft Anime Scene via Semi-Supervised Image-to-Image Translation**
- Paper: https://arxiv.org/abs/2308.12968
- Code: https://github.com/Yuxinn-J/Scenimefy

**A Latent Space of Stochastic Diffusion Models for Zero-Shot Image Editing and Guidance**
- Paper: https://arxiv.org/abs/2210.05559
- Code: https://github.com/ChenWu98/cycle-diffusion

## Others for image generation

**Conditional 360-degree Image Synthesis for Immersive Indoor Scene Decoration**
- Paper: https://arxiv.org/abs/2307.09621

**Masked Diffusion Transformer is a Strong Image Synthesizer**
- Paper: https://arxiv.org/abs/2303.14389
- Code: https://github.com/sail-sg/MDT

**Q-Diffusion: Quantizing Diffusion Models**
- Paper: https://arxiv.org/abs/2302.04304
- Code: https://github.com/Xiuyu-Li/q-diffusion

**The Euclidean Space is Evil: Hyperbolic Attribute Editing for Few-shot Image Generation**
- Paper:
- Code: https://github.com/lingxiao-li/HAE

**LFS-GAN: Lifelong Few-Shot Image Generation**
- Paper: https://arxiv.org/abs/2308.11917
- Code: https://github.com/JJuOn/LFS-GAN

**FreeDoM: Training-Free Energy-Guided Conditional Diffusion Model**
- Paper: https://arxiv.org/abs/2303.09833
- Code: https://github.com/vvictoryuki/FreeDoM

**Improving Diversity in Zero-Shot GAN Adaptation with Semantic Variations**
- Paper: https://arxiv.org/abs/2308.10554

**Smoothness Similarity Regularization for Few-Shot GAN Adaptation**
- Paper: https://arxiv.org/abs/2308.09717

**UnitedHuman: Harnessing Multi-Source Data for High-Resolution Human Generation**
- Paper: https://arxiv.org/abs/2309.14335
- Code: https://github.com/UnitedHuman/UnitedHuman

## Video Generation

**Bidirectionally Deformable Motion Modulation For Video-based Human Pose Transfer**
- Paper: https://arxiv.org/abs/2307.07754
- Code: https://github.com/rocketappslab/bdmm

**MODA: Mapping-Once Audio-driven Portrait Animation with Dual Attentions**
- Paper: https://arxiv.org/abs/2307.10008
- Code: https://github.com/DreamtaleCore/MODA

**Text2Video-Zero: Text-to-Image Diffusion Models are Zero-Shot Video Generators**
- Paper: https://arxiv.org/abs/2303.13439
- Code: https://github.com/Picsart-AI-Research/Text2Video-Zero

**FateZero: Fusing Attentions for Zero-shot Text-based Video Editing**
- Paper: https://arxiv.org/abs/2303.09535
- Code: https://github.com/ChenyangQiQi/FateZero

**RIGID: Recurrent GAN Inversion and Editing of Real Face Videos**
- Paper: https://arxiv.org/abs/2308.06097

**StableVideo: Text-driven Consistency-aware Diffusion Video Editing**
- Paper: https://arxiv.org/abs/2308.09592
- Code: https://github.com/rese1f/StableVideo

**StyleInV: A Temporal Style Modulated Inversion Network for Unconditional Video Generation**
- Paper: https://arxiv.org/abs/2308.16909
- Code: https://github.com/johannwyh/StyleInV

**The Power of Sound (TPoS): Audio Reactive Video Generation with Stable Diffusion**
- Paper: https://arxiv.org/abs/2309.04509
- Project: https://ku-vai.github.io/TPoS/

[[Back-to-Overview](#overview)]

## Others [[back](#catalogue)]

**DDColor: Towards Photo-Realistic and Semantic-Aware Image Colorization via Dual Decoders**
- Paper: https://arxiv.org/abs/2212.11613
- Code: https://github.com/piddnad/DDColor
- Tags: Colorization

**DDFM: Denoising Diffusion Model for Multi-Modality Image Fusion**
- Paper: https://arxiv.org/abs/2303.06840
- Code: https://github.com/Zhaozixiang1228/MMIF-DDFM
- Tags: Image Fusion

**Name Your Colour For the Task: Artificially Discover Colour Naming via Colour Quantisation Transformer**
- Paper: https://arxiv.org/abs/2212.03434
- Code: https://github.com/ryeocthiv/CQFormer

**Unfolding Framework with Prior of Convolution-Transformer Mixture and Uncertainty Estimation for Video Snapshot Compressive Imaging**
- Paper: https://arxiv.org/abs/2306.11316
- Code: https://github.com/zsm1211/CTM-SCI
- Tags: Snapshot Compressive Imaging

**Deep Optics for Video Snapshot Compressive Imaging**
- Paper:
- Code: https://github.com/pwangcs/DeepOpticsSCI
- Tags: Snapshot Compressive Imaging

**SimFIR: A Simple Framework for Fisheye Image Rectification with Self-supervised Representation Learning**
- Paper: https://arxiv.org/abs/2308.09040
- Code: https://github.com/fh2019ustc/SimFIR
- Tags: Fisheye Image Rectification

**Single Image Reflection Separation via Component Synergy**
- Paper: https://arxiv.org/abs/2308.10027
- Code: https://github.com/mingcv/DSRNet
- Tag: Image Reflection Separation

**Learned Image Reasoning Prior Penetrates Deep Unfolding Network for Panchromatic and Multi-Spectral Image Fusion**
- Paper: https://arxiv.org/abs/2308.16083
- Tags: pan-sharpening

## Talking Head Generation

**Implicit Identity Representation Conditioned Memory Compensation Network for Talking Head video Generation**
- Paper: https://arxiv.org/abs/2307.09906
- Code: https://github.com/harlanhong/ICCV2023-MCNET

**Efficient Emotional Adaptation for Audio-Driven Talking-Head Generation**
- Paper: https://arxiv.org/abs/2309.04946
- Code: https://github.com/yuangan/EAT_code

## Handwriting/Font Generation

**Few shot font generation via transferring similarity guided global style and quantization local style**
- Paper: https://arxiv.org/abs/2309.00827
- Code: https://github.com/awei669/VQ-Font

<!--
## Virtual Try-on
-->

