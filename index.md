---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<style>
.image-cropper {
  width: 200px;
  height: 200px;
  position: relative;
  overflow: hidden;
  border-radius: 50%;
}

.flex-header {
  display: flex; 
  align-items: center; 
  justify-content: center; 
  gap: 20px; 
  flex-flow: row wrap;
}

.flex-header-left {
  flex-grow: 0; 
  flex-shrink: 0;
}

.flex-header-right {
  flex-basis: 720px;
}
</style>

<div class="flex-header">

<div class="flex-header-left">

<div class="image-cropper">
  <img src="/assets/me.jpg">
</div>

</div>

<div class="flex-header-right">
  <h2> Biography </h2>
  Caroline Pascal is a PhD student in robotics and mechanics at <a href="http://u2is.ensta-paris.fr/">U2IS</a> and <a href="https://www.ensta-paris.fr/sites/default/files/fichiers/decouvrir/unite_de_mecanique.pdf">UME</a>, <a href="https://www.ensta-paris.fr/">ENSTA Paris</a>. Despite her all-rounder personality, her focus is currently on the development of robotized solutions for the vibratory and acoustic characterization of unknown structures. In this context, her work blends together various topics, including the modeling, calibration and control of robotic arms, and the implementation of innovative mechanical characterization methods, especially in acoustics. Despite the research substance of any PhD thesis, a significant part of Caroline's work is dedicated to the design of generic and user-friendly ROS-based tools for a simplified sensor and tool integration on robotic arms. 
</div>

</div>

## Research

### [Publications]

