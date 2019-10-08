# URECA - Deep Transfer Learning For Abnormality Detection

URECA stands for Undergraduate Research Experience on CAmpus (URECA). It is a 1 year research programme at Nanyang Technological University. I am honoured that my paper was selected to be published in the [4th International Conference on Crowd Science and Engineering (ICCSE 2019)](http://iccse2019.crowdscience.org/).

## Data Sources:
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- [Stanford Musculoskeletal Radiographs (MURA)  Dataset](https://stanfordmlgroup.github.io/competitions/mura/)

## Implementation of Research
- [DCGAN implementation (MNIST)](https://www.kaggle.com/joashjw/conditional-dcgan-cnn-using-32-images#GAN)
- [Evaluation of DCGAN on MNIST](https://github.com/Joash-JW/URECA/blob/master/transfer-learning-with-mobilenet.ipynb)
- [DCGAN implementation (MURA)](https://github.com/Joash-JW/URECA/blob/master/dcgan.ipynb)

## Results of Research (MNIST)
| Epochs | Transfer Learning Model | Data Size | Accuracy |
|:---:|:---:|:---:|:---:|
| $10$ | MobileNet | $320$ (32 of each class) | $80.94$% |
| $10$ | MobileNet | $32000$ (synthesized data) | **$91.88$**% |
| $10$ | MobileNet | $41680$ (full data) | $95.63$% |
