# MIAT
## Install
Pytorch
```
$ pip install torch torchvision
```

## CIFAR-10
Training:
```
$ python train_cifar10.py --stage 1 --resume
```
Natural & White-Box Tests:
```
$ python test_cifar10_white_box.py
```
Black-Box Test:
```
$ python test_cifar10_black_box.py
```

## CIFAR-100
Training:
```
$ python train_cifar100.py --stage 1 --resume
```
Natural & White-Box Tests:
```
$ python test_cifar100_white_box.py
```
Black-Box Test:
```
$ python test_cifar100_black_box.py
```
