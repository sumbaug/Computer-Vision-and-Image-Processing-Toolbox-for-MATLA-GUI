# Computer-Vision-and-Image-Processing-Toolbox-for-MATLAB
![hello](https://user-images.githubusercontent.com/53453731/91340468-b3c2ef00-e79d-11ea-88fc-c2d3a3c36b4d.png)
* The primary purpose of the CVIPtools development environment is to allow students, faculty, researchers and all users to explore the power of computer processing of digital images.The original CVIPtools is a comprehensive GUI-based software which includes image analysis, enhancement, restoration and compression algorithms. It includes the CVIP-ATAT for algorithm development and analysis and the CVIP-FEPC for performing experiments with large groups of images and multiple combinations of feature extraction and pattern classification parameters. The CVIPlab for C/C++ programmers is a skeleton program that allows for access to all the CVIPtools library functions. The newest addition is the CVIP Toolbox for MATLAB, which also includes a CVIPlab skeleton program for exploration of the Toolbox which contains the Matlab versions of the CVIPtools library functions. a thresholded image, and the execution time of 
threshold operation.

* The Windows version of CVIPtools, developed at the [Computer Vision and Image Processing Laboratory] (https://www.siue.edu/engineering/ece/about/computer-vision-and-image-processing-lab.shtml) here at Southern Illinois University at Edwardsville, under the continuing direction of Dr. Scott E Umbaugh, is currently available for use with the textbook, Digital Image Processing and Analysis: Applications with Matlab and CVIPtools, Third Edition. CVIPtools 5.x is implemented in four layers: the algorithms code layer, the Common Object Module (COM) interface layer, the CvipOp layer, and the Graphical User Interface (GUI). The algorithms code layer is based primarily on previous versions of CVIPtools, consists of all image and data processing procedures and functions, and is written in standard C. The COM interface layer is written in C++ and links the CVIPtools C functions to the GUI through the CvipOp Class. The CvipOp layer, written in C#, provides an object-oriented paradigm to consolidate data safety and memory management. The GUI layer, written in C#, implements the image queue, viewer, and manages user input and output. For development, CVIPtools5.x includes the CVIPlab environment and the CVIPtools libraries. In addition to the standard C libraries, a dynamically linked library (cviptools.dll) is provided that contains all the COM versions of these functions. CVIPtools5.x also contains two powerful development tools that allow for batch processing and automatic algorithm analysis and development. The CVIP-ATAT, Algorithm Test and Analysis Tool, can be used to test all combinations and values of parameters to speed front-end algorithm development. The CVIP-FEPC, Feature Extraction and Pattern Classification, will allow for batch processing and test all combinations of features and pattern classification techniques. These are described in more detail, along with application examples, in the new edition of the textbook Digital Image Processing and Analysis: Applications with Matlab and CVIPtools, Third Edition.

* The previous version of the software, CVIPtools 4.x is also implemented in four layers: the algorithms code layer, the Common Object Module (COM) interface layer, the CVIPimage layer, and the Graphical User Interface (GUI). The algorithms code layer is based primarily on previous versions of CVIPtools, consists of all image and data processing procedures and functions, and is written in standard C. The COM interface layer is written in C++ and links the CVIPtools C functions to the GUI through the CVIPimage Class. The CVIPimage layer provides an object-oriented paradigm by using the Class CVIPimage to consolidate data safety and memory management. The GUI layer, written in Visual Basic, implements the image queue, viewer, and manages user input and output. For development, CVIPtools4.x includes the CVIPlab environment and the CVIPtools libraries. In addition to the standard C libraries, a dynamically linked library (cviptools.dll) is provided that contains all the COM versions of these functions.

* CVIPtools version 3.9 is a UNIX/Win32-based software package and is a collection of computer imaging tools providing services to the users at three layers. At the bottom level are the CVIPtools libraries (the application programming interface). Based on the CVIPtools libraries are the cviptcl and cvipwish shells. The cviptcl shell is an extension of Tcl with additional CVIP capabilities. With cviptcl, the user can either use the command line for interactive image processing, or write cviptcl shell scripts for batch processing. The cvipwish shell is the extension of cviptcl with the added functionality for building a graphical user interface (GUI). On the top of CVIPtools is the CVIPtools GUI (see screen snapshots) which allows even the casual computer users to experiment with many of the sophisticated tools available to computer imaging specialists without the need for any knowledge of computer programming.

* CVIPtools3.9 supports various flavors of UNIX as well as Windows NT/95/98/2000/Me. Version 3.7 is also available which supports more UNIX flavors. You can download the precompiled executables only (bin), executables and libraries (lib), or the source (src). All tar files include the documentation and installation programs.
