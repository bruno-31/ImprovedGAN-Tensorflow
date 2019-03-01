# ImprovedGAN-Tensorflow

This is a simple Tensorflow implementation of the Semi-Supervised GAN proposed in the paper Improved Techniques
for Training GANs from Salimans et al. https://arxiv.org/abs/1606.03498

The code reproduces the results presented in the original paper. It uses the same tricks than the original Theano implementation.

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

## Experiments

CIFAR(% errors) | 1000 labels | 4000 labels
-- | -- | --
Improved GAN (ours) | **20.24 +/- 2.17** |**17.34 +/- 1.97**

SVHN(% errors) | 400 labels | 1000 labels 
-- | -- | --
Improved GAN (ours) | **5.22 +/- 1.02**  | **4.12 +/- 1.23** 
