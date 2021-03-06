# URECA - Deep Transfer Learning For Abnormality Detection
[![Last Commit](https://img.shields.io/github/last-commit/joash-jw/URECA)]() [![License: MIT](https://img.shields.io/github/license/joash-jw/URECA)](https://opensource.org/licenses/MIT)

URECA stands for Undergraduate Research Experience on CAmpus (URECA). It is a 1 year research programme at Nanyang Technological University. I am honoured that my paper was selected to be published in the [4th International Conference on Crowd Science and Engineering (ICCSE 2019)](http://iccse2019.crowdscience.org/). The link to the published paper can be found [here](https://dl.acm.org/doi/abs/10.1145/3371238.3371274).

## Data Sources:
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- [Stanford Musculoskeletal Radiographs (MURA)  Dataset](https://stanfordmlgroup.github.io/competitions/mura/)

## Implementation of Research
- [Conditional Deep Convolutional Generative Adversarial Network (DCGAN) Implementation (MNIST)](https://www.kaggle.com/joashjw/conditional-dcgan-cnn-using-32-images#GAN)
- [Evaluation of Conditional DCGAN on MNIST](https://github.com/Joash-JW/URECA/blob/master/transfer-learning-with-mobilenet.ipynb)
- [Conditional DCGAN implementation (MURA)](https://github.com/Joash-JW/URECA/blob/master/dcgan.ipynb)

## Results of Research (MNIST)
| Epochs | Transfer Learning Model | Data Size | Accuracy |
|:---:|:---:|:---:|:---:|
| 10 | MobileNet | 320 (32 of each class) | 80.94% |
| 10 | MobileNet | 32000 (synthesized data) | **91.88**% |
| 10 | MobileNet | 41680 (full data) | 95.63% |

## Sample Images Generated by the Conditional DCGAN
![Sample Images from Conditional DCGAN (MNIST)](https://github.com/Joash-JW/URECA/blob/master/__results___23_0.png)
![Sample Images from Conditional DCGAN (MURA)](https://github.com/Joash-JW/URECA/blob/master/__results___19_0.png)

## Acknowledgments
I would like to thank Soumith Chintala for his [notes on training a GAN](https://github.com/soumith/ganhacks), which greatly helped me in developing the GAN architectures I used for this research.
