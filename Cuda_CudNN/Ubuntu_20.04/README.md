# Scrips

Install cuda, cudnn, nvidiaDriver  

Installer scripts tested on ubuntu20.04  
--Cuda 11.1.1 (run file) + cuDNN 8.0.5  
--Cuda 11.6.2 (deb file) + cuDNN 8.4.1  
--Cuda 11.8.0 (deb file) + cuDNN 8.8.1  
--Cuda 11.8.0 (deb file) + cuDNN 8.9.0  
--Cuda 11.8.0 (run file) + cuDNN 8.8.1  

--------------------

1: download cuda  
--use this link: https://developer.nvidia.com/cuda-toolkit-archive  
--or download link in scripts  
2: run "Cuda Installer" script  
3: Reboot the system to use CUDA and Nvidia driver  
4: Check the Nvidia driver in the terminal: "nvidia-smi"  

--------------------

5: download cuDNN from Nvidia website  
you need to have an account in Nvidia  
link: https://developer.nvidia.com/rdp/cudnn-download  
after login and checking "I Agree To the Terms of the cuDNN Software License Agreement" you can see the "Archived cuDNN Releases" link  
On this page, find "Download cuDNN ..., for CUDA ...."  
download this file: Local Installer for Ubuntu20.04 x86_64 (Deb)  
6: run "cuDNN Installer" script  
7: If you see the successful message, The test has been passed and you are ready to use CUDA and CUDNN  

