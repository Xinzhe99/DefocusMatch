# DefocusMatch
## environment
```
conda create -n defocusmatch python=3.10
conda activate defocusmatch
conda install cudatoolkit==11.8 -c nvidia
pip install torch==2.1.1 torchvision==0.16.1 torchaudio==2.1.1 --index-url https://download.pytorch.org/whl/cu118
conda install -c "nvidia/label/cuda-11.8.0" cuda-nvcc
conda install packaging
pip install h5py matplotlib kornia opencv-python tensorboard
