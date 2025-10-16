# Coin-detection-using-morphological-operators

This project demonstrates basic image processing and blob detection using OpenCV and Matplotlib in Python. It processes an image of coins through a sequence of computer vision operations to detect and count the total number of coins present.

## Features

Read and display an image using OpenCV

Convert the image to grayscale

Split the image into RGB color channels

Perform thresholding to create a binary mask

Apply morphological operations such as erosion and dilation for noise removal

Detect blobs (coins) using OpenCV’s SimpleBlobDetector

Display intermediate processing stages and final results using Matplotlib

## Concepts Used

Grayscale Conversion: Simplifies image data by reducing color information

Thresholding: Converts grayscale images into binary images for segmentation

Morphological Operations: Refine binary images to eliminate small noise and improve object boundaries

Blob Detection: Identifies circular, coin-like objects based on shape, size, and intensity patterns

Requirements

The project requires the following Python libraries: OpenCV, Matplotlib, and NumPy.


## Example Output

The program displays the following stages during execution:

Original image

Grayscale image

RGB channel split (R, G, B)

Thresholded binary image

Eroded and dilated images after morphological operations

Final output showing detected coins and their total count

## Learning Outcome

By completing this experiment, you will understand how morphological operators and blob detection techniques are applied for object segmentation, noise reduction, and shape-based object recognition in digital image processing.
