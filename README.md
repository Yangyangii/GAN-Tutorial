# GANs Tutorial
Very simple implementation of GANs, DCGANs, CGANs, WGANs, and etc. with PyTorch for only MNIST.

You can run the code at Jupyter Notebook. And actually you can also run these codes by using Google Colab immediately!

## Requirements
>* python 3.6 (Anaconda)
>* pytorch 1.0.0 (updated from 0.4.0. If you want to use the previous version, then find previous commit.)

## Implementation List
### **GANs**
>* [Vanilla GAN](https://github.com/Yangyangii/GAN-Tutorial/blob/master/Notebooks/VanillaGAN.ipynb)
>* [Conditional GANs](https://github.com/Yangyangii/GAN-Tutorial/blob/master/Notebooks/Conditional-GAN.ipynb)
>* [DCGAN](https://github.com/Yangyangii/GAN-Tutorial/blob/master/Notebooks/DCGAN.ipynb)
>* [Wasserstain GAN](https://github.com/Yangyangii/GAN-Tutorial/blob/master/Notebooks/W-GAN.ipynb)
>* [WGAN-gp](https://github.com/Yangyangii/GAN-Tutorial/blob/master/Notebooks/WGAN-GP.ipynb)
>* [infoGAN](https://github.com/Yangyangii/GAN-Tutorial/blob/master/Notebooks/infoGAN.ipynb)

## Experimental Samples
- You can see the samples at ipynbs.
- After DCGAN, DCGAN with condition is a base model.
- Trained 30 epochs respectively.

### Vanilla GAN
![Vanilla GAN](/images/Vanilla-GAN.gif "Optional title")

### Conditional GAN
![Conditional GAN](/images/Conditional-GAN.gif "Optional title")

### DC GAN
![DCGAN](/images/Conditional-DCGAN.gif "Optional title")

### WGAN-gp
![WGAN-gp](/images/WGAN-gp.gif "Optional title")

### infoGAN w/ walking code 1
![infoGAN](/images/infoGAN_type1.jpg "Optional title")

### infoGAN w/ walking code 2
![infoGAN](/images/infoGAN_type2.jpg "Optional title")

## Colab
- [https://colab.research.google.com](https://colab.research.google.com)
- You can run it with GPU(K80) Runtime mode
- Training Vanilla GAN takes only 10 minutes.
![Colab](/images/colab-usage.JPG "Optional title")
