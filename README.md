# JudgeBookByCover
## Problem Statement: The goal is to determine if genre information can be learned based on the visual aspects of a cover created by the designer. 

### Solution:
To tackle this problem I used the concept of transfer learning and developed a Convolutional Neural Networks (CNN) based system for book cover genre classification
I used a pre-trained network on ImageNet. By pre-training VGG16 and ResNet50 models on a very large dataset such as ImageNet, its possible to take advantage of the learned features and transfer it to other applications.

#### Steps:
##### 1] WEb scrapping book cover images from Amazon.com

