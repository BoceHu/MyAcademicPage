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

<ul><li>
    <p style='text-align: justify;font-size:16px'><b>Visual Information-Based Grasping of the Robotic Arm Using the Deep Learning Model</b></p> 
    <ul><li>
    <p style='text-align: justify;font-size: 14px;'>Leveraged a deep learning model to predict the robotic arm grasp poses from a depth image scene, which contains a variety of objects at random locations.</p>
    </li></ul>
    <ul><li> <p style='text-align: justify;font-size: 14px;'>According to the objects' spatial information, the deep learning model can output the grasp position, grasp angle, and gripper width to complete the grasp work.</p></li></ul>
    <ul><li>
            <p style='text-align: justify;font-size: 14px;'><a href="https://github.com/BoceHu/vision_based_grasp" target="_blank">Code</a></p>
	</li></ul>
</li></ul>
<center>
	<figure>  
		<img class="centerr" src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/grasp.gif" alt="grasp" width="90%" >  <figcaption style="margin:5px 0px -20px 0px" >The left gif shows the grasping process of the panda robotic arm in the Pybullet simulation environment, and the right gif shows the rendered depth map. The red line in the depth map is the grasping position of the gripper.</figcaption>
    </figure>
</center>


<ul><li>
    <p style='text-align: justify;font-size:16px'>
        <b>SARN: Shifted Attention Regression Network for 3D Hand Pose Estimation</b>
    </p> 
    <ul><li>
    	<p style='text-align: justify; font-size: 14px;' >Proposed a novel network architecture, shifted attention regression network (SARN), which is characterized by shifted attention heatmap and soft input aggregation, to perform accurate, robust and unbiased 3D hand pose estimation (HPE) for hand disorder recognition.
    	</p>
    </li></ul>
    <ul><li>
    	<p style='text-align: justify;font-size: 14px;'>Built a hand movement dataset (PAKH) based on Parkinson???s finger tapping test (FTT) by conducting experiments on 17 subjects. PAKH contains 26k depth images collected by a Intel RealSense D435i depth camera with 2 hand joint annotations.
   		</p>
    </li></ul>
   	<ul><li>
    	<p style='text-align: justify;font-size: 14px;'>Proposed method outperforms or achieves state-of-the-art performance on three public datasets: NYU, ICVL and MSRA datasets, and achieves low error on predicting joint position and all task-specific metrics on PAKH, which indicates that the proposed method can perform accurate and robust HPE and has the potential for medical applications.
    	</p>    
    </li></ul>
    <center>
	<figure>  
		<img class="centerpipe" src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/SARN_pipeline.png" alt="sarn_pipeline" width="100%" >  <figcaption style="margin:5px 0px -20px 0px" >SARN Working Pipeline</figcaption>
    </figure>
    <figure>  
		<img class="centerpipe" src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/qual.png" alt="qual" width="100%" >  <figcaption style="margin:5px 0px -20px 0px" >Qualitative Results (Ground truth is shown in red, and the prediction is in yellow.)</figcaption>
    </figure>
</center>
</li></ul>
<ul><li>
	<p style='text-align: justify;font-size:16px'><b>ACRNet: Attention Cube Regression Network for Multi-view 3D Human Pose Estimation in the Postural Star-sitting Test</b></p> 
    <ul><li>
    <p style='text-align: justify;font-size: 14px;'>Designed a novel end-to-end Attention Cube Regression Network (ACRNet), which introduces an attention cube to enclose the
object and aggregates information from each cube???s surface to estimate the 3D position of the key points on the human body based on multi-view depth images.</p>
    </li></ul>
    <ul><li>
        <p style='text-align: justify;font-size: 14px;'>Proposed a new backbone structure and a dynamic multi-view fusion module based on cross-attention mechanism. Both of them improve the representation ability of our model.</p>
    </li></ul>
    <ul><li>
    <p style='text-align: justify;font-size: 14px;'>Collected a multi-view upper body movement dataset (UBM) based on the postural star-sitting test, consisting of 156K trunk movement depth images from 16 healthy subjects tested on the Trunk Support Trainer (TruST).
	</p>
    </li></ul>
    <center>
	<figure>  
		<img class="centerpipe" src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/pipeline.png" alt="pipeline" width="100%">  <figcaption style="margin:5px 0px -20px 0px" >ACRNet Working Pipeline</figcaption>
    </figure>
     <figure>
          <img class="centerpipe" src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/acr.png" alt="acr" width="100%" >  <figcaption style="margin:5px 0px -20px 0px" >Attention Cube</figcaption>
    </figure>
        <figure>
            <img class="centerpipe" src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/qual_acr.png" alt="qual_acr" width="100%" >  <figcaption style="margin:5px 0px -20px 0px" >Qualitative Results (Ground truth is shown in red, and the predicted pose is green.)</figcaption>
        </figure>
</center>
</li></ul>

