---
audience: []
tags:
- machine learning
- computer vision
title: Evision One Year - An Evolving Elixir Library for Computer Vision Tasks
speakers:
- _participants/cocoa-xu.md

---
One year into the development of the Evision library, evision is actively integrating itself with Nx, Kino and Livebook to create an easy-to-learn computer vision library with visualised results and several out-of-the-box Kino widgets. Meanwhile, it now supports not only OpenCV core modules but also extension modules from the opencv_contrib repo. That includes these CUDA modules that enable processing images or inferencing neural networks on an NVIDIA GPU. 

This session will cover 3 main points, 1) all out-of-the-box Kino widgets (as of 1st Jan 2023, there are 5 of them, one of which is a collection of 6 different neural network tasks. New widgets will also be included if the session time allows.) 2) how to use Evision with Nx to create a machine learning + computer vision pipeline. I'll do a live demo that shows how to solve a sudoku game (the puzzle will be captured using camera input) on Livebook. 3) Show and compare the differences when processing images using CPU, OpenCL and CUDA.