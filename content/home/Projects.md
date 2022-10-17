---
widget: blank  # See https://wowchemy.com/docs/page-builder/
headless: true  # This file represents a page section.
weight: 40  # Order that this section will appear.
title: "Projects"
subtitle: ""
design:
  columns: '1'
  image_position: center
---

## Research Projects

- <p style='text-align: justify;font-size:16px'><b>SARN: Shifted Attention Regression Network for 3D Hand Pose Estimation in Medical Application</b></p> <p style='text-align: right;font-color:grey; font-size:11px'><i>Feb 2022 – Present</i></p>
  
  - <p style='text-align: justify; font-size: 14px;' >Proposed a novel network architecture, shifted attention regression network (SARN), which is characterized by shifted attention heatmap and soft input aggregation, to perform accurate, robust and unbiased 3D hand pose estimation (HPE) for medical application. </p>
  - <p style='text-align: justify;font-size: 14px;'>Built a hand movement dataset (PAKH) based on Parkinson’s finger tapping test (FTT) by conducting experiments on 17 subjects. PAKH contains 92k depth images collected by two Intel RealSense D435i depth cameras with 5 hand joint annotations labeled by Vicon infrared system.</p>
  - <p style='text-align: justify;font-size: 14px;'>Proposed method outperforms or achieves state-of-the-art performance on three public datasets: NYU, ICVL and MSRA datasets, and achieves low error on predicting joint position and all task-specific metrics on PAKH, which indicates that the proposed method can perform accurate and robust HPE and has the potential for medical applications.</p>
  
- <p style='text-align: justify;font-size:16px'><b>ACRNet: Attention Cube Regression Network for Multi-view Real-time 3D Human Pose Estimation in Telemedicine</b></p> <p style='text-align: right; font-color:grey; font-size:11px'><i>Feb 2022 – Oct 2022</i></p>
  
  <img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/pipeline.png" class="center">
  
  - <p style='text-align: justify;font-size: 14px;'>Collected a multi-view upper body movement dataset (UBM)  with the assistance of the trunk support trainer (TruST), consisting of 156K trunk movement depth images collected from 16 healthy subjects. The key points in the dataset is labeled by Vicon infrared system and the concept behind this dataset is the Star Excursion Balance Test (SEBT).</p>
  - <p style='text-align: justify;font-size: 14px;'>Designed a novel end-to-end Attention Cube Regression Network (ACRNet) for multi-view real-time 3D human pose estimation based on depth images, and validated the superiority of ACRNet on the ITOP dataset and UBM dataset compared with other state-of-the-art methods.</p>
  - <p style='text-align: justify;font-size: 14px;'>Proposed a new backbone structure and a dynamic multi-view fusion module based on cross-attention mechanism. Both of them improve the representation ability of our model.</p>
  
- <p style='text-align: justify;font-size:16px'><b>A Deep-Learning Based Real-Time Prediction of Seated Postural Limits and its Application in Trunk Rehabilitation</b></p> <p style='text-align: right; font-color:grey; font-size:11px'><i>Oct 2021 – May 2022</i></p>
  
  <p style='text-align: center'>
  <img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/bounding.png">
  </p>			
  
  - <p style='text-align: justify;font-size: 14px;'>Developed a new deep-learning-based controller for TruST to predict the dynamic virtual motion boundary of upper body movements in real-time, which can represent the actual seated postural limits more accurately in the rehabilitation sitting task of patients with cerebral palsy, replacing the fixed boundary without strong representational ability used in the previous version.</p>





## Course Projects

- <p style='text-align: justify;font-size:16px'><b>Robot Learning (MECE 6616) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Advisor: Matei Ciocarlie</b></p>

  - Controlled the state (i.e., velocity, angle, and torque) of multi-link robotic arms to achieve specific positions.

  - Compared the speed of approaching the target position and the ability to maintain the current state after reaching the target position of simple deep learning and multiple deep reinforcement learning algorithms (deep Q-Network, proximal policy optimization).

  - Leveraged PyTorch, OpenAi Gym, and Stable-Baselines3 to stimulate the working environment.

    <figure>  
        <img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/project4.gif" alt="project4" style="width:100%">  <figcaption align = "center">Fig.1 - Deep Q-learning.</figcaption>
    </figure>

    <figure>
        <img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/project5.gif" alt="project5" style="width:100%">  <figcaption align = "center">Fig.2 - Proximal Policy Optimization.</figcaption>
    </figure>

- Robot Studio

- EA

- Glass Cleaning Robot
