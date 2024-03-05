# Computer Vision Course Assignment: Shape Detection and Classification in Video

## Overview

Welcome to the Shape Detection and Classification assignment for the Computer Vision course! In this assignment, you are provided with a video containing different geometrical figures, specifically yellow shapes. Your task is to detect and classify each shape into one of three classes: circle, rectangle, or triangle. The goal is to create an output video where each shape is signed by the name of its class, and different colors mark the classes.

### Task

Your objective is to:

1. Process the provided video `figures.mp4` frame by frame.
2. Detect and classify yellow shapes (circles, rectangles, triangles) in each frame.
3. Annotate each shape with the name of its class.
4. Create an output video where the shapes are marked with different colors based on their classes.

### Getting Started

1. **Clone this repository to your local machine:**

     ```bash
     git clone https://github.com/mshamrai-teaching/image-processing-detection-*your-name*
     ```
2. **Navigate to the project directory:**
      ```bash
       cd image-processing-detection-*your-name*
      ```

3. **Familiarize yourself with the provided video:**
* figures.mp4


### Hints
* Color Detection:
  * Use color segmentation techniques to detect yellow shapes.
* Shape Classification:
  * Consider using contour detection to identify the shapes.
  * Implement a mechanism to classify the shapes based on their geometrical properties.


### Submission
To submit your solution create pull request to the `main` branch.  

Ensure your final submission includes:

* Source code (shape_detection_classification.py\\.ipynb or similar).
* Output video.
* A brief report (report.md or similar) explaining your approach and any challenges faced.


Good luck, and enjoy exploring the world of image stitching! If you have any questions, feel free to reach out.
