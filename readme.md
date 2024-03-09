# SurSathi:Music Recommendation through Facial Emotion Recognition

This project aims to  create a music recommendation system that uses affective image content to amplify the personalization and emotional impact of music recommendation. Key elements involve deploying a deep learning model for analyzing images, formulating recommendation systems, and crafting an intuitive user interface for interactions based on images. The project will have limitations associated with computational resources and dataset constraints.


## Table of Contents
- [Dataset](#dataset)
- [Predictions](#predictions)
- [Refrences](#refrences)
# Dataset
## Emoset
It is a large-scale visual emotion dataset with rich attributes, named EmoSet. With 3.3 million images in total (EmoSet-3.3M), 118,102 of these images are carefully labeled with machines and human annotators (EmoSet-118K). EmoSet is labeled with 8 emotion categories (amusement, anger, awe, contentment, disgust, excitement, fear, and sadness) in Mikels' emotion model and 6 proposed emotion attributes (brightness, colorfulness, scene type, object class, facial expression, and human action). We believe EmoSet will bring some key insights and encourage further research in visual emotion analysis and understanding.


## AffectNet
 AffectNet, a new database of facial expressions in the wild, by collecting and annotating facial images. AffectNet contains more than 1M facial images collected from the Internet by querying three major search engines using 1250 emotion related keywords in six different languages. About half of the retrieved images (~440K) were manually annotated for the presence of seven discrete facial expressions (categorial model) and the intensity of valence and arousal (dimensional model). AffectNet is by far the largest database of facial expressions, valence, and arousal in the wild enabling research in automated facial expression recognition in two different emotion models.

# Predictions 
## On Emoset
The MobileNetV3Large-based model, trained on Emoset, achieved a final accuracy of approximately 68%. Below are the predictions on the test dataset, along with their corresponding confidence levels:
![Predictions](https://github.com/anmol-c03/Sursathi/blob/main/Images/Emoset/emoset_prediction.png)

## On AffectNet
The VGG16-based model, trained on Emoset, achieved a final accuracy of approximately 71%. Below are the predictions on the test dataset, along with their corresponding confidence levels:
![Predictions](https://github.com/anmol-c03/Sursathi/blob/main/Images/Finalized_AffectNet/plot_probablity.png)

# Refrences
![AffectNet](http://mohammadmahoor.com/affectnet/)

![Emoset](https://github.com/JingyuanYY/EmoSet)


