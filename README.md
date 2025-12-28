# Predicting-Colorectal-Cancer-using-ML-and-DL-Algorithms
The project includes Python-based data science approach using libraries like NumPy &amp; Matplotlib for data analysis, visualization &amp; prediction.

# Introduction
1. This type of cancer is the 2nd cause of deaths by cancer worldwide (1.93 million cases - https://www.who.int/news-room/fact-sheets/detail/cancer). CRC, or cancer of the large intestine, is the third most frequent cancer in the world, with an annual incidence of 1.2 million cases and a 50 % fatality rate, making it the fourth leading cause of cancer-related fatalities.
 
2. CRC has a high prevalence globally, & early detection & diagnosis of CRC can significantly  improve  patients  survival  rates.  Traditional  CRC  scanning  & detection  methods  was  often  invasive,  exhaustive,  time-consuming  &  was  more indulge to the errors.
 
3. Primary aim of this project is to predict & diagnose CRC at an early stage by implementing  a  comprehensive  structure  that  employs  CNNs,  that  includes  all critical steps from image acquisition through disease detection.

# Getting Started
I have tried to keep everything self containted in the notebook. So it should be ready to go.

# Prerequisites
Datasets are (so far) available in this git repository. However, if for some reason they are done, they can be retrieved in these repositories:

Histological samples: https://github.com/tampapath/lung_colon_image_set

# Contents
The  Histopathology  image  Dataset  was  split  into  three  sets:  Training, Validation, and Test. The output labels include Cancerous (Malignant) and Non-cancerous (Benign). The images were converted into grayscale and then were resized and resampled, as a part of data preprocessing, to enhance better classification accuracy. After splitting the preprocessed data into training and testing, the CNN based VGG-16 was fitted into the data and was implemented for 10 epochs. Further, Tensor flow lib was used for Model Testing to give predictions for new and unseen images.

# Technologies Used
Programming - Python

Platform - Google Colab

Data Handling - NumPy, OpenCV(cv2), os

Visualization - Matplotlib
Deep Learning - TensorFlow, Keras, Keras Layers(Conv2D, Dense)
Data Augmentation - ImageDataGenerator(TensorFlow)
Model Persistence - Model.save(), load_model()
Evaulation - Model.fit() with validation, model.evaluate()

# Author
Kumar Ratnesh - Initial work - (https://github.com/ratnesh27)

# License 
NA

# References
(1)D.    Alboaneen,    “Predicting    Colorectal    Cancer    Using    Machine  and  Deep Learning Algorithms: Challenges and Approaches,” MDPI Journal of Artificial
Intelligence,    vol.    7,    no.    2,    p.    74,    2024.    [Online].    Available: https://www.mdpi.com/2504-2289/7/2/74
 
(2)S. Mehta et al., “Advancements in Deep Learning for Colorectal Cancer Image    Analysis,”    ScienceDirect,    Computer    Methods    and    Programs    in Biomedicine,2023. https://www.sciencedirect.com/science/article/pii/S2665917423003124  [Online].
 
(3)A. Kumar et al., “Colorectal Cancer Detection  and Classification Using Deep   Learning   Techniques,”   ScienceDirect,   Journal   of   Biomedical Informatics,  https://www.sciencedirect.com/science/article/pii/
