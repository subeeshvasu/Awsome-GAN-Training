# Awsome-GAN-Training
A curated list of resources related to training of GANs


**GAN Variants**

+ 2014-NIPS - Vanilla-GAN - Generative Adversarial Networks. [[Paper]](https://arxiv.org/abs/1406.2661)[[Code]](https://github.com/wiseodd/generative-models)

+ 2017-ICCV - LS-GAN - Least Squares Generative Adversarial Networks. [[Paper]](https://arxiv.org/abs/1611.04076v2)[[Code]](https://github.com/wiseodd/generative-models)

+ 2017-ICML - WGAN - Wasserstein GAN. [[Paper]](https://arxiv.org/abs/1701.07875)[[Code]](https://github.com/wiseodd/generative-models)

+ 2017-NIPS - WGAN-GP - Improved Training of Wasserstein GANs. [[Paper]](https://arxiv.org/abs/1704.00028)[[Code]](https://github.com/wiseodd/generative-models)

+ 2019-ICLR - The relativistic discriminator: a key element missing from standard gan. [[Paper]](https://openreview.net/forum?id=S1erHoR5t7&noteId=S1erHoR5t7) [[Code]](https://github.com/AlexiaJM/RelativisticGAN)

**Normalization, Network Architecture**

+ 2017-CVPR - PatchGAN - Image-to-Image Translation with Conditional Adversarial Nets. [[Paper]](https://arxiv.org/abs/1611.07004)[[Code]](https://github.com/phillipi/pix2pix)

+ 2018-ICLR - SN-GAN - Spectral Normalization for Generative Adversarial Networks. [[Paper]](https://arxiv.org/abs/1802.05957)[[Code]](https://github.com/godisboy/SN-GAN)

+ 2018-ICLR - Progressive Growing of GANs for Improved Quality, Stability, and Variation. [[Paper]](https://arxiv.org/abs/1710.10196)[[Code]](https://github.com/tkarras/progressive_growing_of_gans) 
  - To generate images of high resolution (1024 x 1024).

+ 2019-ICLR - BigGAN - Large Scale GAN Training for High Fidelity Natural Image Synthesis. [[Paper]](https://arxiv.org/abs/1809.11096)[[Code]](https://github.com/ajbrock/BigGAN-PyTorch)


**Performance analysis and comparisons**

+ 2016-NIPS - Improved Techniques for Training GANs. [[Paper]](https://papers.nips.cc/paper/6125-improved-techniques-for-training-gans)[[Code]](https://github.com/Sleepychord/ImprovedGAN-pytorch)

+ 2017-ICLR - Towards Principled Methods for Training Generative Adversarial Networks. [[Paper]](https://arxiv.org/abs/1701.04862)

+ 2018-NIPS - Are GANs Created Equal? A Large-Scale Study. [[Paper]](https://arxiv.org/abs/1711.10337)[[Code]](https://github.com/google/compare_gan)

+ 2018-NIPS - Assessing Generative Models via Precision and Recall. [[Paper]](https://arxiv.org/abs/1806.00035)[[Code]](https://github.com/google/compare_gan)

+ 2019-ICML - High-Fidelity Image Generation With Fewer Labels. [[Paper]](https://arxiv.org/abs/1903.02271)[[Code]](https://github.com/google/compare_gan)

+ 2019-ICML - A Large-Scale Study on Regularization and Normalization in GANs. [[Paper]](https://arxiv.org/pdf/1807.04720.pdf)[[Code]](https://github.com/google/compare_gan)

**Hacks**

+ [ganhacks](https://github.com/soumith/ganhacks)

+ 2016 - Deconvolution and Checkerboard Artifacts. [Link](https://distill.pub/2016/deconv-checkerboard/)

+ 2018-ECCVW - ESRGAN: Enhanced Super-Resolution Generative Adversarial Networks. [[Paper]](https://arxiv.org/pdf/1809.00219.pdf) 
  - First work to apply relativistic discriminator for image super-resolution. 
  - Batch normalization (BN) can generate artifacts when the generator goes deeper or there is an extra BN layer in HR (high-resolution) space.
  
+ [Tips for Training Stable GANs](https://machinelearningmastery.com/how-to-train-stable-generative-adversarial-networks/)

+ [Getting Started With GANs](https://machinelearningmastery.com/resources-for-getting-started-with-generative-adversarial-networks/)

+ [How generative adversarial networks and their variants work: An overview](https://arxiv.org/abs/1711.05914v9)

**Other works**

+ 2019-CVPR - Label-Noise Robust Generative Adversarial Networks. [[Paper]](https://arxiv.org/abs/1811.11165)[[Code]](https://github.com/takuhirok/rGAN/)[[Project Page]](https://takuhirok.github.io/rGAN/)


**Other Resources**

