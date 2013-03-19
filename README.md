Image Morphology
================

This code implements OpenCV based morphological image processing. The operations include erosion, dilation, opening and closing. It works on color images too. I have included a sample input image along with this project. There is a file called "CMakeLists.txt". This file will be used to build the project (if you have built OpenCV using cmake). If not, just use the .cpp file in your project and build it. To build using command line, follow the steps below to get it up and running:

	$ cmake .
	$ make
	$ ./main inputImage.jpg 

When you run the code, two windows will pop up; one for erosion/dilation and another for opening/closing. The instructions will be displayed on the terminal.