\\DIP Task 3 & 4 – Image Enhancement Techniques

Overview
This project focuses on image enhancement methods used to improve the visual quality of digital images. Using Python and image processing libraries, the program applies multiple enhancement techniques to a color image and visually compares their effects.

Objectives
To read and display a color image
To enhance image contrast using histogram-based methods
To implement histogram equalization using both built-in and manual approaches
To apply contrast stretching for dynamic range improvement
To demonstrate point transformation techniques
To compare enhancement results visually

Tools & Libraries Used
Python
OpenCV (cv2)
NumPy
Matplotlib

Enhancement Techniques Implemented
1. Color Space Conversion (YCrCb)
The original color image is converted from RGB to YCrCb color space. Histogram equalization is applied only on the luminance (Y) channel to enhance brightness without distorting color information.

2. Histogram Equalization (Built-in)
OpenCV’s built-in histogram equalization function is applied to the Y channel to improve overall contrast.

3. Histogram Equalization (Manual Implementation)
Histogram equalization is manually implemented by:
Computing the image histogram
Calculating the cumulative distribution function (CDF)
Mapping original intensity values to equalized values
The equalized image and its histogram are displayed for analysis.

4. Contrast Stretching
Contrast stretching expands the range of intensity values to enhance image contrast and highlight details.

5. Point Transformation Techniques
Logarithmic Transformation
Enhances low-intensity pixel values, making dark regions more visible.
Gamma (Power-Law) Transformation

Adjusts image brightness based on gamma value:
γ < 1 enhances darker regions
γ > 1 enhances brighter regions

Results Visualization
All processed images are displayed using Matplotlib with appropriate titles, including:
Original image
Histogram equalized images
Contrast-stretched image
Log-transformed image
Gamma-transformed image
This allows easy visual comparison of enhancement techniques.

Applications
Image contrast improvement
Medical image enhancement
Satellite and aerial imaging
Computer vision preprocessing

Conclusion
This task demonstrates how various image enhancement techniques improve image quality. Histogram-based and point transformation methods each offer unique advantages, and selecting the right technique depends on the image characteristics and desired enhancement.