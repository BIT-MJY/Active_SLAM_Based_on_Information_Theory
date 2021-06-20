# Active SLAM Based on Information Theory
Information Theoretic Exploration with Gaussian Process (GP) and Bayesian Optimization (BO)

## Overview
Here is a simulation of infomation-theoretic exploration with python. ROS-based method is released by **Robust Field Autonomy Lab**. To make the principle and mechanism more clear for active slamer, I reproduce it with python and revise some functions. 

## Related Work
Some basic knowledge is suggested for understanding this work.
* Gaussian Process: https://krasserm.github.io/2018/03/19/gaussian-processes/
* Bayesian Optimization: http://krasserm.github.io/2018/03/21/bayesian-optimization/
* Information-Theoretic Exploration with Bayesian Optimization: https://personal.stevens.edu/~benglot/Bai_Wang_Chen_Englot_IROS2016_AcceptedVersion.pdf

## Source Code
* [Jupyter Notebook](https://github.com/BIT-MJY/Active_SLAM_Based_on_Information_Theory/blob/master/src/Active_SLAM_based_on_MI.ipynb)
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gq0Qn-_PdKFZFr_LIxd-WWJBT3Mm1TP4?usp=sharing)

## Results
3 pictures from each step. The first picture illustrates the candidates. The second picture illustrates the top 5. The third picture illustrates the chosen next location and its receptive field. 
<div align=center>
<img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/1-2.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/1-3.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/1-4.png" width="180" height="105"/>
  
<img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/2-2.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/2-3.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/2-4.png" width="180" height="105"/>

<img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/3-2.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/3-3.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/3-4.png" width="180" height="105"/>

<img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/4-2.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/4-3.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/4-4.png" width="180" height="105"/>

<img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/5-2.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/5-3.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/5-4.png" width="180" height="105"/>

<img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/6-2.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/6-3.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/6-4.png" width="180" height="105"/>

<img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/7-2.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/7-3.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/7-4.png" width="180" height="105"/>

<img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/8-2.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/8-3.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/8-4.png" width="180" height="105"/>

<img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/9-2.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/9-3.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/9-4.png" width="180" height="105"/>

<img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/10-2.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/10--3.png" width="180" height="105"><img src="https://github.com/BIT-MJY/Active-SLAM-Based-on-Information-Theory/blob/master/img/10-4.png" width="180" height="105">
</div>

# Authors
Junyi Ma, Beijing Institute of Technology

# Acknowledgement
* Source Code from [Robust Field Autonomy Lab](https://github.com/RobustFieldAutonomyLab/turtlebot_exploration_3d)
* [Information-Theoretic Exploration with Bayesian Optimization](https://personal.stevens.edu/~benglot/Bai_Wang_Chen_Englot_IROS2016_AcceptedVersion.pdf)
