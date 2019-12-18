# CS4487_Project
Kaggle Image Challenge

CIFAR10 Resnet-18 modified implementation
- Replace initail 7 * 7 + maxpool with 3 * 3
- Add 0.5 dropout at fc

Parameters:
  Batch_size: 128
  Learning rate: [0,135] 0.1
                 [136,185] 0.001
                 [186,240] 0.0001
                 [241,250] 0.00001
  Optimizer: SGD, momentum=0.9, weight_decay=5e-4
  
Best accuracy: 0.93641
