# Scrips

Install cuda_11.6.2 , cudnn8_8.4.1.50_1.0-1 and nvidia driver  
This script tested on ubuntu20.04  

--------------------
1: download cuda-repo-ubuntu2004-11-6-local_11.6.2-510.47.03-1_amd64.deb  

wget https://developer.download.nvidia.com/compute/cuda/11.6.2/local_installers/cuda-repo-ubuntu2004-11-6-local_11.6.2-510.47.03-1_amd64.deb  

--------------------
2: download cudnn8_8.4.1.50_1.0-1 from nvidia website  

you need to have an account in nvidia  
link: https://developer.nvidia.com/cudnn-download-survey  
after login and check "I Agree To the Terms of the cuDNN Software License Agreement" you can see "Archived cuDNN Releases" link  
in this page, find "Download cuDNN v8.4.1 (May 27th, 2022), for CUDA 11.x"  
download this file: Local Installer for Ubuntu20.04 x86_64 (Deb)  

--------------------

3: run "1_Intall_CUDAToolkit" script  
4: Reboot system to use CUDA and nvidia driver  
5: Check nvidia-smi in terminal  
6: run "2_IntallAndTest_cuDNN" script  
7: If you see the successful message, The test has been passed and you are ready to use CUDA and CUDNN  

--------------------
