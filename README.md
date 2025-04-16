# DefocusMatch
## environment
```
conda create -n DefocusMatch python==3.9
conda activate DefocusMatch
conda install nvidia/label/cuda-11.8.0::cuda
wget https://download.pytorch.org/whl/cu118/torch-2.6.0%2Bcu118-cp39-cp39-linux_x86_64.whl#sha256=68d455d5094c0fae420c7f757e6000383f08ac3d8469d0fc11a5e1f8f8c07a54
pip install torch-2.6-xxxx
wget https://github.com/state-spaces/mamba/releases/download/v2.2.4/mamba_ssm-2.2.4+cu11torch2.6cxx11abiTRUE-cp39-cp39-linux_x86_64.whl
pip install mamba_ssm-xxxx
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install h5py
pip install matplotlib
pip install kornia
pip install opencv-python
pip install tensorboard
