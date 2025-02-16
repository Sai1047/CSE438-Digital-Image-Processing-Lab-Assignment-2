### Digital Image Processing Lab Report 02

**Introduction**

This report provides an overview of the Digital Image Processing Lab, detailing the objectives, methodologies, and results of the exercises conducted. The focus is on implementing fundamental image processing techniques using Python and OpenCV.

**Faculty**

Audity Ghosh, Lecturer
Department of Computer Science & Engineering University of Information Technology and Sciences (UITS)

**Submitted by**

Md. Saiful Islam Santo 
ID: 2125051047 
Section: 8A Batch: 50


**Course Details**

Course Code: CSE 438

Course Title: Digital Image Processing Lab

Section: 8A (50th Batch)

Date: 17-February-2025

**Objective**

This lab assignment aims to implement multiple image transformation techniques using Python and OpenCV. The transformations include resizing, rotating, and flipping an image, followed by displaying all results in a single plot.

**Tasks**

a. Resize an Image: Resize the image to 256x256 pixels.

b. Rotate by 180 Degrees (Clockwise): Rotate the image by 180 degrees in the clockwise direction.

c. Vertical Flip: Flip the image vertically.

d. Display Transformations: Display the original image and all transformed images in a 2x2 subplot for comparison.

**Tools and Libraries**

Python 3.x

OpenCV (cv2)

NumPy

Matplotlib

**Methodology**

a. Resizing

The image is resized to 256x256 pixels using cv2.resize().

b. Rotation

The image is rotated by 180 degrees clockwise using cv2.rotate() with cv2.ROTATE_180.

c. Vertical Flip

The image is flipped vertically using cv2.flip() with the flip code 0.

d. Visualization

The original image and transformed images are displayed in a 2x2 subplot using Matplotlib.

**Results**

1. The resized image (256x256 pixels) was successfully displayed.

2. The image was rotated by 180 degrees clockwise.

3. The image was vertically flipped.

4. All images were displayed in a 2x2 subplot using plt.subplot() for visual comparison.

**How to Run (Google Colab)**

Open Google Colab: Google Colab.

Navigate to the repository containing this assignment:

%cd dip-lab

Open and execute the Jupyter Notebook file:

!jupyter notebook santo_2125051047_8A_assignment2.ipynb


**Conclusion**

This lab exercise successfully demonstrated multiple image transformations, including resizing, rotation, and flipping, using OpenCV and Python. Combining these techniques enhances the understanding of image manipulation fundamentals.

**Future Work**

Experiment with additional geometric transformations like scaling, shearing, and translations.

Apply transformations to real-time video streams.

**License**

This project is for educational purposes. Feel free to use and modify as needed.

**Acknowledgments**

Special thanks to our honorable faculty, Audity Ghosh, for guidance and support throughout this lab session
