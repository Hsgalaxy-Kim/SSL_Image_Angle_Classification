# Class-Agnostic Self-Supervised Learning for Image Angle Classification
This is the official repository related to "Class-Agnostic Self-Supervised Learning for Image Angle Classification" (ICCAS 2023, Poster)

2023 23rd International Conference on Control, Automation and Systems (ICCAS): [Paper](https://ieeexplore.ieee.org/abstract/document/10317040)

<img src="https://github.com/user-attachments/assets/e392fb17-c689-4cf0-8b01-ae4c91e56621" alt="teaser" style="width:50%;">

## Abstract
The prediction of image angles is a crucial area of study for industrial automation. Despite the various studies conducted in computer vision, predicting image angles has received limited attention. One of the reasons for this lack of focus is that not all objects have clear directionality. For example, an image of a car wheel may have an ambiguous angle, making it infeasible to accurately predict the rotation angle. Therefore, objects with ambiguous angles can introduce noise during the training and testing of rotation angle prediction models. To tackle this issue, we propose a class-agnostic selfsupervised angle prediction learning framework that filters out images containing objects with ambiguous angles based on feature similarity. This approach involves two networks: the directionality categorization network, which identifies and eliminates images of undirectional objects, and the rotation categorization network, which learns from the filtered inputs to improve the accuracy of angle predictions. The experimental results using the STL-10 and CIFAR-100 datasets demonstrate that the proposed framework improves rotation angle classification accuracy without the need for rotation angle labels, which are often difficult to obtain in the literature.

For other libraries, please refer to 'requirements.txt'.
  ```
  pip install -r requirements.txt
  ```

## The code will be released soon.
