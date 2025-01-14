# Image-Processing
This repository offers a simple toolkit for exploring core image processing concepts in Python. Load images, adjust brightness, filter noise, detect edges, segment objects, and more. It’s perfect for students who want to learn step by step with OpenCV, NumPy, and scikit-image.

Image Processing Toolkit

A Python toolkit showcasing fundamental and advanced operations in image processing. It covers:
	1.	Acquisition & Representation
	•	Load images (BGR→RGB) and store copies for processing.
	2.	Brightness Adjustment
	•	Modify brightness via HSV conversion.
	3.	Sampling & Quantization
	•	Downsample spatial resolution and reduce intensity levels.
	4.	Resolution
	•	Demonstrate spatial and intensity-level resolution changes.
	5.	Interpolation
	•	Resize images (Nearest, Bilinear, Bicubic).
	6.	Point Processing
	•	Negative, Log, Gamma, Intensity Slicing, Bit-Plane, Linear transforms.
	7.	Spatial Filtering
	•	Gaussian, Weighted, Median, Bilateral, Laplacian Sharpening.
	8.	Histogram Operations
	•	Equalization, Matching, Contrast Stretching.
	9.	Segmentation
	•	Felzenszwalb, SLIC, Quickshift.
	10.	Edge Detection & Linking
	•	Roberts, Prewitt, Sobel, Canny, Marr-Hildreth, Thinning.
	11.	Thresholding
	•	Global, Adaptive (mean, gaussian), Otsu.
	12.	Connected Components
	•	Labels, stats, and colored output.
	13.	Morphological Filtering
	•	Erosion, Dilation, Opening, Closing.
	14.	Hough Transform
	•	Lines (Standard & Probabilistic) and Circles.

Installation

pip install opencv-python-headless numpy matplotlib scikit-image scipy

(Use opencv-python if GUI support is needed.)

Usage
	1.	Clone:

git clone https://github.com/yourusername/ImageProcessingToolkit.git
cd ImageProcessingToolkit


	2.	Import and Run:

from ImageProcessingToolkit import ImageProcessingToolkit
toolkit = ImageProcessingToolkit("path/to/image.jpg")
bright_image = toolkit.adjust_brightness(factor=1.5)
# etc.


	3.	Visualization:
Most methods include a visualize_results function to display images side by side.

Contributing
	•	Fork, create a branch, commit, push, and open a pull request.

License

Released under the MIT License.

For questions, contact me via GitHub Issues or email. Enjoy exploring image processing with this toolkit!
