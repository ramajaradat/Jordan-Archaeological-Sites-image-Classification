# Jordan Archaeological Sites Pre-traind Image Classification 

## Overview 
Image classification in the context of Jordanian archaeological sites involves utilizing machine learning techniques to categorize images according to the specific archaeological
sites they depict. This task can aid in various applications such as tourism promotion, historical research, and cultural preservation.

The process typically involves collecting a dataset of images featuring different archaeological sites across Jordan, including famous landmarks like Petra, Jerash, and the wadi rum 
, among others. These images may vary in terms of lighting conditions, angles, and image quality, presenting a challenge for accurate classification.

Machine learning algorithms such as convolutional neural networks (CNNs) are commonly employed for image classification tasks due to their effectiveness in learning hierarchical features
from images. The dataset is divided into training, validation, and testing sets, and the CNN model is trained on the training data to learn the features that distinguish between different 
archaeological sites.

During training, the model adjusts its parameters to minimize the classification error, and the performance is evaluated using the validation set. 
Hyperparameter tuning and optimization techniques may be applied to enhance the model's accuracy and generalization ability.

Once trained, the model can be deployed to classify new images of Jordanian archaeological sites with high accuracy.
This classification can provide valuable insights for archaeological studies, tourism planning, and cultural heritage preservation efforts in Jordan. 
Additionally, the model can be integrated into various applications, such as mobile apps or websites, to offer users information about different archaeological sites as they explore Jordan's 
rich cultural landscape.



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
 <div style="display: flex; flex-direction: column; justify-content: space-between;">
  <img src="example/10.png" alt="Example  Image 1" width="300" height="250"/>
  <img src="example/1848e964b6aa16dbf91e5a011a32e847.png" alt="Example  Image 2" width="300" height="250"/>
  <img src="example/Screenshot_4.png" alt="Example  Image 5" width="300" height="250"/>
 </div>

<div style="display: flex; flex-direction: column; justify-content: space-between;">
  <img src="example/28.png" alt="Example  Image 3" width="300" height="250"/>
  <img src="example/2024-01-19 024910.png" alt="Example  Image 4" width="300" height="250"/>
  <img src="example/img38.png" alt="Example  Image 6" width="300" height="250"/>
</div>

### Models Evaluated
The following pre-trained models are evaluated in this project:
- **InceptionV3**
- **EfficientNet**
- **ResNet**
- **VGGNet**

## Inference with Hugging Face

Once the model is trained, you can utilize the power of Hugging Face for inference on new images of Jordanian archaeological sites. Hugging Face provides a user-friendly interface for deploying and utilizing pre-trained models, making it easy to integrate state-of-the-art natural language processing and computer vision capabilities into your projects.

### Using the Pre-trained Models

1. **Choose a Model**: Select a pre-trained model suitable for your task. Hugging Face offers a wide range of models fine-tuned on various datasets, including computer vision models for image classification, object detection, and more.

2. **Input Data**: Prepare your input data, in this case, images of Jordanian archaeological sites, ensuring they are in a compatible format and quality for the chosen model.

3. **Model Inference**: Utilize Hugging Face's inference capabilities to process the input images through the selected pre-trained model. This step will generate predictions or insights based on the model's understanding of the input data.
please follow this <a href="https://huggingface.co/spaces/trs/Image_Classification_with_pre-traind_Models">Image Classification for Archaeological Sites Interface</a>.
 <img src="example/Image Classification for Archaeological Sites Interface.png" alt="Image Classification for Archaeological Sites Interface" width="300" />

### Example Code Snippet

Here's a simple example code snippet demonstrating how to use the Hugging Face API for inference on images of Jordanian archaeological sites:

## Presentation
For more details, please refer to our presentation <a href="https://prezi.com/p/edit/rob86aji2seu/">here</a>

