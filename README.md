# Artist Identification From Paintings Using Convolutional Neural Network (CNN)

## Introduction

This project tackles the issue of artist identification from paintings. Our aim is to accurately identify the artist of a painting using transfer learning by training different Convolutional Neural Networks (CNNs) with varying Residual Networks (ResNet). We have acquired our dataset from the Kaggle competition "best-artworks-of-all-time". Our best network achieves significantly higher classification accuracy than prior work. Our results demonstrate that CNNs are a powerful tool for artist identification and that when asked to identify artists, they are able to learn a representation of painting style.


## Python Libraries

* [glob](https://docs.python.org/3/library/glob.html)
* [itertools](https://docs.python.org/3/library/itertools.html) 
* [matplotlib](https://docs.python.org/3/library/matplotlib.html) 
* [fastai](https://docs.python.org/3/library/fastai.html) 
* [pandas](https://docs.python.org/3/library/pandas.html) 
* [numpy](https://docs.python.org/3/library/numpy.html) 
* [collections](https://docs.python.org/3/library/collections.html) 

## Dataset Sample

![Dateset](https://i.ibb.co/kD8ZGqb/Image-Batch.png)

## Results 

![ResNet-34](https://i.ibb.co/jWCP9wW/Screen-Shot-2019-12-06-at-3-21-55-PM.png)
![ResNet-50](https://i.ibb.co/2FW0k3Z/Screen-Shot-2019-12-06-at-3-22-02-PM.png)
![ResNet-152](https://i.ibb.co/jgn8m9V/Screen-Shot-2019-12-06-at-3-22-08-PM.png)

## Confusion Matrix

![Matrix](https://i.ibb.co/thCYc9b/Screen-Shot-2019-12-06-at-3-22-21-PM.png)

## Top Losses ResNet-152

![TopLosses](https://i.ibb.co/d5DgMBk/Top-losses-Res-Net152.png)



