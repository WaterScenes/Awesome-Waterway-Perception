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


  * The 4th Workshop on Maritime Computer Vision (MaCVi) 2026 [[Website](https://macvi.org/workshop/cvpr)] [[Results](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Kiefer_4th_Workshop_on_Maritime_Computer_Vision_MaCVi_Challenge_Overview_CVPRW_2026_paper.html)] [[Paper List](https://openaccess.thecvf.com/CVPR2026_workshops/MaCVi)]
  * Baseline: **LaRS**: A Diverse Panoptic Maritime Obstacle Detection Dataset and Benchmark [Dataset: *`LaRS`*] [[Paper](https://doi.org/10.1109/ICCV51070.2023.01857)]

  #### Segmentation

  * 2026 - Improving Thing Segmentation for USV Panoptic Scene Understanding with Detector-Guided Class-Specific Refinement [Dataset: *`LaRS`*] __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Chun_Improving_Thing_Segmentation_for_USV_Panoptic_Scene_Understanding_with_Detector-Guided_CVPRW_2026_paper.html)]
  * 2026 - **LEMMA**: Laplacian pyramids for Efficient Marine SeMAntic Segmentation __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Gakhar_LEMMA_Laplacian_pyramids_for_Efficient_Marine_SeMAntic_Segmentation_CVPRW_2026_paper.html)]

  #### Detection

  * 2026 - **Thermal-Adapted RF-DETR**: Skyline-guided filtering and cross-scale fusion for maritime thermal object detection __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Jo_Thermal-Adapted_RF-DETR_with_Skyline-Guided_Filtering_and_Cross-Scale_Fusion_for_Maritime_CVPRW_2026_paper.html)] (🥉 in Thermal Object Detection)
  * 2026 - Optimization-Diverse Transformer Adaptation with Gated Heterogeneous Fusion for Robust Thermal Object Detection __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Tsai_Optimization-Diverse_Transformer_Adaptation_with_Gated_Heterogeneous_Fusion_for_Robust_Thermal_CVPRW_2026_paper.html)]
  * 2026 - Towards Robust Object Detection in Underwater Sonar Imagery __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Auer_Towards_Robust_Object_Detection_in_Underwater_Sonar_Imagery_A_Cross-Modality_CVPRW_2026_paper.html)]

  #### Multimodal Fusion / Association

  * 2026 - Real-Time Fusion of Visual and Chart Data for Enhanced Maritime Vision [Task: *`Vision-to-Chart Data Association`*] __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Kreis_Real-Time_Fusion_of_Visual_and_Chart_Data_for_Enhanced_Maritime_CVPRW_2026_paper.html)]
  * 2026 - Skyline-Aware ROI-Calibrated Buoy Association for Vision-to-Chart Data Association [Task: *`Vision-to-Chart Data Association`*] __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Jo_Skyline-Aware_ROI-Calibrated_Buoy_Association_for_Vision-to-Chart_Data_Association_CVPRW_2026_paper.html)] (🥇 in Vision-to-Chart Data Association)
  * 2026 - Real-Time Radar--Vision Association via Monocular Distance Estimation [Task: *`Radar-Vision Association`* *`Distance Estimation`*] __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Kiefer_Real-Time_Radar--Vision_Association_via_Monocular_Distance_Estimation_CVPRW_2026_paper.html)]

  #### Distance Estimation

  * 2026 - Monocular Metric Distance Estimation in Maritime Scenes via Reference-Based Scale Recovery __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Pizzicoli_Monocular_Metric_Distance_Estimation_in_Maritime_Scenes_via_Reference-Based_Scale_CVPRW_2026_paper.html)]

  #### Classification / Recognition

  * 2026 - **Mine-JEPA**: In-domain self-supervised learning for mine-like object classification in side-scan sonar __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Kwon_Mine-JEPA_In-Domain_Self-Supervised_Learning_for_Mine-Like_Object_Classification_in_Side-Scan_CVPRW_2026_paper.html)]
  * 2026 - **IALA-10**: A benchmark for fine-grained maritime buoy classification aligned with the maritime buoyage system [Dataset: *`IALA-10`*] __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Augustin_IALA-10_A_Benchmark_for_Fine-Grained_Maritime_Buoy_Classification_Aligned_with_CVPRW_2026_paper.html)]

  #### Image Enhancement / Restoration

  * 2026 - A unified Benchmark for Multi-Frame Image Restoration under Severe Refractive Warping __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Shugaev_A_unified_Benchmark_for_Multi-Frame_Image_Restoration_under_Severe_Refractive_CVPRW_2026_paper.html)]

  #### Embedded Deployment

  * 2026 - Deployment Characterization of Onboard Computing Platforms for Underwater Visual Inference __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/Lee_Deployment_Characterization_of_Onboard_Computing_Platforms_for_Underwater_Visual_Inference_CVPRW_2026_paper.html)]

  #### Synthetic Data / Simulation

  * 2026 - **PS3Simulator**: Physics-parametrised synthetic sonar for self-supervised sim-to-real transfer __`CVPR Workshop`__ [[Paper](https://openaccess.thecvf.com/content/CVPR2026W/MaCVi/html/S_PS3Simulator_Physics-Parametrised_Synthetic_Sonar_for_Self-Supervised_Sim-to-Real_Transfer_CVPRW_2026_paper.html)]
* ### MaCVi 2025


  * The 3rd Workshop on Maritime Computer Vision (MaCVi) 2025 [[Website](https://macvi.org/workshop/macvi25)] [[Results](https://openaccess.thecvf.com/content/WACV2025W/MaCVi/html/Kiefer_3rd_Workshop_on_Maritime_Computer_Vision_MaCVi_2025_Challenge_Results_WACVW_2025_paper.html)] [[Paper List](https://openaccess.thecvf.com/WACV2025_workshops/MaCVi)]
  * Baseline: **LaRS**: A Diverse Panoptic Maritime Obstacle Detection Dataset and Benchmark [Dataset: *`LaRS`*] [[Paper](https://doi.org/10.1109/ICCV51070.2023.01857)]

  #### Detection

  * 2025 - **FalconEye**: Efficient Centroid-Based Object Detection for Maritime High Altitude UAV Images on Embedded Devices __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2025W/MaCVi/html/Sawahn_FalconEye_Efficient_Centroid-Based_Object_Detection_for_Maritime_High_Altitude_UAV_WACVW_2025_paper.html)]
  * 2025 - **Marine Event Vision**: Harnessing Event Cameras For Robust Object Detection In Marine Scenarios __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2025W/MaCVi/html/Dadson_Marine_Event_Vision_Harnessing_Event_Cameras_For_Robust_Object_Detection_WACVW_2025_paper.html)]
  * 2025 - Underwater Image Enhancement and Object Detection: Are Poor Object Detection Results On Enhanced Images Due to Missing Human Labels? __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2025W/MaCVi/html/Lucas_Underwater_Image_Enhancement_and_Object_Detection_Are_Poor_Object_Detection_WACVW_2025_paper.html)]
  * 2025 - Camera-based Intruder Detection and Monitoring of Ship Crew Work Hours __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2025W/MaCVi/html/Murad_Camera-based_Intruder_Detection_and_Monitoring_of_Ship_Crew_Work_Hours_WACVW_2025_paper.html)]

  #### Classification / Recognition

  * 2025 - A Framework for Imbalanced SAR Ship Classification __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2025W/MaCVi/html/Awais_A_Framework_for_Imbalanced_SAR_Ship_Classification_Curriculum_Learning_Weighted_WACVW_2025_paper.html)]
  * 2025 - Vessel registration number detection and recognition system __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2025W/MaCVi/html/Fabijanic_Vessel_registration_number_detection_and_recognition_system_WACVW_2025_paper.html)]
  * 2025 - Navigating Coreset Selection and Model Compression for Efficient Maritime Image Classification __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2025W/MaCVi/html/Shinde_Navigating_Coreset_Selection_and_Model_Compression_for_Efficient_Maritime_Image_WACVW_2025_paper.html)]
  * 2025 - In-domain self-supervised learning for plankton image classification on a budget __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2025W/MaCVi/html/Ciranni_In-domain_self-supervised_learning_for_plankton_image_classification_on_a_budget_WACVW_2025_paper.html)]

  #### Multimodal Prediction

  * 2025 - Automatic Fish Age Prediction using Deep Machine Learning: Combining Otolith Image, NIR Spectra, and Metadata Features [Task: *`Fish Age Prediction`* *`Multimodal Prediction`*] __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2025W/MaCVi/html/Zheng_Automatic_Fish_Age_Prediction_using_Deep_Machine_Learning_Combining_Otolith_WACVW_2025_paper.html)]

  #### Dataset / Benchmark

  * 2025 - **AutoFish**: Dataset and Benchmark for Fine-grained Analysis of Fish [Dataset: *`AutoFish`*] __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2025W/MaCVi/html/Bengtson_AutoFish_Dataset_and_Benchmark_for_Fine-grained_Analysis_of_Fish_WACVW_2025_paper.html)]
  * 2025 - **MTReD**: 3D Reconstruction Dataset for Fly-over Videos of Maritime Domain [Dataset: *`MTReD`*] __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2025W/MaCVi/html/Yong_MTReD_3D_Reconstruction_Dataset_for_Fly-over_Videos_of_Maritime_Domain_WACVW_2025_paper.html)]
