# pytorch distribution training examples and tips, fork from [link](https://github.com/yangkky/distributed_tutorial)

Currently works fine with 2 nodes, each of which equips double RTX3090.
More details:
```
pip list | grep torch
```
> torch                              1.10.0+cu113\
 torch-tb-profiler                  0.2.1\
 torchaudio                         0.10.0+cu113\
 torchfile                          0.1.0\
 torchnet                           0.0.4\
 torchvision                        0.11.1+cu113

```
nvcc -V
```
> nvcc: NVIDIA (R) Cuda compiler driver\
Copyright (c) 2005-2021 NVIDIA Corporation\
Built on Mon_May__3_19:15:13_PDT_2021\
Cuda compilation tools, release 11.3, V11.3.109\
Build cuda_11.3.r11.3/compiler.29920130_0