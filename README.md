# NVIDIA GPU drivers and CUDA toolkit installation instructions. (this installs cuda toolkit 11.8 and compatible CuDNN libraries to accelerate deep learning

# nvidia-gpu drivers (CUDA 11.8)

![image](https://github.com/ajeetkverma/nvidia-cuda11.8_cudnn/assets/33716142/8d357dc6-fb9a-4da8-ac1a-f73212472122)

```
wget https://developer.download.nvidia.com/compute/cuda/repos/ubuntu2004/x86_64/cuda-ubuntu2004.pin
sudo mv cuda-ubuntu2004.pin /etc/apt/preferences.d/cuda-repository-pin-600
wget https://developer.download.nvidia.com/compute/cuda/11.8.0/local_installers/cuda-repo-ubuntu2004-11-8-local_11.8.0-520.61.05-1_amd64.deb
sudo dpkg -i cuda-repo-ubuntu2004-11-8-local_11.8.0-520.61.05-1_amd64.deb
sudo cp /var/cuda-repo-ubuntu2004-11-8-local/cuda-*-keyring.gpg /usr/share/keyrings/
sudo apt-get update
sudo apt-get -y install cuda
```
# NVIDIA-CUDA

![image](https://github.com/ajeetkverma/nvidia-cuda11.8_cudnn/assets/33716142/da26bd55-9c53-450c-aebb-b2108e31a692)

# CuDNN

![image](https://github.com/ajeetkverma/nvidia-cuda11.8_cudnn/assets/33716142/d3d129d0-c20d-414e-901f-8b54b5466011)

# if it helps...

![image](https://github.com/ajeetkverma/nvidia-cuda11.8_cudnn/assets/33716142/8d69daf4-145d-4dae-b75c-42ed55d24be8)