<ul><li>
    <p style='text-align: justify;font-size:16px'><b>A Deep-Learning Based Real-Time Prediction of Seated Postural Limits and its Application in Trunk Rehabilitation</b></p> 
    <ul><li>
    <p style='text-align: justify;font-size: 14px;'>Developed a new deep-learning-based controller for TruST to predict the dynamic virtual motion boundary of upper body movements in real-time, which can represent the actual seated postural limits more accurately in the rehabilitation sitting task of patients with cerebral palsy, replacing the fixed boundary without strong representational ability used in the previous version.</p>
    </li></ul>
</li></ul>
<center>
	<figure>  
		<img class="centerr" src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/bounding.png" alt="project4" width="100%" >  <figcaption style="margin:5px 0px -20px 0px" >The TruST System With Dynamic Virtual Motion Boundary</figcaption>
    </figure>
</figure></center>

<ul><li><p class="left" style='font-size:16px'><b>Dynamic Torque Control of Multi-link Robotic Arms According to End Effector Target Positions</b></p><br/>
        <p style='font-size:16px'>
    	<b>Projects of Robot Learning (MECE 6616)</b>
    </p>
    <p style='font-size:16px'><b>Advisor: Matei Ciocarlie</b></p>
    <ul><li><p style='text-align: justify;font-size: 14px;'>Controlled the state (i.e., velocity, angle, and torque) of multi-link robotic arms to achieve specific positions.</p></li></ul>		
    <ul><li><p style='text-align: justify;font-size: 14px;'>Compared the speed of approaching the target position and the ability to maintain the current state after reaching the target position of simple deep learning and multiple deep reinforcement learning algorithms (deep Q-Network, proximal policy optimization).</p></li></ul>
    <ul><li>
        <p style='text-align: justify;font-size: 14px;'>Leveraged OpenAi Gym, PyTorch, and Stable-Baselines3 to build the real physical working environment and train the model to complete different control tasks.
        </p>
    </li></ul>
</li></ul>
<center>
	<figure>  
		<img class="centerr" src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/project4.gif" alt="project4" width="120%" >  <figcaption style="margin:5px 0px -20px 0px" >Deep Q-learning</figcaption>
    </figure><figure>
	<img class="centerr" src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/project5.gif" alt="project5" width="120%">  <figcaption style="margin:5px 0px -20px 0px">Proximal Policy Optimization</figcaption>
</figure></center>

<ul><li>
    <p class="left" style='font-size:16px'>
        <b>Design, Fabrication, and Programming of a Humanoid Robot</b>
    </p><br/>
    <p style='font-size:16px'>
    	<b>The Final Project of Robot Studio (MECE 4611)</b>
    </p>
    <p style='font-size:16px'><b>Advisor: Hod Lipson</b></p>
    <ul><li><p style='text-align: justify;font-size: 14px;'>Brainstormed the appearance of the organic-looking two-legged robot, and designed the CAD model of all components in this robot.</p></li></ul>		
    <ul><li><p style='text-align: justify;font-size: 14px;'>Fabricated each part of the robot using 3D printing and assembled them with the Raspberry Pi, motors, the controller board, etc., as the entire robot.</p></li></ul>
    <ul><li><p style='text-align: justify;font-size: 14px;'>Programmed and tested each motor of the robot, allowing our robot to walk and dance stably.</p></li></ul>
    </li></ul>
<center><iframe src="https://drive.google.com/file/d/16rJ4tMXq-6bOT0jgmPtxK9u5p8Ao408n/preview" width="640" height="480" allow="autoplay"></iframe><figcaption style="font-size: 14px; margin:0px 0px 0px 0px" >Journal Video</figcaption>
</center>

<ul><li>
 	<p class="left" style='font-size:16px'><b>Glass Cleaning Robot Design</b></p><br/>
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
		<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo1.gif" alt="zoo1" width="100%" style="margin:0px -10px">
	</figure>
    <figure>  
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo2.gif" alt="zoo2" width="100%" style="margin:0px -10px"> 
	</figure>
    <figure>
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo3.gif" alt="zoo3" width="100%" style="margin:0px -10px">
	</figure>
    <figure>  
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo4.gif" alt="zoo4" width="100%" style="margin:0px -10px">
	</figure>
    <figure>
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo5.gif" alt="zoo5" width="100%" style="margin:0px -10px">
	</figure>
        <figure>
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo6.gif" alt="zoo6" width="100%" style="margin:0px -10px">
	</figure>
    <figure>
    	<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo7.gif" alt="zoo7" width="100%" style="margin:0px -10px">
	</figure>
    <figure>
        <img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo8.gif" alt="zoo8" width="100%" style="margin:0px -10px">
	</figure>
    <figure>
  		<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/zoo9.gif" alt="zoo9" width="100%" style="margin:0px -10px">
	</figure><figcaption><b>Robot Zoo</b></figcaption>
</center>
<center>
    <figure>
  		<img src="https://github.com/BoceHu/MyAcademicPage/raw/master/assets/media/robotzoo/fast.gif" alt="fast robot" width="90%" style="margin:0px -10px">
	</figure><figcaption><b>The Fastest Robot</b></figcaption>
</center><br/>


