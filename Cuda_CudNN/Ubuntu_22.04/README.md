# Scrips

Install cuda, cudnn, nvidiaDriver and TensorRT  
This scripts tested on ubuntu22.04  
--Cuda 11.7.1 + cuDNN 8.5.0  
--Cuda 11.8.0 + cuDNN 8.8.1  
--Cuda 11.8.0 + cuDNN 8.9.0  

--------------------

1: download cuda  
2: run "Cuda Installer" script  
3: Reboot system to use CUDA and nvidia driver  
4: check nvidia driver in terminal : "nvidia-smi"  

--------------------

5: download cudnn from nvidia website  
you need to have an account in nvidia  
link: https://developer.nvidia.com/rdp/cudnn-download  
after login and check "I Agree To the Terms of the cuDNN Software License Agreement" you can see "Archived cuDNN Releases" link  
in this page, find "Download cuDNN ..., for CUDA ...."  
download this file: Local Installer for Ubuntu22.04 x86_64 (Deb)  
6: run "cuDNN Installer" script  
7: If you see the successful message, The test has been passed and you are ready to use CUDA and CUDNN  

--------------------

8: download TensorRT  
link: https://developer.nvidia.com/nvidia-tensorrt-8x-download  
after login and check "I Agree To the Terms of the NVIDIA TensorRT License Agreement" you can see TensorRT versions  
click on "TensorRT ..." and download "TensorRT ... for Ubuntu 22.04 and CUDA ... DEB local repo Package" and download this file  
9: run "TensorRT Installer" script  

