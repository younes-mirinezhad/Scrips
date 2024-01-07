# Scrips

Build OpenCV from the source  

opencv_dnn_4.5.0 tested on Ubuntu 20.04  
opencv_dnn_4.6.0 tested on Ubuntu 20.04  
opencv_dnn_4.7.0 tested on Ubuntu 20.04  
opencv_dnn_4.7.0 tested on Ubuntu 22.04  
opencv_dnn_4.9.0 tested on Ubuntu 22.04  

--------------------
1: Determine your GPU CUDA architecture version (Compute Capability)  
Link: https://developer.nvidia.com/cuda-gpus  

2: Open the script and replace the "CUDA_ARCH_BIN=7.5" with your GPU Compute Capability  
Note: just replace 7.5 with your GPU Compute Capability  

3: If you want another version, you can change OpenCV and OpenCV_contrib  
Note: both OpenCV and OpenCV_contrib must have the same version.  
OpenCV link: https://github.com/opencv/opencv/tags  
OpenCV contrib link: https://github.com/opencv/opencv_contrib/tags  

4: move Script, Opencv, and OpenCV contrib into the home folder.  

5: Save the script and run it  
