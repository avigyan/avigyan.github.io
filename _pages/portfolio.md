---
layout: archive
title: "Research"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

<!-- 
{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}
-->

### 1. Defect Detection and Localization in Industrial Products with Class Activation Mapping 
<p style="text-align: justify;">
In this project the goal is to detect the presence of any metallic defects and locate them in images of industrial products using Class Activation Mapping (CAM). CAM highlights the discriminative regions in an image that a Convolutional Neural Network (CNN) uses to predict a specific class. By visualizing the CAM for a particular object class, one can localize where that object is located in the image.
</p>
**Keywords:** Class Activation Mapping, Defect Detection, Localization, Computer Vision, Deep Learning, Keras  
**GitHub Repo:** [Link](https://github.com/avigyan/Defect-Detection-and-Localization-in-Industrial-Products-using-DL.git)  


### 2. Real-time hand gesture recognition with Deep Learning 
<p style="text-align: justify;">
This project achieves the aim of recognizing the hand gestures of a person in real-time from the video provided by a webcam and displays the gesture label on the input camera frame in real-time, along with the probability of the detected label being correct. A modified LeNet-5 architecture is used to classify the 9 hand gestures.
</p>
**Keywords:** Gesture Recognition, OpenCV, LeNet, Computer Vision, Deep Learning, Keras  
**GitHub Repo:** [Link](https://github.com/avigyan/Hand_gesture_recognition_realtime_using_Deep_Learning.git)  
**Paper:** [Link](https://ijiie.org/journals/ijiie_2019dec1003/)


### 3. Real-time Facial Emotion Recognition using Deep Learning
<p style="text-align: justify;">
This project uses a modified VGGnet architecture of deep learning and the fer2013 dataset.  Given the images from a real-time webcam video input, the goal is to categorize the emotion expressed on each face in each frame into six distinct classes:  angry, afraid, happy, sad, surprised, neutral.
</p>
**Keywords:** Emotion Recognition, Deep Learning, VGG Net, FER2013, Computer Vision, Keras  
**GitHub Repo:** [Link](https://github.com/avigyan/RealTime-FacialEmotionRecognition-from-Webcam-using-DeepLearning.git)  
**Paper:** [Link](https://www.ijiie.org/journals/ijiie_2019dec1001/)


### 4. Drowsiness Detection System Using Deep Learning
<p style="text-align: justify;">
Drivers drowsiness is the major problem that causes road accidents. The drivers' drowsiness state is estimated using the facial regions corresponding to the entire face. The algorithms employed for face detection are i) Viola Jones ii) DLib iii) Yolo V3. For the Classification and drowsiness detection, a CNN (Convolutional Neural Network) architecture is employed.
</p>
**Keywords:** Convolutional Neural Network (CNN), Drowsiness detection, Face Detection, Viola Jones algorithm, dlib, YoloV3, LeNet, DarkNet-53, Deep Learning, multi-modal analysis  
**Paper:** [Link](https://ieeexplore.ieee.org/abstract/document/9445132)


### 5. Eye Tumour Detection Using Deep Learning
<p style="text-align: justify;">
In this project a deep learning algorithm with modified LeNet architecture has been developed to detect eye tumors. Due to limited availability of eye tumor images, data augmentation techniques were used to increase the number of images for training.  For segmenting the circular boundary of the iris, Hough transform was used.
</p>
**Keywords:** Eye Tumor, Cancer, Deep Learning, CNN, LeNet, Hough Transform  
**Paper:** [Link](https://ieeexplore.ieee.org/abstract/document/9445172)
