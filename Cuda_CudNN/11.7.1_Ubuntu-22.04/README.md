# Scrips

Install cuda_11.7.1 , cudnn8_8.5.0.96_1.0-1 and nvidia driver  
This script tested on ubuntu22.04  

--------------------
1: download cuda-repo-ubuntu2204-11-7-local_11.7.1-515.65.01-1_amd64.deb  

link: https://developer.download.nvidia.com/compute/cuda/11.7.1/local_installers/cuda-repo-ubuntu2204-11-7-local_11.7.1-515.65.01-1_amd64.deb  

--------------------
2: download cudnn8_8.5.0.96_1.0-1 from nvidia website  

you need to have an account in nvidia  
link: https://developer.nvidia.com/rdp/cudnn-download 
after login and check "I Agree To the Terms of the cuDNN Software License Agreement" you can see "Archived cuDNN Releases" link  
in this page, find "Download cuDNN v8.5.0 (August 8th, 2022), for CUDA 11.x"  
download this file: Local Installer for Ubuntu22.04 x86_64 (Deb)  

--------------------

3: run "1_Intall_CUDAToolkit" script  
4: Reboot system to use CUDA and nvidia driver  
5: Check nvidia-smi in terminal  
6: run "2_IntallAndTest_cuDNN" script  
7: If you see the successful message, The test has been passed and you are ready to use CUDA and CUDNN  

--------------------
