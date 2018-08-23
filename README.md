# ImprovedGAN-Tensorflow

This is a Tensorflow implementation of semi-supervised learning GAN proposed in the paper Improved Techniques
for Training GANs from Salimans et al. https://arxiv.org/abs/1606.03498

The code reproduces the results presented in the original paper. It uses the same tricks which are used in the original implementation and gives better performance than existing reproductions available online.

## Requirements

The repo supports python 3.5 + tensorflow 1.5

## Run the Code

To reproduce our results on SVHN
```
python train_svhn.py
```

To reproduce our results on CIFAR-10
```
python train_cifar.py
```

## Results

Here is a comparison of different models using standard architectures on several datasets (SVHN and CIFAR-10):

CIFAR(% errors) | 4000 labels
Improved GAN (original)  | 18.63 +/- 2.32
Improved GAN (ours) | **16.37 +/- 0.42**| **17.34 +/- 1.97**
