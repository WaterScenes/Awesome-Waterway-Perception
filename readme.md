
# Awesome Waterborne Transportation Systems

<img src='images/cover.jpg' width=600 /> 

## Overview
- [Teams](#teams)
- [Workshops](#workshops)
- [Surveys](#surveys)
- [Datasets](#datasets)
- [Uni-Modal Perception](#uni-modal-perception)
  - [Detection](#detection)
    - [Small Object Detection](#small-object-detection)
    - [Open-Vocabulary Object Detection](#open-vocabulary-object-detection)
  - [Segmentation](#segmentation)
  - [Tracking](#tracking)
  - [Diffusion](#diffusion)
  - [Image Enhancement](#image-enhancement)
- [Multi-Modal Perception](#multi-modal-perception)
  - [Radar-Camera](#radar-camera)
  - [AIS-Camera](#ais-camera)


## Teams
* ### WaterScenes [[Website](https://waterscenes.github.io)] [[Github](https://github.com/WaterScenes)] 
  Yancheng Institute of Technology
  
* ### MAP Group [[Website](https://www.x-mol.com/groups/mipc)] 
  Wuhan University of Technology
  
* ### Avalon [[Website](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/kognitive-systeme/projects/avalon/)] 
  University of Tübingen

* ### Visual Cognitive Systems (ViCos) Laboratory [[Website](https://vicos.si/research/autonomous-boats)] [[Datasets](https://box.vicos.si/borja/viamaro/index.html)] 
  University of Ljubljana 

## Workshops

* ### MaCVi 2026
  * The 4th Workshop on Maritime Computer Vision (MaCVi) 2026 [[Website](https://macvi.org/workshop/cvpr)] [[Challenges](https://macvi.org/workshop/cvpr/challenges)] [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Kiefer_4th_Workshop_on_Maritime_Computer_Vision_MaCVi_Challenge_Overview_CVPRW_2026_paper.html)]
  * 2026 - **MaCVi Challenge Overview**: 4th Workshop on Maritime Computer Vision (MaCVi) Challenge Overview [*`MaCVi`* *`USV`*] __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Kiefer_4th_Workshop_on_Maritime_Computer_Vision_MaCVi_Challenge_Overview_CVPRW_2026_paper.html)] [[Website](https://macvi.org/workshop/cvpr)]

* ### MaCVi 2025
  * The 3rd Workshop on Maritime Computer Vision (MaCVi) 2025 [[Website](https://macvi.org/workshop/macvi25)]

* ### MaCVi 2024
  * The 2nd Workshop on Maritime Computer Vision (MaCVi) 2024 [[Website](https://macvi.org/workshop/macvi24)] [[Results](https://arxiv.org/abs/2311.14762)] [[Paper List](https://openaccess.thecvf.com/WACV2024_workshops/MaCVi)]
  * Baseline: **SeaDronesSee**: A Maritime Benchmark for Detecting Humans in Open Water [*`SeaDroneSee`*] [[Paper](https://arxiv.org/abs/2105.01922)]
  * 2023 - **Sea You Later**: Metadata-Guided Long-Term Re-Identification for UAV-Based Multi-Object Tracking [*`SeaDroneSee-MOT`* *`BoaTrack`*] __`WACV Workshop`__ [[Paper](https://arxiv.org/abs/2311.03561)] (🥇 in UAV-based Multi-Object Tracking, and 🥇 in USV-based Multi-Object Tracking)
  * 2023 - **ReIDTracker Sea**: the technical report of BoaTrack and SeaDronesSee-MOT challenge at MaCVi [*`SeaDroneSee-MOT`* *`BoaTrack`*] __`WACV Workshop`__ [[Paper](https://arxiv.org/abs/2311.07616)] (🥈 in UAV-based Multi-Object Tracking, 🥉 in USV-based Multi-Object Tracking)
  * 2023 - [**DLR-BoaTrack**]: Improving YOLOv8 with Scattering Transform and Attention for Maritime Awareness [*`SeaDroneSee-MOT`* *`BoaTrack`*] __`ISPA`__ [[Paper](https://ieeexplore.ieee.org/document/10279352)] (+BoT-SORT, 🥉 in UAV-based Multi-Object Tracking)
  * 2023 - **SeaDSC**: A video-based unsupervised method for dynamic scene change detection in unmanned surface vehicles [*`RoboWhaler`*] __`WACV Workshop`__ [[Paper](https://arxiv.org/abs/2311.11580)]

* ### MaCVi 2023
  * The 1nd Workshop on Maritime Computer Vision (MaCVi) 2023 [[Website](https://macvi.org/workshop/macvi23)] [[Results](https://ieeexplore.ieee.org/document/10031200/)] [[Paper List](https://openaccess.thecvf.com/WACV2023_workshops/MaCVi)]
  * Baseline: **SeaDronesSee**: A Maritime Benchmark for Detecting Humans in Open Water [*`SeaDroneSee`*] [[Paper](https://arxiv.org/abs/2105.01922)]
  * 2023 - A Novel Framework to Evaluate and Train Object Detection Models for Real-Time Victims Search and Rescue at Sea with Autonomous Unmanned Aerial Systems Using High-Fidelity Dynamic Marine Simulation Environment [*`SeaDroneSee`*] [[Paper](https://ieeexplore.ieee.org/document/10031171)]
  * 2023 - Improving the Detection of Small Oriented Objects in Aerial Images [[Paper](https://openaccess.thecvf.com/content/WACV2023W/MaCVi/papers/Zhao_YOLOv7-Sea_Object_Detection_of_Maritime_UAV_Images_Based_on_Improved_WACVW_2023_paper.pdf)]
  * 2023 - **YOLOv7-Sea**: Object Detection of Maritime UAV Images Based on Improved YOLOv7 [[Paper](https://openaccess.thecvf.com/content/WACV2023W/MaCVi/papers/Doloriel_Improving_the_Detection_of_Small_Oriented_Objects_in_Aerial_Images_WACVW_2023_paper.pdf)]
  

## Surveys
* 2017 - Video Processing From Electro-Optical Sensors for Object Detection and Tracking in a Maritime Environment: A Survey __`TITS`__ [[Paper](https://ieeexplore.ieee.org/document/7812788)]
* 2022 - Vessel Trajectory Prediction in Maritime Transportation: Current Approaches and Beyond __`TITS`__ [[Paper](https://ieeexplore.ieee.org/document/9843851/)]
* 2023 - Deep learning-based object detection in maritime unmanned aerial vehicle imagery: Review and experimental comparisons __`EAAI`__ [[Paper](https://www.sciencedirect.com/science/article/pii/S0952197623016974)]
* 2026 - **VLA Survey**: A Survey on Vision-Language-Action Models for Embodied AI __`TNNLS`__ [[Paper](https://pubmed.ncbi.nlm.nih.gov/42048203/)]

## Datasets

| **Name** | **Year** | **Publish** | **Task** | **Affiliation** | **Link** |
| --- | --- | --- | --- | --- | --- |
| **MarDCT** | 2015 | | Classification <br> Object Detection <br> Tracking | Sapienza University of Rome| [Website](http://www.diag.uniroma1.it//~labrococo/MAR/index.htm) <br> [Paper](http://www.diag.uniroma1.it//~bloisi/papers/bloisi-vrs2015-draft.pdf) |
| **MODD** | 2016 | | Object Detection <br> Semantic Segmentation | University of Ljubljana| [Website](http://vision.fe.uni-lj.si/RESEARCH/modd/) <br> [Paper](https://arxiv.org/abs/1503.01918) <br> [Github](https://vicos.si/resources/modd/) |
| **SMD** | 2017 | | Object Detection <br> Object Tracking | The Arctic University of Norway| [Website](https://sites.google.com/site/dilipprasad/home/singapore-maritime-dataset) <br> [Paper](https://openaccess.thecvf.com/content_CVPRW_2019/papers/PBVS/Moosbauer_A_Benchmark_for_Deep_Learning_Based_Object_Detection_in_Maritime_CVPRW_2019_paper.pdf) <br> [Github](https://github.com/yaoshanliang/Singapore-Maritime-Dataset) |
| **Visual-Inertial-Canoe**  | 2018 | | SLAM |  University of Illinois at Urbana-Champaign| [Website](https://databank.illinois.edu/datasets/IDB-9342111) <br> [Paper](https://journals.sagepub.com/doi/pdf/10.1177/0278364917751842)|
| **MODD2** | 2018 | | Object Detection <br> Semantic Segmentation  |University of Ljubljana| [Website](https://box.vicos.si/borja/viamaro/index.html) <br> [Paper](https://arxiv.org/abs/1802.07956) <br> [Github](https://arxiv.org/abs/1802.07956) |
| **SeaShips** | 2018 |  | Object Detection | Wuhan University | [Paper](https://doi.org/10.1109/TMM.2018.2865686) <br> [Github](https://github.com/jiaming-wang/SeaShips) |
| **MaSTr1325** | 2019 | | Semantic Segmentation | University of Ljubljana| [Website](https://vicos.si/resources/mastr1325/) <br> [Paper](https://ieeexplore.ieee.org/document/8967909) <br> [Github](https://github.com/bborja/modd) |
| **Tampere-WaterSeg** | 2019 | | Semantic Segmentation | Tampere University| [Paper](https://ieeexplore.ieee.org/document/8918694) |
| **MariShipSeg-HEU** | 2020 |  | Semantic Segmentation | Harbin Engineering University | [Paper](https://doi.org/10.1016/j.imavis.2019.11.002) <br> [Github](https://github.com/EddieEduardo/MariShipSeg-HEU) |
| **MCShips** | 2020 |  | Object Detection | Zheng Yitong and Zhang Shun | [Paper](https://doi.org/10.1109/ICME46284.2020.9102907) <br> [Github](https://github.com/ZhengYitong2333/Mcships) |
| **WaterV2** | 2020 |  | Semantic Segmentation | Louisiana State University | [Website](https://www.ece.lsu.edu/xinli/WaterNet/index.html) <br> [Paper](https://doi.org/10.1007/s41095-020-0156-x) <br> [Github](https://github.com/xmlyqing00/WaterNet) |
| **MID** | 2020 |  |Object Detection | Shanghai University| [Paper](https://doi.org/10.1002/rob.21983) <br> [Github](https://github.com/aluckyi/MID) |
| **ABOShips** | 2021 |  | Object Detection | Åbo Akademi University | [Dataset](https://zenodo.org/records/4736931) <br> [Paper](https://doi.org/10.3390/rs13050988) |
| **WSODD** | 2021 |  |Object Detection <br> Instance Segmentation | Beijing Institute of Technology | [Paper](https://www.frontiersin.org/articles/10.3389/fnbot.2021.723336/full) <br>[Github](https://github.com/sunjiaen/WSODD) |
| **USVInland** | 2021 | | SLAM <br> Stereo Matching <br> Water Segmentation | ORCA-tech | [Weibsite](https://www.orca-tech.cn/datasets/USVInland/Introduction) <br> [Paper](https://arxiv.org/abs/2103.05383) <br> [Github](https://github.com/ORCA-Uboat/USVInland-Dataset) |
| **FloW** | 2021 | | Object Detection <br> Multimodal Object Detection | ORCA-tech | [Website](https://www.orca-tech.cn/datasets/FloW/Introduction) <br> [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Cheng_FloW_A_Dataset_and_Benchmark_for_Floating_Waste_Detection_in_ICCV_2021_paper.html) <br> [Github](https://github.com/ORCA-Uboat/FloW-Dataset) |
| **SeaDronesSee** | 2021 | | Object Detection <br> Object Tracking | University of Tuebingen | [Website](https://seadronessee.cs.uni-tuebingen.de) <br> [GitHub](https://github.com/Ben93kie/SeaDronesSee) <br> [Paper](https://openaccess.thecvf.com/content/WACV2022/html/Varga_SeaDronesSee_A_Maritime_Benchmark_for_Detecting_Humans_in_Open_Water_WACV_2022_paper.html) |
| **MSGMP** | 2021 |  | Multimodal Perception | MIT Sea Grant AUV Lab | [Website](https://seagrant.mit.edu/auvlab-datasets-marine-perception-1/) <br> [Paper](https://doi.org/10.23919/OCEANS44145.2021.9705871) |
| **Dasha River** | 2022 |  | Semantic Segmentation | Shenzhen Polytechnic University | [Paper](https://doi.org/10.1109/TIM.2022.3165803) <br> [Github](https://github.com/zhourd-szpu/WaterSeg) |
| **MaSTr1478** | 2022 |  | Semantic Segmentation | University of Ljubljana | [Paper](https://doi.org/10.1109/IROS47612.2022.9982043) <br> [Github](https://github.com/lojzezust/WaSR-T) |
| **MU-SSiD** | 2022 |  | Sea State Classification | Manzoor Umair Team | [Dataset](https://www.kaggle.com/datasets/umairatwork/mu-ssid) <br> [Paper](https://doi.org/10.3390/sym14071487) |
| **ROSEBUD** | 2022 |  | Semantic Segmentation | Purdue University | [Dataset](https://purr.purdue.edu/publications/4072/1) <br> [Paper](https://doi.org/10.3390/s22134681) |
| **MassMIND** | 2023 |  | Semantic Segmentation <br> Instance Segmentation | University of Massachusetts Lowell | [Paper](https://doi.org/10.1177/02783649231153020) <br> [Github](https://github.com/uml-marine-robotics/MassMIND) |
| **LaRS** | 2023 |  |Semantic Segmentation <br> Panoptic Segmentation | University of Ljubljana | [Website](https://lojzezust.github.io/lars-dataset) <br> [GitHub](https://github.com/lojzezust/lars_evaluator) <br> [Paper](https://arxiv.org/abs/2308.09618) |
| **MariBoats** | 2023 |  | Instance Segmentation | Harbin Engineering University | [Paper](https://doi.org/10.1371/journal.pone.0279248) <br> [Github](https://github.com/Qunfunction/Visible-ship-dataset) |
| **Pohang Canal Dataset** | 2023 |  | SLAM | Korea Advanced Institute of Science and Technology | [Website](https://sites.google.com/view/pohang-canal-dataset) <br> [Paper](https://doi.org/10.1177/02783649231191145) <br> [Github](https://github.com/dhchung/pohang_canal_dataset) |
| **SPSCD** | 2023 |  | Object Detection <br> Classification | University of Split | [Website](https://labs.pfst.hr/maritime-dataset/) <br> [Paper](https://doi.org/10.3390/jmse11030578) |
| **WaterScenes** | 2023 | TITS |Object Detection <br> Instance Segmentation <br> Semantic Segmentation <br> Free-Space Segmentation <br> Waterline Segmentation <br> Panoptic Perception | University of Liverpool | [Website](https://waterscenes.github.io) <br> [GitHub](https://github.com/WaterScenes/WaterScenes) <br> [Paper](https://ieeexplore.ieee.org/document/10571852) |
| **MVDD13** | 2024 |  |Object Detection | Dalian Maritime University | [GitHub](https://github.com/yyuanwang1010/MVDD13) <br> [Paper](https://www.sciencedirect.com/science/article/pii/S0141118723003760) |
| **OASIs** | 2024 |  | Semantic Segmentation | Seadronix | [Website](https://www.navlue.com/dataset) <br> [Paper](https://arxiv.org/abs/2407.09005) |
| **GLSD** | 2025 |  | Object Detection | Wuhan University | [Paper](https://doi.org/10.1080/10095020.2024.2416896) <br> [Github](https://github.com/jiaming-wang/GLSD) |
| **IWHR_AI_Lable_Floater_V1** | 2025 |  | Object Detection | China Institute of Water Resources and Hydropower Research | [Dataset](https://doi.org/10.6084/m9.figshare.27376851.v1) <br> [Paper](https://doi.org/10.1038/s41597-025-04594-9) |
| **PoLaRIS** | 2025 |  | Object Detection <br> Object Tracking | Seoul National University | [Website](https://sites.google.com/view/polaris-dataset) <br> [Paper](https://doi.org/10.1109/ICRA55743.2025.11128583) <br> [Github](https://github.com/sparolab/PoLaRIS) |
| **SeePerSea** | 2025 |  | Object Detection | Dartmouth College | [Website](https://seepersea.github.io/) <br> [Paper](https://doi.org/10.1109/TFR.2025.3602937) <br> [Github](https://github.com/dartmouthrobotics/SeePerSea) |
| **MULTIAQUA** | 2025 |  | Semantic Segmentation | University of Ljubljana | [Website](https://lmi.fe.uni-lj.si/en/multiaqua/) <br> [Paper](https://arxiv.org/abs/2512.17450) |
| **MVTD** | 2025 |  | Object Tracking | Khalifa University | [Dataset](https://figshare.com/articles/dataset/MVTD/29177147) <br> [Paper](https://arxiv.org/abs/2506.02866) <br> [Github](https://github.com/AhsanBaidar/MVTD) |
| **USVTrack** | 2025 | IROS | Object Detection <br> Object Tracking | University of Liverpool | [Website](https://usvtrack.github.io/) <br> [Paper](https://ieeexplore.ieee.org/document/11246786) <br> [Github](https://github.com/USVTrack/USVTrack) |
| **MaCVi 2026 Challenges** | 2026 | CVPR Workshop | Vision-to-Chart Association <br> Thermal Object Detection <br> Panoptic Segmentation <br> Embedded Semantic Segmentation <br> Multimodal Semantic Segmentation | MaCVi Initiative | [Website](https://macvi.org/workshop/cvpr) <br> [Challenges](https://macvi.org/workshop/cvpr/challenges) <br> [Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Kiefer_4th_Workshop_on_Maritime_Computer_Vision_MaCVi_Challenge_Overview_CVPRW_2026_paper.html) |
| **Maritime-MmD+** | 2026 | arXiv | Multimodal Vessel Trajectory Prediction | Yuxu Lu et al. | [Paper](https://arxiv.org/abs/2605.26524) <br> [Github](https://github.com/LouisYxLu/CmIVTP) |
| **SeaClips** | 2026 | WACV | Object Detection | SEA.AI | [Dataset](https://huggingface.co/datasets/SEA-AI/SeaClips) <br> [Paper](https://doi.org/10.1109/WACV61042.2026.00447) |
| **WUTDet** | 2026 |  | Object Detection | Wuhan University of Technology | [Paper](https://arxiv.org/abs/2604.07759) <br> [Github](https://github.com/MAPGroup/WUTDet) |


## Uni-Modal Perception

### Detection

* 2019 - Object Detection in a Maritime Environment: Performance Evaluation of Background Subtraction Methods [*`SMD`*] __`TITS`__  [[Paper](https://ieeexplore.ieee.org/abstract/document/8401855)]
* 2020 - Are Object Detection Assessment Criteria Ready for Maritime Computer Vision? [*`SMD`*] __`TITS`__  [[Paper](https://ieeexplore.ieee.org/document/8911242)]
* 2023 - An Automated Method for the Creation of Oriented Bounding Boxes in Remote Sensing Ship Detection Datasets __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2024W/MaCVi/html/Savathrakis_An_Automated_Method_for_the_Creation_of_Oriented_Bounding_Boxes_WACVW_2024_paper.html)]
* 2024 - **MDD-ShipNet**: Math-Data Integrated Defogging for Fog-Occlusion Ship Detection __`TITS`__ [[Paper](https://ieeexplore.ieee.org/abstract/document/10527397/)]
* 2024 - **AodeMar**: Attention-Aware Occlusion Detection of Vessels for Maritime Autonomous Surface Ships __`TITS`__ [[Paper](https://ieeexplore.ieee.org/abstract/document/10537110)]
* 2024 - **RaViDeep**: Target Detection Based on Deep Fusion of Radar and Vision in Berthing Scenarios  __`TIV`__ [[Paper](https://ieeexplore.ieee.org/abstract/document/10607951)]
* 2024 - Panoptic Water Surface Visual Perception for USVs Using Monocular Camera Sensor [Detection, Segmentation]  __`IEEE Sensors`__ [[Paper](https://ieeexplore.ieee.org/document/10562207)]


#### Small Object Detection
* 2023 - A novel Multi to Single Module for small object detection  [*`SeaDroneSee`*] [[Paper](https://arxiv.org/abs/2303.14977)]
* 2024 - [**RCFNet**] Small Object Detection on the Water Surface Based on Radar and Camera Fusion [*`FloW`*] __`ICASSP`__ [[Paper](https://ieeexplore.ieee.org/abstract/document/10446880)]

#### Open-Vocabulary Object Detection
* 2026 - **HSGDet**: Prompt-Free Unknown Label Generation for Open World Detection in Remote Sensing [*`Remote Sensing`* *`Open World Detection`*] __`CVPR`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Azeem_Prompt-Free_Unknown_Label_Generation_for_Open_World_Detection_in_Remote_CVPR_2026_paper.html)]


### Segmentation
* 2018 - Stereo obstacle detection for unmanned surface vehicles by IMU-assisted semantic segmentation [*`MODD2`*] [[Paper](https://www.sciencedirect.com/science/article/pii/S0921889017305808)]
* 2021 - ShorelineNet: An Efficient Deep Learning Approach for Shoreline Semantic Segmentation for Unmanned Surface Vehicles [*`MODD2`*]  **IROS** [[Paper](https://ieeexplore.ieee.org/document/9636614)]
* 2026 - **MM-OVSeg**: Multimodal Optical-SAR Fusion for Open-Vocabulary Segmentation in Remote Sensing [*`Remote Sensing`* *`Optical-SAR`*] __`CVPR`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Wei_MM-OVSeg_Multimodal_Optical-SAR_Fusion_for_Open-Vocabulary_Segmentation_in_Remote_Sensing_CVPR_2026_paper.html)] [[GitHub](https://github.com/Jimmyxichen/MM-OVSeg)]
* 2026 - **ReAttnCLIP**: Training-Free Open-Vocabulary Remote Sensing Image Segmentation via Re-defined Attention in CLIP [*`Remote Sensing`* *`Open-Vocabulary Segmentation`*] __`CVPR`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Niu_ReAttnCLIP_Training-Free_Open-Vocabulary_Remote_Sensing_Image_Segmentation_via_Re-defined_Attention_CVPR_2026_paper.html)]
* 2026 - **ConInfer**: Context-Aware Inference for Training-Free Open-Vocabulary Remote Sensing Segmentation [*`Remote Sensing`* *`Open-Vocabulary Segmentation`*] __`arXiv`__ [[Paper](https://arxiv.org/abs/2603.29271)]

### Tracking
* 2021 - A Robust Deep Affinity Network for Multiple Ship Tracking  [*`SMD`*] __`TIM`__ [[Paper](https://ieeexplore.ieee.org/abstract/document/9423987)]
* 2023 - Asynchronous Trajectory Matching-Based Multimodal Maritime Data Fusion for Vessel Traffic Surveillance in Inland Waterways __`TITS`__ [[Paper](https://ieeexplore.ieee.org/abstract/document/10159572)]
* 2023 - Stable Yaw Estimation of Boats from the Viewpoint of UAVs and USVs __`ECMR`__ [[Paper](https://arxiv.org/abs/2306.14056)]
* 2023 - Memory Maps for Video Object Detection and Tracking on UAVs __`IROS`__ [[Paper](https://arxiv.org/abs/2303.03508)]
* 2023 - Improving maritime traffic surveillance in inland waterways using the robust fusion of AIS and visual data __`Ocean Engineering`__ [[Paper](https://www.sciencedirect.com/science/article/pii/S0029801823005826)]
* 2023 - **Sea You Later**: Metadata-Guided Long-Term Re-Identification for UAV-Based Multi-Object Tracking [*`SeaDroneSee-MOT`* *`BoaTrack`*] __`WACV Workshop`__ [[Paper](https://arxiv.org/abs/2311.03561)]
* 2023 - **ReIDTracker Sea**: the technical report of BoaTrack and SeaDronesSee-MOT challenge at MaCVi [*`SeaDroneSee-MOT`* *`BoaTrack`*] __`WACV Workshop`__ [[Paper](https://arxiv.org/abs/2311.07616)]
* 2023 - [**DLR-BoaTrack**]: Improving YOLOv8 with Scattering Transform and Attention for Maritime Awareness [*`SeaDroneSee-MOT`* *`BoaTrack`*] __`ISPA`__ [[Paper](https://ieeexplore.ieee.org/document/10279352)]
* 2024 - Active Vision-Based Finite-Time Trajectory-Tracking Control of an Unmanned Surface Vehicle Without Direct Position Measurements __`TITS`__ [[Paper](https://ieeexplore.ieee.org/abstract/document/10443713)]
* 2026 - **UAST**: Unified Active Search and Tracking for Arbitrary Targets with UAVs [*`UAV`* *`RGB-D`*] __`CVPR`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Qin_UAST_Unified_Active_Search_and_Tracking_for_Arbitrary_Targets_with_CVPR_2026_paper.html)] [[GitHub](https://github.com/qinliangql/UAST)]

### Mapping
* 2024 - Real-Time Volumetric Perception for Unmanned Surface Vehicles Through Fusion of Radar and Camera __`TIM`__ [[Paper](https://ieeexplore.ieee.org/document/10478941)]

### Diffusion
* 2023 - **SafeSea**: Synthetic Data Generation for Adverse & Low Probability Maritime Conditions [*`SeaDroneSee`*] __`WACV Workshop`__[[Paper](https://arxiv.org/abs/2311.14764)] [[Code](https://github.com/martin-3240/SafeSea)]

### Image Enhancement
* 2023 - **AiOENet**: All-in-One Low-Visibility Enhancement to Improve Visual Perception for Intelligent Marine Vehicles Under Severe Weather Conditions  __`TIV`__[[Paper](https://ieeexplore.ieee.org/abstract/document/10375786)] [[Code](https://github.com/LouisYuxuLu/AiOENet)]

## Multi-Modal Perception

### Radar-Camera

* 2023 - **Achelous**: A Fast Unified Water-surface Panoptic Perception Framework based on Fusion of Monocular Camera and 4D mmWave Radar [Detection, Segmentation] [*`WaterScenes`*] __`ITSC`__ [[Paper](https://arxiv.org/abs/2307.07102)] [[GitHub](https://github.com/GuanRunwei/Achelous)]
* 2024 - **RCBDet**: Space Grafted Velocity 3D Boat Detection for Unmanned Surface Vessel via mmWave Radar and Camera [Detection] __`IEEE Sensors`__ [[Paper](https://ieeexplore.ieee.org/document/10836144)]
* 2024 - **FVMNet**: Real-Time Volumetric Perception for Unmanned Surface Vehicles Through Fusion of Radar and Camera [Segmentation] __`TIM`__ [[Paper](https://ieeexplore.ieee.org/document/10478941/)] 

### AIS-Camera
* 2026 - **Unified Multimodal Vessel Trajectory Prediction**: Unified Multimodal Vessel Trajectory Prediction With Explainable Navigation Intention [*`AIS`* *`Vessel Trajectory Prediction`*] __`TITS`__ [[Paper](https://ieeexplore.ieee.org/document/11278469/)]
* 2026 - **CmIVTP**: Cross-modal Interaction-based Vessel Trajectory Prediction for Maritime Intelligence [*`Maritime-MmD+`* *`AIS`* *`CCTV`*] __`arXiv`__ [[Paper](https://arxiv.org/abs/2605.26524)] [[GitHub](https://github.com/LouisYxLu/CmIVTP)]
* 2026 - **Memory-Augmented VTP**: AIS-Based Vessel Trajectory Prediction Using Memory-Augmented Neural Networks [*`AIS`* *`Vessel Trajectory Prediction`*] __`arXiv`__ [[Paper](https://arxiv.org/abs/2606.06311)]

### Marine Radar-Camera

### LiDAR-Camera

### RGB-IR
* 2026 - **RAGTrack**: Language-aware RGBT Tracking with Retrieval-Augmented Generation [*`RGBT Tracking`*] __`CVPR`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Li_RAGTrack_Language-aware_RGBT_Tracking_with_Retrieval-Augmented_Generation_CVPR_2026_paper.html)] [[GitHub](https://github.com/IdolLab/RAGTrack)]

