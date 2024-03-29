# Awesome-ICCV2021-Low-Level-Vision
A Collection of Papers and Codes in ICCV2021 related to Low-Level Vision

**[Completed]** If you find some missing papers or typos, feel free to pull issues or requests.

## Related collections for low-level vision
- [Awesome-CVPR2023/2022-Low-Level-Vision](https://github.com/DarrenPan/Awesome-CVPR2023-Low-Level-Vision)
- [Awesome-NeurIPS2022/2021-Low-Level-Vision](https://github.com/DarrenPan/Awesome-NeurIPS2022-Low-Level-Vision)
- [Awesome-ECCV2022-Low-Level-Vision](https://github.com/DarrenPan/Awesome-ECCV2022-Low-Level-Vision)
- [Awesome-AAAI2022-Low-Level-Vision](https://github.com/DarrenPan/Awesome-AAAI2022-Low-Level-Vision)
- [Awesome-CVPR2021/2020-Low-Level-Vision](https://github.com/Kobaayyy/Awesome-CVPR2021-CVPR2020-Low-Level-Vision)
- [Awesome-ECCV2020-Low-Level-Vision](https://github.com/Kobaayyy/Awesome-ECCV2020-Low-Level-Vision)


## Catalogue

- [Image Restoration](#ImageRetoration)
  - [Video Restoration](#VideoRestoration)

- [Super Resolution](#SuperResolution)
  - [Image Super Resolution](#ImageSuperResolution)
  - [Video Super Resolution](#VideoSuperResolution)
- [Image Rescaling](#Rescaling)

- [Denoising](#Denoising)
  - [Image Denoising](#ImageDenoising)
  - [Video Denoising](#VideoDenoising)

- [Deblurring](#Deblurring)
  - [Image Deblurring](#ImageDeblurring)
  - [Video Deblurring](#VideoDeblurring)

- [Deraining](#Deraining)

- [HDR Imaging / Multi-Exposure Image Fusion](#HDR)

- [Frame Interpolation](#FrameInterpolation)

- [Image Enhancement](#Enhancement)
  - [Low-Light Image Enhancement](#LowLight)

- [Image Harmonization](#Harmonization)

- [Image Completion/Inpainting](#Inpainting)

- [Image Matting](#Matting)

- [Image Stitching](#Stitching)

- [Image Compression](#ImageCompression)

- [Image Quality Assessment](#ImageQualityAssessment)

- [Style Transfer](#StyleTransfer)

- [Image Editing](#ImageEditing)

- [Image Generation/Synthesis/ Image-to-Image Translation](#ImageGeneration)
  - [Video Generation](#VideoGeneration)

- [Others](#Others)


<a name="ImageRetoration"></a>
# Image Restoration - 图像恢复 [[back](#catalogue)]

**Spatially-Adaptive Image Restoration using Distortion-Guided Networks**
- Paper：https://arxiv.org/abs/2108.08617
- Code: https://github.com/human-analysis/spatially-adaptive-image-restoration

**Dynamic Attentive Graph Learning for Image Restoration**
- Paper：https://arxiv.org/abs/2109.06620
- Code：https://github.com/jianzhangcs/DAGL

**Searching for Controllable Image Restoration Networks**
- Paper: https://arxiv.org/abs/2012.11225

**Self-Supervised Cryo-Electron Tomography Volumetric Image Restoration From Single Noisy Volume With Sparsity Constraint**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Yang_Self-Supervised_Cryo-Electron_Tomography_Volumetric_Image_Restoration_From_Single_Noisy_Volume_ICCV_2021_paper.html
- Code: https://github.com/icthrm/SC-Net
- Tags: Self-Supervised, Cryo-Electron Tomography Volumetric

**Let's See Clearly: Contaminant Artifact Removal for Moving Cameras**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Li_Lets_See_Clearly_Contaminant_Artifact_Removal_for_Moving_Cameras_ICCV_2021_paper.html

**Light Source Guided Single-Image Flare Removal from Unpaired Data**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Qiao_Light_Source_Guided_Single-Image_Flare_Removal_From_Unpaired_Data_ICCV_2021_paper.html
- Tags: Flare Removal

**How to Train Neural Networks for Flare Removal**
- Paper: https://arxiv.org/abs/2011.12485
- Code: https://github.com/google-research/google-research/tree/master/flare_removal
- Tags: Flare Removal

**Location-Aware Single Image Reflection Removal**
- Paper: https://arxiv.org/abs/2012.07131
- Code: https://github.com/zdlarr/Location-aware-SIRR
- Tags: Reflection Removal

**V-DESIRR: Very Fast Deep Embedded Single Image Reflection Removal**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Prasad_V-DESIRR_Very_Fast_Deep_Embedded_Single_Image_Reflection_Removal_ICCV_2021_paper.html
- Code: https://github.com/ee19d005/vdesirr
- Tags: Reflection Removal

**Unsupervised Non-Rigid Image Distortion Removal via Grid Deformation**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Li_Unsupervised_Non-Rigid_Image_Distortion_Removal_via_Grid_Deformation_ICCV_2021_paper.html
- Code: https://github.com/Nianyi-Li/unsupervised-NDIR

**Towards Flexible Blind JPEG Artifacts Removal**
- Paper: https://arxiv.org/abs/2109.14573
- Code: https://github.com/jiaxi-jiang/FBCNN
- Tags: JPEG Artifacts Removal

**Learning Dual Priors for JPEG Compression Artifacts Removal**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Fu_Learning_Dual_Priors_for_JPEG_Compression_Artifacts_Removal_ICCV_2021_paper.html
- Tags: JPEG Artifacts Removal

**CANet: A Context-Aware Network for Shadow Removal**
- Paper: https://arxiv.org/abs/2108.09894
- Code: https://github.com/Zipei-Chen/CANet
- Tags: Shadow Removal

**DC-ShadowNet: Single-Image Hard and Soft Shadow Removal Using Unsupervised Domain-Classifier Guided Network**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Jin_DC-ShadowNet_Single-Image_Hard_and_Soft_Shadow_Removal_Using_Unsupervised_Domain-Classifier_ICCV_2021_paper.html
- Code: https://github.com/jinyeying/DC-ShadowNet-Hard-and-Soft-Shadow-Removal
- Tags: Shadow Removal

**Learning To Remove Refractive Distortions From Underwater Images**
- Paper：https://openaccess.thecvf.com/content/ICCV2021/html/Thapa_Learning_To_Remove_Refractive_Distortions_From_Underwater_Images_ICCV_2021_paper.html
- Code: https://github.com/SimronThapa/DG-Net-ICCV2021
- Tags: Underwater, Refraction Removal

**ALL Snow Removed: Single Image Desnowing Algorithm Using Hierarchical Dual-Tree Complex Wavelet Representation and Contradict Channel Loss**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Chen_ALL_Snow_Removed_Single_Image_Desnowing_Algorithm_Using_Hierarchical_Dual-Tree_ICCV_2021_paper.html
- Code: https://github.com/weitingchen83/ICCV2021-Single-Image-Desnowing-HDCWNet
- Tags: Desnowing

## Burst Restoration

**Deep Reparametrization of Multi-Frame Super-Resolution and Denoising**
- Paper: https://arxiv.org/abs/2108.08286
- Code: https://github.com/goutamgmb/deep-rep

<a name="SuperResolution"></a>
# Super Resolution - 超分辨率 [[back](#catalogue)]
<a name="ImageSuperResolution"></a>
## Image Super Resolution

**Attention-based Multi-Reference Learning for Image Super-Resolution**
- Paper：https://arxiv.org/abs/2108.13697
- Code：https://github.com/marcopesavento/Attention-based-Multi-Reference-Learning-for-Image-Super-Resolution

**Learning A Single Network for Scale-Arbitrary Super-Resolution**
- Paper：https://arxiv.org/abs/2004.03791
- Code：https://github.com/LongguangWang/ArbSR

**Fourier Space Losses for Efficient Perceptual Image Super-Resolution**
- Paper：https://arxiv.org/abs/2106.00783

**Dynamic High-Pass Filtering and Multi-Spectral Attention for Image Super-Resolution**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Magid_Dynamic_High-Pass_Filtering_and_Multi-Spectral_Attention_for_Image_Super-Resolution_ICCV_2021_paper.html
- Code: https://github.com/sabdelmagid/DFSA_ICCV21

**Context Reasoning Attention Network for Image Super-Resolution**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Zhang_Context_Reasoning_Attention_Network_for_Image_Super-Resolution_ICCV_2021_paper.html
- Code(Unofficial): https://github.com/Ast-363/CRAN

**Learning Frequency-aware Dynamic Network for Efficient Super-Resolution**
- Paper: https://arxiv.org/abs/2103.08357
- Code(Unofficial): https://github.com/songyonger/FADN

**Benchmarking Ultra-High-Definition Image Super-Resolution**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Zhang_Benchmarking_Ultra-High-Definition_Image_Super-Resolution_ICCV_2021_paper.html
- Code: https://github.com/HDCVLab/UHD4K_UHD8K

**Mutual Affine Network for Spatially Variant Kernel Estimation in Blind Image Super-Resolution**
- Code：https://github.com/JingyunLiang/MANet
- Code: https://arxiv.org/abs/2108.05302
- Tags: Blind SR

**Designing a Practical Degradation Model for Deep Blind Image Super-Resolution**
- Paper：https://arxiv.org/abs/2103.14006
- Code：https://github.com/cszn/BSRGAN
- Tags: Blind SR

**Unsupervised Real-World Super-Resolution: A Domain Adaptation Perspective**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Unsupervised_Real-World_Super-Resolution_A_Domain_Adaptation_Perspective_ICCV_2021_paper.html
- Code(Unofficial): https://github.com/anse3832/USR_DA
- Tags: Unsupervised

**Achieving On-Mobile Real-Time Super-Resolution With Neural Architecture and Pruning Search**
- Paper: https://arxiv.org/abs/2108.08910

**EvIntSR-Net: Event Guided Multiple Latent Frames Reconstruction and Super-Resolution**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Han_EvIntSR-Net_Event_Guided_Multiple_Latent_Frames_Reconstruction_and_Super-Resolution_ICCV_2021_paper.html
- Tags: Event 

**Super-Resolving Cross-Domain Face Miniatures by Peeking at One-Shot Exemplar**
- Paper：https://openaccess.thecvf.com/content/ICCV2021/html/Li_Super-Resolving_Cross-Domain_Face_Miniatures_by_Peeking_at_One-Shot_Exemplar_ICCV_2021_paper.html

**Dual-Camera Super-Resolution with Aligned Attention Modules**
- Paper: https://arxiv.org/abs/2109.01349
- Code: https://github.com/Tengfei-Wang/DCSR
- Tags: Dual-Camera

**Lucas-Kanade Reloaded: End-to-End Super-Resolution from Raw Image Bursts**
- Paper：https://arxiv.org/abs/2104.06191
- Tags: Burst SR

<a name="VideoSuperResolution"></a>
## Video Super Resolution

**Deep Blind Video Super-resolution**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Pan_Deep_Blind_Video_Super-Resolution_ICCV_2021_paper.html
- Code：https://github.com/csbhr/Deep-Blind-VSR

**Omniscient Video Super-Resolution**
- Paper: https://arxiv.org/abs/2103.15683
- Code：https://github.com/psychopa4/OVSR

**COMISR: Compression-Informed Video Super-Resolution**
- Paper：https://arxiv.org/abs/2105.01237
- Code：https://github.com/google-research/google-research/tree/master/comisr

**Real-World Video Super-Resolution: A Benchmark Dataset and a Decomposition Based Learning Scheme**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Yang_Real-World_Video_Super-Resolution_A_Benchmark_Dataset_and_a_Decomposition_Based_ICCV_2021_paper.html
- Code: https://github.com/IanYeung/RealVSR
- Tags: Real

**Event Stream Super-Resolution via Spatiotemporal Constraint Learning**
- Paper：https://openaccess.thecvf.com/content/ICCV2021/html/Li_Event_Stream_Super-Resolution_via_Spatiotemporal_Constraint_Learning_ICCV_2021_paper.html
- Tags: Event

<a name="Rescaling"></a>
# Image Rescaling - 图像缩放 [[back](#catalogue)]

**Hierarchical Conditional Flow: A Unified Framework for Image Super-Resolution and Image Rescaling**
- Paper: https://arxiv.org/abs/2108.05301
- Code: https://github.com/JingyunLiang/HCFlow

**Self-Conditioned Probabilistic Learning of Video Rescaling**
- Paper: https://arxiv.org/abs/2107.11639
- Code: https://github.com/tianyuan168326/SelfC

<a name="Denoising"></a>
# Denoising - 去噪 [[back](#catalogue)]

<a name="ImageDenoising"></a>
## Image Denoising

**Rethinking Deep Image Prior for Denoising**
- Paper: https://arxiv.org/abs/2108.12841
- Code: https://github.com/gistvision/DIP-denosing

**Self-Supervised Image Prior Learning With GMM From a Single Noisy Image**
- Paper：https://openaccess.thecvf.com/content/ICCV2021/html/Liu_Self-Supervised_Image_Prior_Learning_With_GMM_From_a_Single_Noisy_ICCV_2021_paper.html
- Code：https://github.com/HUST-Tan/SS-GMM
- Tags: self-supervised, Gaussian Mixture Mode

**Cross-Patch Graph Convolutional Network for Image Denoising**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Li_Cross-Patch_Graph_Convolutional_Network_for_Image_Denoising_ICCV_2021_paper.html
- Tags: GCN

**C2N: Practical Generative Noise Modeling for Real-World Denoising**
- Paper：https://openaccess.thecvf.com/content/ICCV2021/html/Jang_C2N_Practical_Generative_Noise_Modeling_for_Real-World_Denoising_ICCV_2021_paper.html
- Code: https://github.com/onwn/c2n
- Tags: Noise Modeling

**Rethinking Noise Synthesis and Modeling in Raw Denoising**
- Paper: https://arxiv.org/abs/2110.04756
- Code: https://github.com/zhangyi-3/noise-synthesis
- Tags: Noise Modeling

**Hyperspectral Image Denoising With Realistic Data**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Zhang_Hyperspectral_Image_Denoising_With_Realistic_Data_ICCV_2021_paper.html
- Code: https://github.com/ColinTaoZhang/HSIDwRD
- Tags: Hyperspectral Image

**End-to-End Unsupervised Document Image Blind Denoising**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Gangeh_End-to-End_Unsupervised_Document_Image_Blind_Denoising_ICCV_2021_paper.html
- Tags: Unsupervised, Document Denoising

<a name="VideoDenoising"></a>
## Video Denoising

**Patch Craft: Video Denoising by Deep Modeling and Patch Matching**
- Paper: https://arxiv.org/abs/2103.13767
- Code: https://github.com/grishavak/PaCNet-denoiser 

**Unsupervised Deep Video Denoising**
- Paper: https://arxiv.org/abs/2011.15045
- Code: https://github.com/sreyas-mohan/udvd
- Tags: Unsupervised

<a name="Deblurring"></a>
# Deblurring - 去模糊 [[back](#catalogue)]
<a name="ImageDeblurring"></a>
## Image Deblurring

**Rethinking Coarse-to-Fine Approach in Single Image Deblurring**
- Paper：https://arxiv.org/abs/2108.05054
- Code：https://github.com/chosj95/MIMO-UNet

**Single Image Defocus Deblurring Using Kernel-Sharing Parallel Atrous Convolutions**
- Paper：https://arxiv.org/abs/2108.09108
- Code: https://github.com/HyeongseokSon1/KPAC

**Defocus Map Estimation and Deblurring From a Single Dual-Pixel Image**
- Paper: https://arxiv.org/abs/2110.05655
- Code: https://github.com/cmu-ci-lab/dual_pixel_defocus_estimation_deblurring

**Pyramid Architecture Search for Real-Time Image Deblurring**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Hu_Pyramid_Architecture_Search_for_Real-Time_Image_Deblurring_ICCV_2021_paper.html

**Perceptual Variousness Motion Deblurring With Light Global Context Refinement**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Li_Perceptual_Variousness_Motion_Deblurring_With_Light_Global_Context_Refinement_ICCV_2021_paper.html

**Motion Deblurring with Real Events**
- Paper: https://arxiv.org/abs/2109.13695
- Code: https://github.com/xufangchn/Motion-Deblurring-with-Real-Events

<a name="VideoDeblurring"></a>
## Video Deblurring

**Bringing Events into Video Deblurring with Non consecutively Blurry Frames**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Shang_Bringing_Events_Into_Video_Deblurring_With_Non-Consecutively_Blurry_Frames_ICCV_2021_paper.html
- Code：https://github.com/shangwei5/D2Net

**Multi-Scale Separable Network for Ultra-High-Definition Video Deblurring**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Deng_Multi-Scale_Separable_Network_for_Ultra-High-Definition_Video_Deblurring_ICCV_2021_paper.html
- Code: https://github.com/dseny/UHDVD

<a name="Deraining"></a>
# Deraining - 去雨 [[back](#catalogue)]

**Structure-Preserving Deraining with Residue Channel Prior Guidance**
- Paper: https://arxiv.org/abs/2108.09079
- Code：https://github.com/Joyies/SPDNet

**Improving De-Raining Generalization via Neural Reorganization**
- Paper：https://openaccess.thecvf.com/content/ICCV2021/html/Xiao_Improving_De-Raining_Generalization_via_Neural_Reorganization_ICCV_2021_paper.html
- Code：https://github.com/cszn/BSRGAN

**Unpaired Learning for Deep Image Deraining With Rain Direction Regularizer**
- Paper：https://openaccess.thecvf.com/content/ICCV2021/html/Liu_Unpaired_Learning_for_Deep_Image_Deraining_With_Rain_Direction_Regularizer_ICCV_2021_paper.html


 <a name="HDR"></a>
# HDR Imaging / Multi-Exposure Image Fusion - HDR图像生成 / 多曝光图像融合 [[back](#catalogue)]

**Unpaired Learning for High Dynamic Range Image Tone Mapping**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Vinker_Unpaired_Learning_for_High_Dynamic_Range_Image_Tone_Mapping_ICCV_2021_paper.html
- Code: https://github.com/yael-vinker/unpaired_hdr_tmo
- Tone Mapping

**HDR Video Reconstruction: A Coarse-to-fine Network and A Real-world Benchmark Dataset**
- Paper：https://arxiv.org/abs/2103.14943
- Code：https://github.com/guanyingc/DeepHDRVideo

**A New Journey from SDRTV to HDRTV**
- Paper：https://arxiv.org/abs/2108.07978
- Code：https://github.com/chxy95/HDRTVNet

**Ultra-High-Definition Image HDR Reconstruction via Collaborative Bilateral Learning **
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Zheng_Ultra-High-Definition_Image_HDR_Reconstruction_via_Collaborative_Bilateral_Learning_ICCV_2021_paper.html


<a name="FrameInterpolation"></a>
# Frame Interpolation - 插帧 [[back](#catalogue)]

**XVFI: eXtreme Video Frame Interpolation**
- Paper：https://arxiv.org/abs/2103.16206
- Code：https://github.com/JihyongOh/XVFI

**Asymmetric Bilateral Motion Estimation for Video Frame Interpolation**
- Paper： https://arxiv.org/abs/2108.06815
- Code： https://github.com/JunHeum/ABME

**Training Weakly Supervised Video Frame Interpolation With Events**
- Paper： https://openaccess.thecvf.com/content/ICCV2021/html/Yu_Training_Weakly_Supervised_Video_Frame_Interpolation_With_Events_ICCV_2021_paper.html

**Motion-Aware Dynamic Architecture for Efficient Frame Interpolation**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Choi_Motion-Aware_Dynamic_Architecture_for_Efficient_Frame_Interpolation_ICCV_2021_paper.html


<a name="Enhancement"></a>
# Image Enhancement - 图像增强 [[back](#catalogue)]

**StarEnhancer: Learning Real-Time and Style-Aware Image Enhancement**
- Paper：https://arxiv.org/abs/2107.12898
- Code：https://github.com/IDKiro/StarEnhancer

**Real-time Image Enhancer via Learnable Spatial-aware 3D Lookup Tables**
- Paper：https://arxiv.org/abs/2108.08697

**Deep Symmetric Network for Underexposed Image Enhancement With Recurrent Attentional Learning**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Zhao_Deep_Symmetric_Network_for_Underexposed_Image_Enhancement_With_Recurrent_Attentional_ICCV_2021_paper.html
- Code: https://github.com/lin-zhao-resoLve/Deep-Symmetric-Network-Enhancement

**STAR: A Structure-Aware Lightweight Transformer for Real-Time Image Enhancement**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Zhang_STAR_A_Structure-Aware_Lightweight_Transformer_for_Real-Time_Image_Enhancement_ICCV_2021_paper.html
- Code: https://github.com/zzyfd/STAR-pytorch

<a name="LowLight"></a>
## Low-Light Image Enhancement

**Adaptive Unfolding Total Variation Network for Low-Light Image Enhancement**
- Paper：https://arxiv.org/abs/2110.00984
- Code：https://github.com/YU-Zhiyang/WEVI

**Representative Color Transform for Image Enhancement**
- Paper：https://openaccess.thecvf.com/content/ICCV2021/html/Kim_Representative_Color_Transform_for_Image_Enhancement_ICCV_2021_paper.html
- Code: https://github.com/ThanosM97/Representative-Color-Transform

**Seeing Dynamic Scene in the Dark: A High-Quality Video Dataset With Mechatronic Alignment**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Seeing_Dynamic_Scene_in_the_Dark_A_High-Quality_Video_Dataset_ICCV_2021_paper.html
- Code: https://github.com/dvlab-research/SDSD


<a name="Harmonization"></a>
# Image Harmonization/Composition - 图像协调/图像合成 [[back](#catalogue)]

**SSH: A Self-Supervised Framework for Image Harmonization**
- Paper：https://arxiv.org/abs/2108.06805
- Code：https://github.com/VITA-Group/SSHarmonization

**Image Harmonization With Transformer**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Guo_Image_Harmonization_With_Transformer_ICCV_2021_paper.html
- Code: https://github.com/zhenglab/HarmonyTransformer


<a name="Inpainting"></a>
# Image Completion/Inpainting - 图像修复 [[back](#catalogue)]

**High-Fidelity Pluralistic Image Completion with Transformers**
- Paper：https://arxiv.org/abs/2103.14031
- Code：https://github.com/raywzy/ICT

**Image Inpainting via Conditional Texture and Structure Dual Generation**
- Paper：https://arxiv.org/abs/2108.09760
- Code：https://github.com/Xiefan-Guo/CTSDG

**CR-Fill: Generative Image Inpainting with Auxiliary Contextual Reconstruction**
- Paper：https://arxiv.org/abs/2011.12836
- Code：https://github.com/zengxianyu/crfill

**Parallel Multi-Resolution Fusion Network for Image Inpainting**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Parallel_Multi-Resolution_Fusion_Network_for_Image_Inpainting_ICCV_2021_paper.html

**WaveFill: A Wavelet-based Generation Network for Image Inpainting**
- Paper: https://arxiv.org/abs/2107.11027
- Code: https://github.com/yingchen001/WaveFill

**Learning a Sketch Tensor Space for Image Inpainting of Man-made Scenes**
- Paper: https://arxiv.org/abs/2103.15087
- Code: https://github.com/ewrfcas/MST_inpainting

**Distillation-Guided Image Inpainting**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Suin_Distillation-Guided_Image_Inpainting_ICCV_2021_paper.html

## Video Inpainting

**Internal Video Inpainting by Implicit Long-range Propagation**
- Paper: https://arxiv.org/abs/2108.01912
- Code1：https://github.com/Tengfei-Wang/Annotated-4K-Videos
- Code2: https://github.com/Tengfei-Wang/Implicit-Internal-Video-Inpainting

**Occlusion-Aware Video Object Inpainting**
- Paper：https://arxiv.org/abs/2108.06765

**FuseFormer: Fusing Fine-Grained Information in Transformers for Video Inpainting**
- Paper：https://openaccess.thecvf.com/content/ICCV2021/html/Liu_FuseFormer_Fusing_Fine-Grained_Information_in_Transformers_for_Video_Inpainting_ICCV_2021_paper.html
- Code：https://github.com/ruiliu-ai/FuseFormer

**Flow-Guided Video Inpainting with Scene Templates**
- Paper: https://arxiv.org/abs/2108.12845
- Code: https://github.com/donglao/videoinpainting

<a name="Matting"></a>
# Image Matting - 图像抠图 [[back](#catalogue)]

**Cascade Image Matting with Deformable Graph Refinement**
- Paper: https://arxiv.org/abs/2105.02646

**Tripartite Information Mining and Integration for Image Matting**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Liu_Tripartite_Information_Mining_and_Integration_for_Image_Matting_ICCV_2021_paper.html
- Code: https://github.com/kelisiya/TIMI-Net

**Virtual Multi-Modality Self-Supervised Foreground Matting for Human-Object Interaction**
- Paper: https://arxiv.org/abs/2110.03278
- Code: https://github.com/jacksyu/hoi-matting

**Video Matting via Consistency-Regularized Graph Neural Networks**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Video_Matting_via_Consistency-Regularized_Graph_Neural_Networks_ICCV_2021_paper.html
- Code: https://github.com/TiantianWang/VideoMatting-CRGNN


<a name="Stitching"></a>
# Image Stitching - 图像拼接 [[back](#catalogue)]

**Minimal Solutions for Panoramic Stitching Given Gravity Prior**
- Paper: https://arxiv.org/abs/2012.00465


<a name="ImageCompression"></a>
# Image Compression - 图像压缩 [[back](#catalogue)]

**Variable-Rate Deep Image Compression through Spatially-Adaptive Feature Transform**
- Paper：https://arxiv.org/abs/2108.09551
- Code：https://github.com/micmic123/QmapCompression

**Neural Image Compression via Attentional Multi-Scale Back Projection and Frequency Decomposition**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Gao_Neural_Image_Compression_via_Attentional_Multi-Scale_Back_Projection_and_Frequency_ICCV_2021_paper.html

## Video Compression

**Extending Neural P-frame Codecs for B-frame Coding**
- Paper：https://arxiv.org/abs/2104.00531

**Efficient Video Compression via Content-Adaptive Super-Resolution**
- Paper：https://arxiv.org/abs/2104.02322
- Code：https://github.com/AdaptiveVC/SRVC

**Online-Trained Upsampler for Deep Low Complexity Video Compression**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Klopp_Online-Trained_Upsampler_for_Deep_Low_Complexity_Video_Compression_ICCV_2021_paper.html


<a name="ImageQualityAssessment"></a>
# Image Quality Assessment - 图像质量评价 [[back](#catalogue)]

**Learning Conditional Knowledge Distillation for Degraded-Reference Image Quality Assessment**
- Paper: https://arxiv.org/abs/2108.07948
- Code: https://github.com/researchmm/CKDN

**Unsupervised Curriculum Domain Adaptation for No-Reference Video Quality Assessment**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Chen_Unsupervised_Curriculum_Domain_Adaptation_for_No-Reference_Video_Quality_Assessment_ICCV_2021_paper.html
- Code: https://github.com/cpf0079/UCDA

**MUSIQ: Multi-scale Image Quality Transformer**
- Paper: https://arxiv.org/abs/2108.05997
- Code: https://github.com/anse3832/MUSIQ


<a name="StyleTransfer"></a>
# Style Transfer - 风格迁移 [[back](#catalogue)]

**Diverse Image Style Transfer via Invertible Cross-Space Mapping**
- Paper：https://openaccess.thecvf.com/content/ICCV2021/html/Chen_Diverse_Image_Style_Transfer_via_Invertible_Cross-Space_Mapping_ICCV_2021_paper.html

**DRB-GAN: A Dynamic ResBlock Generative Adversarial Network for Artistic Style Transfer**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Xu_DRB-GAN_A_Dynamic_ResBlock_Generative_Adversarial_Network_for_Artistic_Style_ICCV_2021_paper.html

**Domain Aware Universal Style Transfer**
- Paper：https://arxiv.org/abs/2108.04441
- Code：https://github.com/Kibeom-Hong/Domain-Aware-Style-Transfer

**StyleFormer: Real-Time Arbitrary Style Transfer via Parametric Style Composition**
- Paper：https://openaccess.thecvf.com/content/ICCV2021/html/Wu_StyleFormer_Real-Time_Arbitrary_Style_Transfer_via_Parametric_Style_Composition_ICCV_2021_paper.html

**AdaAttN: Revisit Attention Mechanism in Arbitrary Neural Style Transfer**
- Paper：https://arxiv.org/abs/2108.03647
- Code：https://github.com/Huage001/AdaAttN

**Manifold Alignment for Semantically Aligned Style Transfer**
- Paper: https://arxiv.org/abs/2005.10777
- Code: https://github.com/NJUHuoJing/MAST

**ALADIN: All Layer Adaptive Instance Normalization for Fine-grained Style Similarity**
- Paper：https://arxiv.org/abs/2103.09776


<a name="ImageEditing"></a>
# Image Editing - 图像编辑 [[back](#catalogue)]

**Latent Transformations via NeuralODEs for GAN-Based Image Editing**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Khrulkov_Latent_Transformations_via_NeuralODEs_for_GAN-Based_Image_Editing_ICCV_2021_paper.html

**Language-Guided Global Image Editing via Cross-Modal Cyclic Mechanism**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Jiang_Language-Guided_Global_Image_Editing_via_Cross-Modal_Cyclic_Mechanism_ICCV_2021_paper.html

**Talk-to-Edit: Fine-Grained Facial Editing via Dialog**
- Paper: https://arxiv.org/abs/2109.04425
- Code: https://github.com/yumingj/Talk-to-Edit

**A Latent Transformer for Disentangled Face Editing in Images and Videos**
- Paper: https://arxiv.org/abs/2106.11895
- Code: https://github.com/InterDigitalInc/latent-transformer

**GAN Inversion for Out-of-Range Images with Geometric Transformations**
- Paper: https://arxiv.org/abs/2108.08998
- Code: https://github.com/kkang831/BDInvert_Release

**Image Shape Manipulation from a Single Augmented Training Sample**
- Paper: https://arxiv.org/abs/2007.01289
- Code: https://github.com/eliahuhorwitz/DeepSIM

**Dressing in Order: Recurrent Person Image Generation for Pose Transfer, Virtual Try-on and Outfit Editing**
- Paper: https://arxiv.org/abs/2104.07021
- Code: https://github.com/cuiaiyu/dressing-in-order

**Toward a Visual Concept Vocabulary for GAN Latent Space**
- Paper: https://arxiv.org/abs/2110.04292
- Code: https://github.com/schwettmann/visual-vocab

<a name=ImageGeneration></a>
# Image Generation/Synthesis / Image-to-Image Translation - 图像生成/合成/转换 [[back](#catalogue)]
## Text-to-Image / Text Guided / Multi-Modal

**StyleCLIP: Text-Driven Manipulation of StyleGAN Imagery**
- Paper: https://arxiv.org/abs/2103.17249
- Code: https://github.com/orpatashnik/StyleCLIP

**DAE-GAN: Dynamic Aspect-Aware GAN for Text-to-Image Synthesis**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Ruan_DAE-GAN_Dynamic_Aspect-Aware_GAN_for_Text-to-Image_Synthesis_ICCV_2021_paper.html
- Code: https://github.com/hiarsal/DAE-GAN

**PIRenderer: Controllable Portrait Image Generation via Semantic Neural Rendering**
- Paper: https://arxiv.org/abs/2109.08379
- Code: https://github.com/RenYurui/PIRender

## Image-to-Image / Image Guided

**Bridging the Gap Between Label- and Reference-Based Synthesis in Multi-Attribute Image-to-Image Translation**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Huang_Bridging_the_Gap_Between_Label-_and_Reference-Based_Synthesis_in_Multi-Attribute_ICCV_2021_paper.html
- Code: https://github.com/huangqiusheng/BridgeGAN

**Instance-wise Hard Negative Example Generation for Contrastive Learning in Unpaired Image-to-Image Translation**
- Paper: https://arxiv.org/abs/2108.04547
- Code: https://github.com/WeilunWang/NEGCUT

**Unaligned Image-to-Image Translation by Learning to Reweight**
- Paper：https://arxiv.org/abs/2109.11736
- Code：https://github.com/Mid-Push/IrwGAN

**TransferI2I: Transfer Learning for Image-to-Image Translation from Small Datasets**
- Paper: https://arxiv.org/abs/2105.06219

**SPatchGAN: A Statistical Feature Based Discriminator for Unsupervised Image-to-Image Translation**
- Paper：https://arxiv.org/abs/2103.16219
- Code：https://github.com/NetEase-GameAI/SPatchGAN

**Rethinking the Truly Unsupervised Image-to-Image Translation**
- Paper: https://arxiv.org/abs/2006.06500
- Code: https://github.com/clovaai/tunit

**Scaling-up Disentanglement for Image Translation**
- Paper：https://arxiv.org/abs/2103.14017
- Code：https://github.com/avivga/overlord

**Harnessing the Conditioning Sensorium for Improved Image Translation**
- Paper: https://arxiv.org/abs/2110.06443

**Semantically Robust Unpaired Image Translation for Data with Unmatched Semantics Statistics**
- Paper: https://arxiv.org/abs/2012.04932
- Code: https://github.com/SeanJia/SRUNIT

**Frequency Domain Image Translation: More Photo-realistic, Better Identity-preserving**
- Paper: https://arxiv.org/abs/2011.13611
- Code: https://github.com/mu-cai/frequency-domain-image-translation

**Diagonal Attention and Style-based GAN for Content-Style Disentanglement in Image Generation and Translation**
- Paper: https://arxiv.org/abs/2103.16146
- Code: https://github.com/cyclomon/DiagonalGAN

**Image Synthesis via Semantic Composition**
- Paper: https://arxiv.org/abs/2109.07053
- Code:https://github.com/dvlab-research/SCGAN

**Collaging Class-specific GANs for Semantic Image Synthesis**
- Paper: https://arxiv.org/abs/2110.04281

**Image Synthesis From Layout With Locality-Aware Mask Adaption**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Li_Image_Synthesis_From_Layout_With_Locality-Aware_Mask_Adaption_ICCV_2021_paper.html

**Structure-Transformed Texture-Enhanced Network for Person Image Synthesis**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Xu_Structure-Transformed_Texture-Enhanced_Network_for_Person_Image_Synthesis_ICCV_2021_paper.html

**ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models**
- Paper: https://arxiv.org/abs/2108.02938
- Code: https://github.com/jychoi118/ilvr_adm

**Sketch Your Own GAN**
- Paper: https://arxiv.org/abs/2108.02774
- Code: https://github.com/PeterWang512/GANSketching

**Re-Aging GAN: Toward Personalized Face Age Transformation**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Makhmudkhujaev_Re-Aging_GAN_Toward_Personalized_Face_Age_Transformation_ICCV_2021_paper.html

## Others for image generation

**Focal Frequency Loss for Image Reconstruction and Synthesis**
- Paper: https://arxiv.org/abs/2012.12821
- Code: https://github.com/EndlessSora/focal-frequency-loss

**Unsupervised Image Generation with Infinite Generative Adversarial Networks**
- Paper: https://arxiv.org/abs/2108.07975
- Code: https://github.com/yinghdb/MICGANs

**Semi-Supervised Single-Stage Controllable GANs for Conditional Fine-Grained Image Generation**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Chen_Semi-Supervised_Single-Stage_Controllable_GANs_for_Conditional_Fine-Grained_Image_Generation_ICCV_2021_paper.html

**Orthogonal Jacobian Regularization for Unsupervised Disentanglement in Image Generation**
- Paper: https://arxiv.org/abs/2108.07668
- Code: https://github.com/csyxwei/OroJaR

**LoFGAN: Fusing Local Representations for Few-Shot Image Generation**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Gu_LoFGAN_Fusing_Local_Representations_for_Few-Shot_Image_Generation_ICCV_2021_paper.html
- Code: https://github.com/edward3862/LoFGAN-pytorch

**Dual Projection Generative Adversarial Networks for Conditional Image Generation**
- Paper: https://arxiv.org/abs/2108.09016
- Code: https://github.com/phymhan/P2GAN

**Multi-Class Multi-Instance Count Conditioned Adversarial Image Generation**
- Paper: https://arxiv.org/abs/2103.16795
- Code: https://github.com/boschresearch/MCCGAN

**GAN-Control: Explicitly Controllable GANs**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Shoshan_GAN-Control_Explicitly_Controllable_GANs_ICCV_2021_paper.html
- Code: https://github.com/amazon-science/gan-control

**Omni-GAN: On the Secrets of cGANs and Beyond**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Zhou_Omni-GAN_On_the_Secrets_of_cGANs_and_Beyond_ICCV_2021_paper.html
- Code: https://github.com/PeterouZh/Omni-GAN-PyTorch

**Detail Me More: Improving GAN's Photo-Realism of Complex Scenes**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Gadde_Detail_Me_More_Improving_GANs_Photo-Realism_of_Complex_Scenes_ICCV_2021_paper.html

**Online Multi-Granularity Distillation for GAN Compression**
- Paper: https://arxiv.org/abs/2108.06908
- Code: https://github.com/bytedance/OMGD

**WarpedGANSpace: Finding non-linear RBF paths in GAN latent space**
- Paper: https://arxiv.org/abs/2109.13357
- Code: https://github.com/chi0tzp/WarpedGANSpace

<a name="VideoGeneration"></a>
## Video Generation

**Click to Move: Controlling Video Generation with Sparse Motion**
- Paper: https://arxiv.org/abs/2108.08815
- Code: https://github.com/PierfrancescoArdino/C2M

**iPOKE: Poking a Still Image for Controlled Stochastic Video Synthesis**
- Paper: https://arxiv.org/abs/2107.02790
- Code: https://github.com/CompVis/ipoke

**Sat2Vid: Street-view Panoramic Video Synthesis from a Single Satellite Image**
- Paper: https://arxiv.org/abs/2012.06628


<a name="Others"></a>
## Others [[back](#catalogue)]

**Neural Video Portrait Relighting in Real-time via Consistency Modeling**
- Paper: https://arxiv.org/abs/2104.00484
- Code: https://github.com/ZoneLikeWonderland/Neural-Video-Portrait-Relighting-in-Real-time-via-Consistency-Modeling
- Tags: Relighting

**Towards Vivid and Diverse Image Colorization with Generative Color Prior**
- Paper：https://arxiv.org/abs/2108.08826
- Code: https://github.com/ToTheBeginning/GCP-Colorization
- Tags: Colorization

**Deep Edge-Aware Interactive Colorization against Color-Bleeding Effects**
- Paper：https://arxiv.org/abs/2107.01619
- Code: https://github.com/niceDuckgu/CDR
- Tags: Colorization

**Overfitting the Data: Compact Neural Video Delivery via Content-aware Feature Modulation**
- Paper: https://arxiv.org/abs/2108.08202
- Code: https://github.com/Neural-video-delivery/CaFM-Pytorch-ICCV2021
- Tags: Video Delivery

**IICNet: A Generic Framework for Reversible Image Conversion**
- Paper: https://arxiv.org/abs/2109.04242
- Code: https://github.com/felixcheng97/IICNet
- Tags: Reversible Image Conversion

**FashionMirror: Co-Attention Feature-Remapping Virtual Try-On With Sequential Template Poses**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Chen_FashionMirror_Co-Attention_Feature-Remapping_Virtual_Try-On_With_Sequential_Template_Poses_ICCV_2021_paper.html
- Code: https://github.com/FashionMirror/FashionMirror
- Tags: Virtual Try-on

## Talking Head Generation

**Learned Spatial Representations for Few-shot Talking-Head Synthesis**
- Paper: https://arxiv.org/abs/2104.14557
- Code: https://github.com/MoustafaMeshry/lsr

**FACIAL: Synthesizing Dynamic Talking Face with Implicit Attribute Learning**
- Paper: https://arxiv.org/abs/2108.07938
- Code: https://github.com/zhangchenxu528/FACIAL

## Handwriting/Font Generation

**Handwriting Transformers**
- Paper: https://arxiv.org/abs/2104.03964
- Code: https://github.com/ankanbhunia/Handwriting-Transformers

**Multiple Heads are Better than One: Few-shot Font Generation with Multiple Localized Exper**
- Paper: https://arxiv.org/abs/2104.00887
- Code: https://github.com/clovaai/mxfont
