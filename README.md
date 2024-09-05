# WACV2018/TIP: Gabor Convolutional Networks

Official PyTorch implementation of Gabor CNN. 
But all the results in the paper are based on [Torch 7](https://github.com/bczhangbczhang/Gabor-Convolutional-Networks).
These two implementations are sharing the same infrastructure level code.

## Requirements
- PyTorch 1.1.0 (earlier versions are not supported)
- torchvision
关键：个人配置运行环境说明|：CUDA11.8, PyTorch 1.4.0, Torchvision 0.5.0, Python 3.6.2(3.6.0会出现问题)
  
## Install

```
git clone https://github.com/jxgu1016/Gabor_CNN_PyTorch
cd Gabor_CNN_PyTorch
sh install.sh
```

## Run MNIST demo

```
cd demo
python main.py --model gcn --gpu 0
```
