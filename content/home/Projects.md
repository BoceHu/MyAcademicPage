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
  
  <img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/pipeline.png" class="centerrr">
  
  - <p style='text-align: justify;font-size: 14px;'>Collected a multi-view upper body movement dataset (UBM)  with the assistance of the trunk support trainer (TruST), consisting of 156K trunk movement depth images collected from 16 healthy subjects. The key points in the dataset is labeled by Vicon infrared system and the concept behind this dataset is the Star Excursion Balance Test (SEBT).</p>
  - <p style='text-align: justify;font-size: 14px;'>Designed a novel end-to-end Attention Cube Regression Network (ACRNet) for multi-view real-time 3D human pose estimation based on depth images, and validated the superiority of ACRNet on the ITOP dataset and UBM dataset compared with other state-of-the-art methods.</p>
  - <p style='text-align: justify;font-size: 14px;'>Proposed a new backbone structure and a dynamic multi-view fusion module based on cross-attention mechanism. Both of them improve the representation ability of our model.</p>
  
- <p style='text-align: justify;font-size:16px'><b>A Deep-Learning Based Real-Time Prediction of Seated Postural Limits and its Application in Trunk Rehabilitation</b></p> <p style='text-align: right; font-color:grey; font-size:11px'><i>Oct 2021 – May 2022</i></p>
  
  <img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/bounding.png" class="center">
  		
  
  
  - <p style='text-align: justify;font-size: 14px;'>Developed a new deep-learning-based controller for TruST to predict the dynamic virtual motion boundary of upper body movements in real-time, which can represent the actual seated postural limits more accurately in the rehabilitation sitting task of patients with cerebral palsy, replacing the fixed boundary without strong representational ability used in the previous version.</p>





## Course Projects

<ul><li><p class="left" style='font-size:16px'><b>Dynamic Torque Control of Multi-link Robotic Arms According to End Effector Target positions</b></p><br/>
        <p style='font-size:16px'>
    	<b>Projects of Robot Learning (MECE 6616)</b>
    </p>
    <p style='font-size:16px'><b>Advisor: Matei Ciocarlie</b></p>
    <ul><li><p style='text-align: justify;font-size: 14px;'>Controlled the state (i.e., velocity, angle, and torque) of multi-link robotic arms to achieve specific positions.</p></li></ul>		
    <ul><li><p style='text-align: justify;font-size: 14px;'>Compared the speed of approaching the target position and the ability to maintain the current state after reaching the target position of simple deep learning and multiple deep reinforcement learning algorithms (deep Q-Network, proximal policy optimization).</p></li></ul>
    <ul><li>
        <p style='text-align: justify;font-size: 14px;'>Leveraged OpenAi Gym, PyTorch, and Stable-Baselines3 to build the real physcial working environment and train the model to complete different control tasks.
        </p>
    </li></ul>
    <center>
    <figure>  
    <img class="centerr" src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/project4.gif" alt="project4" width="120%" >  <figcaption style="margin:5px 0px -20px 0px">Deep Q-learning</figcaption>
</figure>
    <figure>
    <img class="centerr" src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/project5.gif" alt="project5" width="120%">  <figcaption style="margin:5px 0px -20px 0px">Proximal Policy Optimization</figcaption>
</figure>
    </center>
    </li></ul>
<ul><li>
    <p class="left" style='font-size:16px'>
        <b>Design, Fabrication, and Programming of Humanoid Robot</b>
    </p><br/>
    <p style='font-size:16px'>
    	<b>The Final Project of Robot Studio (MECE 4611)</b>
    </p>
    <p style='font-size:16px'><b>Advisor: Hod Lipson</b></p>
    <ul><li><p style='text-align: justify;font-size: 14px;'>Brainstormed the appearance of the organic-looking two-legged robot, and designed the CAD model of all components in this robot.</p></li></ul>		
    <ul><li><p style='text-align: justify;font-size: 14px;'>Fabricated each part of the robot using 3D printing and assembled them with the Raspberry Pi, motors, the controller board, etc., as the entire robot.</p></li></ul>
    <ul><li><p style='text-align: justify;font-size: 14px;'>Programmed and tested each motor of the robot, allowing our robot to walk and dance stably.</p></li></ul>
    </li></ul>
<center><iframe src="https://drive.google.com/file/d/16rJ4tMXq-6bOT0jgmPtxK9u5p8Ao408n/preview" width="640" height="480" allow="autoplay"></iframe>
</center>

