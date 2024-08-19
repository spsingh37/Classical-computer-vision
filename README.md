## 🤖 Classical-computer-vision
Note:  This project is a culmination of my work for the **"EECS 504: Foundations of Computer Vision"** course, conducted from September to December 2023. The course provided a solid foundation in classical computer vision algorithms/techniques for feature extraction, feature matching, image transformation, color image reconstruction, image denoising, image classification, and image segmentation.

<p align="center">
  <img src="assets/img_matches.png" alt="Simulation 1" width="400" />
  <img src="assets/sunflower_detction_filter.png" alt="Simulation 2" width="400" />
  <img src="assets/demosaicking.png" alt="Simulation 3" width="400" />
  <img src="assets/msf.png" alt="Simulation 4" width="400" />
</p>

### 🎯 Goal
The goal of this project is to provide a useful resource for anyone seeking to understand and implement classical computer vision techniques. For a brief overview, this repo contains the following implementations:
- Harris corner detector
- ORB-feature detector
- Homography estimation
- Image transformation
- Color Image reconstruction
- Image denoising
- Image segmentation

## 🛠️ Test/Demo
- Feature extraction and matching
    - Launch the jupyter notebook inside the directory 'Feature extraction and matching'. The notebook contains implementations of Harris corner detector, ORB-feature detector, and later on image stitching and blob detection.
- Homography and Image Demosaicking
    - Launch the jupyter notebook inside the directory 'Homography and Image Demosaicking'. The notebook contains implementations of Homography estimation for drawing lines on NFL pitch, and later on simulating the RGB color image reconstruction using Bayer Demosaicking.
- Image Denoising and segmentation
    - Launch the jupyter notebook inside the directory 'Image Denoising and segmentation'. The notebook contains implementations of Mumford-Shah model for image denoising, foreground-background segmentation using graph-cut algorithm, and multi-group segmentation using minimum spanning forest algorithm.

## 📊 Results
### 📈 Feature extraction and matching
- Harris corner detector
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/harris_corner1.png">
</div>
<div style="width: 80%; text-align: center;">
      <img style="width:80%" src="assets/harris_corner2.png">
</div>

- Image stitching using ORB features
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/img_features.png">
</div>
<div style="width: 80%; text-align: center;">
      <img style="width:80%" src="assets/img_matches.png">
</div>
<div style="width: 80%; text-align: center;">
      <img style="width:80%" src="assets/stitching.png">
</div>

- Blob detection
<div style="width: 80%; text-align: center;">
      <img style="width:80%" src="assets/circle_detections_filter.png">
</div>
<div style="width: 80%; text-align: center;">
      <img style="width:80%" src="assets/sunflower_detction_filter.png">
</div>

### 📈 Homography and Image Demosaicking
- NFL Pitch homography (drawing line upon estimating the homography)
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/homography.png">
</div>

- Color Image reconstruction (using Bayer demosaicking)
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/demosaicking.png">
</div>

### 📈 Image Denoising and segmentation
- Image denoising (left: original image; Right: denoised image)
<p align="center">
  <img src="assets/orig_img.png" alt="Simulation 1" width="400" />
  <img src="assets/denoised_img.png" alt="Simulation 2" width="400" />
</p>

- Foreground-background segmentation (using graph_cut algorithm)
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/graph_cut.png">
</div>

- Superpixel maps
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/superpixel maps.png">
</div>

- Multi-group segmentation (minimum spanning forest algorithm)
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/msf.png">
</div>