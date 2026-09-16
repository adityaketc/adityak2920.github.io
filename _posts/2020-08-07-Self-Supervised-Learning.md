---
title: 'Self Supervised Learning'
date: 2020-08-07
permalink: /posts/2019/08/selfsupervised/
tags:
  - self-supervised
  - unsupervised
  - computer vision
---

## What is Self Supervised Learning ?
   Self Supervised Learning(SSL) is a method to train neural networks in which we don't require any extra labels, we take labels from the input data itself. It's not a very new concept, we are using SSL in NLP from quite some time to train language models, in which we train our model to predict next word of a sentence given a word. It's proved to give accuracies a large boost in NLP tasks beacuse it's observed that a model which learns the nature or the way to generate nature language, can be fine tuned for any task.

## SSL in Computer Vision
  In computer vision, it's not being used frequently beacuse we became satisfied or dependent on Imagenet pretrained weights and nowadays also on COCO for detection and segmentation tasks. But in medical domain, these weights don't proved to be very ground breaking, it improved results a little bit but not to a large margin and the same time in these domains, there is not much data available right now. So, for these SSL proved to be a very good option. 
  
  In SSL, there are mainly two types of tasks:-
  
   1. Pretext Tasks: The tasks which we use for pretraining our network are pretext tasks.
   2. Downstream Tasks: The tasks which we use for fine-tuning our network are downstream tasks.

The pretext tasks can be [Colorization](https://arxiv.org/abs/1603.08511), [Inpainting](https://arxiv.org/abs/1604.07379), [Placing image pathches in the right place](https://arxiv.org/abs/1603.09246), [Classify Corrupted Images](https://zpascal.net/cvpr2018/Jenni_Self-Supervised_Feature_Learning_CVPR_2018_paper.pdf), etc.

 One thing we should be taken into account is that the pretext task should be choosen such that it should give an understanding of data and so that it makes easier to solve downstream task. It's suggested that we should not be spending too much time in deciding pretext task, we should build an easy and fast task. After that spending time in finetuning through downstream task to check whether it's working or not.
 
## Unsupervised Data Augmentation and Consistency Loss
   In July 2019 a paper from google came to show, how we can use data augmentation on unlabeled data to improve accuracy. 
   Now, In this paper they proposed a method for training called Unsupervised Data Augmentation. In this method they are using
![](https://raw.githubusercontent.com/adityaketc/aiblog/master/images/USDA.png "Unsupervised Data Augmentation")
both labelled and unlabelled data for training with a loss function combining both the loss functions from data. One loss function function is computed from labelled data by supervised learning methods and the other loss is computed from consistency training by enforcing a model to predict similar predictions from augmented and unaugmented unlabelled data. The same model is used for computing both the loss function. The loss which we are getting from unlablled data is called Consistency Loss or Noise Contrastive Estimation. From statistical point, it is basically distance between two prediction distribution. The pretext tasks messes with data in different ways through augmentation but we always want that the prediction with original and messed should be same and the intermediate representation should also be consistent, otherwise it will affect our predictions. At final, we add both the loss functions to train beacuse it penalizes our model for getting different prediction for differnt version of the same data.


## Credits
I wrote this blog after reading Jeremy Howard blog on Self Supervised learning just to improve my writing skills and to learn concepts in a better fashion.

   Links:
   1. [Jeremy Howard Blog](https://www.fast.ai/2020/01/13/self_supervised/)                                                   
   2. [Unsupervised Data Augmentation](https://ai.googleblog.com/2019/07/advancing-semi-supervised-learning-with.html)



