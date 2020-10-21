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
|2017|Arxiv||[Megapixel Size Image Creation using Generative Adversarial Networks](https://arxiv.org/abs/1706.00082)|
|2018|ICLR|[Pt](https://github.com/godisboy/SN-GAN)|[SN-GAN - Spectral Normalization for Generative Adversarial Networks](https://arxiv.org/abs/1802.05957)|
|2018|ICLR|[Tf+Theano](https://github.com/tkarras/progressive_growing_of_gans)|[Progressive Growing of GANs for Improved Quality, Stability, and Variation](https://arxiv.org/abs/1710.10196)|
|2018|Arxiv||[Efficient Super Resolution For Large-Scale Images Using Attentional GAN](https://arxiv.org/pdf/1812.04821.pdf)|
|2019|ICLR|[Pt](https://github.com/ajbrock/BigGAN-PyTorch)|[BigGAN - Large Scale GAN Training for High Fidelity Natural Image Synthesis](https://arxiv.org/abs/1809.11096)|
|2020|CVPR|[Pt](https://github.com/lucidrains/unet-stylegan2)|[A U-Net Based Discriminator for Generative Adversarial Networks](https://arxiv.org/abs/2002.12655)
|2020|CVPR|[Pt](https://github.com/lucidrains/stylegan2-pytorch)|[Analyzing and Improving the Image Quality of StyleGAN](https://arxiv.org/abs/1912.04958)

**Performance analysis and comparisons**

|Year|Conf|Code|Title|
|----|----|----|-----|
|2016|NIPS|[Pt](https://github.com/Sleepychord/ImprovedGAN-pytorch)|[Improved Techniques for Training GANs](https://papers.nips.cc/paper/6125-improved-techniques-for-training-gans)|
|2017|ICLR||[Towards Principled Methods for Training Generative Adversarial Networks](https://arxiv.org/abs/1701.04862)|
|2017|Arxiv||[On the Effects of Batch and Weight Normalization in Generative Adversarial Networks](https://arxiv.org/abs/1704.03971)|
|2017|Arxiv||[Stabilizing Training of Generative Adversarial Networks through Regularization](https://arxiv.org/abs/1705.09367)|
|2018|NIPS|[Tf](https://github.com/google/compare_gan)|[Are GANs Created Equal? A Large-Scale Study](https://arxiv.org/abs/1711.10337)|
|2018|NIPS|[Tf](https://github.com/google/compare_gan)|[Assessing Generative Models via Precision and Recall](https://arxiv.org/abs/1806.00035)|
|2019|ICML|[Tf](https://github.com/google/compare_gan)|[High-Fidelity Image Generation With Fewer Labels](https://arxiv.org/abs/1903.02271)|
|2019|ICML|[Tf](https://github.com/google/compare_gan)|[A Large-Scale Study on Regularization and Normalization in GANs](https://arxiv.org/pdf/1807.04720.pdf)|
|2020|Arxiv||[GANs with Variational Entropy Regularizers: Applications in Mitigating the Mode-Collapse Issue](https://arxiv.org/abs/2009.11921)|

**Misc**

|Year|Conf|Code|Title|
|----|----|----|-----|
|2019|CVPR|[Pt](https://github.com/takuhirok/rGAN/)|[Label-Noise Robust Generative Adversarial Networks](https://arxiv.org/abs/1811.11165)|
|2019|ICCV|[Pt](https://github.com/tamarott/SinGAN)|[Singan: Learning a generative model from a single natural image](https://arxiv.org/abs/1905.01164)|
|2020|Arxiv||[Training Generative Adversarial Networks with Limited Data](https://arxiv.org/abs/2006.06676)|
|2020|CVPR||[Noise Robust Generative Adversarial Networks](http://openaccess.thecvf.com/content_CVPR_2020/papers/Kaneko_Noise_Robust_Generative_Adversarial_Networks_CVPR_2020_paper.pdf)|
|2020|Arxiv||[A review on generative adversarial networks: Algorithms, theory, and applications](https://arxiv.org/abs/2001.06937)|
|2020|Arxiv||[Regularization Methods for Generative Adversarial Networks: An Overview of Recent Studies](https://arxiv.org/pdf/2005.09165.pdf)|
|2020|Arxiv|[Pt](https://github.com/tohinz/ConSinGAN)|[Improved techniques for training single-image gans](https://arxiv.org/abs/2003.11512)

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


**Other Resources**

+ [really-awsome-gan](https://github.com/nightrome/really-awesome-gan)

+ [awesome-GAN](https://github.com/Faldict/awesome-GAN)

+ [awesome-GAN-papers](https://github.com/ChanChiChoi/awesome-GAN-papers)
