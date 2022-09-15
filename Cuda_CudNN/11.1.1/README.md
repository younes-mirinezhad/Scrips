# Scrips

Install cuda_11.1.1 , cudnn8_8.0.5.39-1 and nvidia driver  
This script tested on ubuntu20.04  

--------------------
1: download cuda cuda_11.1.1_455.32.00_linux  

link: https://developer.download.nvidia.com/compute/cuda/11.1.1/local_installers/cuda_11.1.1_455.32.00_linux.run  

--------------------
2: download cudnn8_8.0.5.39-1 from nvidia website  

you need to have an account in nvidia  
link: https://developer.nvidia.com/cudnn-download-survey  
after login and check "I Agree To the Terms of the cuDNN Software License Agreement" you can see "Archived cuDNN Releases" link  
in this page, find "Download cuDNN v8.0.5 (November 9th, 2020), for CUDA 11.1"  
download this 3 file  
cuDNN Runtime Library for Ubuntu20.04 x86_64 (Deb)  
cuDNN Developer Library for Ubuntu20.04 x86_64 (Deb)  
cuDNN Code Samples and User Guide for Ubuntu20.04 x86_64 (Deb)  

--------------------

3: run "1_Intall_CUDAToolkit" script  
4: run "2_Install_NvidiaDriver" script  
5: Reboot system to use nvidia driver  
6: Check nvidia-smi in terminal  
6: run "3_IntallAndTest_cuDNN" script  
7: If you see the successful message, The test has been passed and you are ready to use CUDA and CUDNN  

--------------------
