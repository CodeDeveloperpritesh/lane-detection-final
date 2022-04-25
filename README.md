## Computer Vision Based Road lane Detection
# Pritesh Alshetty
# created on 20/03/2022

`The Project`
---

The goals / steps of this project are the following:

* 1.Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* 2.Apply a distortion correction to raw images.
* 3.Apply a perspective transform to rectify binary image ("birds-eye view").
* 4.Use color transforms, gradients, etc., to create a thresholded binary image.
* 5.Detect lane pixels and fit to find the lane boundary.
* 6.Determine the curvature of the lane and vehicle position with respect to center.
* 7.Warp the detected lane boundaries back onto the original image.
* 8.Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

The images for camera calibration are stored in the folder called `camera_cal`.  The images in `test_images` are for testing your pipeline on single frames.


## Usage:

### 1. Set up the environment 
`conda env create -f environment.yml`

To activate the environment:

Window: `conda activate carnd`

### 2. Run the pipeline:
```bash
python main.py INPUT_IMAGE OUTPUT_IMAGE_PATH
python main.py --video INPUT_VIDEO OUTPUT_VIDEO_PATH
```
