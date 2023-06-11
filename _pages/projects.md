---
permalink: /projects/
title: "Projects"
author_profile: true

toc: true
toc_label: "Projects"
toc_icon: "stream"
toc_sticky: true

gallery_catninja:
    - image_path: ../assets/images/personal_projects/SamuraiCat2.png
    - image_path: ../assets/images/personal_projects/SamuraiCat5.png
    - image_path: ../assets/images/personal_projects/SamuraiCat1.png

gallery_ink:
    - image_path: ../assets/images/courses/ink1.png
    - image_path: ../assets/images/courses/ink2.png

gallery_signature:
    - image_path: ../assets/images/courses/signature_forgery.png

gallery_depth1:
    - image_path: ../assets/images/courses/Squishy_Color.JPG
    - image_path: ../assets/images/courses/Squishy_Depth.png

gallery_ironman:
    - image_path: ../assets/images/courses/ironman_helmet_pieces.jpeg
    - image_path: ../assets/images/courses/ironman_helmet_prototype.jpeg
    - image_path: ../assets/images/courses/ironman_helmet_closed.jpeg
    - image_path: ../assets/images/courses/ironman_helmet_open.jpeg
---

Helen Huang's personal, research, and course projects.

# Personal Projects

## Cat Ninja iOS Game
Cat Ninja is an iOS game created in Swift using SwiftUI and SpriteKit. As a cat ninja, swipe cat toys and avoid water balloons. Score points and gain combos before the time runs out! [[Github]](https://github.com/helen-huang9/CatNinja)

*Artwork created by Helen Huang using Procreate.*

**Soon to be released on the App Store as* Samurai Cat

{% include gallery id="gallery_catninja" layout="third" %}

<video width="300" controls style="display: block; margin: auto;">
    <source src="../assets/images/personal_projects/SamuraiCatPreview.mp4">
</video>

# Research
## NeRF Models
The following are some of the NeRF videos I helped produce during my research with Prof. Sridhar in the Brown Interactive 3D Vision & Learning Lab. 

These videos are 3D continuous scenes learned from a sparse set of images using a deep neural network. The object models and camera data was created and sampled in Blender.

<video width="100%" controls>
    <source src="../assets/images/research/volsdfHand.mp4">
</video>

<video width="49%" controls>
    <source src="../assets/images/research/burger_pytorch.mp4">
</video>

<video width="49%" controls>
    <source src="../assets/images/research/hand_spiral.mp4">
</video>

# Course Projects

## Ink Simulation
I created a physics-based ink simulation of ink diffusing in water for my CSCI 2240 Advanced Computer Graphics project with Austin Miles, Mandy He, and Tianran Zhang. This project was based off of the two papers, "Interactive Visual Simulation of Dynamic Ink Diffusion Effects" and "Fluid Flow for the Rest of Us." 

The water is simulated as a velocity grid which is updated per timestep using the Navier-Stokes equations. After the water is updated, the ink particles are then convected through the velocity grid. Each timestep is saved as a .ply file containing the positions of all the ink particles which were then rendered sequentially in Blender. Implemented in C++ and rendered in Blender. [[Github]](https://github.com/gizmo1479/DaDDi).

I independently created a real-time version of this project in Swift using Metal. [[Github]](https://github.com/helen-huang9/Ink_Simulation).

{% include gallery id="gallery_ink" layout="half" %}

<video width="600" controls>
    <source src="../assets/images/courses/ink_best.mp4">
</video>

## Signature Forgery Detector
I created a signature forgery detector for my CSCI 1470 Deep Learning final project with Josh Kruzan and Pavani Neralla. 

We implemented several different models to test their accuracies, including a CNN, Vision Transformer, Siamese CNN, and Siamese Vision Transformer. We further examined what features of the signatures that the models identified were important in classification by running LIME (Local Interpretable Model-Agnostic Explanations) using our models and datasets. Implemented in Python using Tensorflow. [[Github]](https://github.com/helen-huang9/GAN-DLD)

{% include gallery id="gallery_signature" %}

## Depth Capture System
I created a depth capture system as part of my CSCI 1430 Computer Vision final project with Kate Nelson, Angela Xing, and Lo McKeown. I developed an app that capture RGB images and its corresponding depth data, then visualize scene as a 3D voxel model. Implemented in Swift and Python. [[Github]](https://github.com/helen-huang9/Depth-Capture-System)

{% include gallery id="gallery_depth1" caption="Capture RGB image and depth map example" %}

<video width="600" controls>
    <source src="../assets/images/courses/Squishy_Voxel.mp4">
</video>

## OpenGL Underwater Scene
I created an underwater scene for my CSCI 1230 Computer Graphics final project with Kate Nelson and Angela Xing. We implemented randomly generated terrain, bezier curve camera movement, and L-system coral plants using C++ and OpenGL.

<video width="600" controls>
    <source src="../assets/images/courses/Short_underwater_scene.mp4">
</video>

## Iron Man Helmet
I created a functioning Iron Man helmet for my ENGN 0032 Intro to Engineering: Design final project with Kevin Hsu and Angela Xing. 

{% include gallery id="gallery_ironman" layout="half" caption="Documented progress of prototype to final product" %}

<video width="500" controls style="display: block; margin: auto;">
    <source src="../assets/images/courses/ironman_working.mp4">
</video>

## "Field" - Instrumental Song
I wrote, composed, and produced a song for my MUSC 0400B Intro to Popular Music Theory final project.

<audio controls>
    <source src="../assets/images/courses/song.m4a" style="display: block; margin: auto;">
</audio>