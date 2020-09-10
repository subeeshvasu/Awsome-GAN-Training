# Awsome-GAN-Training
A curated list of resources related to training of GANs


**GAN Variants**

|Year|Conf|Code|Title|
|----|----|----|-----|
|2014|NIPS|[Pt+Tf](https://github.com/wiseodd/generative-models)|[Vanilla-GAN - Generative Adversarial Networks](https://arxiv.org/abs/1611.04076v2)|
|2017|ICCV|[Pt+Tf](https://github.com/wiseodd/generative-models)|[LS-GAN - Least Squares Generative Adversarial Networks](https://arxiv.org/abs/1611.04076v2)|
|2017|ICML|[Pt+Tf](https://github.com/wiseodd/generative-models)|[WGAN - Wasserstein GAN](https://arxiv.org/abs/1701.07875)|
|2017|NIPS|[Pt+Tf](https://github.com/wiseodd/generative-models)|[WGAN-GP - Improved Training of Wasserstein GANs](https://arxiv.org/abs/1704.00028)|
|2019|ICLR|[Pt](https://github.com/AlexiaJM/RelativisticGAN)|[The relativistic discriminator: a key element missing from standard gan](https://openreview.net/forum?id=S1erHoR5t7&noteId=S1erHoR5t7)|

**Normalization, Network Architecture**

|Year|Conf|Code|Title|
|----|----|----|-----|
|2017|CVPR|[Torch](https://github.com/phillipi/pix2pix),[Pt](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)|[PatchGAN - Image-to-Image Translation with Conditional Adversarial Nets](https://arxiv.org/abs/1611.07004)|
|2017|||[Megapixel Size Image Creation using Generative Adversarial Networks](https://arxiv.org/abs/1706.00082)|
|2018|ICLR|[Code](https://github.com/godisboy/SN-GAN)|[SN-GAN - Spectral Normalization for Generative Adversarial Networks](https://arxiv.org/abs/1802.05957)|
|2018|ICLR|[Code](https://github.com/tkarras/progressive_growing_of_gans)|[Progressive Growing of GANs for Improved Quality, Stability, and Variation](https://arxiv.org/abs/1710.10196)|
|2018|||[Efficient Super Resolution For Large-Scale Images Using Attentional GAN](https://arxiv.org/pdf/1812.04821.pdf)|
|2019|ICLR|[Code](https://github.com/ajbrock/BigGAN-PyTorch)|[BigGAN - Large Scale GAN Training for High Fidelity Natural Image Synthesis](https://arxiv.org/abs/1809.11096)|
|2020|CVPR||[A U-Net Based Discriminator for Generative Adversarial Networks](https://arxiv.org/abs/2002.12655)


**Performance analysis and comparisons**

+ 2016-NIPS - Improved Techniques for Training GANs. [[Paper]](https://papers.nips.cc/paper/6125-improved-techniques-for-training-gans)[[Code]](https://github.com/Sleepychord/ImprovedGAN-pytorch)

+ 2017-ICLR - Towards Principled Methods for Training Generative Adversarial Networks. [[Paper]](https://arxiv.org/abs/1701.04862)

+ 2017 - On the Effects of Batch and Weight Normalization in Generative Adversarial Networks. [[Paper]](https://arxiv.org/abs/1704.03971)

+ 2017 - Stabilizing Training of Generative Adversarial Networks through Regularization. [[Paper]](https://arxiv.org/abs/1705.09367)

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

+ [Instance Noise: A trick for stabilising GAN training](https://www.inference.vc/instance-noise-a-trick-for-stabilising-gan-training/)

**Other works**

+ 2019-CVPR - Label-Noise Robust Generative Adversarial Networks. [[Paper]](https://arxiv.org/abs/1811.11165)[[Code]](https://github.com/takuhirok/rGAN/)[[Project Page]](https://takuhirok.github.io/rGAN/)

+ 2020-CVPR - Noise Robust Generative Adversarial Networks. [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Kaneko_Noise_Robust_Generative_Adversarial_Networks_CVPR_2020_paper.pdf)

+ 2020 - A review on generative adversarial networks: Algorithms, theory, and applications. [[Paper]](https://arxiv.org/abs/2001.06937)

+ 2020 - Regularization Methods for Generative Adversarial Networks: An Overview of Recent Studies. [[Paper]](https://arxiv.org/pdf/2005.09165.pdf)


**Other Resources**

+ [really-awsome-gan](https://github.com/nightrome/really-awesome-gan)

+ [awesome-GAN](https://github.com/Faldict/awesome-GAN)

+ [awesome-GAN-papers](https://github.com/ChanChiChoi/awesome-GAN-papers)
