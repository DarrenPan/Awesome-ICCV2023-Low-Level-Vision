# Awesome-ICCV2021-Low-Level-Vision
A Collection of Papers and Codes in ICCV2021 related to Low-Level Vision

## Related collections for low-level vision
- [Awesome-CVPR2023/2022-Low-Level-Vision](https://github.com/DarrenPan/Awesome-CVPR2023-Low-Level-Vision)
- [Awesome-NeurIPS2022/2021-Low-Level-Vision](https://github.com/DarrenPan/Awesome-NeurIPS2022-Low-Level-Vision)
- [Awesome-ECCV2022-Low-Level-Vision](https://github.com/DarrenPan/Awesome-ECCV2022-Low-Level-Vision)
- [Awesome-AAAI2022-Low-Level-Vision](https://github.com/DarrenPan/Awesome-AAAI2022-Low-Level-Vision)
- [Awesome-ICCV2021-Low-Level-Vision](https://github.com/Kobaayyy/Awesome-ICCV2021-Low-Level-Vision)
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

- [Dehazing](#Dehazing)

- [Demosaicing](#Demosaicing)

- [HDR Imaging / Multi-Exposure Image Fusion](#HDR)

- [Frame Interpolation](#FrameInterpolation)

- [Image Enhancement](#Enhancement)
  - [Low-Light Image Enhancement](#LowLight)

- [Image Harmonization](#Harmonization)

- [Image Completion/Inpainting](#Inpainting)

- [Image Matting](#Matting)

- [Shadow Removal](#ShadowRemoval)

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

## Burst Restoration

**Deep Reparametrization of Multi-Frame Super-Resolution and Denoising **
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


<a name="Denoising"></a>
# Denoising - 去噪 [[back](#catalogue)]

<a name="ImageDenoising"></a>
## Image Denoising

**Rethinking Deep Image Prior for Denoising**
- Paper: https://arxiv.org/abs/2108.12841
- Code: https://github.com/gistvision/DIP-denosing

**Cross-Patch Graph Convolutional Network for Image Denoising **
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

**Self-Supervised Image Prior Learning With GMM From a Single Noisy Image**
- Paper：https://openaccess.thecvf.com/content/ICCV2021/html/Liu_Self-Supervised_Image_Prior_Learning_With_GMM_From_a_Single_Noisy_ICCV_2021_paper.html
- Code：https://github.com/HUST-Tan/SS-GMM

**Hyperspectral Image Denoising With Realistic Data**
- Paper: https://openaccess.thecvf.com/content/ICCV2021/html/Zhang_Hyperspectral_Image_Denoising_With_Realistic_Data_ICCV_2021_paper.html
- Code: https://github.com/ColinTaoZhang/HSIDwRD
- Tags: Hyperspectral Image

**End-to-End Unsupervised Document Image Blind Denoising **
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


<a name="VideoDeblurring"></a>
## Video Deblurring


<a name="Deraining"></a>
# Deraining - 去雨 [[back](#catalogue)]


<a name="Dehazing"></a>
# Dehazing - 去雾 [[back](#catalogue)]


<a name="Demosaicing"></a>
# Demosaicing - 去马赛克 [[back](#catalogue)]


 <a name="HDR"></a>
# HDR Imaging / Multi-Exposure Image Fusion - HDR图像生成 / 多曝光图像融合 [[back](#catalogue)]


<a name="FrameInterpolation"></a>
# Frame Interpolation - 插帧 [[back](#catalogue)]

<a name="Enhancement"></a>
# Image Enhancement - 图像增强 [[back](#catalogue)]

<a name="LowLight"></a>
## Low-Light Image Enhancement


<a name="Harmonization"></a>
# Image Harmonization/Composition - 图像协调/图像合成 [[back](#catalogue)]


<a name="Inpainting"></a>
# Image Completion/Inpainting - 图像修复 [[back](#catalogue)]


<a name="Matting"></a>
# Image Matting - 图像抠图 [[back](#catalogue)]



<a name="ShadowRemoval"></a>
# Shadow Removal - 阴影消除 [[back](#catalogue)]


<a name="Relighting"></a>
# Relighting


<a name="Stitching"></a>
# Image Stitching - 图像拼接 [[back](#catalogue)]



<a name="ImageCompression"></a>
# Image Compression - 图像压缩 [[back](#catalogue)]



<a name="ImageQualityAssessment"></a>
# Image Quality Assessment - 图像质量评价 [[back](#catalogue)]


<a name="StyleTransfer"></a>
# Style Transfer - 风格迁移 [[back](#catalogue)]


<a name="ImageEditing"></a>
# Image Editing - 图像编辑 [[back](#catalogue)]


<a name=ImageGeneration></a>
# Image Generation/Synthesis / Image-to-Image Translation - 图像生成/合成/转换 [[back](#catalogue)]
## Text-to-Image / Text Guided / Multi-Modal

## Image-to-Image / Image Guided

## Others for image generation


<a name="VideoGeneration"></a>
## Video Generation



<a name="Others"></a>
## Others [[back](#catalogue)]

## Talking Head Generation

## Virtual Try-on

## Handwriting/Font Generation