* [IROS 2023](https://ieee-iros.org/) - Caroline Pascal, Alexandre Chapoutot, Olivier Doaré, "A ROS-based kinematic calibration tool for serial robots", _2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)_, Oct 2023, Detroit, Michigan, United States ([HAL link](https://hal.science/hal-04165802)).

### Presentations

* [IDIA Day 2022](https://idia-day-2022.sciencesconf.org/) - _Robotized measurements : autonomous geometric and vibro acoustic characterisation of structures_ ([poster](/assets/Poster_28062022.pdf)).

* [JJCR 2022](https://jjcr-2022.sciencesconf.org/) - _Robotized measurements : autonomous geometric and vibro acoustic characterisation of structures_ ([poster](/assets/Poster_07112022.pdf)).

* U2IS Lab Day 2023 - _Acoustic far-field prediction using robotized measurements and the boundary elements method_ ([poster](/assets/LABDAY2023.pdf)).

* [ROSConFr 2023](https://roscon.fr/) - _robot\_arm\_calibration: a kinematic calibration tool for serial robots, or the unberdening of a crucial task_ (talk with peer review process, [slides](/assets/ROSCon2023.pdf)).

* [R4 Seminar](https://r4-robotique.fr/) - _Robotized measurements for geometric and acoustic characterization of unknown structures_ ([slides](/assets/INRIABordeaux_talk.pdf), [video](https://www.youtube.com/watch?v=UCCju3B8p_U))

* [FreeFEM Days 2023](https://freefem.org/ffdays.html) - _Far-field acoustic prediction using the boundary element method and robotized measurements_ (talk with peer review process, [slides](/assets/FreeFEMDays.pdf)).

* U2IS Lab Day 2024 - _Robotized metrology : wait, it's all calibration ?_ ([slides](/assets/CarolinePascal(6).pdf).

## Teaching

### Courses at ENSTA Paris (2021-2022)

* [MO101](https://perso.ensta-paris.fr/~chapoutot/teaching/mo101/) (_Introduction to Linux_) - Introduction to Linux/Unix commands, shell scripting and related utilities.
* [IN102](https://perso.ensta-paris.fr/~frehse/in102web/) (_Introduction to the C programming language_) - Introduction to the basics of C : compilation, pointers, functions, structures, arrays, etc.
* [IN101](https://ecampus.paris-saclay.fr/enrol/index.php?id=13880) (_Algorithms and programming_) - Familiarisation with systematic and scientific ways to concieve algorithms, through an analysis-formalisation-conception-implementation process.

### Courses at ENPC (2021-2022)

* [ARCSO](http://gede.enpc.fr/programme/Fiche.aspx) (_Tools for computer science in industry_) - Introduction to object-oriented programming and distributed version control in the context of industrial system design.

## Previous experiences

<style>
.flex-content {
  display: flex; 
  align-content: start; 
  flex-flow: row wrap; 
  margin-bottom: 10px;
}

.flex-content-left {
  flex-basis: 200px; 
  margin-right: 20px;
}

.flex-content-right {
  flex-basis: 720px; 
}
</style>

<div class="flex-content">

<div class="flex-content-left">
  <h4>**Research engineer**<br>
  U2IS & UME - ENSTA Paris<br>
  Jan. 2021 - Oct. 2021</h4>
</div>

<div class="flex-content-right">
  _Development of an user-friendly interface for the integration of various sensors in the use of the use of a robotic arm._ <br> Developement of an intuitive ROS library and designed ergonomic tool-holding devices for the simplified implementation of
  geometric and vibro-acoustic measurement routines.
</div>

</div>

<div class="flex-content">

<div class="flex-content-left">
  <h4>**End-of-studies intern**<br>
  U2IS & CEA-LIST<br>
  May 2019 - Nov. 2020</h4>
</div>

<div class="flex-content-right">
  _Development of an object-centered grasp analysis and synthesis framework – Application to multi-fingered grippers._ <br> Conception of a set of configurable task-oriented grasp quality metrics and formulated a state-of-the art hybrid
  friction-adhesion contact mode, which were successfully combined in a custom optimized gripper design aid tool.
</div>

</div>

<div class="flex-content">

<div class="flex-content-left">
  <h4>**Gap year intern**<br>
  BALYO SA <br>
  Jan. 2019 - Jun. 2020</h4>
</div>

<div class="flex-content-right">
  _Development of an automated optimized-trajectory generation process for autonomous forklifts._ <br> Design of an innovative forklift trajectory generation process allowing the vehicle to perform turns while avoiding collisions.
</div>

</div>

<div class="flex-content">

<div class="flex-content-left">
  <h4>**Gap year intern**<br>
  Navier Lab. - ENPC <br>
  Jun. 2018 - Dec. 2018</h4>
</div>

<div class="flex-content-right">
  _Force and torque sensors integration in the use of 6-axis robots._ <br> Development of a C# sensor network aiming to facilitate the integration of sensors in the use of 6-axis robots.
</div>

</div>

## Education

<div class="flex-content">

<div class="flex-content-left">
  <h4>**Final MSc year**<br>
  ENSTA Paris <br>
  Sept. 2019 - Mar. 2020</h4>
</div>

<div class="flex-content-right">
  _Robotics and Embedded Systems Department._ <br> Embedded software, perception, modeling and simulation, control.
</div>

</div>

<div class="flex-content">

<div class="flex-content-left">
  <h4>**First MSc year**<br>
  ENPC <br>
  Sept. 2016 - May. 2018</h4>
</div>

<div class="flex-content-right">
  _Mechanical and Materials Department._ <br> CFAO, mechanics of solids and fluids, structural dynamics, FEA.
</div>

</div>

<div class="flex-content">

<div class="flex-content-left">
  <h4>**PhD side course**<br>
  MVA - Paris Saclay <br>
  Jan. 2023 - Mar. 2023</h4>
</div>

<div class="flex-content-right">
  _NPM3D - Point clouds and 3D modeling._
</div>

</div>

<div class="flex-content">

<div class="flex-content-left">
  <h4>**PhD side course**<br>
  Telecom Paris <br>
  Feb. 2023 - Apr. 2023 </h4>
</div>

<div class="flex-content-right">
  _RUST programming language for embedded systems._
</div>

</div>

## Projects 

* Conception, modeling and control of a [self-made 6-axis robot](/assets/robot.jpg) with an actuated gripper (Mar. 2020);

* Developement of an [autonomous portraitist application](/assets/portrait.mp4) using a robotic arm (Sept. 2021); 

## Community involvement

* PhD and master degree students representative at ENSTA Paris board of directors (2022 - 2025).

* Staff representative at ENSTA Paris work council (2023 - 2026).
