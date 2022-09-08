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

gallery_nerf1:
    - image_path: ../assets/images/research/volsdfHand.mp4
gallery_nerf2:
    - image_path: ../assets/images/research/burger_pytorch.mp4
    - image_path: ../assets/images/research/hand_spiral.mp4

gallery_depth1:
    - image_path: ../assets/images/courses/Squishy_Color.JPG
    - image_path: ../assets/images/courses/Squishy_Depth.png

gallery_ironman:
    - image_path: ../assets/images/courses/ironman_helmet_pieces.jpeg
    - image_path: ../assets/images/courses/ironman_helmet_prototype.jpeg
    - image_path: ../assets/images/courses/ironman_helmet_closed.jpeg
    - image_path: ../assets/images/courses/ironman_helmet_open.jpeg
---

Helen Huang's class, personal, and research projects.

# Personal Projects

## Cat Ninja iOS Game
Cat Ninja is an iOS game created in Swift using SwiftUI and SpriteKit. As a cat ninja, swipe cat toys and avoid water balloons. Score points and gain combos before the time runs out! [[Github]](https://github.com/helen-huang9/CatNinja)

*Artwork created by Helen Huang using Procreate.*

**Soon to be released on the App Store as* Samurai Cat

{% include gallery id="gallery_catninja" layout="third" %}

<video width="300" controls>
    <source src="../assets/images/personal_projects/SamuraiCatPreview.mp4">
</video>

# Research
## NeRF Models
The following are some of the NeRF videos I helped produce during my research with Prof. Sridhar in the Brown Interactive 3D Vision & Learning Lab. 

These videos are 3D continuous scenes learned from a sparse set of images using a deep neural network. The object models and camera data was created and sampled in Blender.

{% include gallery id="gallery_nerf1" caption="Hand mesh created using [VolSDF](https://lioryariv.github.io/volsdf/)" %}

{% include gallery id="gallery_nerf2" layout="half" caption="Models created using [NeRF](https://www.matthewtancik.com/nerf)" %}

# Course Projects
## Depth Capture System
I created a depth capture system as part of my CSCI 1430 Computer Vision final project with Kate Nelson, Angela Xing, and Lo McKeown. Implemented in Swift and Python. [[Github]](https://github.com/helen-huang9/Depth-Capture-System)

{% include gallery id="gallery_depth1" caption="Capture RGB image and depth map example" %}

{% include figure image_path="../assets/images/courses/Squishy_Voxel.mp4" caption="Generated voxel model" %}

## OpenGL Underwater Scene
I created an underwater scene for my CSCI 1230 Computer Graphics final project with Kate Nelson and Angela Xing. We implemented randomly generated terrain, bezier curve camera movement, and L-system coral plants using C++ and OpenGL.

{% include figure image_path="../assets/images/courses/Short_underwater_scene.mp4"%}

## Iron Man Helmet
I created a functioning Iron Man helmet for my ENGN 0032 Intro to Engineering: Design final project with Kevin Hsu and Angela Xing. 

{% include gallery id="gallery_ironman" layout="half" caption="Documented progress of prototype to final product" %}

<video width="500" controls>
    <source src="../assets/images/courses/ironman_working.mp4">
</video>

## "Field" - Instrumental Song
I wrote, composed, and produced a song for my MUSC 0400B Intro to Popular Music Theory final project.

<audio controls>
    <source src="../assets/images/courses/song.m4a">
</audio>