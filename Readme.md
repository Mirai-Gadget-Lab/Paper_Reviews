# DeepLearning Paper List
A list of papers that we reviewd.

## Contents
- [Data-Privacy](#Data-Privacy) 
- [Computer-Vision](#Computer-Vision)
  - [Self-Supervised-Learning](#Self-Supervised-Learning)
  - [ViewPoint-Estimation](#ViewPoint-Estimation)
  - [Image-Synthesis](#Image-Synthesis)

# Data-Privacy

Title | Contributions | Code | reviewer |
--- | --- | --- | --- |
Learn From Distributed Asynchronized GAN Without Sharing Medical Image Data(CVPR 2020)[[pdf]](https://arxiv.org/abs/2006.00080) | <ul><li> Prevent privacy violation using GAN | [code](https://github.com/tommy-qichang/AsynDGAN) | [Young Woo Nam](https://medium.com/analytics-vidhya/paper-review-asyndgan-train-deep-learning-without-sharing-medical-image-data-ac93b5592be4) |

# Computer-Vision
## Self-Supervised Learning

Title | Contributions | Code | reviewer |
--- | --- | --- | --- |
Diverse Image Generation via Self-Conditioned GANs(CVPR 2020)[[pdf]](https://arxiv.org/abs/2006.10728) | <ul><li> Self-Conditional GAN by clustering </il><li> Computing Dataset partition by clustering | [code](https://github.com/stevliu/self-conditioned-gan) | [Young Woo Nam](https://medium.com/analytics-vidhya/paper-review-diverse-image-generation-via-self-conditioned-gans-fa847f696e04) |
Reference-Based Sketch Image Colorization using Augmented-Self Reference and Dense Semantic Correspondence(CVPR 2020)[[pdf]](https://arxiv.org/abs/2005.05207) | <ul><li> Augmented-Self Reference Generation </il><li> Spatially Corresponding Feature Transfer module(for Attribute transfer) | Not implemented(2021/02/14) |[Young Woo Nam](https://medium.com/analytics-vidhya/paper-review-reference-based-sketch-image-colorization-using-augmented-self-reference-and-dense-4e646f811ff2)
DeshuffleGAN: A Self-Supervised GAN to Improve Structure Learning(IEEE 2020)[[pdf]](https://arxiv.org/abs/2006.08694) | <ul><li> Apply idea that solve Jigsaw puzzle to GAN | Not implemented(2021/02/14) | [Young Woo Nam](https://medium.com/analytics-vidhya/paper-review-deshufflegan-a-self-supervised-gan-to-improve-structure-learning-1d601f3d95f8) |

## ViewPoint-Estimation
Title | Contributions | Code | reviewer |
--- | --- | --- | --- |
Cylindrical Convolutional Networks for Joint Object Detection and Viewpoint Estimation(CVPR 2020)[[pdf]](https://arxiv.org/abs/2003.11303) | <ul><li> Extract the view-specific feature conditioned on the object viewpoint that encodes structural information at each viewpoint <il><li> Differentiable argmax operator called sinusoidal soft-argmax that can manage sinusoidal | [code](https://github.com/sunghunjoung/CCNs/) | [Young Woo Nam](https://medium.com/@yw_nam/paper-review-cylindrical-convolutional-networks-for-joint-object-detection-and-viewpoint-813acead4b2c)

## Image-Synthesis
Title | Contributions | Code | reviewer |
--- | --- | --- | --- |
ADGAN:Controllable Person Image Synthesis With Attribute-Decomposed GAN(CVPR 2020)[[pdf]](https://arxiv.org/pdf/2003.12267.pdf) | <ul><li> Cloth Transfer by Decomposed Component Encoder and Global Texture Encoder <il><li> Texture Style Transfer using Fusion module | [code](https://github.com/menyifang/ADGAN) | [Young Woo Nam](https://medium.com/analytics-vidhya/paper-review-adgan-controllable-person-image-synthesis-with-attribute-decomposed-gan-1c45bddbe00a)