* ### MaCVi 2024


  * The 2nd Workshop on Maritime Computer Vision (MaCVi) 2024 [[Website](https://macvi.org/workshop/macvi24)] [[Results](https://openaccess.thecvf.com/content/WACV2024W/MaCVi/html/Kiefer_2nd_Workshop_on_Maritime_Computer_Vision_MaCVi_2024_Challenge_Results_WACVW_2024_paper.html)] [[Paper List](https://openaccess.thecvf.com/WACV2024_workshops/MaCVi)]
  * Baseline: **SeaDronesSee**: A Maritime Benchmark for Detecting Humans in Open Water [Dataset: *`SeaDroneSee`*] [[Paper](https://arxiv.org/abs/2105.01922)]

  #### Tracking / ReID

  * 2023 - **Sea You Later**: Metadata-Guided Long-Term Re-Identification for UAV-Based Multi-Object Tracking [Dataset: *`SeaDroneSee-MOT`* *`BoaTrack`*] __`WACV Workshop`__ [[Paper](https://arxiv.org/abs/2311.03561)] (🥇 in UAV-based Multi-Object Tracking with Re-identification)
  * 2023 - **ReIDTracker Sea**: the technical report of BoaTrack and SeaDronesSee-MOT challenge at MaCVi [Dataset: *`SeaDroneSee-MOT`* *`BoaTrack`*] __`WACV Workshop`__ [[Paper](https://arxiv.org/abs/2311.07616)] (🥉 in UAV-based Multi-Object Tracking with Re-identification, 🥈 in USV-based Multi-Object Tracking)
  * 2023 - **DLR-BoaTrack**: Improving YOLOv8 with Scattering Transform and Attention for Maritime Awareness [Dataset: *`SeaDroneSee-MOT`* *`BoaTrack`*] __`ISPA`__ [[Paper](https://ieeexplore.ieee.org/document/10279352)] (+BoT-SORT, 🥉 in USV-based Multi-Object Tracking)

  #### Multimodal Fusion / Association

  * 2024 - Image and AIS Data Fusion Technique for Maritime Computer Vision Applications [Task: *`Image-AIS Fusion`*] __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2024W/MaCVi/html/Gulsoylu_Image_and_AIS_Data_Fusion_Technique_for_Maritime_Computer_Vision_WACVW_2024_paper.html)]

  #### Dynamic Scene Change Detection

  * 2024 - **SeaDSC**: A video-based unsupervised method for dynamic scene change detection in unmanned surface vehicles [Dataset: *`RoboWhaler`*] __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2024W/MaCVi/html/Trinh_SeaDSC_A_Video-Based_Unsupervised_Method_for_Dynamic_Scene_Change_Detection_WACVW_2024_paper.html)]

  #### Synthetic Data / Simulation

  * 2023 - **SafeSea**: Synthetic data generation for adverse and low probability maritime conditions __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2024W/MaCVi/html/Tran_SafeSea_Synthetic_Data_Generation_for_Adverse__Low_Probability_Maritime_WACVW_2024_paper.html)]

  #### Detection

  * 2024 - An Automated Method for the Creation of Oriented Bounding Boxes in Remote Sensing Ship Detection Datasets __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2024W/MaCVi/html/Savathrakis_An_Automated_Method_for_the_Creation_of_Oriented_Bounding_Boxes_WACVW_2024_paper.html)]

  #### Classification / Recognition

  * 2024 - Active Learning Strategy Using Contrastive Learning and K-Means for Aquatic Invasive Species Recognition __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2024W/MaCVi/html/Chowdhury_Active_Learning_Strategy_Using_Contrastive_Learning_and_K-Means_for_Aquatic_WACVW_2024_paper.html)]