<ul><li>
 	<p class="left" style='font-size:16px'><b>Glass Cleaning Robot</b></p><br/>
    <p style='font-size:16px'>
    	<b>The Final Project of Introduction to Robotics (MECE 4602)</b>
    </p>
    <p style='font-size:16px'><b>Advisor: Sunil K. Agrawal</b></p>
    	<ul><li>
            <p style='text-align: justify;font-size: 14px;'>Applied SolidWorks to design a 4 DOF redundant robotic arm with a rotating base.
            </p>
         </li></ul>		
    	<ul><li>
            <p style='text-align: justify;font-size: 14px;'>Simulated the cleaning robot in MATLAB using Robotics System Toolbox.
            </p>
        </li></ul>
    	<ul><li>
            <p style='text-align: justify;font-size: 14px;'>Analyzed the workspace and the cleaning trajectory of the robot depending on the simulation.
            </p>
         </li></ul>
    	<ul><li>
            <p style='text-align: justify;font-size: 14px;'><a href="uploads/FinalReport.pdf" target="_blank">Final Report</a></p>
	</li></ul>
</li></ul>

<center>
    <figure>  
		<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/render.png" alt="render" width="90%" vspace="1" hspace="5">  <figcaption style="margin:5px 0px -20px 0px">Render Robotic Arm</figcaption>
	</figure>
    <figure>  
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/structure.png" alt="structure" width="90%" vspace="1" hspace="5">  <figcaption style="margin:5px 0px -20px 0px">Arm Structure</figcaption>
	</figure>
    <figure>
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/workspace.png" alt="workspace" width="90%" vspace="1" hspace="5">  <figcaption style="margin:5px 0px -20px 0px">Complete Workspace</figcaption>
	</figure>
    <figure>  
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/trajectory.gif" alt="trajectory" width="90%" vspace="1" hspace="1">  <figcaption style="margin:5px 0px -20px 0px">Cleaning Trajectory</figcaption>
	</figure>
    <figure>
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/randomworkspace.gif" alt="random workspace" width="90%" vspace="1" hspace="1">  <figcaption style="margin:5px 0px -20px 0px">Random Workspace</figcaption>
	</figure>
</center>



<ul><li>
 	<p class="left" style='font-size:16px'><b>Soft Robot Locomotion Training with Evolutionary Algorithm</b></p><br/>
        <p style='font-size:16px'>
    	<b>The Final Project of Evolutionary Computation (MECE 4510)</b>
    </p><p style='font-size:16px'><b>Advisor: Hod Lipson</b></p>
    	<ul><li>
            <p style='text-align: justify;font-size: 14px;'>Built a virtual physics engine with Python and OpenGL to simulate the real-world environment that satisfies the laws of physics.
            </p>
         </li></ul>		
    	<ul><li>
            <p style='text-align: justify;font-size: 14px;'>Treated each soft robot as a parent genotype and iteratively utilized the selection, mutation, and crossover mechanism to evolve the internal state of soft robots to improve the speed of hopping gait.
            </p>
        </li></ul>
    	<ul><li>
            <p style='text-align: justify;font-size: 14px;'>Calculated the speed of each robot and used this speed as a reward to optimize the soft robot population.
            </p>
         </li></ul>
</li></ul>
<center>
    <figure>  
		<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo1.gif" alt="render" width="100%" style="margin:0px -10px">
	</figure>
    <figure>  
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo2.gif" alt="structure" width="100%" style="margin:0px -10px"> 
	</figure>
    <figure>
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo3.gif" alt="workspace" width="100%" style="margin:0px -10px">
	</figure>
    <figure>  
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo4.gif" alt="trajectory" width="100%" style="margin:0px -10px">
	</figure>
    <figure>
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo5.gif" alt="random workspace" width="100%" style="margin:0px -10px">
	</figure>
        <figure>
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo6.gif" alt="random workspace" width="100%" style="margin:0px -10px">
	</figure>
    <figure>
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo7.gif" alt="random workspace" width="100%" style="margin:0px -10px">
	</figure>
    <figure>
        <img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo8.gif" alt="random workspace" width="100%" style="margin:0px -10px">
	</figure>
    <figure>
  		<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo9.gif" alt="random workspace" width="100%" style="margin:0px -10px">
	</figure><figcaption><b>Robot Zoo</b></figcaption>
</center><br/>



