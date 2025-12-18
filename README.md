# D2Mamba: A Mamba-based Method for Floodway Obstructions Segmentation

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Framework: PyTorch](https://img.shields.io/badge/Framework-PyTorch-orange.svg)](https://pytorch.org/)
![Status: Under Review](https://img.shields.io/badge/Status-Under%20Review-blue)

This repository contains the official implementation and dataset samples for the paper:  
**"D2Mamba: A Mamba-based method for floodway obstructions segmentation from multispectral satellite imagery"**.


### 🛰️ Dataset

We constructed the **Multispectral Floodway Obstructions Dataset (MFOD)**, containing 8,301 high-resolution images.

> **Transparency Note:** We provide supplementary sample data via the Baidu Netdisk folder `MFOD_samples` ([link](https://pan.baidu.com/s/1uBZI8E5MuzKrzRqIv9oxsQ?pwd=tgvk), extraction code: `tgvk`).


### 🛠️ Environment

To reproduce the results, please set up the environment using the following dependencies.

```bash
# Basic requirements
python
torch
torchvision
torchaudio

# Mamba specific requirements (please refer to official mamba installation)
pip install "causal-conv1d==1.0.0"
pip install "mamba-ssm==1.0.1"

# Other dependencies
pip install -r requirements.txt
```

### 📧 Contact

For questions regarding the dataset or code, please contact the corresponding author.

---