* ### MaCVi 2023


  * The 1st Workshop on Maritime Computer Vision (MaCVi) 2023 [[Website](https://macvi.org/workshop/macvi23)] [[Results](https://openaccess.thecvf.com/content/WACV2023W/MaCVi/html/Kiefer_1st_Workshop_on_Maritime_Computer_Vision_MaCVi_2023_Challenge_Results_WACVW_2023_paper.html)] [[Paper List](https://openaccess.thecvf.com/WACV2023_workshops/MaCVi)]
  * Baseline: **SeaDronesSee**: A Maritime Benchmark for Detecting Humans in Open Water [Dataset: *`SeaDroneSee`*] [[Paper](https://arxiv.org/abs/2105.01922)]

  #### Detection

  * 2023 - A Novel Framework To Evaluate and Train Object Detection Models for Real-Time Victims Search and Rescue at Sea With Autonomous Unmanned Aerial Systems Using High-Fidelity Dynamic Marine Simulation Environment [Dataset: *`SeaDroneSee`*] __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2023W/MaCVi/html/Poudel_A_Novel_Framework_To_Evaluate_and_Train_Object_Detection_Models_WACVW_2023_paper.html)]
  * 2023 - Improving the Detection of Small Oriented Objects in Aerial Images __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2023W/MaCVi/html/Doloriel_Improving_the_Detection_of_Small_Oriented_Objects_in_Aerial_Images_WACVW_2023_paper.html)]
  * 2023 - **YOLOv7-Sea**: Object Detection of Maritime UAV Images Based on Improved YOLOv7 [Dataset: *`SeaDroneSee`*] __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2023W/MaCVi/html/Zhao_YOLOv7-Sea_Object_Detection_of_Maritime_UAV_Images_Based_on_Improved_WACVW_2023_paper.html)] (🥉 in UAV-based Maritime Object Detection)

  #### Segmentation

  * 2023 - Sonar Image Composition for Semantic Segmentation Using Machine Learning __`WACV Workshop`__ [[Paper](https://doi.org/10.1109/WACVW58289.2023.00031)]
  * 2023 - A Survey on the Deployability of Semantic Segmentation Networks for Fluvial Navigation __`WACV Workshop`__ [[Paper](https://doi.org/10.1109/WACVW58289.2023.00032)]
  * 2023 - Combining Photogrammetric Computer Vision and Semantic Segmentation for Fine-Grained Understanding of Coral Reef Growth Under Climate Change __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2023W/MaCVi/html/Zhong_Combining_Photogrammetric_Computer_Vision_and_Semantic_Segmentation_for_Fine-Grained_Understanding_WACVW_2023_paper.html)]

  #### Image Enhancement / Restoration

  * 2023 - An Efficient Approach for Underwater Image Improvement __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2023W/MaCVi/html/Espinosa_An_Efficient_Approach_for_Underwater_Image_Improvement_Deblurring_Dehazing_and_WACVW_2023_paper.html)]
  * 2023 - **DepthCue**: Restoration of underwater images using monocular depth as a clue __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2023W/MaCVi/html/Desai_DepthCue_Restoration_of_Underwater_Images_Using_Monocular_Depth_as_a_WACVW_2023_paper.html)]

  #### Classification / Recognition

  * 2023 - Sea Ice Classification With Dual-Polarized SAR Imagery __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2023W/MaCVi/html/Chen_Sea_Ice_Classification_With_Dual-Polarized_SAR_Imagery_A_Hierarchical_Pipeline_WACVW_2023_paper.html)]

  #### Synthetic Data / Simulation

  * 2023 - **SeaDroneSim**: Simulation of aerial images for detection of objects above water [Dataset: *`SeaDroneSee`*] __`WACV Workshop`__ [[Paper](https://openaccess.thecvf.com/content/WACV2023W/MaCVi/html/Lin_SeaDroneSim_Simulation_of_Aerial_Images_for_Detection_of_Objects_Above_WACVW_2023_paper.html)]

## Surveys

### Detection / Tracking Survey

* 2017 - Video Processing From Electro-Optical Sensors for Object Detection and Tracking in a Maritime Environment __`TITS`__ [[Paper](https://doi.org/10.1109/TITS.2016.2634580)]
* 2021 - Survey on Deep Learning-Based Marine Object Detection __`Journal of Advanced Transportation`__ [[Paper](https://doi.org/10.1155/2021/5808206)]
* 2024 - Deep Learning-Based Object Detection in Maritime Unmanned Aerial Vehicle Imagery: Review and Experimental Comparisons __`EAAI`__ [[Paper](https://doi.org/10.1016/j.engappai.2023.107513)]

### Maritime Situational Awareness / Multimodal Perception Survey

* 2021 - Marine Vision-Based Situational Awareness Using Discriminative Deep Learning __`JMSE`__ [[Paper](https://doi.org/10.3390/jmse9040397)]

## Datasets


| **Name**                     | **Year** | **Publish** | **Task**                                                                                                                                                | **Affiliation**                                            | **Link**                                                                                                                                                                                                                                                                                                                                  |
| ---------------------------- | -------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **MarDCT**                   | 2015     |             | Classification<br> Object Detection <br> Tracking                                                                                                       | Sapienza University of Rome                                | [Website](http://www.diag.uniroma1.it//~labrococo/MAR/index.htm) <br> [Paper](http://www.diag.uniroma1.it//~bloisi/papers/bloisi-vrs2015-draft.pdf)                                                                                                                                                                                       |
| **MODD**                     | 2016     |             | Object Detection<br> Semantic Segmentation                                                                                                              | University of Ljubljana                                    | [Website](http://vision.fe.uni-lj.si/RESEARCH/modd/) <br> [Paper](https://arxiv.org/abs/1503.01918) <br> [Github](https://vicos.si/resources/modd/)                                                                                                                                                                                       |
| **SMD**                      | 2017     |             | Object Detection<br> Object Tracking                                                                                                                    | The Arctic University of Norway                            | [Website](https://sites.google.com/site/dilipprasad/home/singapore-maritime-dataset) <br> [Paper](https://openaccess.thecvf.com/content_CVPRW_2019/papers/PBVS/Moosbauer_A_Benchmark_for_Deep_Learning_Based_Object_Detection_in_Maritime_CVPRW_2019_paper.pdf) <br> [Github](https://github.com/yaoshanliang/Singapore-Maritime-Dataset) |
| **Visual-Inertial-Canoe**    | 2018     |             | SLAM                                                                                                                                                    | University of Illinois at Urbana-Champaign                 | [Website](https://databank.illinois.edu/datasets/IDB-9342111) <br> [Paper](https://journals.sagepub.com/doi/pdf/10.1177/0278364917751842)                                                                                                                                                                                                 |
| **MODD2**                    | 2018     |             | Object Detection<br> Semantic Segmentation                                                                                                              | University of Ljubljana                                    | [Website](https://box.vicos.si/borja/viamaro/index.html) <br> [Paper](https://arxiv.org/abs/1802.07956) <br> [Github](https://arxiv.org/abs/1802.07956)                                                                                                                                                                                   |
| **SeaShips**                 | 2018     |             | Object Detection                                                                                                                                        | Wuhan University                                           | [Paper](https://doi.org/10.1109/TMM.2018.2865686) <br> [Github](https://github.com/jiaming-wang/SeaShips)                                                                                                                                                                                                                                 |
| **MaSTr1325**                | 2019     |             | Semantic Segmentation                                                                                                                                   | University of Ljubljana                                    | [Website](https://vicos.si/resources/mastr1325/) <br> [Paper](https://ieeexplore.ieee.org/document/8967909) <br> [Github](https://github.com/bborja/modd)                                                                                                                                                                                 |
| **Tampere-WaterSeg**         | 2019     |             | Semantic Segmentation                                                                                                                                   | Tampere University                                         | [Paper](https://ieeexplore.ieee.org/document/8918694)                                                                                                                                                                                                                                                                                     |
| **MariShipSeg-HEU**          | 2020     |             | Semantic Segmentation                                                                                                                                   | Harbin Engineering University                              | [Paper](https://doi.org/10.1016/j.imavis.2019.11.002) <br> [Github](https://github.com/EddieEduardo/MariShipSeg-HEU)                                                                                                                                                                                                                      |
| **MCShips**                  | 2020     |             | Object Detection                                                                                                                                        | Zheng Yitong and Zhang Shun                                | [Paper](https://doi.org/10.1109/ICME46284.2020.9102907) <br> [Github](https://github.com/ZhengYitong2333/Mcships)                                                                                                                                                                                                                         |
| **WaterV2**                  | 2020     |             | Semantic Segmentation                                                                                                                                   | Louisiana State University                                 | [Website](https://www.ece.lsu.edu/xinli/WaterNet/index.html) <br> [Paper](https://doi.org/10.1007/s41095-020-0156-x) <br> [Github](https://github.com/xmlyqing00/WaterNet)                                                                                                                                                                |
| **MID**                      | 2020     |             | Object Detection                                                                                                                                        | Shanghai University                                        | [Paper](https://doi.org/10.1002/rob.21983) <br> [Github](https://github.com/aluckyi/MID)                                                                                                                                                                                                                                                  |
| **ABOShips**                 | 2021     |             | Object Detection                                                                                                                                        | Åbo Akademi University                                    | [Dataset](https://zenodo.org/records/4736931) <br> [Paper](https://doi.org/10.3390/rs13050988)                                                                                                                                                                                                                                            |
| **WSODD**                    | 2021     |             | Object Detection<br> Instance Segmentation                                                                                                              | Beijing Institute of Technology                            | [Paper](https://www.frontiersin.org/articles/10.3389/fnbot.2021.723336/full) <br>[Github](https://github.com/sunjiaen/WSODD)                                                                                                                                                                                                              |
| **USVInland**                | 2021     |             | SLAM<br> Stereo Matching <br> Water Segmentation                                                                                                        | ORCA-tech                                                  | [Weibsite](https://www.orca-tech.cn/datasets/USVInland/Introduction) <br> [Paper](https://arxiv.org/abs/2103.05383) <br> [Github](https://github.com/ORCA-Uboat/USVInland-Dataset)                                                                                                                                                        |
| **FloW**                     | 2021     |             | Object Detection<br> Multimodal Object Detection                                                                                                        | ORCA-tech                                                  | [Website](https://www.orca-tech.cn/datasets/FloW/Introduction) <br> [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Cheng_FloW_A_Dataset_and_Benchmark_for_Floating_Waste_Detection_in_ICCV_2021_paper.html) <br> [Github](https://github.com/ORCA-Uboat/FloW-Dataset)                                                        |
| **SeaDronesSee**             | 2021     |             | Object Detection<br> Object Tracking                                                                                                                    | University of Tuebingen                                    | [Website](https://seadronessee.cs.uni-tuebingen.de) <br> [GitHub](https://github.com/Ben93kie/SeaDronesSee) <br> [Paper](https://openaccess.thecvf.com/content/WACV2022/html/Varga_SeaDronesSee_A_Maritime_Benchmark_for_Detecting_Humans_in_Open_Water_WACV_2022_paper.html)                                                             |
| **MSGMP**                    | 2021     |             | Multimodal Perception                                                                                                                                   | MIT Sea Grant AUV Lab                                      | [Website](https://seagrant.mit.edu/auvlab-datasets-marine-perception-1/) <br> [Paper](https://doi.org/10.23919/OCEANS44145.2021.9705871)                                                                                                                                                                                                  |
| **Dasha River**              | 2022     |             | Semantic Segmentation                                                                                                                                   | Shenzhen Polytechnic University                            | [Paper](https://doi.org/10.1109/TIM.2022.3165803) <br> [Github](https://github.com/zhourd-szpu/WaterSeg)                                                                                                                                                                                                                                  |
| **MaSTr1478**                | 2022     |             | Semantic Segmentation                                                                                                                                   | University of Ljubljana                                    | [Paper](https://doi.org/10.1109/IROS47612.2022.9982043) <br> [Github](https://github.com/lojzezust/WaSR-T)                                                                                                                                                                                                                                |
| **MU-SSiD**                  | 2022     |             | Sea State Classification                                                                                                                                | Manzoor Umair Team                                         | [Dataset](https://www.kaggle.com/datasets/umairatwork/mu-ssid) <br> [Paper](https://doi.org/10.3390/sym14071487)                                                                                                                                                                                                                          |
| **ROSEBUD**                  | 2022     |             | Semantic Segmentation                                                                                                                                   | Purdue University                                          | [Dataset](https://purr.purdue.edu/publications/4072/1) <br> [Paper](https://doi.org/10.3390/s22134681)                                                                                                                                                                                                                                    |
| **MassMIND**                 | 2023     |             | Semantic Segmentation<br> Instance Segmentation                                                                                                         | University of Massachusetts Lowell                         | [Paper](https://doi.org/10.1177/02783649231153020) <br> [Github](https://github.com/uml-marine-robotics/MassMIND)                                                                                                                                                                                                                         |
| **LaRS**                     | 2023     |             | Semantic Segmentation<br> Panoptic Segmentation                                                                                                         | University of Ljubljana                                    | [Website](https://lojzezust.github.io/lars-dataset) <br> [GitHub](https://github.com/lojzezust/lars_evaluator) <br> [Paper](https://arxiv.org/abs/2308.09618)                                                                                                                                                                             |
| **MariBoats**                | 2023     |             | Instance Segmentation                                                                                                                                   | Harbin Engineering University                              | [Paper](https://doi.org/10.1371/journal.pone.0279248) <br> [Github](https://github.com/Qunfunction/Visible-ship-dataset)                                                                                                                                                                                                                  |
| **Pohang Canal Dataset**     | 2023     |             | SLAM                                                                                                                                                    | Korea Advanced Institute of Science and Technology         | [Website](https://sites.google.com/view/pohang-canal-dataset) <br> [Paper](https://doi.org/10.1177/02783649231191145) <br> [Github](https://github.com/dhchung/pohang_canal_dataset)                                                                                                                                                      |
| **SPSCD**                    | 2023     |             | Object Detection<br> Classification                                                                                                                     | University of Split                                        | [Website](https://labs.pfst.hr/maritime-dataset/) <br> [Paper](https://doi.org/10.3390/jmse11030578)                                                                                                                                                                                                                                      |
| **WaterScenes**              | 2023     | TITS        | Object Detection<br> Instance Segmentation <br> Semantic Segmentation <br> Free-Space Segmentation <br> Waterline Segmentation <br> Panoptic Perception | University of Liverpool                                    | [Website](https://waterscenes.github.io) <br> [GitHub](https://github.com/WaterScenes/WaterScenes) <br> [Paper](https://ieeexplore.ieee.org/document/10571852)                                                                                                                                                                            |
| **MVDD13**                   | 2024     |             | Object Detection                                                                                                                                        | Dalian Maritime University                                 | [GitHub](https://github.com/yyuanwang1010/MVDD13) <br> [Paper](https://www.sciencedirect.com/science/article/pii/S0141118723003760)                                                                                                                                                                                                       |
| **OASIs**                    | 2024     |             | Semantic Segmentation                                                                                                                                   | Seadronix                                                  | [Website](https://www.navlue.com/dataset) <br> [Paper](https://arxiv.org/abs/2407.09005)                                                                                                                                                                                                                                                  |
| **GLSD**                     | 2025     |             | Object Detection                                                                                                                                        | Wuhan University                                           | [Paper](https://doi.org/10.1080/10095020.2024.2416896) <br> [Github](https://github.com/jiaming-wang/GLSD)                                                                                                                                                                                                                                |
| **IWHR_AI_Lable_Floater_V1** | 2025     |             | Object Detection                                                                                                                                        | China Institute of Water Resources and Hydropower Research | [Dataset](https://doi.org/10.6084/m9.figshare.27376851.v1) <br> [Paper](https://doi.org/10.1038/s41597-025-04594-9)                                                                                                                                                                                                                       |
| **PoLaRIS**                  | 2025     |             | Object Detection<br> Object Tracking                                                                                                                    | Seoul National University                                  | [Website](https://sites.google.com/view/polaris-dataset) <br> [Paper](https://doi.org/10.1109/ICRA55743.2025.11128583) <br> [Github](https://github.com/sparolab/PoLaRIS)                                                                                                                                                                 |
| **SeePerSea**                | 2025     |             | Object Detection                                                                                                                                        | Dartmouth College                                          | [Website](https://seepersea.github.io/) <br> [Paper](https://doi.org/10.1109/TFR.2025.3602937) <br> [Github](https://github.com/dartmouthrobotics/SeePerSea)                                                                                                                                                                              |
| **MULTIAQUA**                | 2025     |             | Semantic Segmentation                                                                                                                                   | University of Ljubljana                                    | [Website](https://lmi.fe.uni-lj.si/en/multiaqua/) <br> [Paper](https://arxiv.org/abs/2512.17450)                                                                                                                                                                                                                                          |
| **MVTD**                     | 2025     |             | Object Tracking                                                                                                                                         | Khalifa University                                         | [Dataset](https://figshare.com/articles/dataset/MVTD/29177147) <br> [Paper](https://arxiv.org/abs/2506.02866) <br> [Github](https://github.com/AhsanBaidar/MVTD)                                                                                                                                                                          |
| **USVTrack**                 | 2025     | IROS        | Object Detection<br> Object Tracking                                                                                                                    | University of Liverpool                                    | [Website](https://usvtrack.github.io/) <br> [Paper](https://ieeexplore.ieee.org/document/11246786) <br> [Github](https://github.com/USVTrack/USVTrack)                                                                                                                                                                                    |
| **SeaClips**                 | 2026     |             | Object Detection                                                                                                                                        | SEA.AI                                                     | [Dataset](https://huggingface.co/datasets/SEA-AI/SeaClips) <br> [Paper](https://doi.org/10.1109/WACV61042.2026.00447)                                                                                                                                                                                                                     |
| **WUTDet**                   | 2026     |             | Object Detection                                                                                                                                        | Wuhan University of Technology                             | [Paper](https://arxiv.org/abs/2604.07759) <br> [Github](https://github.com/MAPGroup/WUTDet)                                                                                                                                                                                                                                               |

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

### Segmentation

* 2018 - Stereo obstacle detection for unmanned surface vehicles by IMU-assisted semantic segmentation [*`MODD2`*] [[Paper](https://www.sciencedirect.com/science/article/pii/S0921889017305808)]
* 2021 - ShorelineNet: An Efficient Deep Learning Approach for Shoreline Semantic Segmentation for Unmanned Surface Vehicles [*`MODD2`*]  **IROS** [[Paper](https://ieeexplore.ieee.org/document/9636614)]

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

### Marine Radar-Camera

### LiDAR-Camera

### RGB-IR
