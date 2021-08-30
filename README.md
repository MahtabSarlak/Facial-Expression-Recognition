# Facial-Expression-Recognition
This is the final project of Computer vision course fall 2020. 
## Description
We implemented two deep learning models for facial expression recognition (FER) using FER2013 dataset for recognizing 6 emotion of (Anger ,Disgust, Fear, Happy, Sad, 
Surprise, Neutral).
### Preprocessing
We applied multiple preprocessing technique before spliting data and training models.
* Apply noise reduction
* Augmentation
* Edge detection

### First Model(paper model)
This model is based on the CNN introduced in paper, [Deep-Emotion](https://arxiv.org/abs/1902.01019)
* Architecture

<p align="center">
  <img src="imgs/result1.PNG" width="960" title="Deep-Emotion Architecture">
</p>

* Result

| Training Accuracy  | Validation Accuracy | Test Accuracy |
| ------------- | ------------- | ------------- |
| 87% | 67%  | 58% |


### Second Model(miniVGG)
This model is modified version of VGG.
* Architecture

<p align="center">
  <img src="imgs/result2.PNG" width="960" title="Deep-Emotion Architecture">
</p>

* Result


| Training Accuracy  | Validation Accuracy | Test Accuracy |
| ------------- | ------------- | ------------- |
| 75% | 61%  | 61% |
