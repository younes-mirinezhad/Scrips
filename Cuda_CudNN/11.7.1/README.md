# Scrips

Install cuda_11.7.1 and nvidia driver  
This script tested on ubuntu20.04  

--------------------
1: download cuda-repo-ubuntu2004-11-7-local_11.7.1-515.65.01-1_amd64.deb  

link: https://developer.download.nvidia.com/compute/cuda/11.7.1/local_installers/cuda-repo-ubuntu2004-11-7-local_11.7.1-515.65.01-1_amd64.deb

--------------------
2: cuDNN not published for CUDA_11.7  
note: if you need cuDNN, you can use libcudnn8=8.4.1.50-1+cuda11.6  

--------------------

3: run "1_Intall_CUDAToolkit" script  
4: Reboot system to use nvidia driver  
6: Check nvidia-smi in terminal  

--------------------
