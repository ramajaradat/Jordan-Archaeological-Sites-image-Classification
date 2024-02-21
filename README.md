# Jordan Coins Detection (Tracking & Counting)

## Overview 
Image classification in the context of Jordanian archaeological sites involves utilizing machine learning techniques to categorize images according to the specific archaeological sites they depict. 
This task can aid in various applications such as tourism promotion, historical research, and cultural preservation.

The process typically involves collecting a dataset of images featuring different archaeological sites across Jordan, including famous landmarks like Petra, Jerash, and the wadi rum , among others.
These images may vary in terms of lighting conditions, angles, and image quality, presenting a challenge for accurate classification.

Machine learning algorithms such as convolutional neural networks (CNNs) are commonly employed for image classification tasks due to their effectiveness in learning hierarchical features from images. 
The dataset is divided into training, validation, and testing sets, and the CNN model is trained on the training data to learn the features that distinguish between different archaeological sites.

During training, the model adjusts its parameters to minimize the classification error, and the performance is evaluated using the validation set. 
Hyperparameter tuning and optimization techniques may be applied to enhance the model's accuracy and generalization ability.

Once trained, the model can be deployed to classify new images of Jordanian archaeological sites with high accuracy.
This classification can provide valuable insights for archaeological studies, tourism planning, and cultural heritage preservation efforts in Jordan. 
Additionally, the model can be integrated into various applications, such as mobile apps or websites, to offer users information about different archaeological sites as they explore Jordan's rich cultural landscape.



## Dataset:
The dataset for this project was created by collecting images of Jordanian archaeological sites from various website sources. [dataset](https://drive.google.com/drive/folders/1ty_T_iXx35HAuSkEgbXiOlwoLjH75jLC?usp=sharing)


### Data Collection:

The dataset consists of images with the following 9 classes:

- Petra
- Wadi_Rum
- Umm_Qais
- Roman amphitheater
- Jeresh
- Ajloun Castle


### Models Evaluated
The following pre-trained models are evaluated in this project:

-InceptionV3
-EfficientNet
-ResNet
-VGGNet
