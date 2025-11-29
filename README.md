# Advanced-potato-Disease-detection
Potato Disease Detection Using deep learning

About Dataset:

This is the plant village potato disease Dataset
This Dataset is a comprehensive collection of images which is categorized into three distinct classes: early blight, late blight, and healthy.
Early blight of potato is caused by the fungus, Alternaria solani, which can cause disease in potato, tomato, other members of the potato family, and some mustards. This disease, also known as target spot, rarely affects young, vigorously growing plants.
Late blight caused by the fungus Phytophthora infestans is the most important disease of potato that can result into crop failures in a short period if appropriate control measures are not adopted.
Healthy potatoes: They're rich in vitamin C, which is an antioxidant and are life-saving food source in early times because the vitamin C prevented scurvy. Another major nutrient in potatoes is potassium, an electrolyte which aids in the workings of our heart, muscles, and nervous system.
Each class represents a specific condition affecting potato crops
With this rich dataset, we can explore various images of plant diseases.

Dataset Content:

There are Total 2152 number of Images in Dataset
The plant village contains 3 folders such as of Class Potato Early_blight, Potato Late_blight and Potato healthy
The Class Potato Early_blight consists of 1000 number of Images
The Class Potato Late_blight also consists of 1000 number of Images
The Potato Healthy consists of 152 number of Images

Aims and Objectives:

This is the plant village potato disease Dataset
The Aim to take this Dataset is to explore the plant diseases which belongs to the classes such as the Potato late_blight, Potato Early_blight and also the healthy poato plants
For this I firstly took the overview of the dataset in order to take a look how many number of images in each class has according to this dataset.
Then I display the images of each class in order to take the insights about the dataset.
Then I load and Finetune EfficientNetB3 and evlauate the results
Then I Generate the predictions based on that model

Dataset Link:

Dataset link: https://www.kaggle.com/datasets/aarishasifkhan/plantvillage-potato-disease-dataset/data

Exploratory Data Analysis (EDA):

- Class distribution bar plots
- Sample images grid per class
- Image size & aspect ratio distribution
- Pixel intensity summaries (detecting corrupted/blank images)
- Notes on label noise and possible corrections

 Evaluation Metrics:

Accuracy

Precision, Recall, F1-score (per-class and macro)
Confusion matrix
ROC-AUC (for multi-class use one-vs-rest)
Top-2 / Top-3 accuracy (helpful if classes visually similar)
Calibration plots (to validate confidence)

Citations & Acknowledgements:

PlantVillage dataset and contributors
Kaggle community notebooks that inspired architectures and augmentations
Papers: EfficientNet, ResNet, Vision Transformer (cite if used)


