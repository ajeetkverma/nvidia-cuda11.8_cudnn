# NVIDIA GPU drivers and CUDA toolkit installation instructions. (this installs cuda toolkit 11.8 and compatible CuDNN libraries to accelerate deep learning

# nvidia-gpu drivers (CUDA 11.8)

![image](https://github.com/ajeetkverma/nvidia-cuda11.8_cudnn/assets/33716142/8d357dc6-fb9a-4da8-ac1a-f73212472122)

(Local file)
```
wget https://developer.download.nvidia.com/compute/cuda/repos/ubuntu2004/x86_64/cuda-ubuntu2004.pin
sudo mv cuda-ubuntu2004.pin /etc/apt/preferences.d/cuda-repository-pin-600
wget https://developer.download.nvidia.com/compute/cuda/11.8.0/local_installers/cuda-repo-ubuntu2004-11-8-local_11.8.0-520.61.05-1_amd64.deb
sudo dpkg -i cuda-repo-ubuntu2004-11-8-local_11.8.0-520.61.05-1_amd64.deb
sudo cp /var/cuda-repo-ubuntu2004-11-8-local/cuda-*-keyring.gpg /usr/share/keyrings/
sudo apt-get update
sudo apt-get -y install cuda
```
(Network file)

```
wget https://developer.download.nvidia.com/compute/cuda/repos/ubuntu2004/x86_64/cuda-keyring_1.0-1_all.deb
sudo dpkg -i cuda-keyring_1.0-1_all.deb
sudo apt-get update
sudo apt-get -y install cuda
```

![image](https://github.com/ajeetkverma/nvidia-cuda11.8_cudnn/assets/33716142/da26bd55-9c53-450c-aebb-b2108e31a692)
![image](https://github.com/ajeetkverma/nvidia-cuda11.8_cudnn/assets/33716142/d3d129d0-c20d-414e-901f-8b54b5466011)
# PyTorch-cuda-11.8

CUDA 11.8
```
1. conda install pytorch==2.2.2 torchvision==0.17.2 torchaudio==2.2.2 pytorch-cuda=11.8 -c pytorch -c nvidia
2. conda install pytorch==2.2.1 torchvision==0.17.1 torchaudio==2.2.1 pytorch-cuda=11.8 -c pytorch -c nvidia
3. conda install pytorch==2.2.0 torchvision==0.17.0 torchaudio==2.2.0 pytorch-cuda=11.8 -c pytorch -c nvidia
4. conda install pytorch==2.1.2 torchvision==0.16.2 torchaudio==2.1.2 pytorch-cuda=11.8 -c pytorch -c nvidia



1. pip install torch==2.2.2 torchvision==0.17.2 torchaudio==2.2.2 --index-url https://download.pytorch.org/whl/cu118
2. pip install torch==2.2.1 torchvision==0.17.1 torchaudio==2.2.1 --index-url https://download.pytorch.org/whl/cu118
3. pip install torch==2.2.0 torchvision==0.17.0 torchaudio==2.2.0 --index-url https://download.pytorch.org/whl/cu118
4. pip install torch==2.1.2 torchvision==0.16.2 torchaudio==2.1.2 --index-url https://download.pytorch.org/whl/cu118




```


# if it helps...

![image](https://github.com/ajeetkverma/nvidia-cuda11.8_cudnn/assets/33716142/8d69daf4-145d-4dae-b75c-42ed55d24be8)
