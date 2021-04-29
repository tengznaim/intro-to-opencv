# OpenCV Tutorial

#### Overview

This is my exploratory repository for learning basic computer vision using OpenCV. It acts as my personal guide in attempting to thoroughly understand the concepts surrounding programmatic image processing and computer vision with hopes in being able to apply them in projects. There are currently three notebooks in this repository:

**1. basics.ipynb**

- Based on the earlier portion of the video linked under "References"
- Contains guides on performing basic things with OpenCV such as:
  - Reading Images and Videos
  - Resizing and Rescaling Frames
  - Drawing Shapes and Writing Text
  - Essential Functions in OpenCV
  - Image Transformations
  - Contour Detection
- This is an overview on the functions and may not contain detailed explanations on why we pass in certain things into the function and what the function actually does.

**2. advanced.ipynb**

- Based on the later portion of the video.
- Contains guides and slight explanations on:
  - Color Spaces
  - Color Channels
  - Smoothing and Blurring
  - Bitwise Operations
  - Masking
  - Histogram Computation
  - Thresholding/Binarising Images
  - Edge Detection
- These have a more detailed explanation on some functions referenced in the basic notebook with more theoretical overview on what concepts such as thresholding and blurring actually do.

**3. face_detection.ipynb**

- This looks at the simple usage of a haarcascade pretrained classifier by OpenCV in detecting faces.

### Usage

If you find interest in using and running the notebooks, you may need to install the following modules:

- OpenCV
- matplotlib
- numpy

### References

1. Full Introductory Tutorial on OpenCV
   - Video - https://www.youtube.com/watch?v=oXlwWbU8l2o
   - Accompanying Repository - https://github.com/jasmcaus/opencv-course
2. Cascade Classifier Documentation
   - https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html
