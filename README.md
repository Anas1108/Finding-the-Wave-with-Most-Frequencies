# DIP - Finding the Wave with Most Frequencies

## Introduction
This repository contains the implementation of finding the wave with the highest number of frequencies (peaks) in an image, as well as drawing a bounding rectangle around it.

## Algorithm
1. Load the input image
2. Apply the Sobel Edge Detector to detect the edges in the image
3. Threshold the image to remove noise and enhance the edges
4. Find the peaks in the image using the peak detection algorithm
5. Select the wave with the highest number of peaks
6. Draw a bounding rectangle around the selected wave
7. Display the original image with the bounding rectangle

## Usage
The code in this repository can be run to find the wave with the highest number of peaks in an image and display it with a bounding rectangle. The input image can be changed to observe the effects on the output.

## Conclusion
This implementation provides a foundation for finding and visualizing the wave with the highest number of peaks in an image. Further modifications and optimizations can be made to the code to improve its accuracy and efficiency.
