# Scrips

Install cuda, cudnn, nvidiaDriver  

Installer scripts tested on ubuntu22.04  
--Cuda 11.7.1 (deb file) + cuDNN 8.5.0  
--Cuda 11.8.0 (deb file) + cuDNN 8.8.1  
--Cuda 11.8.0 (deb file) + cuDNN 8.9.0  
--Cuda 11.8.0 (deb file) + cuDNN 8.9.2  
--Cuda 12.1.1 (deb file) + cuDNN 8.9.7  

--------------------

1: download cuda  
--use this link: https://developer.nvidia.com/cuda-toolkit-archive  
--or download link in scripts  
2: run "Cuda Installer" script  
3: Reboot the system to use CUDA and Nvidia driver  
4: Check the Nvidia driver in the terminal: "nvidia-smi"  

--------------------

5: download cuDNN from Nvidia website  
you need to have an account with Nvidia  
link: https://developer.nvidia.com/rdp/cudnn-download  
after login and checking "I Agree To the Terms of the cuDNN Software License Agreement" you can see the "Archived cuDNN Releases" link  
On this page, find "Download cuDNN ..., for CUDA ...."  
download this file: Local Installer for Ubuntu22.04 x86_64 (Deb)  
6: run the "cuDNN Installer" script  
7: If you see the successful message, The test has been passed and you are ready to use CUDA and CUDNN  

