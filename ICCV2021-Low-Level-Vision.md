# Awesome-ICCV2021-Low-Level-Vision
A Collection of Papers and Codes in ICCV2021 related to Low-Level Vision

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


## Burst Restoration

**Deep Reparametrization of Multi-Frame Super-Resolution and Denoising**
- Paper: https://arxiv.org/abs/2108.08286
- Code: https://github.com/goutamgmb/deep-rep

<a name="SuperResolution"></a>
# Super Resolution - 超分辨率 [[back](#catalogue)]
<a name="ImageSuperResolution"></a>
## Image Super Resolution


<a name="VideoSuperResolution"></a>
## Video Super Resolution


<a name="Rescaling"></a>
# Image Rescaling - 图像缩放 [[back](#catalogue)]

**Hierarchical Conditional Flow: A Unified Framework for Image Super-Resolution and Image Rescaling **
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


<a name="ImageEditing"></a>
# Image Editing - 图像编辑 [[back](#catalogue)]


<a name=ImageGeneration></a>
# Image Generation/Synthesis / Image-to-Image Translation - 图像生成/合成/转换 [[back](#catalogue)]
## Text-to-Image / Text Guided / Multi-Modal

## Image-to-Image / Image Guided

## Others for image generation

**Focal Frequency Loss for Image Reconstruction and Synthesis**
- Paper: https://arxiv.org/abs/2012.12821
- Code: https://github.com/EndlessSora/focal-frequency-loss


<a name="VideoGeneration"></a>
## Video Generation



<a name="Others"></a>
## Others [[back](#catalogue)]

**Neural Video Portrait Relighting in Real-time via Consistency Modeling**
- Paper: https://arxiv.org/abs/2104.00484
- Code: https://github.com/ZoneLikeWonderland/Neural-Video-Portrait-Relighting-in-Real-time-via-Consistency-Modeling
- Tags: Relighting

## Talking Head Generation

## Virtual Try-on

## Handwriting/Font Generation


