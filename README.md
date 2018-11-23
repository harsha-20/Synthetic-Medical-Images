# Synthetic Medical Images from Dual Generative Adversarial Networks

Code is split into two stages: a segmentation-mask-generating DCGAN, and an image-to-image translator using pix2pix.

Paper: https://arxiv.org/abs/1709.01872

SynthMed (Repository for GAN-produced synthetic medical images): https://synthmed.github.io/

# Pipeline

![Flowchart](/imgs/flowchart.png)

# Prerequisites
- Python 2 and 3
- numpy
- [TensorFlow](https://www.tensorflow.org/install/) 1.0+
- Keras
- Preprocessed dataset


# Acknowledgements

Stage-I GAN based on: https://github.com/carpedm20/DCGAN-tensorflow
<br></br>
Stage-II GAN based on: https://github.com/ray0809/pix2pix

Authors: [John Guibas](https://github.com/johnguibas), [Tejpal Virdi](https://github.com/tejpalv), [Peter Li](https://github.com/petersli)
