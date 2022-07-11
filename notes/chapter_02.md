# Chapter 02 : Representing a Moving Scene

## Table of Contents
1. [The Origins of 3D Reconstruction](#the-origins-of-3d-reconstruction)
2. [3D Space & Rigid Body Motion](#3d-space--rigid-body-motion)
3. [The Lie Group SO(3)](#the-lie-group-so3)
4. [The Lie Group SE(3)](#the-lie-group-se3)
5. [Representing the Camera Motion](#representing-the-camera-motion)
6. [Euler Angles](#euler-angles)

## The Origins of 3D Reconstruction
+ The goal is to reconstruct a 3D structure of a scene from a set of 2D views. 
    - The scene being recovered can be dynamic or static with respect to the motion of the camera. 
    - It is an ill-posed problem as the reconstruction consistent with the views are not unique.

- Typically, the simplest use-case is to reconstruct the structure of a static scene based on the two (2D) views. 

+ We study the geometric relations between a 3D scene and the observed 2D projections using two types of transformations:
    - The **rigid-body motion** representing the motion of the camera from one frame to the next
    - The **perspective projection** to account for the image formation process.

- The problem of joint estimation of camera motion and 3D location is of interest to many communities. 
    +  Computer Vision community : **Structure from Motion**.
    +  Robotics community : **Visual SLAM** (Simultaneous Localization And Mapping).

+  Refer the slides for some of the historical works on this problem.

## 3D Space & Rigid Body Motion
## The Lie Group SO(3)
## The Lie Group SE(3)
## Representing the Camera Motion
## Euler Angles
