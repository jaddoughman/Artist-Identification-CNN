# Artist Identification From Paintings Using Convolutional Neural Network (CNN

## Introduction

Artist Identification is a very interesting topic that is constantly being explored due to how intricate things can get regarding paintings. Painting forgery has been an issue that museums and artists deal with, and is a major issue. Usually, they refer to an expert whose dedicated their life to this issue (from painting restoration, maintenance, and identification of fake paintings). However, the problem is even after the expert carefully inspects the painting there still is a high chance of them misclassifying the painting due to how hard it is to tell. Therefore, people decided to solve this using computers (similar to the expert), but they aren't able to recreate some of the methods (X-ray, chemical analysis, etc...). Therefore, other methods had to be created in order to make this a "computer problem". After exploring papers and looking at other's work, we ran into some issues. One issue was feature engineering, where we had to decide if were gonna create features and choose which features were gonna help us train our model. The problem here is first that creating tabular data for our model required some domain knowledge; however, we just had to research more and we found some features. Another issue was that we couldn't find a good dataset that included fake paintings and real ones so that we could tackle this issue, but this would be good for future work. Hence, we decided to tackle the problem of painter identification from paintings; Our aim is to facilitate this task through the use of Convolutional Neural Networks (CNN) through Residual Networks (ResNet). 


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



