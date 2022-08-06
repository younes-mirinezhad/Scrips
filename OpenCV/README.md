# Scrips

Build OpenCV from source  
This script tested on ubuntu20.04  

--------------------
1: Determine your GPU CUDA architecture version (Compute Capability)  
Link: https://developer.nvidia.com/cuda-gpus  

2: Open the script and replace the number of "CUDA_ARCH_BIN=8.6" by your GPU Compute Capability in line 75  
Note: just replace 7.5 by you GPU Compute Capability  

3: If you want another version, you can change OpenCV and OpenCV_contrib download link in line 52, 53, 56 and 57  
Nore: both of OpenCV and OpenCV_contrib must have the same version.  
OpenCV link: https://github.com/opencv/opencv/tags  
OpenCV contrib link: https://github.com/opencv/opencv_contrib/tags  

4: Save script and run it  
