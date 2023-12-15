# Scrips

Build OpenCV from source  

opencv_dnn_4.5.0 tested on ubuntu 20.04  
opencv_dnn_4.6.0 tested on ubuntu 20.04  
opencv_dnn_4.7.0 tested on ubuntu 20.04  
opencv_dnn_4.7.0 tested on ubuntu 22.04  

--------------------
1: Determine your GPU CUDA architecture version (Compute Capability)  
Link: https://developer.nvidia.com/cuda-gpus  

2: Open the script and replace the "CUDA_ARCH_BIN=7.5" by your GPU Compute Capability  
Note: just replace 7.5 by you GPU Compute Capability  

3: If you want another version, you can change OpenCV and OpenCV_contrib  
Nore: both of OpenCV and OpenCV_contrib must have the same version.  
OpenCV link: https://github.com/opencv/opencv/tags  
OpenCV contrib link: https://github.com/opencv/opencv_contrib/tags  

4: move Script, Opencv and OpenCV contrib into home folder.  

5: Save script and run it  
