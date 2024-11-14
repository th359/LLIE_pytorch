# LLIE_pytorch

## Get started
```
git clone https://github.com/th359/LLIE_pytorch.git
cd LLIE_pytorch
mkdir result
cd result
mkdir Enhance
```
Download the [LOL dataset](https://drive.google.com/file/d/157bjO1_cFuSd0HWDUuAmcHRJDVyWpOxB/view) and place it in the desired location, replacing th following in [train_enhancement.py](train_enhancement.py) with the path to the dataset.
```
TRAIN_DATA_IP = 'data/LOLdataset/our485/low'
TRAIN_DATA_TARGET = 'data/LOLdataset/our485/high'
VALID_DATA_IP = 'data/LOLdataset/eval15/low'
VALID_DATA_TARGET = 'data/LOLdataset/eval15/high'
SAVE_DIR = 'result/Enhance'
LOG_DIR = 'result/Enhance'
FIXED_IP_PATH = 'data/LOLdataset/our485/low/100.png'
FIXED_IP_TARGET = 'data/LOLdataset/our485/high/100.png'
FIXED_IP1_PATH = 'data/LOLdataset/eval15/low/111.png'
```
## Training
```
python train_enhancement.py
```
