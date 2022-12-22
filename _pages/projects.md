---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

# Table of Contents
* [Robot Motion Planning and Localization](#p11)
* [Learning Machine Classifier Comparison](#p10)
* [Global Navigation Satellite System Software-Defined Radio](#p9)
* [Automated Flash Cable Cutter (Senior Capstone Project)](#p8)
* [Two Cart System System Identification and Control](#p7)
* [Amphibious Climbing Soft Robot](#p6)
* [Plastic Degradation Toggle Switch Research Proposal](#p5)
* [Robotic Path-Planning and Control Labs](#p4)
  - [Two-Link Arm: Triangle Path Planning & Control](#p4a)
  - [Two-Link Arm: Maze Path Planning & Control](#p4b)
  - [Omnibot: Path Planning Square and Circle](#p4c)
  - [Omnibot: Point Tracking & Control](#p4d)
* [Automated Hanging Plant Rotator (Junior Design Project)](#p3)
* [Computational Modeling and Simulation](#p2)
  - [Bouncing Ball Simulation](#p2a)
  - [Upwind Advection Simulation](#p2b)
  - [Diffusion Simulation](#p2c)
  - [Oil Spill Concentration Simulation](#p2d)
* [Compressed Air Motor](#p1)

## Robot Motion Planning and Localization <a name="p11"></a>
**Date:** Spring Quarter 2021 <br/>
**Description:** This project was two-folded. (1) Implemented one of the bug algorithms and the decomposition & search method algorithm to plan a robot's path from any start point to any goal point in the free work space. (2) Implemented an extended Kalman filter (EKF) using relative range and bearing measurements for (i) robot localization and (ii) simultaneous robot localization and measurement beacon mapping. <br/>

- Motion Planning Project Report [[PDF]](https://alexngxyen.github.io/files/MAE_195_Project_1_Report.pdf) <br/>
- Robot Localization and SLAM Report [[PDF]](https://alexngxyen.github.io/files/MAE_195_Project_2_Report.pdf) <br/>

## Learning Machine Classifier Comparison <a name="p10"></a>
**Date:** Spring Quarter 2021 <br/>
**Description:** This project studied the classification performance of several different learning machines, such as a feed-forward neural network (FFNN), k-nearest neighbors (K-NN), multi-class support vector machines (SVMs), and k-means clustering with principal component analysis (PCA), applied to the "wine data set" found on the "UCI Machine Learning Repository" which contains 13 wine attributes associated with three different wine classes.  <br/>

- Final Project Proposal [[PDF]](https://alexngxyen.github.io/files/MAE_277_Project_Proposal.pdf) <br/> 
- Final Project Report [[PDF]](https://alexngxyen.github.io/files/MAE_277_Final_Project.pdf) <br/> 

## Global Navigation Satellite System Software-Defined Radio <a name="p9"></a>
**Date:** Fall Quarter 2020 <br/>
**Description:** This project was to create a global navigation satellite system (GNSS) software-defined radio (SDR) from scratch to successfully acquire and track different pseudorandom noise (PRN) codes from the different GNSS constellations. The GNSS SDR output the code error (in chips), phase error (in degrees), estimated Doppler frequency (in Hz), carrier-to-noise ratio (in dB-Hz), tracked in-phase and quadrature components, and code phase estimate (in meters). Moreover, the extracted navigation observables, in the form of pseudoranges, will need to be compensated for correctly (ionospheric and tropospheric delays) in order to obtain an accurate navigation solution for a stationary receiver using a nonlinear least squares estimator. <br/>

- Final Project Report [[PDF]](https://alexngxyen.github.io/files/MAE_295_Updated_Project.pdf) <br/> 

## Automated Flash Cable Cutter (Senior Capstone Project) <a name="p8"></a>
**Date:** Fall Quarter 2019 - Spring Quarter 2020  <br/>
**Awards:** Best Technical Project in Mechanical Engineering & Best Project Pitch
<p align="center">
  <iframe src="https://www.youtube.com/embed/wKkle1032tw" width="480" height="270" ></iframe>
</p>

<!--[Design Competition Video](https://www.youtube.com/watch?v=wKkle1032tw"CG Automation Design Competition Video 2020") -->

**Desciption:** This was the senior capstone project assigned to a team of five mechanical engineers (including myself) sponsored by Strand Products Incorporated (Inc) as part of University of California Santa Barabara's (UCSB) three quarter long capstone series. Strand Products Inc asked our team to automate the cable cutting process by developing an electromechanical system which can seamlessly integrate with an existing Ewald ﬂash cutter. Typically the setup for cutting cable (e.g., machine preparation, cable measuring, cable dereeling, ect.) are arduously performed by a lab technician resulting in slow manufacturing cycle times. The developed autonomous cable cutting system is intended to mimic the lab technician's hands during each cutting job by utilizing a suite of sensors, pneumatic actuators, stepper motors, and microcontrollers. Our team's design solution contained a cable dereeler, feeder system, cable cutter, and extraction system. The final product was intended to be user friendly by having a simple touchscreen graphical user interface (GUI) such that individuals can easily specify their desired cable length and quantity for each cutting job, among other things, during the set up phase. The final design was intended to be safe to use with minimal supervision and robust to varying cable cutting job types (e.g., change of spool size, cable material, or cable sizes). Our team was able to successfully optimize Strand Products Inc's time while being able to accurately and precisely cutting large amounts of cable. <br/>  

<p align="center">
  <img src="https://alexngxyen.github.io/images/Final_Product_Image.png" width="650" height="450">
</p>

**Website:** [Strand Products C.G. Automation](https://capstone.engineering.ucsb.edu/projects/strand-products-cg-automation)

- Design Packet (Final Product Report) [[PDF]](https://drive.google.com/file/d/10hjroGt8Rv5S4S-wX_5Q6qTRCjsmiUaj/view?usp=share_link) <br/>  
- Mechanical Engineering Design Competition Slides [[PDF]](https://alexngxyen.github.io/files/ME_Design_Competition_Slides) <br/>  
- Printed Circuit Board (PCB) Schematic [[PDF]](https://alexngxyen.github.io/files/PCB_Schematic.pdf) <br/>  

## Two Cart System System Identification and Control <a name="p7"></a>
**Date:** Spring Quarter 2020 <br/>

<p align="center">
  <img src="https://alexngxyen.github.io/images/Two_Cart_System.png">
</p>

**Description:** This project was to perform system identification of a two cart system connected by a spring, then synthesis a closed-loop feedback controller for the identified model which satisfies several performance requirements. There were four parts: (1) expriment data collection, (2) system identification using nonparametric and parametric methods, (3) controller design, and (4) controller design testing.

- Final Project Report [[PDF]](https://alexngxyen.github.io/files/ME_155C_Project.pdf) <br/>  

## Amphibious Climbing Soft Robot <a name="p6"></a>
**Date:** Winter Quarter 2020 <br/>

<p align="center">
  <img src="https://alexngxyen.github.io/images/Fabricated_Soft_Robotics.png">
  <img src="https://alexngxyen.github.io/images/Project_Challenge.png">
</p>

**Description:** This project was designed for a team of two people to fabricate a soft robot which can traverse 1 meter carrying a 100 gram mass. We decided to recreate an ampibious climbing soft robot (ACSR). This specific soft robot took many iterations of different silicone casting molds to successfully fabricate the correct air pathway configuration which creates a suction force required for a walking gait. The final iteration of the ACSR worm was able to move forwards and backwards but we were unable to design a method to change the worm's heading (or yaw) angle. 

- Final Project Report [[PDF]](https://drive.google.com/file/d/1AdhZADR4BmFNbZ3EoYtXFWTv76lr34FD/view?usp=share_link) <br/>  

## Plastic Degradation Toggle Switch <a name="p5"></a>
**Date:** Fall Quarter 2019 <br/>

<p align="center">
  <img src="https://alexngxyen.github.io/images/image_1.png">
  <img src="https://alexngxyen.github.io/images/image_2.png">
</p>

**Description:** This project involved writing a research proposal describing a potential biological computing problem, contains a literature review, and discusses the hypothesized solution's impact on the environment. My project focused on a plastic degredation toggle switch which could break down the PET plastics floating throughout vast water ecosystems (e.g., rivers, oceans, seas, ect.). The challenge of this problem is to develop a plastic degrading enzyme which does not harm the ambient marine life in the environment. <br/>

- Research Proposal [[PDF]](https://alexngxyen.github.io/files/Plastic_Degredation_Toggle_Switch.pdf) <br/>  

## Robotic Path-Planning and Control Labs <a name="p4"></a>
**Date:** Fall Quarter 2019 <br/>

* Two-Link Arm: Triangle Path Planning & Control  <a name="p4a"></a>
  <p align="center">
    <img src="https://alexngxyen.github.io/images/Triangle_Path.png">
  </p>
  
  * **Description:** This laboratory focused on tracing a triangle using a two-link arm. A MATLAB and simulink script utilized inverse kinematics for the trajectory planning and control of the robotic arm's end effector coordinates. Forward kinematics were used to find the laser path from the angles outputted in simulink. <br/>
  
  - Lab Report [[PDF]](https://alexngxyen.github.io/files/Lab_1A.pdf) <br/>   
  
* Two-Link Arm: Maze Path Planning & Control  <a name="p4b"></a>
  <p align="center">
    <img src="https://alexngxyen.github.io/images/Angle_Tracking.png">
    <img src="https://alexngxyen.github.io/images/maze.png">
  </p>

  * **Description:** This laboratory focused on having a laser pointer reach the end a goal point within a maze as fast as possible without exiting the specified boundaries. A MATLAB and simulink script utilized inverse kinematics for the trajectory planning and control of the robotic arm's end effector coordinates. Forward kinematics were used to find the laser path from the angles outputted in simulink. <br/>

  - Lab Report [[PDF]](https://alexngxyen.github.io/files/Lab_1B_Report.pdf) <br/>  
  
* Omnibot: Path Planning Square and Circle  <a name="p4c"></a>
  <p align="center">
    <iframe src="https://drive.google.com/file/d/1jNwVhaoBjV1Uk_1Hg4bzypUY43nu47gy/preview" width="480" height="280" allow="autoplay"></iframe>
    <iframe src="https://drive.google.com/file/d/16OpMTcEGmPgyUQ_EgaSQVchVo7_OblKp/preview" width="480" height="280" allow="autoplay"></iframe>
  </p>

  * **Description:** This laboratory focused on coordinating a single omnibot to drive in a circle and square pattern. A MATLAB and simulink script utilized inverse kinematics for the trajectory planning and control of the omnibot. Forward kinematics were used to find the omnibot's actual path from the angles obtained in simulink. <br/>

- Lab Report [[PDF]](https://alexngxyen.github.io/files/Lab_2A.pdf) <br/>   
  
* Omnibot: Point Tracking & Control  <a name="p4d"></a>
  <p align="center">
    <iframe src="https://drive.google.com/file/d/1DZIEPTFzLKw_gvt6EwQ1PUEQ9wdhX6-X/preview" width="480" height="280" allow="autoplay"></iframe>
  </p>

  * **Description:** This laboratory focused on having an omnibot trace a semicircle while a laser tracks a user-specified point. A MATLAB and simulink script utilized inverse kinematics for the trajectory planning and control of the omnibot. Forward kinematics were used to find the laser path from the angles outputted in simulink. <br/>

- Pre-Lab Results [[PDF]](https://alexngxyen.github.io/files/Nguyen_Alex_Prelab2b.pdf) <br/> 
- Lab Report [[PDF]](https://alexngxyen.github.io/files/Lab_2B_Report.pdf) <br/> 

## Automated Hanging Plant Rotator (Junior Design Project) <a name="p3"></a>
**Date:** Spring Quarter 2019 <br/>

<p align="center">
  <img src="https://alexngxyen.github.io/images/automatic_plant.jpg" width="700">
  <!-- <img src="https://alexngxyen.github.io/images/ME_153_Design_Poster.jpg" width=75% height=75%> -->
</p>

**Description:** This was the junior design project that a team of five mechanical engineers (including myself) built over six weeks as part of the University of California Santa Barbara's (UCSB) "Introduction to Mechanical Design" course. Our team built a device to autonomously rotate a hanging plant to evenly distribute sunlight to all sides of a plant throughout the day. A photoresistor is used to measure the ambient light intensity values which incentivizes the plant to rotate accordingly. The automated rotations were controlled using an Arduino Nano connected to a DC motor. A housing was created for the electrical devices from a strong polymer material where we made it robust by machining plastic stoppers to dampen vibrations and included evenly distributed holes to minimize the residual heat created from the electrical components. <br/>

- Final Report [[PDF]](https://alexngxyen.github.io/files/SB_Goats_Final_Report.pdf) <br/>  

## Computational Modeling and Simulation <a name="p2"></a>
**Date:** Spring Quarter 2019 <br/>

* Bouncing Ball Simulation <a name="p2a"></a>
  <p align="center">
    <iframe src="https://drive.google.com/file/d/1JaECVwixwH3ExrXA4h8BFqTg_1YRTC-G/preview" width="480" height="270" allow="autoplay"></iframe>
  </p>

  * **Description:** This project aimed to capture the motion of a disk interacting with the walls of a closed container. The evolution for the disk's center of mass was found using Euler's scheme and Newton's second law of motion for an ordinary differential equation.  <br/>

- Final Report [[PDF]](https://alexngxyen.github.io/files/ME_17_HW2_report.pdf) <br/>   

* Upwind Advection Simulation <a name="p2b"></a>
  <p align="center">
    <iframe src="https://drive.google.com/file/d/14BdjXeutdu-Vn-vdsUgFeE4ZQsnTJCV2/preview" width="480" height="280" allow="autoplay"></iframe>
    <iframe src="https://drive.google.com/file/d/1oHdbKweD9wC5gj7w7NE5CcFwj6xyRyJG/preview" width="480" height="280" allow="autoplay"></iframe>
  </p>
  
  <p align="center">
    <iframe src="https://drive.google.com/file/d/14BdjXeutdu-Vn-vdsUgFeE4ZQsnTJCV2/preview" width="280" height="180" allow="autoplay"></iframe>
    <iframe src="https://drive.google.com/file/d/1oHdbKweD9wC5gj7w7NE5CcFwj6xyRyJG/preview" width="280" height="180" allow="autoplay"></iframe>
  </p>
  
  *  **Description:** This project aimed to simulate the upwind scheme by solving the two-dimensional (2-D) advection equation to obtain the advection solution and the velocity field.

- Final Report [[PDF]](https://alexngxyen.github.io/files/Alex_Nguyen_HW4.pdf) <br/>   

* Diffusion Simulation <a name="p2c"></a>
  <p align="center">
    <iframe src="https://drive.google.com/file/d/1u10muevlDhQp-gqbWTKRL0u8R7EbrVAg/preview" width="480" height="280" allow="autoplay"></iframe>
  </p>
  
  * **Description:** This project aimed to solve the two-dimensional (2-D) diffusion equation for some concentration. The solution was found using Robin and Dirichlet boundary conditions. Moreover, the error between the exact and numerical cases were calculated for the two boundary conditions. <br/>

- Final Report [[PDF]](https://alexngxyen.github.io/files/Nguyen_Alex_HW5.pdf) <br/>   
 
* Oil Spill Concentration Simulation <a name="p2d"></a>
  <p align="center">
    <iframe src="https://drive.google.com/file/d/1-dsMsxM6IZ8mjn1-GOI3y7AxNpq56Oy-/preview" width="480" height="280" allow="autoplay"></iframe>
  </p>

  *  **Description:** This project aimed to simulate an oil spill using the two-dimensional (2-D) advection-diffusion equation over several hours of the day. The numerical solution produced the oil spill concentration's evolution over time which was utilized to figure out when the unsafe concentration limit was surpassed. Furthermore, the maximum error was computed between the numerical and exact concentration values at the end of the simulation.

- Final Report [[PDF]](https://alexngxyen.github.io/files/Alex_Nguyen_ME17_Final_P2.pdf) <br/>   

## Compressed Air Motor <a name="p1"></a>
**Date:** Fall Quarter 2018 <br/>

<p align="center">
  <img src="https://alexngxyen.github.io/images/CAM_image_1.png">
  <img src="https://alexngxyen.github.io/images/CAM_image_2.png">
  <img src="https://alexngxyen.github.io/images/CAM_image_3.png">
  <img src="https://alexngxyen.github.io/images/CAM_image_4.png">
</p>

**Description:** This project's goal was to assemble a compressed air motor while adhering to specified dimension and tolerance values. Machine shop tools, such as the lathe, mill, band saw, hack saw, calipers, drills, and taps, were used to machine the different parts. My time was efficiently managed to machine, construct, and test the final design product within six weeks. My compressed air motor had a max RPM of 2300 and an idle RPM of 700 after testing. <br/>
