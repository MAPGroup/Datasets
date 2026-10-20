# <p align=center> Datasets: Navigational Safety of Marine Surface Vehicles</p>

---
>**Navigational Safety of Marine Surface Vehicles in Restricted Visibility: From Intelligent Vision to Vision-Centered Multi-Sensor Fusion**<br>
>[Ryan Wen Liu](https://scholar.google.com/citations?user=klYz-acAAAAJ&hl=zh-CN), [Fengchuan Song], [Tianxiang Wang], [Guobei Peng], [Youngrong Kim], [Xian Zhong], [Hooi-Siang Kang], [Maohan Liang]<sup>* </sup>, [Junzhi Yu]<sup>* </sup>, [Shanliang Yao]<sup>* </sup><br>
>(* Corresponding Author)<br> 
>Submitted to Autonomous Transportation Research

> **Introduction:** *Marine surface vehicles (MSVs) require reliable environmental perception to detect obstacles, interpret traffic encounters, and support timely navigation decisions. Fog, precipitation, low illumination, glare, and vessel motion degrade shipboard imagery, while distant targets and water-surface reflections further complicate perception. Cameras provide detailed appearance and semantic information, but their limitations motivate fusion with thermal imaging, radar, light detection and ranging (LiDAR), and the automatic identification system (AIS). This survey examines how intelligent vision and vision-centered multi-sensor fusion support MSV navigation in restricted visibility. We first introduce sensor capabilities and degradation models, linking sensing limitations to the synthesis of adverse-condition training data. We then organize visual methods by video stabilization, image enhancement, object detection, object tracking, and navigable-area segmentation, and review fusion according to the complementary modalities involved. Public maritime datasets are examined separately from downstream applications in vessel behavior prediction, collision avoidance, and integrated navigation systems. Throughout the review, we distinguish maritime applications from methods developed in other domains and discuss their relevance to degraded sensing conditions. The synthesis identifies five priorities: visibility-aware benchmarks, physically grounded imaging and restoration, small-target perception, reliability-aware fusion, and evidence-grounded scene reasoning. Progress toward safer navigation requires these capabilities to be evaluated jointly with temporal consistency, uncertainty, and operational constraints.*
<hr />

## MSV Architecture

![Figure01_Flowchart](https://user-images.githubusercontent.com/48637474/230878573-a26b035d-3ed0-4db9-9b58-161067632daf.jpg)
<div align=center>Architecture of a typical MSV.</div>
