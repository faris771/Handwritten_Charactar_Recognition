# Handwritten Character Recognition using CNN

This project implements a Convolutional Neural Network (CNN) to classify handwritten characters with high accuracy. The model is trained on various tasks and showcases strong performance across diverse classification challenges.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Conclusion](#conclusion)
- [References](#references)

## Project Overview
Handwriting recognition, a **computer vision challenge**, involves identifying and converting handwritten text from documents or touchscreens into a machine-readable format. Various machine learning methods, including K-nearest neighbors, Support Vector Machines, transfer learning, and Convolutional Neural Networks (CNN), are explored for automatic handwritten recognition.
Each language's handwritten text exhibits diverse patterns influenced by factors such as age, background, and native language. Arabic script, with its semi-cursive style and right-to-left writing, presents additional challenges due to multiple character shapes based on position within a word. Consequently, recognizing Arabic script is more complex than in other languages.

This notebook implements **4 different CNN models** that classify the Arabic handwritten characters using  **AHCD dataset**.  
## Features
- Customized CNN architecture for high-accuracy recognition
- VGG-based architecture for complex feature extraction
- Transfer learning implementation for efficient model fine-tuning

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/faris771/Handwritten_Charactar_Recognition

## Run
In order to run the code you need to use Google Colab, and upload the zipped Dataset file, and run all the cells :)


## Conclusion

In summary, the customized model excelled in both Task #1 (96.40%) and Task #2 (98.10%), showcasing the effectiveness of its architecture and training strategy over 30 epochs. The VGG model achieved a commendable accuracy of 96.22% for Task #3, demonstrating its capability in capturing complex features. The transferred model, while slightly lower at 94.64% for Task #4, still exhibited strong performance after 30 epochs of fine-tuning. These results underscore the versatility of the models in handling diverse classification tasks, with considerations for architecture and training duration playing a pivotal role in their success.

## References
1. [Arabic Handwritten Character Recognition Using Convolutional Neural Networks](https://10.21203/rs.3.rs-3141935/v1)
2. [Classification of Russian Handwritten Letters on Kaggle](https://www.kaggle.com/code/bryanb/cnn-for-handwritten-letters-classification/notebook)

## Contributors
1. [Aseel Deek](https://github.com/aseeldeek)
2. [Faris Abu Farha](https://github.com/faris771)
