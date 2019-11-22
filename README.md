# GANs Tutorial
Very simple implementation of GANs, DCGANs, CGANs, WGANs, and etc. with PyTorch for various dataset (MNIST, CARS, CelebA).

You can run the code at Jupyter Notebook. And actually you can also run these codes by using Google Colab immediately (needed downloading some dataset)!

Sometimes ipynb files do not work in Github, please clone and run it in your server.

## Requirements
>* python 3.6 (Anaconda)
>* pytorch 1.0.0 (updated from 0.4.0. If you want to use the previous version, then find previous commit.)

## Implementation List
#### MNIST
>* [Vanilla GAN](https://github.com/Yangyangii/GAN-Tutorial/blob/master/MNIST/VanillaGAN.ipynb)
>* [Conditional GANs](https://github.com/Yangyangii/GAN-Tutorial/blob/master/MNIST/Conditional-GAN.ipynb)
>* [DCGAN](https://github.com/Yangyangii/GAN-Tutorial/blob/master/MNIST/DCGAN.ipynb)
>* [Wasserstain GAN](https://github.com/Yangyangii/GAN-Tutorial/blob/master/MNIST/W-GAN.ipynb)
>* [WGAN-gp](https://github.com/Yangyangii/GAN-Tutorial/blob/master/MNIST/WGAN-GP.ipynb)
>* [infoGAN](https://github.com/Yangyangii/GAN-Tutorial/blob/master/MNIST/infoGAN.ipynb)

#### CARS (Stanford dataset)
>* you can download the dataset from [https://ai.stanford.edu/~jkrause/cars/car_dataset.html](https://ai.stanford.edu/~jkrause/cars/car_dataset.html)
>* [DCGAN](https://github.com/Yangyangii/GAN-Tutorial/blob/master/CARS/DCGAN.ipynb)
>* But I think the dataset is small and needs preprocessing a lot.

#### CelebA (aligned dataset)
>* you can download the dataset from [http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)
>* [BEGAN](https://github.com/Yangyangii/GAN-Tutorial/blob/master/CelebA/BEGAN.ipynb)
>* [R1GAN](https://github.com/Yangyangii/GAN-Tutorial/blob/master/CelebA/R1GAN.ipynb)


## Experimental Results
- You can also see the samples at ipynbs.
- After DCGAN, DCGAN with condition is a base model.
- Trained 30 epochs respectively.

### Vanilla GAN
<img src="/images/Vanilla-GAN.gif" width="200" height="200" />

### Conditional GAN
<img src="/images/Conditional-GAN.gif" width="200" height="200" />

### DC GAN
<img src="/images/Conditional-DCGAN.gif" width="200" height="200" />

### WGAN-gp
<img src="/images/WGAN-gp.gif" width="200" height="200" />

### infoGAN w/ walking code 1
<img src="/images/infoGAN_type1.jpg" width="200" height="200" />

### infoGAN w/ walking code 2
<img src="/images/infoGAN_type2.jpg" width="200" height="200" />

### BEGAN random samples (20 epochs)
<img src="/images/BEGAN.jpg" width="400" height="400" />

### BEGAN interpolation
<img src="/images/interpolation.jpg" width="800" height="100" />

### GAN with R1 regularization random samples (20 epochs)
<img src="/images/R1GAN.jpg" width="400" height="400" />
<img src="/images/R1GAN-sample1.jpg" width="200" height="200" />

### GAN with R1 regularization interpolation
<img src="/images/R1GAN-interp.jpg" width="800" height="100" />

## Colab
- [https://colab.research.google.com](https://colab.research.google.com)
- You can run it with GPU(K80) Runtime mode
- Training Vanilla GAN takes only 10 minutes.
![Colab](/images/colab-usage.JPG "Optional title")
