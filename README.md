<div align="center">

<img src="https://img.icons8.com/fluency/96/000000/artificial-intelligence.png" alt="AI Medical Imaging" width="100"/>

# 🏥 Awesome Generative AI in Medical Imaging

[![Paper](https://img.shields.io/badge/📄_Paper-SPJ_Research-b31d28?style=for-the-badge)](https://spj.science.org/doi/full/10.34133/research.1029)
[![Supplementary](https://img.shields.io/badge/📎_Supplementary-DOCX-6f42c1?style=for-the-badge)](https://spj.science.org/doi/suppl/10.34133/research.1029/suppl_file/research.1029.f1.docx)

[![Datasets](https://img.shields.io/badge/📊_Datasets-93-2ea44f?style=flat-square)](#-datasets)
[![Methods](https://img.shields.io/badge/🔬_Methods-175-0969da?style=flat-square)](#-methods)
[![License](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey?style=flat-square)](#-license)

---

</div>

## 🌟 Highlights

**A curated collection of datasets, methods, and resources for Generative AI in Medical Imaging**

*Compiled from "[Generative Artificial Intelligence in Medical Imaging: Foundations, Progress, and Clinical Translation](https://spj.science.org/doi/full/10.34133/research.1029)"*

**🎯 What Makes This Different:**

- ✨ **Complete Clinical Coverage**: First survey mapping generative AI across diagnosis, treatment, and prognosis
- 🎓 **Standardized Evaluation**: Three-tiered framework (image fidelity, feature consistency, clinical relevance)
- 🔗 **Ready-to-Use Resources**: All datasets and methods with direct links and implementation details
- 📊 **Comprehensive Scope**: 93 datasets, 175 methods, 10+ imaging modalities

---

## 📑 Table of Contents

<details open>
<summary><b>📚 Quick Navigation</b></summary>

- [🌟 Highlights](#-highlights)
- [🚀 Quick Start](#-quick-start)
- [📊 Datasets](#-datasets)
  - [🌐 Whole Body](#-whole-body)
  - [🧠 Head and Neck](#-head-and-neck)
  - [🫁 Chest](#-chest)
  - [❤️ Cardiac](#-cardiac)
  - [🫃 Abdomen](#-abdomen)
  - [🦴 Musculoskeletal](#-musculoskeletal-and-other)
  - [🔗 Multimodal](#-multimodal-datasets)
- [🔬 Methods](#-methods)
  - [🧹 Denoising &amp; Artifact Removal](#-denoising-and-artifact-removal)
  - [🔄 Image Reconstruction](#-image-reconstruction)
  - [🔍 Super-Resolution](#-super-resolution)
  - [🎨 Unconditional Synthesis](#-unconditional-synthesis)
  - [🎯 Conditional Synthesis](#-conditional-synthesis)
  - [💊 Treatment Planning](#-treatment-planning-and-dynamic-intervention)
  - [📈 Disease Progression](#-disease-progression-prediction)
  - [🏗️ Foundation Models](#-foundation-models)
- [🤝 Contributing](#-contributing)
- [🙏 Acknowledgments](#-acknowledgments)
- [📜 License](#-license)
- [📖 Citation](#-citation)

</details>

---

## 🚀 Quick Start

### 🎯 What You'll Find

| Resource                          | Description                                        | Count         |
| --------------------------------- | -------------------------------------------------- | ------------- |
| 📊**Public Datasets**       | Curated medical imaging datasets with direct links | 93            |
| 🔬**Research Methods**      | State-of-the-art generative AI methods             | 175           |
| 💻**Code Repositories**     | GitHub/project links for implementations           | 90+           |
| 📝**Loss Functions**        | Detailed training objectives for each method       | All           |
| 🏥**Clinical Applications** | Diagnosis, treatment, and prognosis workflows      | Full Coverage |

---

## 📊 Datasets

> **💡 Tip**: All 93 datasets include direct download links. Click on dataset names to access them immediately.

### 📍 Browse by Anatomy

| Anatomical Region           | Datasets | Modalities                                  | Jump                             |
| --------------------------- | -------- | ------------------------------------------- | -------------------------------- |
| 🌐**Whole Body**      | 14       | CT, PET-CT, MRI, Pathology                  | [View](#-whole-body)                |
| 🧠**Head & Neck**     | 21       | CT, PET-CT, MRI, US, OCT, Fundus, Pathology | [View](#-head-and-neck)             |
| 🫁**Chest**           | 16       | X-ray, CT, MRI, US, Pathology               | [View](#-chest)                     |
| ❤️**Cardiac**       | 12       | MRI, Ultrasound                             | [View](#-cardiac)                   |
| 🫃**Abdomen**         | 15       | CT, MRI, US, Pathology                      | [View](#-abdomen)                   |
| 🦴**Musculoskeletal** | 5        | MRI                                         | [View](#-musculoskeletal-and-other) |
| 🔗**Multimodal**      | 10       | Image-Text, Clinical Data                   | [View](#-multimodal-datasets)       |

---

### 🌐 Whole Body

<details open>
<summary><b>🌐 View 14 Whole Body Datasets</b></summary>

<br>

> Comprehensive datasets covering multiple organs and body regions

| Dataset                                                                            | Modality  | Scale                           | Source             |
| ---------------------------------------------------------------------------------- | --------- | ------------------------------- | ------------------ |
| [AutoPET](https://autopet.grand-challenge.org/Dataset/)                               | 3D PET-CT | 1014 volumes                    | Grand Challenge    |
| [AutoPETIII](https://autopet-iii.grand-challenge.org/autopet-iii/)                    | 3D PET-CT | 1614 volumes                    | Grand Challenge    |
| [CPIA](https://github.com/zhanglab2021/CPIA_Dataset)                                  | Pathology | 21.4M WSI                       | GitHub             |
| [CT-ORG](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=61080890) | 3D CT     | 140 volumes                     | TCIA               |
| [DeepLesion](https://nihcc.app.box.com/v/DeepLesion)                                  | 2D CT     | 32.7K images                    | nihcc.app.box.com  |
| [FLARE24 Task1](https://www.codabench.org/competitions/2319/)                         | 3D CT     | 10K volumes                     | Challenge Platform |
| [MedMNIST](https://doi.org/10.5281/zenodo.10519652)                                   | 2D & 3D   | 708K 2D images & 10K 3D volumes | Zenodo/DOI         |
| [NAFLD](https://osf.io/gqutd/)                                                        | Pathology | 119.8K WSI                      | osf.io             |
| [PreCT-160K](https://huggingface.co/datasets/Luffy503/PreCT-160K)                     | 3D CT     | 160K volumes                    | Hugging Face       |
| [TotalSegmentator](https://zenodo.org/records/6802614)                                | 3D CT     | 1204 volumes                    | Zenodo/DOI         |
| [TotalSegmentator MRI](https://zenodo.org/records/11367005)                           | 3D MRI    | 298 volumes                     | Zenodo/DOI         |
| [TotalSegmentator MRI v2](https://zenodo.org/records/14710732)                        | 3D MRI    | 616 volumes                     | Zenodo/DOI         |
| [TotalSegmentator v2](https://zenodo.org/records/10047292)                            | 3D CT     | 1228 volumes                    | Zenodo/DOI         |
| [ULS](https://uls23.grand-challenge.org/)                                             | 3D CT     | 38.8K volumes                   | Grand Challenge    |

</details>

### 🧠 Head and Neck

<details>
<summary><b>🧠 View 21 Head & Neck Datasets</b></summary>

<br>

> Datasets for brain, thyroid, retina, and head/neck imaging

| Dataset                                                                                   | Modality  | Scale         | Source                |
| ----------------------------------------------------------------------------------------- | --------- | ------------- | --------------------- |
| [AIROGS](https://airogs.grand-challenge.org/data-and-challenge/)                             | Fundus    | 101.4K images | Grand Challenge       |
| [AOMIC](https://nilab-uva.github.io/AOMIC.github.io/)                                        | 3D MRI    | 1370 volumes  | nilab-uva.github.io   |
| [BraTS2023-MEN](https://www.synapse.org/Synapse:syn51156910/wiki/627000)                     | 3D MRI    | 1650 volumes  | Synapse               |
| [BraTS21](https://www.synapse.org/Synapse:syn25829067/wiki/610863)                           | 3D MRI    | 2040 volumes  | Synapse               |
| [CrossMoDA2021](https://crossmoda.grand-challenge.org/)                                      | 3D MRI    | 349 volumes   | Grand Challenge       |
| [CrossMoDA2023](https://www.synapse.org/Synapse:syn51236108/files/)                          | 3D MRI    | 983 volumes   | Synapse               |
| [Diabetic Retinopathy Arranged](https://tianchi.aliyun.com/dataset/93926)                    | Fundus    | 35.1K images  | tianchi.aliyun.com    |
| [HECKTOR2022](https://hecktor.grand-challenge.org/Data/)                                     | 3D PET-CT | 882 volumes   | Grand Challenge       |
| [INSTANCE2022](https://instance.grand-challenge.org/)                                        | 3D CT     | 200 volumes   | Grand Challenge       |
| [IXI Dataset](https://brain-development.org/ixi-dataset/)                                    | 3D MRI    | 600 volumes   | brain-development.org |
| [LAG](https://github.com/smilell/AG-CNN?tab=readme-ov-file)                                  | Fundus    | 11.7K images  | GitHub                |
| [OCT2017](https://data.mendeley.com/datasets/rscbjbr9sj/2)                                   | OCT       | 35.1K images  | data.mendeley.com     |
| [ODIR-5K](https://odir2019.grand-challenge.org/dataset/)                                     | Fundus    | 5000 images   | Grand Challenge       |
| [OSCC](https://data.mendeley.com/datasets/ftmp4cvtmb/1)                                      | Pathology | 1224 WSI      | data.mendeley.com     |
| [PatchCamelyon](https://github.com/basveeling/pcam)                                          | Pathology | 327.7K WSI    | GitHub                |
| [Retinal OCT-C8](https://www.kaggle.com/datasets/obulisainaren/retinal-oct-c8)               | OCT       | 24K images    | Kaggle                |
| [SegRap2023](https://segrap2023.grand-challenge.org/dataset/)                                | 3D CT     | 200 volumes   | Grand Challenge       |
| [TN-SCUI2020](https://tn-scui2020.grand-challenge.org/Home/)                                 | 2D US     | 4554 images   | Grand Challenge       |
| [TN3K](https://github.com/haifangong/TRFE-Net-for-thyroid-nodule-segmentation)               | 2D US     | 3493 images   | GitHub                |
| [Ultrasound Nerve Segmentation](https://www.kaggle.com/c/ultrasound-nerve-segmentation/data) | 2D US     | 11.1K images  | Kaggle                |
| [fastMRI_Brain](https://fastmri.med.nyu.edu/)                                                | 2D MRI    | 6970 images   | Project Site          |

</details>

### 🫁 Chest

<details>
<summary><b>🫁 View 16 Chest Datasets</b></summary>

<br>

> Datasets for lung, breast, and thoracic imaging

| Dataset                                                                                                      | Modality  | Scale        | Source            |
| ------------------------------------------------------------------------------------------------------------ | --------- | ------------ | ----------------- |
| [ACRIN-Contralateral-Breast-MR](https://www.cancerimagingarchive.net/collection/acrin-contralateral-breast-mr/) | 3D MRI    | 984 volumes  | TCIA              |
| [ATM22](https://atm22.grand-challenge.org/)                                                                     | 3D CT     | 500 volumes  | Grand Challenge   |
| [BRAX](https://physionet.org/content/brax/1.1.0/)                                                               | 2D X-ray  | 40.9K images | PhysioNet         |
| [BUSI](https://scholar.cu.edu.eg/?q=afahmy/pages/dataset)                                                       | US        | 780 images   | scholar.cu.edu.eg |
| [Breakhis](https://opendatalab.com/OpenDataLab/BreakHis/explore/main)                                           | Pathology | 7909 WSI     | opendatalab.com   |
| [CheXchoNet](https://physionet.org/content/chexchonet/1.0.0/)                                                   | 2D X-ray  | 71.6K images | PhysioNet         |
| [ISPY1-Tumor-SEG-Radiomics](https://www.cancerimagingarchive.net/analysis-result/ispy1-tumor-seg-radiomics/)    | 3D MRI    | 483 volumes  | TCIA              |
| [LIDC-IDRI](https://www.cancerimagingarchive.net/collection/lidc-idri/)                                         | 2D CT     | 1010 images  | TCIA              |
| [LNQ2023](https://lnq2023.grand-challenge.org/lnq2023/)                                                         | 3D CT     | 513 volumes  | Grand Challenge   |
| [LUNA16](https://luna16.grand-challenge.org/Home/)                                                              | 3D CT     | 888 volumes  | Grand Challenge   |
| [MIST-HER2](https://drive.google.com/drive/folders/146V99Zv1LzoHFYlXvSDhKmflIL-joo6p?usp=sharing)               | Pathology | 22.7K WSI    | drive.google.com  |
| [SARS-COV-2 Ct-Scan](https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset)                     | 2D CT     | 2482 images  | Kaggle            |
| [SIIM-FISABIO-RSNA COVID-19](https://www.kaggle.com/competitions/siim-covid19-detection/data)                   | 2D X-ray  | 7597 images  | Kaggle            |
| [TDSC-ABUS2023](https://tdsc-abus2023.grand-challenge.org/TDSC-ABUS2023/)                                       | US        | 200 volumes  | Grand Challenge   |
| [WSSS4LUAD](https://wsss4luad.grand-challenge.org/WSSS4LUAD/)                                                   | Pathology | 10K WSI      | Grand Challenge   |
| [fastMRI_Breast](https://fastmri.med.nyu.edu/)                                                                  | 2D MRI    | 300 images   | Project Site      |

</details>

### ❤️ Cardiac

<details>
<summary><b>❤️ View 12 Cardiac Datasets</b></summary>

<br>

> Datasets for heart structure and function imaging

| Dataset                                                                                                             | Modality | Scale        | Source                                  |
| ------------------------------------------------------------------------------------------------------------------- | -------- | ------------ | --------------------------------------- |
| [ACDC](https://humanheart-project.creatis.insa-lyon.fr/database/)                                                      | 3D MRI   | 150 volumes  | humanheart-project.creatis.insa-lyon.fr |
| [CMRxRecon](https://www.synapse.org/Synapse:syn51471091/datasets/)                                                     | 2Dt MRI  | 300 volumes  | Synapse                                 |
| [Cardiac MRI Dataset](https://data.nvision.eecs.yorku.ca/datasets/MRI/mrimages.tar.gz)                                 | 2Dt MRI  | 7980 volumes | data.nvision.eecs.yorku.ca              |
| [Cardiac super-resolution label maps](https://data.mendeley.com/datasets/pw87p286yx/1)                                 | 2Dt MRI  | 1331 volumes | data.mendeley.com                       |
| [EchoNet-Dynamic](https://echonet.github.io/dynamic/index.html)                                                        | US       | 10K videos   | echonet.github.io                       |
| [EchoNet-LVH](https://echonet.github.io/lvh/)                                                                          | US       | 12K videos   | echonet.github.io                       |
| [GANcMRI](https://biobank.ndph.ox.ac.uk/showcase/field.cgi?id=31085)                                                   | US       | 45.5K videos | biobank.ndph.ox.ac.uk                   |
| [Harvard Cardiac MR Center Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/CI3WB6) | 2Dt MRI  | 108 volumes  | Harvard Dataverse                       |
| [M&amp;Ms Challenge](https://mega.nz/folder/FxAmhbRJ)                                                                  | 3D MRI   | 375 volumes  | mega.nz                                 |
| [M&amp;Ms-2 Challenge](https://mega.nz/file/Y1p0nSqa)                                                                  | 3D MRI   | 360 volumes  | mega.nz                                 |
| [MICCAI 2024 CARE LAScarQS++](https://zmic.org.cn/care_2024/track2/)                                                   | 3D MRI   | 194 volumes  | zmic.org.cn                             |
| [OCMR](https://www.ocmr.info/download/)                                                                                | 2Dt MRI  | 165 volumes  | ocmr.info                               |

</details>

### 🫃 Abdomen

<details>
<summary><b>🫃 View 15 Abdomen Datasets</b></summary>

<br>

> Datasets for liver, kidney, pancreas, and GI tract imaging

| Dataset                                                                                                       | Modality  | Scale         | Source                 |
| ------------------------------------------------------------------------------------------------------------- | --------- | ------------- | ---------------------- |
| [AbdomenAtlas 1.0 Mini](https://huggingface.co/datasets/AbdomenAtlas/AbdomenAtlas1.0MiniBeta)                    | 3D CT     | 5195 volumes  | Hugging Face           |
| [AbdomenCT-1K](https://github.com/JunMa11/AbdomenCT-1K)                                                          | 3D CT     | 1112 volumes  | GitHub                 |
| [EndoSLAM](https://github.com/CapsuleEndoscope/EndoSLAM)                                                         | US        | 1020 videos   | GitHub                 |
| [FLARE 2024 Task3](https://www.codabench.org/competitions/2296/)                                                 | 3D MRI    | 4817 volumes  | Challenge Platform     |
| [FLARE2022](https://flare22.grand-challenge.org/Dataset/)                                                        | 3D CT     | 2300 volumes  | Grand Challenge        |
| [FLARE2023](https://codalab.lisn.upsaclay.fr/competitions/12239)                                                 | 3D CT     | 4500 volumes  | Challenge Platform     |
| [GasHisSDB](https://gitee.com/neuhwm/GasHisSDB)                                                                  | Pathology | 245.2K images | gitee.com              |
| [ISBI 2025 FUGC](https://zenodo.org/records/14305302)                                                            | US        | 890 images    | Zenodo/DOI             |
| [LIMUC](https://zenodo.org/records/5827695)                                                                      | US        | 1043 videos   | Zenodo/DOI             |
| [NCT-CRC-HE](https://zenodo.org/records/1214456)                                                                 | Pathology | 100K WSI      | Zenodo/DOI             |
| [PI-CAI](https://zenodo.org/records/6624726)                                                                     | 3D MRI    | 1500 volumes  | Zenodo/DOI             |
| [RenalCell](https://zenodo.org/records/6528599)                                                                  | Pathology | 625.1K WSI    | Zenodo/DOI             |
| [SUN](http://amed8k.sundatabase.org/)                                                                            | US        | 1018 videos   | amed8k.sundatabase.org |
| [SegPANDA200](https://drive.google.com/drive/folders/1zg_C37B_1HR6miRFuTwPKmueaJzvO-GD)                          | Pathology | 100.9K images | drive.google.com       |
| [UW-Madison GI Tract Image](https://www.kaggle.com/competitions/uw-madison-gi-tract-image-segmentation/overview) | 2D MRI    | 38.5K images  | Kaggle                 |

</details>

### 🦴 Musculoskeletal and Other

<details>
<summary><b>🦴 View 5 Musculoskeletal Datasets</b></summary>

<br>

> Datasets for bone, joint, and spine imaging

| Dataset                                                                                             | Modality | Scale        | Source            |
| --------------------------------------------------------------------------------------------------- | -------- | ------------ | ----------------- |
| [MRNet (Knee)](https://stanfordmlgroup.github.io/competitions/mrnet/)                                  | 3D MRI   | 1370 volumes | Project Site      |
| [SKM-TEA (Knee)](https://stanfordaimi.azurewebsites.net/datasets/4aaeafb9-c6e6-4e3c-9188-3aaaf0e0a9e7) | 3D MRI   | 155 volumes  | Project Site      |
| [SPIDER (Spine)](https://zenodo.org/records/10159290)                                                  | 3D MRI   | 257 volumes  | Zenodo/DOI        |
| [Wrist Dataset](https://data.mendeley.com/datasets/9kx5xp7h6d/2)                                       | 3Dt MRI  | 55 volumes   | data.mendeley.com |
| [fastMRI_knee](https://fastmri.med.nyu.edu/)                                                           | 2D MRI   | 1398 images  | Project Site      |

</details>

### 🔗 Multimodal Datasets

<details>
<summary><b>🔗 View 10 Multimodal Datasets</b></summary>

<br>

> Datasets combining images with text, clinical data, or genomics

| Dataset                                                                                           | Modality                  | Scale                   | Source            |
| ------------------------------------------------------------------------------------------------- | ------------------------- | ----------------------- | ----------------- |
| [CheXpertPlus](https://stanfordaimi.azurewebsites.net/datasets/5158c524-d3ab-4e02-96e9-6ee9efc110a1) | X-ray-Text                | 223K images, 223K texts | Project Site      |
| [Duke Breast Cancer MRI](https://sites.duke.edu/mazurowski/resources/breast-cancer-mri-dataset/)     | Genomic&MRI-Clinical data | 922 cases               | sites.duke.edu    |
| [I-SPY2](https://www.cancerimagingarchive.net/collection/ispy2/)                                     | MRI-Clinical data         | 719 cases               | TCIA              |
| [MedICaT](https://github.com/allenai/medicat)                                                        | Multimodal Images-Text    | 217K images, 217K texts | GitHub            |
| [Medical-CXR-VQA](https://github.com/Holipori/Medical-CXR-VQA)                                       | X-ray-Text                | 377K images, 780K texts | GitHub            |
| [Medtrinity-25M](https://github.com/UCSC-VLAA/MedTrinity-25M)                                        | Multimodal Images-Text    | 25M images, 25M texts   | GitHub            |
| [OpenPath](https://huggingface.co/spaces/vinid/webplip)                                              | Pathology-Text            | 208K images, 208K texts | Hugging Face      |
| [PMC-OA](https://huggingface.co/datasets/axiong/pmc_oa)                                              | Multimodal Images-Text    | 1.6M images, 1.6M texts | Hugging Face      |
| [PadChest](http://bimcv.cipf.es/bimcv-projects/padchest/)                                            | X-ray-Text                | 160K images, 109K texts | bimcv.cipf.es     |
| [Quilt-1M](https://quilt1m.github.io/)                                                               | Pathology-Text            | 1M images, 1M texts     | quilt1m.github.io |

</details>

---

## 🔬 Methods

> **💡 Tip**: 90+ methods include direct links to code repositories and project pages.

### 🎯 Browse by Application

| Application Category                     | Methods | Models                                           | Jump                                               |
| ---------------------------------------- | ------- | ------------------------------------------------ | -------------------------------------------------- |
| 🧹**Denoising & Artifact Removal** | 16      | GAN, CNN, Diffusion, Mamba, Transformer          | [View](#-denoising-and-artifact-removal)              |
| 🔄**Image Reconstruction**         | 47      | GAN, CNN, Diffusion, VAE, Transformer, Mamba, AR | [View](#-image-reconstruction)                        |
| 🔍**Super-Resolution**             | 18      | GAN, CNN, Diffusion, Transformer, Mamba          | [View](#-super-resolution)                            |
| 🎨**Unconditional Synthesis**      | 11      | GAN, VAE, Diffusion, Mamba                       | [View](#-unconditional-synthesis)                     |
| 🎯**Conditional Synthesis**        | 38      | GAN, VAE, Diffusion, Transformer, Mamba          | [View](#-conditional-synthesis)                       |
| 💊**Treatment Planning**           | 23      | GAN, CNN, Diffusion, VAE, Transformer, Mamba     | [View](#-treatment-planning-and-dynamic-intervention) |
| 📈**Disease Progression**          | 12      | GAN, CNN, Diffusion, VAE, AR                     | [View](#-disease-progression-prediction)              |
| 🏗️**Foundation Models**          | 10      | Diffusion, CNN, Transformer, VAE                 | [View](#-foundation-models)                           |

---

### 🧹 Denoising and Artifact Removal

<details open>
<summary><b>🧹 View 16 Denoising & Artifact Removal Methods</b></summary>

<br>

> Methods for noise reduction and artifact suppression in medical images

| Method / Publication                                           | Model           | Application                              | Loss Functions                                                         |
| -------------------------------------------------------------- | --------------- | ---------------------------------------- | ---------------------------------------------------------------------- |
| PWGAN-WSHL (2021)                                              | GAN             | Low-dose CT denoising                    | WGAN loss, L1 loss, MSE loss, structural loss                          |
| [DenoMamba (2024)](https://github.com/icon-lab/DenoMamba)         | Mamba           | Low-dose CT denoising                    | L1 loss                                                                |
| m-WGAN (2019)                                                  | GAN             | CT image artifact removal                | WGAN loss, MSE loss                                                    |
| [TT U-Net (2023)](https://github.com/ivy9092111111/TT-U-Net)      | Transformer     | CT image artifact removal                | L1 loss, adversarial loss                                              |
| [CoreDiff (2024)](https://github.com/qgao21/CoreDiff)             | Diffusion model | Low-dose CT denoising                    | Diffusion denoising loss                                               |
| [PFGM++ (2024)](https://github.com/Newbeeer/pfgmpp)               | Diffusion model | Photon-counting CT denoising             | Diffusion denoising loss                                               |
| Yang et al. (2021)                                             | CNN             | PET image denoising and artifact Removal | MSE loss                                                               |
| Hu et al. (2020)                                               | GAN             | PET image denoising and artifact Removal | WGAN loss, MSE loss, gradient difference loss, content loss, ssim loss |
| [PT-WGAN (2020)](https://github.com/90n9-yu/PT-WGAN)              | GAN             | PET image denoising                      | Adversarial loss, MSE loss, ssim loss, perceptual loss                 |
| Gong et al. (2024)                                             | Diffusion model | PET image denoising                      | Diffusion denoising loss                                               |
| Yu et al. (2024)                                               | Diffusion model | PET image denoising                      | Diffusion denoising loss                                               |
| [RED-WGAN (2019)](https://github.com/Deep-Imaging-Group/RED-WGAN) | GAN             | MRI image denoising                      | WGAN loss, MSE loss, perceptual loss, VGG loss                         |
| Chung et al. (2022)                                            | Diffusion model | MRI image denoising                      | Diffusion denoising loss                                               |
| [CNCL (2022)](https://github.com/gengmufeng/CNCL-denoising)       | GAN             | MR, CT and PET image denoising           | Content loss, noise loss, GAN loss                                     |
| Lim et al. (2023)                                              | GAN             | MRI image artifact removal               | WGAN loss, L1 loss, VGG loss                                           |
| [PFAD (2024)](https://github.com/medcx/PFAD)                      | Diffusion model | MRI image artifact removal               | Diffusion denoising loss                                               |

</details>

### 🧩 Image Reconstruction

#### 🔄 CT Reconstruction

<details>
<summary><b>View 12 CT Reconstruction Methods</b></summary>

<br>

| Method / Publication                                                          | Model           | Application                     | Loss                                                           |
| ----------------------------------------------------------------------------- | --------------- | ------------------------------- | -------------------------------------------------------------- |
| DL-recon (2022)                                                               | GAN             | CBCT-to-CT reconstruction       | Adversarial loss, L1 loss                                      |
| Pradhan et al. (2023)                                                         | GAN             | 2D-to-3D CT reconstruction      | L1 loss, BCE loss, adversarial loss                            |
| [HyperNeRFGAN (2024)](https://github.com/gmum/HyperNeRFGAN)                      | GAN             | X-ray-to-CT reconstruction      | StyleGAN2Loss                                                  |
| [Krishnan et al. (2024)](https://github.com/MASILab/KernelConversionIntraVender) | GAN             | Low-dose CT reconstruction      | L1 loss, adversarial loss, reconstruction loss                 |
| MambaMIR (2025)                                                               | GAN, Mamba      | Low-dose CT/PET reconstruction  | Adversarial loss, Charbonnier loss，image loss, frequency loss |
| SI-GAN (2019)                                                                 | GAN             | Limited-angle CT reconstruction | Adversarialloss, sinogram loss, reconstruction loss            |
| [DOLCE (2023)](https://github.com/wustl-cig/DOLCE)                               | Diffusion model | Limited-angle CT reconstruction | Diffusion denoising loss                                       |
| Lopez-Montes et al. (2024)                                                    | Diffusion model | Limited-angle CT reconstruction | Diffusion denoising loss                                       |
| [TIFA (2024)](https://github.com/tianzhijiaoziA/TIFADiffusion)                   | Diffusion model | Limited-angle CT reconstruction | Diffusion denoising loss                                       |
| Xia et al. (2024)                                                             | Diffusion model | Sparse-view CT reconstruction   | Diffusion denoising loss                                       |
| CDDM (2024)                                                                   | Diffusion model | Sparse-view CT reconstruction   | Diffusion denoising loss                                       |
| [SWORD (2024)](https://github.com/yqx7150/SWORD)                                 | Diffusion model | Sparse-view CT reconstruction   | Diffusion denoising loss                                       |

</details>

#### 🔄 PET Reconstruction

<details>
<summary><b>View 12 PET Reconstruction Methods</b></summary>

<br>

| Method / Publication                                                                                          | Model           | Application                                      | Loss                                                                                |
| ------------------------------------------------------------------------------------------------------------- | --------------- | ------------------------------------------------ | ----------------------------------------------------------------------------------- |
| NADRU (2020)                                                                                                  | CNN             | Low dose PET reconstruction                      | Dice loss, BCE loss, general and adaptive robust loss, ssim loss                    |
| [Shi et al. (2023)](https://github.com/j-onofrey/deep-image-pet)                                                 | CNN             | Low dose PET reconstruction                      | L1 loss, image domain loss, gradient difference loss, LIP loss                      |
| CPR-CNN (2024)                                                                                                | CNN             | Low dose PET reconstruction                      | Reconstruction loss, cycle consistency loss                                         |
| DGLM (2024)                                                                                                   | CNN             | Low count PET reconstruction                     | MSE loss, ssim loss                                                                 |
| Lei et al. (2019)                                                                                             | GAN             | Low count PET reconstruction                     | Cycle-consistent adversarial loss, gradient descent loss, mean p-norm distance loss |
| Task-GAN (2019)                                                                                               | GAN             | Ultra-low dose PET reconstruction                | L1 loss, adversarial loss, regression loss                                          |
| AR-GAN (2022)                                                                                                 | GAN             | Low dose PET reconstruction                      | L1 loss, adversarial loss, cross-entropy loss                                       |
| DDPET-3D (2024)                                                                                               | Diffusion model | Low dose PET reconstruction                      | Diffusion denoising loss                                                            |
| Wikberg et al. (2024)                                                                                         | CNN             | Sparsely acquired projections PET reconstruction | L1 loss, MSE loss                                                                   |
| MMJSD (2024)                                                                                                  | VAE             | Bimodal PET/MRI reconstruction                   | Negative log-likelihood loss, KL loss                                               |
| [Singh et al. (2024)](https://github.com/Imraj-Singh/Score-Based-Generative-Models-for-PET-Image-Reconstruction) | Diffusion model | 2D/3D PET reconstruction                         | Poisson Log-Likelihood loss, Diffusion denoising loss                               |
| [MC-Diffusion (2024)](https://github.com/taofengxie/PET-MRI-reconstruction)                                      | Diffusion model | PET-MRI reconstruction                           | Diffusion denoising loss                                                            |

</details>

#### MRI reconstruction

<details>
<summary><strong>Show 16 entries</strong></summary>

| Method / Publication                                       | Model                | Application                       | Loss                                                                     |
| ---------------------------------------------------------- | -------------------- | --------------------------------- | ------------------------------------------------------------------------ |
| Wang et al. (2019)                                         | GAN                  | MRI reconstruction                | Content loss, perceptual loss, adversarial loss, dc loss                 |
| rsGAN (2020)                                               | GAN                  | Multi-contrast MRI reconstruction | L1 loss, perceptual loss, adversarial loss, dc loss                      |
| Kelkar et al. (2021)                                       | GAN                  | MRI reconstruction                | MSE loss, log-likelihood loss, TV loss, dc loss                          |
| [SwinMR (2022)](https://github.com/ayanglab/SwinMR)           | Transformer          | MRI reconstruction                | Pixel-wise Charbonnier loss, frequency Charbonnier loss                  |
| [KM-MAML (2023)](https://github.com/sriprabhar/KM-MAML/)      | CNN                  | MRI reconstruction                | L1 reconstruction loss, dc loss                                          |
| [MambaMIR (2024)](https://github.com/ayanglab/MambaMIR)       | Mamba                | MRI reconstruction                | Adversarial loss, image loss, kspace loss, perceptual loss, dc loss      |
| [DM-Mamba (2025)](https://github.com/XiaoMengLiLiLi/DM-Mamba) | Mamba                | MRI reconstruction                | L1 loss, dc loss                                                         |
| [MambaRoll (2024)](https://github.com/icon-lab/MambaRoll)     | Mamba, AR            | MRI reconstruction                | Kspace loss, cascade loss, dc loss                                       |
| [HFS-SDE (2024)](https://github.com/Aboriginer/HFS-SDE)       | Diffusion model      | MRI reconstruction                | Diffusion denoising loss, dc loss                                        |
| [JSMoCo (2025)](https://github.com/MeijiTian/JSMoCo)          | Diffusion model      | MRI reconstruction                | Diffusion denoising loss, dc loss                                        |
| [AID (2025)](https://github.com/mrirecon/aid)                 | Diffusion model, AR  | MRI reconstruction                | Diffusion denoising loss, dc loss                                        |
| Kofler et al. (2020)                                       | CNN                  | Cardiac cine MRI reconstruction   | L2 loss, dc loss                                                         |
| Qiu et al. (2024)                                          | Diffusion model      | Cardiac cine MRI reconstruction   | Diffusion denoising loss, dc loss                                        |
| [DiffCMR (2024)](https://github.com/xmed-lab/DiffCMR)         | Diffusion model      | Cardiac cine MRI reconstruction   | Diffusion denoising loss, dc loss                                        |
| [FedGIMP (2023)](https://github.com/icon-lab/FedGIMP)         | GAN                  | Federated MRI reconstruction      | Logistic adversarial loss, local reconstruction loss, dc loss            |
| [FedGAT (2025)](https://github.com/icon-lab/FedGAT)           | VAE, Transformer, AR | Federated MRI reconstruction      | Perceptual loss, adversarial loss, cross-entropy loss, MSE loss, dc loss |

</details>

#### 🔄 Other Modalities

<details>
<summary><strong>Show 7 entries</strong></summary>

| Method / Publication                                          | Model                | Application                             | Loss                                       |
| ------------------------------------------------------------- | -------------------- | --------------------------------------- | ------------------------------------------ |
| [DDRM (2023)](https://github.com/openai/guided-diffusion)        | Diffusion model      | US image reconstruction                 | Diffusion denoising loss                   |
| [DRUSvar (2024)](https://github.com/Yuxin-Zhang-Jasmine/DRUSvar) | Diffusion model      | US image reconstruction                 | Diffusion denoising loss                   |
| Lan et al. (2023)                                             | Diffusion model, GAN | US image reconstruction                 | Diffusion denoising loss                   |
| Merino et al. (2024)                                          | Diffusion model, GAN | US image reconstruction                 | Adversarial loss, Diffusion denoising loss |
| DM-RE2I (2023)                                                | Diffusion model      | EEG to image reconstruction             | Diffusion denoising loss                   |
| [PAT-Diffusion (2023)](https://github.com/yqx7150/PAT-Diffusion) | Diffusion model      | Photoacoustic tomography reconstruction | Diffusion denoising loss                   |
| Tong et al. (2023)                                            | Diffusion model      | Photoacoustic tomography reconstruction | Diffusion denoising loss                   |

</details>

### 🔎 Super-Resolution

#### Temporal super-resolution

<details>
<summary><strong>Show 9 entries</strong></summary>

| Method / Publication                                    | Model            | Application                       | Loss                                                             |
| ------------------------------------------------------- | ---------------- | --------------------------------- | ---------------------------------------------------------------- |
| Ren et al. (2021)                                       | CNN              | Video super‐resolution           | L1 loss                                                          |
| Song (2022)                                             | CNN, Transformer | Video super‐resolution           | MSE loss                                                         |
| VSRResFeatGAN (2019)                                    | GAN              | Video super‐resolution           | Adversarial loss, perceptual loss, charbonnier loss,             |
| MFIN (2019)                                             | CNN              | 4D MRI Temporal super‐resolution | Cycle consistency loss, recon loss, ssim loss,                   |
| [SVIN (2020)](https://github.com/guoyu-niubility/SVIN)     | CNN              | 4D MRI Temporal super‐resolution | Similarity loss, smoothness regularization loss, regression loss |
| [DDoS-Unet (2024)](https://github.com/soumickmj/DDoS)      | CNN              | 4D MRI Temporal super‐resolution | Perceptual loss, L1 loss                                         |
| [MPVF (2023)](https://github.com/Tzu-Ti/MPVF)              | CNN, Transformer | 4D MRI Temporal super‐resolution | Charbonnier loss                                                 |
| [UVI-Net (2024)](https://github.com/jungeun122333/UVI-Net) | CNN, Transformer | 4D MRI Temporal super‐resolution | NCC loss, gradient loss                                          |
| [DDM (2022)](https://github.com/torchDDM/DDM)              | Diffusion model  | 4D MRI Temporal super‐resolution | Diffusion denoising loss, NCC loss, KL loss                      |

</details>

#### Spatial super-resolution

<details>
<summary><strong>Show 9 entries</strong></summary>

| Method / Publication                                                       | Model             | Application                               | Loss                                                                                      |
| -------------------------------------------------------------------------- | ----------------- | ----------------------------------------- | ----------------------------------------------------------------------------------------- |
| [GAN-CIRCLE (2019)](https://github.com/charlesyou999648/GAN-CIRCLE)           | GAN               | CT super‐resolution                      | Adversarial loss, cycle-consistency loss, identity loss, joint sparsifying transform loss |
| TTSR-FD (2021)                                                             | GAN               | X-ray super‐resolution                   | Frequency domain loss, perpetual loss, adversarial loss,                                  |
| [SOUP-GAN (2022)](https://github.com/Mayo-Radiology-Informatics-Lab/SOUP-GAN) | GAN               | MRI super‐resolution                     | Adversarial loss, perceptual loss                                                         |
| DWT-SRGAN (2022)                                                           | GAN               | MRI super‐resolution                     | Perpetual loss, adversarial loss, wavelet loss                                            |
| HA-GAN (2022)                                                              | GAN               | CT/MRI super‐resolution                  | GAN loss, reconstruction loss                                                             |
| Huang et al. (2024)                                                        | Transformer, CNN, | US/OCT/Endoscope/CT/MRI super‐resolution | Charbonnier loss, L1 loss                                                                 |
| [UHRCT_SR (2023)](https://github.com/Arturia-Pendragon-Iris/UHRCT_SR)         | Diffusion model   | CT super‐resolution                      | Diffusion denoising loss                                                                  |
| PartDiff (2023)                                                            | Diffusion model   | MRI super‐resolution                     | Diffusion denoising loss                                                                  |
| Deform-Mamba (2024)                                                        | Mamba             | MRI super‐resolution                     | L1 loss, CE loss                                                                          |

</details>

### 🎲 Unconditional Synthesis

<details>
<summary><strong>Show 11 entries</strong></summary>

| Method / Publication                                                          | Model                  | Application                     | Loss                                                                                 |
| ----------------------------------------------------------------------------- | ---------------------- | ------------------------------- | ------------------------------------------------------------------------------------ |
| Danu et al. (2019)                                                            | VAE，GAN               | Blood vessel surfaces synthesis | MSE loss，adversarial loss                                                           |
| Syn-Net (2020)                                                                | GAN                    | 2D brain MRI synthesis          | L1 loss, perceptual loss, adversarial loss                                           |
| Chong and Ho (2021)                                                           | GAN                    | 3D brain MRI synthesis          | Adversarial loss，GAN loss                                                           |
| [3D-StyleGAN (2021)](https://github.com/sh4174/3DStyleGAN)                       | GAN                    | 3D MRI synthesis                | MSE loss, Logistic loss                                                              |
| Txurio et al. (2023)                                                          | Diffusion model        | 2D CT synthesis                 | Diffusion denoising loss                                                             |
| [MRGen (2024)](https://github.com/haoningwu3639/MRGen)                           | Diffusion model， VAE  | 2D MRI synthesis                | Diffusion denoising loss                                                             |
| VM-DDPM (2024)                                                                | Diffusion model, Mamba | 2D X-ray/MRI synthesis          | Diffusion denoising loss, GAN loss, BCE Loss                                         |
| GH-DDM (2023)                                                                 | Diffusion model        | 2D X-ray/CT/MRI/OCT synthesis   | Diffusion denoising loss                                                             |
| [Medicaldiffusion (2023)](https://github.com/FirasGit/medicaldiffusion)          | Diffusion model        | 3D CT/MRI synthesis             | Diffusion denoising loss                                                             |
| [DRDM (2024)](https://jianqingzheng.github.io/def_diff_rec/)                     | Diffusion model        | 3D CT/MRI synthesis             | Distance error loss, angle error loss, regularization loss                           |
| [3D MedDiffusion (2024)](https://github.com/ShanghaiTech-IMPACT/3D-MedDiffusion) | Diffusion model        | 3D CT/MRI synthesis             | Vector quantization loss, adversarial loss, tri-plane loss, Diffusion denoising loss |

</details>

### 🎯 Conditional Synthesis

#### 🎯 Text-to-Image Synthesis

<details>
<summary><strong>Show 15 entries</strong></summary>

| Method / Publication                                                               | Model                        | Application                                | Loss                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------- | ------------------------------------------ | ----------------------------------------------------------- |
| [Campello et al. (2022)](https://github.com/vicmancr/CardiacAging)                    | GAN                          | Clinical information-to-MRI                | Adversarial loss, cycle-consistency loss                    |
| [CHeart (2023)](https://github.com/MengyunQ/CHeart)                                   | VAE                          | Clinical information-to-MRI                | KL loss, log-likelihood loss                                |
| TUMSyn (2024)                                                                      | Transformer, CNN             | Clinical information-to-MRI                | Contrastive loss, similarity loss                           |
| Del Castillo et al. (2025)                                                         | Diffusion model, VAE         | Clinical information-to-MRI                | Diffusion denoising loss                                    |
| TaDiff (2025)                                                                      | Diffusion model              | Clinical information-to-MRI                | Diffusion denoising loss，dice loss                         |
| [MAISI (2024)](https://github.com/Project-MONAI/tutorials/tree/main/generation/maisi) | Diffusion model              | Clinical information-to-CT                 | Diffusion denoising loss                                    |
| [EchoDiffusion (2023)](https://github.com/HReynaud/EchoDiffusion)                     | Diffusion model              | Clinical information-to-video              | Diffusion denoising loss                                    |
| Kawata et al. (2024)                                                               | Diffusion model, VAE         | Clinical information-to-chest CT synthesis | Diffusion denoising loss, similarity loss                   |
| [GenerateCT (2024)](https://github.com/ibrahimethemhamamci/GenerateCT)                | Diffusion model，Transformer | Report-to-chest CT synthesis               | Diffusion denoising loss, perceptual loss, adversarial loss |
| [MedSyn (2024)](https://github.com/batmanlab/MedSyn)                                  | Diffusion model, VAE         | Report-to-chest CT synthesis               | Diffusion denoising loss, KL loss                           |
| [DCM-VLC (2024)](https://github.com/junzhin/DGM-VLC)                                  | Diffusion model， GAN        | Text-guided CT synthesis                   | Diffusion denoising loss，adversarial loss                  |
| MediSyn (2025)                                                                     | Diffusion model, VAE         | Text-guided diverse synthesis              | Diffusion denoising loss                                    |
| [TextoMorph (2024)](https://github.com/MrGiovanni/TextoMorph)                         | Diffusion model              | Text-guided tumor synthesis                | Diffusion denoising loss, contrastive loss                  |
| [Diff-CXR (2024)](https://github.com/cstreiffer/cxr_diffusion)                        | Diffusion model，Transformer | Report-to-CXR synthesis                    | Diffusion denoising loss，InfoNCE loss, BCE loss            |
| Chest-diffusion (2024)                                                             | Diffusion model, VAE         | Report-to-CXR synthesis                    | Diffusion denoising loss， contrast loss                    |

</details>

#### 🎯 Image-to-Image Synthesis

<details>
<summary><strong>Show 17 entries</strong></summary>

| Method / Publication                                           | Model                  | Application                    | Loss                                                                              |
| -------------------------------------------------------------- | ---------------------- | ------------------------------ | --------------------------------------------------------------------------------- |
| Ben-Cohen (2019)                                               | GAN                    | CT-to-PET translation          | Adversarial loss, MSE loss, L1 loss                                               |
| Jiao et al. (2020)                                             | GAN                    | US-to-MRI translation          | Latent space loss, appearance loss, structural consistency loss, adversarial loss |
| sc-cycleGAN (2020)                                             | GAN                    | MR-to-CT translation           | Adversarial loss, cycle-consistency loss, structure-consistency loss              |
| Gong et al. (2020)                                             | GAN                    | MRI-to-PET translation         | Adversarial loss, cycle-consistency loss                                          |
| [GLFC (2025)](https://github.com/HiLab-git/GLFC)                  | Mamba                  | CBCT-to-CT translation         | Multiple contrast Loss                                                            |
| EGDiff (2024)                                                  | Diffusion model        | CBCT-to-CT translation         | Diffusion denoising loss, MSE loss                                                |
| [DiffMa (2024)](https://github.com/wongzbb/DiffMaDiffusion-Mamba) | Diffusion model, Mamba | CT-to-MRI translation          | Diffusion denoising loss, infoNCE loss                                            |
| [MIDiffusion (2024)](https://github.com/mgh-ccni/midiffusion)     | Diffusion model        | MRI cross-modality translation | Mutual information diffusion denoising loss                                       |
| Yan et al. (2022)                                              | GAN                    | Multimodal MRI completion      | Adversarial loss, cycle-consistency loss                                          |
| Raad et al. (2024)                                             | GAN                    | Multimodal MRI completion      | Adversarial loss, MAE loss                                                        |
| [CKG-GAN (2024)](https://github.com/QianWeiZhou/CKG-GAN)          | GAN                    | Multimodal MRI completion      | Cross-dimensional knowledge loss + adversarial                                    |
| Zhang et al. (2024)                                            | GAN                    | Multimodal MRI completion      | Synthesis loss, reconstruction loss, adversarial loss,                            |
| AutoSyncoder (2020)                                            | GAN，VAE               | Multimodal MRI completion      | Adversarial loss, negative log-likelihood loss                                    |
| [I2I-Mamba (2024)](https://github.com/icon-lab/I2I-Mamba)         | Mamba                  | Multimodal MRI completion      | Adversarial loss, pixel-wise loss                                                 |
| [ResViT (2022)](https://github.com/icon-lab/ResViT)               | Transformer            | Multimodal MRI completion      | L1 loss, adversarial loss                                                         |
| MMT (2023)                                                     | Transformer            | Multimodal MRI completion      | Synthesis loss, reconstruction loss, adversarial loss,                            |
| [FgC2F-UDiff (2024)](https://github.com/xiaojiao929/FgC2F-UDiff)  | Diffusion model        | Multimodal MRI completion      | Diffusion denoising loss                                                          |

</details>

#### Anatomically-Guided Image Synthesis

<details>
<summary><strong>Show 6 entries</strong></summary>

| Method / Publication                                         | Model           | Application                                 | Loss                                                                                |
| ------------------------------------------------------------ | --------------- | ------------------------------------------- | ----------------------------------------------------------------------------------- |
| [CG-SAMR (2021)](https://github.com/guopengf/CG-SAMR)           | GAN             | Anatomy-guided CT synthesis                 | Adversarial loss, confidence map loss,feature matching loss, shape consistency loss |
| Shen et al. (2023)                                           | GAN             | Anatomy-guided CXR synthesis                | Reconstruction loss, Perceptual loss, Adversarial loss                              |
| Hou et al. (2023)                                            | GAN             | Anatomy-guided fundus image synthesis       | Wasserstein GAN loss, feature matching loss, KL-loss                                |
| Real-ESRGAN (2024)                                           | GAN             | Anatomy-guided fundus image synthesis       | Adversarial loss, perceptual loss, L1 loss, L1_seg loss                             |
| [LN-Gen (2024)](https://github.com/schmidtkk/LN-Gen)            | Diffusion model | Anatomy-guided rectal lymph nodes synthesis | Diffusion denoising loss, adapter loss                                              |
| [SegGuidedDiff (2024)](https://github.com/surjo0/SegGuidedDiff) | Diffusion model | Anatomy-guided MRI synthesis                | Diffusion denoising loss                                                            |

</details>

### 💊 Treatment Planning and Dynamic Intervention

#### Generation for Treatment Planning

<details>
<summary><strong>Show 9 entries</strong></summary>

| Method / Publication                                                 | Model                        | Application               | Loss                                                                                         |
| -------------------------------------------------------------------- | ---------------------------- | ------------------------- | -------------------------------------------------------------------------------------------- |
| [DoseNet (2018)](https://github.com/mkdermo/DoseNet)                    | CNN                          | Radiation dose prediction | L2 loss                                                                                      |
| [C3D (2021)](https://github.com/LSL000UD/RTDosePrediction)              | CNN                          | Radiation dose prediction | L1 loss                                                                                      |
| Radonic et al. (2024)                                                | CNN                          | Radiation dose prediction | MSE loss                                                                                     |
| TransDose (2023)                                                     | Transformer                  | Radiation dose prediction | Cross entropy loss，Charbonnier Loss                                                         |
| [VQGAN_TATrans (2024)](https://github.com/IMICSLab/Brain_VQGAN_TATrans) | GAN，VAE，Transformer        | Brain tumor prediction    | Pixel differences loss，perceptual loss，feature matching loss，gradient loss，codebook loss |
| PC-DDPM (2024)                                                       | Diffusion model              | Real-time tumor tracking  | Diffusion denoising loss，cycle-consistency loss                                             |
| [DiffDP (2023)](https://github.com/scufzh/DiffDP)                       | Diffusion model              | Radiation dose prediction | Diffusion denoising loss                                                                     |
| SP-DiffDose (2023)                                                   | Diffusion model，Transformer | Radiation dose prediction | Diffusion denoising loss                                                                     |
| [MD-Dose (2024)](https://github.com/LinjieFu-U/mamba_dose)              | Diffusion model，Mamba       | Radiation dose prediction | Diffusion denoising loss                                                                     |

</details>

#### Intraoperative navigation: Dynamic image synthesis

<details>
<summary><strong>Show 14 entries</strong></summary>

| Method / Publication                                            | Model                        | Application                      | Loss                                                              |
| --------------------------------------------------------------- | ---------------------------- | -------------------------------- | ----------------------------------------------------------------- |
| [SVIN (2020)](https://github.com/guoyu-niubility/SVIN)             | CNN                          | 4D dynamic MRI synthesis         | Similarity loss, smoothness regularization loss, regression loss  |
| DragNet (2023)                                                  | CNN                          | 2Dt cardiac MR synthesis         | ELBO loss, KL loss, similarity loss                               |
| Quintero et al. (2024)                                          | CNN                          | 4D dynamic MRI synthesis         | RMSE loss                                                         |
| [MPVF (2023)](https://github.com/Tzu-Ti/MPVF)                      | CNN, Transformer             | 4D dynamic MRI synthesis         | Charbonnier loss                                                  |
| [UVI-Net (2024)](https://github.com/jungeun122333/UVI-Net)         | CNN, Transformer             | 4D dynamic MRI synthesis         | NCC loss, gradient loss                                           |
| TAV-GAN (2021)                                                  | GAN                          | 4D dynamic MRI synthesis         | Temporally aware loss, SSIM loss, L1 loss                         |
| Thummerer et al. (2022)                                         | GAN                          | 4D CT synthesis                  | MSE loss                                                          |
| REGAIN (2023)                                                   | GAN                          | 2Dt cardiac MRI enhancement      | L1 fast-Fourier transform loss                                    |
| [Seq2Seq (2024)](https://github.com/fiy2W/mri_seq2seq)             | GAN                          | 3D/4D MRI synthesis              | L1 loss, perceptual loss, adversarial loss, cycle-consistent loss |
| DPI-MoCo (2024)                                                 | GAN                          | 4D CBCT reconstruction           | MSE loss, GAN loss, NCC loss, smooth loss                         |
| [DDM (2022)](https://github.com/torchDDM/DDM)                      | Diffusion model              | 4D dynamic MRI synthesis         | Diffusion denoising loss, NCC loss, KL loss                       |
| [Reynaud et al. (2023)](https://github.com/HReynaud/EchoDiffusion) | Diffusion model, Transformer | Echocardiography video synthesis | Diffusion denoising loss                                          |
| HeartBeat (2024)                                                | Diffusion model, VAE         | Echocardiography video synthesis | Diffusion denoising loss                                          |
| [Endora (2024)](https://endora-medvidgen.github.io/)               | Diffusion model, Transformer | Endoscopy video synthesis        | Diffusion denoising loss                                          |

</details>

### 📈 Disease Progression Prediction

<details>
<summary><strong>Show 12 entries</strong></summary>

| Method / Publication                                                                                                              | Model                | Application                                              | Loss                                                                  |
| --------------------------------------------------------------------------------------------------------------------------------- | -------------------- | -------------------------------------------------------- | --------------------------------------------------------------------- |
| Moya-Sáez et al. (2022)                                                                                                          | CNN                  | Glioblastoma survival prediction                         | L1 loss                                                               |
| [EfficientNet B0 (2024)](https://github.com/NIC-VICOROB/HE-prediction-SynthCT)                                                       | CNN                  | Hematoma expansion prediction                            | Focal loss                                                            |
| DaniNet (2019)                                                                                                                    | GAN                  | Mimic disease progression                                | Biological constraints loss, Deformation loss                         |
| GP-GAN (2020)                                                                                                                     | GAN                  | Brain tumor growth prediction                            | Adversarial loss, L1 loss, Dice loss                                  |
| Song et al. (2023)                                                                                                                | GAN                  | Longitudinal MRI prediction                              | Adversarial loss, Binary cross-entropy loss, Gradient difference loss |
| DCGAN and SRGAN (2024)                                                                                                            | GAN                  | Alzheimer's disease progression                          | Adversarial loss, MSE loss, VGG Loss                                  |
| [TADM (2024)](https://github.com/MattiaLitrico/TADM-Temporally-Aware-Diffusion-Model-for-Neurodegenerative-Progression-on-Brain-MRI) | Diffusion model      | Brain neurodegenerative prediction                       | Diffusion denoising loss                                              |
| [BrLP (2024)](https://github.com/LemuelPuglisi/BrLP)                                                                                 | Diffusion model      | Disease progression prediction                           | Diffusion denoising loss                                              |
| [DiffTumor (2024)](https://github.com/MrGiovanni/DiffTumor)                                                                          | Diffusion model，VAE | Generalizable tumor synthesis                            | Diffusion denoising loss                                              |
| [PASTA (2025)](https://github.com/LWHYC/PASTA)                                                                                       | Diffusion model，VAE | Tumor synthesis Foundation model                         | Diffusion denoising loss                                              |
| [SADM (2023)](https://github.com/ubc-tea/SADMLongitudinal-Medical-Image-Generation)                                                  | Diffusion model, AR  | Longitudinal MRI Generation                              | Diffusion denoising loss                                              |
| [TaDiff (2025)](https://github.com/samleoqh/TaDiff-Net)                                                                              | Diffusion model      | Longitudinal MRI Generation and Glioma Growth Prediction | Diffusion denoising loss                                              |

</details>

### 🏗️ Foundation Models

<details>
<summary><strong>Show 10 entries</strong></summary>

| Method / Publication                                                | Model            | Application                          | Loss                                 |
| ------------------------------------------------------------------- | ---------------- | ------------------------------------ | ------------------------------------ |
| MedDiff-FM (2024)                                                   | Diffusion model  | CT Foundation model                  | Denoising diffusion loss             |
| [RETFound-DE (2025)](https://github.com/Jonlysun/DERETFound)           | Diffusion model  | Retinal Foundation model             | Denoising diffusion loss             |
| [RoentGen (2024)](https://github.com/StanfordMIMI/RoentGen)            | Diffusion model  | Chest X-ray Foundation model         | Denoising diffusion loss             |
| [MINIM (2024)](https://github.com/WithStomach/MINIM)                   | Diffusion model  | OCT/CT/X-ray/MRI Foundation model    | Denoising diffusion loss             |
| [BME-X (2024)](https://github.com/DBC-Lab/Brain_MRI_Enhancement.git)   | CNN              | MRI Foundation model                 | Cross-entropy loss，MSE loss         |
| [Triad (2025)](https://github.com/wangshansong1/Triad)                 | Transformer, VAE | MRI Foundation Model                 | L1 loss, Log-ratio loss              |
| [BEPH (2025)](https://github.com/Zhcyoung/BEPH)                        | Transformer      | Pathology Foundation model           | MSE loss                             |
| [Prov-GigaPath (2024)](https://github.com/prov-gigapath/prov-gigapath) | Transformer      | Pathology Foundation model           | Contrastive loss，MSE loss           |
| [MONET (2024)](https://github.com/suinleelab/MONET)                    | Transformer      | Image-text Foundation model          | Contrastive loss，Cross-entropy loss |
| [MaCo (2024)](https://github.com/SZUHvern/MaCo)                        | Transformer      | Radiography-reports Foundation model | InfoNCE loss，MAE loss               |

</details>

---

## 🤝 Contributing

Pull requests are welcome for:

- Fixing broken links
- Adding official code or project pages
- Correcting dataset metadata or scale descriptions
- Extending the list with new generative medical imaging resources

---

## 🙏 Acknowledgments

This repository is built from the supplementary materials of our comprehensive survey. We extend our gratitude to:

- 🎓 **Researchers** who made their datasets and code publicly available
- 💻 **Open-source community** for advancing medical AI
- 🏥 **Medical institutions** for supporting data sharing
- 📚 **Reviewers and editors** for their valuable feedback

**Source and Scope:**

- Primary source: supplementary tables from the review paper
- Dataset entries mainly from **Table S9**
- Method entries mainly from **Tables S2-S8** and **Table S10**
- Links mapped to embedded hyperlink targets in the supplementary file
- This repository is a curated index, not a claim that every linked resource is official code from the original paper authors

---

## 📜 License

- **Content**: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) - Free to share and adapt with attribution
- **Code**: MIT License - Free to use, modify, and distribute

---

## 📖 Citation

If you find this repository helpful for your research, please consider citing our survey:

```bibtex
@article{generative_ai_medical_imaging_2025,
  title   = {Generative Artificial Intelligence in Medical Imaging: Foundations, Progress, and Clinical Translation},
  journal = {Research},
  year    = {2025},
  doi     = {10.34133/research.1029},
  url     = {https://spj.science.org/doi/full/10.34133/research.1029}
}
```

<div align="center">

**⭐ If this resource helps your work, please give us a star! ⭐**

</div>


<div align="center">
[![Star History Chart](https://api.star-history.com/chart?repos=Joker-ZXR/Awesome-Generative-AI-in-Medical-Imaging&type=date&legend=top-left)](https://www.star-history.com/?repos=Joker-ZXR%2FAwesome-Generative-AI-in-Medical-Imaging&type=date&legend=top-left)
</div>
