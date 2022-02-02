# Facial-Emotion-Recognition

# 1. Introduction

The Indian education landscape has been undergoing rapid changes for the past 10 years owing to
the advancement of web-based learning services, specifically, eLearning platforms.
Global E-learning is estimated to witness an 8X over the next 5 years to reach USD 2B in 2021. India
is expected to grow with a CAGR of 44% crossing the 10M users mark in 2021. Although the market
is growing on a rapid scale, there are major challenges associated with digital learning when
compared with brick and mortar classrooms. One of many challenges is how to ensure quality
learning for students. Digital platforms might overpower physical classrooms in terms of content
quality but when it comes to understanding whether students are able to grasp the content in a live
class scenario is yet an open-end challenge.










## 2. Face Emotion Recognition Model

Facial expression recognition system is a computer-based technology and therefore, it uses algorithms to instantaneously detect faces, code facial expressions, and recognize emotional states. It does this by analyzing faces in images or video through computer powered cameras embedded in laptops, mobile phones, and digital signage systems, or cameras that are mounted onto computer screens. Facial analysis through computer powered cameras generally follows three steps:

**A. Face detection**

Locating faces in the scene, in an image or video footage.

**B. Facial Feature Detection**

Extracting information about facial features from detected faces. For example, detecting the shape of facial components or describing the texture of the skin in a facial area.

**C. Facial expression and emotion Classification**

Analyzing the movement of facial features and/or changes in the appearance of facial features and classifying this information into expression-interpretative categories such as facial muscle activations like smile or frown; emotion categories happiness or anger; attitude categories like (dis)liking or ambivalence


The Haar Casscade detects face and those faces are then cropped and convert to gray images. These  gray images further get converted into iamge aaray for processing. Out DNN is made up of 4 CNN blocks and 3 Dense block. Each block has Batch Normalization layer, CNN layer (3x3) kernel, activation Function layer (ReLU) and max pooling (2x2). Dataset which is used to train this DNN is FER 2013 dataset. It has images of all 7 class of emotion. 

Hyper-parameter that were used are epochs = 5-,batch_size = 32 and learning_rate = 0.001

![image](https://user-images.githubusercontent.com/77975029/152092140-1b3688eb-9bab-49d1-a63f-8a0454ae57c9.png)

## 2.3 Evaluation Metrics

**Loss and Accuracy Graph**

![image](https://user-images.githubusercontent.com/77975029/152092180-5a84a715-992d-4f2a-9c5f-0bd01a05374a.png)


**Classification Report**


![image](https://user-images.githubusercontent.com/77975029/152092218-83f098d1-a42f-4328-b793-127417422a08.png)




# 3. Conclusions 

Our model shows accuracy of 67% on validation set and 80% on train set. 

To access weblink please click on this link(Heroku): https://swaroop2310.herokuapp.com/



If unable to access, Clear the cache and reload the browser.


![image](https://user-images.githubusercontent.com/77975029/152092574-24954921-79e5-4510-8c78-04d6417c2275.png)
![image](https://user-images.githubusercontent.com/77975029/152092594-152b9dba-7b02-4aa5-868c-8875f0ceba76.png)


**Live face and emotion detection can be easily done with the help of our model.**



