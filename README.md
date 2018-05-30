## FPGA Acceleration of Canny Edge Detection Algorithm

Implemented Canny Edge Detection Algorithm to detect wide range of edges in images. 
Steps:
* Apply Gaussian filter to smooth the image in order to remove the noise.(MATLAB)
* Find the intensity gradients of the image.(FPGA)
* Apply non-maximum suppression to get rid of spurious response to edge detection.(FPGA)
* Apply double threshold to determine potential edges. (FPGA)
* Detection of edges by suppressing all the other edges that are weak and not in vicinity of strong edges. 


### Directory Structure
**VHDL**   : VHDL code for hardware implementation of algorithm.<br />
**CPP**    : CPP code for software implementation of algorithm.<br />
**MATLAB** : MATLAB scripts to convert image to text and vice versa.
