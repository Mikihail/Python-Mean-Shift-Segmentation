## Python-Mean-Shift-Segmentation
Mean shift segmentation is an iterative process to partition the image into semantically meaningful regions by clustering the pixels in the image. This is done by shifting each data point to the average of data points in its neighborhood.

### Main Technologies and Techniques:
1. Boundary preserving filtering
2. Mean Shift Filtering
3. Thresholding
4. Calculating Euclidean distance
5. Applications of normal or Epanechnikov kernels
6. Mean shift vector
7. Cluster Analysis
8. Image Segmentation

### Project Overview:
The project revolves around the concept of mean shift, a non-parametric feature-space analysis technique. We used this method to segment an image into different regions. The resulting segments are displayed after the mean shift procedure is applied to the given points.

Algorithm implemented:
1. Mode Detection
2. Discontinuity Preserving filtering
3. Mean shift image segmentation

### Software Used:
Enthought Canopy 1.6.1

### Outcome:
The ultimate objective is to ensure that our mean shift algorithm is able to traverse all the rows until every point is exhausted. The results are then discussed and evaluated.

### Shortcomings:
The appropriate selection of the window size is non-trivial. Inappropriate size can lead to merging of modes or creation of additional shallow modes.

### Lessons Learned:
Through the course of this project, we have honed our understanding on Python programming, image processing techniques and libraries like scipy, numpy, sys, random and opencv.

### Acknowledgement:
This work is being continued by Mikihail and all queries should be directed to them.

### References:
1. <https://en.wikipedia.org/wiki/Mean_shift#Applications>
2. <http://luthuli.cs.uiuc.edu/~daf/courses/CS-498-DAF-PS/Segmentation.pd