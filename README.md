# **Finding Lane Lines on the Road** 

# Overview
The purpose of this project is to detect lines on the road.We start with images to check if algorithm works on overlaying lines correctly and once it works on images same is applied to video as video is just a stream of images.

This project would use following machine learning algorithm
* GrayScale transform
* Canny Edge detection
* Gaussian Filter Matrix for image blur
* Hough Transform

Repository has following folder/files

* test_images - Folder has images files and images with output_* are output files
* test_videos - Folder has video files 
* test_videos_output - Folder has video files generated after processing
* P1.ipynb is jupyter notebook to run lane lines algorithm for images and videos
* writeup.md - File has details about approach

---
# Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

Things to install ( Mac OS )

* Install Anaconda [here](https://www.anaconda.com/download/#macos)
* Create environment conda create --name `myenv` python=3.6 
* To start working on myenv ```source activate myenv```
* Run ```anaconda-navigator``` to use vscode for debugging and jupyter to run P1.ipynb



