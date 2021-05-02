# Neural Networks for Face Recognition

## Description

Based on artificial neural network and backpropagation algorithm to recognize the features of the face.

## Dataset

[face images](https://drive.google.com/file/d/1gmP7Hz0Cgmjd4QR7hYaUqZ8tngJg_2pG/view?usp=sharing)

The data set contains 20 subfolders, each folder contains 1 person, a total of 20 people.

The name of the picture contains the userid, sunglass, pose, expression, scale information.

## Usage

```shell
> cd project-path
> make
> ./facetrain
```


Need to be modified  **.list** the path of the picture in the file so that the program can read the input data correctly.

Enter a face picture, our ANN can mainly do 5 things：

* specfic-person-recognizer - Identify if he is a certain person.
* sunglass-recognizer - Identify if he has eyes.
* face-recognizer - Identify which of the 20 people he is.
* pose-recognizer - Recognize the orientation of his face.
* expression-recognizer - Recognize his expression.

of course，facetrain. The function does not stop there. It can also output a list of images that have failed classification, visualize hidden layer weights and so on.

facetrain Please refer to the specific usage doc/ysjai01.pdf，At the same time, this document also introduces my experiment process, experiment results and experience in detail.

## References

* [Neural Networks for Face Recognition](http://webpage.pace.edu/vs05672n/Neural_Networks_for_Face_Recognition.html)
* [Machine Learning](http://webpage.pace.edu/vs05672n/Machine_Learning_textbook.html), Tom Mitchell, McGraw Hill, 1997.
