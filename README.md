# Computer-Vision-and-Image-Processing-Toolbox-for-MATLA-

* threshols_lab.m
 The function performs the multiband thresholding of an input image.The user can select either Loop-based method or Vectorization method to perform the threshold operation. Vectorization method involves vectorized code, which looks like  a mathematical expressions and is easier to
understand. Also, it runs much faster than the non-vectorized code, i.e. 
loop-based code.  
The threshold function will compare the actual gray level of the input
image with the threshold value. If the gray-level value is greater than
the threshold value, then the gray level is set to WHITE, else to BLACK. 
This function assumes inputImage as of either 'double' or 'uint8' class.
The output arguments are a thresholded image, and the execution time of 
threshold operation.
