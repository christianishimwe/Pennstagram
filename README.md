# Pennstagram
**Overview**

In this project, I developed Pennstagram, a Java-based photo manipulation application designed to perform a variety of image processing tasks. The project involved implementing complex algorithms to manipulate and transform images efficiently.

**Features**


Image Rotation: Implemented algorithms to rotate images by any degree, ensuring minimal distortion and maintaining image quality.

Color Inversion: Developed functionality to invert image colors, creating a negative effect by reversing RGB values.

Grayscale Conversion: Added the ability to convert images to grayscale using weighted averaging of RGB components to mimic human perception of brightness.

Contrast Adjustment: Implemented contrast adjustment techniques to enhance image clarity and highlight features.

Palette Reduction: Reduced color palettes using quantization methods to limit the number of colors while preserving image integrity.

Blurring: Designed and applied convolutional kernels to achieve image blurring, smoothing transitions between colors and reducing noise.



**Implementation Details**


Data Structures: Utilized BufferedImage from the Java AWT library to store and manipulate pixel data efficiently, allowing direct access to image properties and pixel arrays.

Rotation Algorithm: Implemented a custom rotation algorithm using trigonometric functions to calculate new pixel positions, maintaining image quality by using bilinear interpolation for pixel value estimation.

Color Inversion and Grayscale: Applied direct manipulation of RGB values using loops and bitwise operations for fast color inversion and conversion to grayscale.

Contrast Adjustment: Used histogram equalization techniques to enhance contrast, dynamically redistributing pixel intensity values.

Palette Reduction: Implemented k-means clustering to group similar colors and reduce palette size while preserving image integrity.

Blurring: Employed a Gaussian blur algorithm using convolution with a Gaussian kernel, smoothing transitions between colors and reducing noise.

Libraries Used: Leveraged Java AWT and Swing for image manipulation and GUI components, providing a robust framework for handling images and user interaction.

**Impact**


This project honed my skills in Java programming, algorithm design, and image processing. It provided hands-on experience with implementing and optimizing complex algorithms, improving my ability to build efficient and effective software solutions.


**Conclusion**


Pennstagram showcases the power of algorithmic thinking and efficient coding practices in developing applications that require intensive data manipulation. It highlights the importance of understanding image processing techniques and optimizing for performance in software development.
