# **Age, Gender, and Emotion classification with Images using Deep Learning**

As a part of the Final project for EEL6825 - Pattern Recognition an Intelligent Systems.   
Note: This project is best implemented on Google Colab.

## Code Files

This repository includes three python notebooks: [Age Classification Model, Age Regression Model](https://github.com/AkashKK25/AGE-Age-Gender-and-Emotion-Classification/blob/master/Age%20Model.ipynb), [Gender Classification Model](https://github.com/AkashKK25/AGE-Age-Gender-and-Emotion-Classification/blob/master/Gender%20Model.ipynb) and [Emotion Classification Model](https://github.com/AkashKK25/AGE-Age-Gender-and-Emotion-Classification/blob/master/Emotion%20Model.ipynb).

## Code Implementation
For Age Classification and Regression Models, the dataset is provided for download within the python notebook.   
**For Training**: Run all the cells in the same order in Google Colab.   
**For Testing**: Have the all the [model files](https://drive.google.com/drive/folders/1UPqaEISu-gM7yVbnow942-vymhFQ965b?usp=sharing)([AgeClassification.h5](https://drive.google.com/drive/folders/1UPqaEISu-gM7yVbnow942-vymhFQ965b?usp=sharing) and [AgeRegressionModel](https://drive.google.com/drive/folders/1UPqaEISu-gM7yVbnow942-vymhFQ965b?usp=sharing)) in the same location as the notebook and run all the in the same order except for the cells under "Training" subsection in the Notebook.   

For Gender Classification Model, the dataset is same as the one used for Age so the dataset is available to download within the notebook if running on Google Colab. If running on a local machine, install wget on your machine to be able to run the cells for downloading the datasets.   
**For Training**: Run all the cells in the notebook.   
**For Testing**: Have the model ([GenderClassificationModel.h5](https://drive.google.com/drive/folders/1UPqaEISu-gM7yVbnow942-vymhFQ965b?usp=sharing)) file in the same directory as the ipynb file. Run all the cells except the training block in the notebook.   

For Emotion classification, first download the dataset from [kaggle](https://www.kaggle.com/datasets/msambare/fer2013).   
PLace the file in the same directory as the ipynb and name the zipped folder as 'fer2013.zip'.   
**For Training**: Run all the cells in the notebook.   
**For Testing**: Have the model ([EmotionClassificationModel.h5](https://drive.google.com/drive/folders/1UPqaEISu-gM7yVbnow942-vymhFQ965b?usp=sharing)) file in the same directory as the ipynb file. Run all the cells except the training block in the notebook.   

The project demonstration can also be viewed in the following video:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/m19YnYMiZQc/0.jpg)](https://www.youtube.com/watch?v=m19YnYMiZQc)



## Library Requirements   

If running on Google Colab: No additional installations required.   
If running on a local machine: The code is implemented using Tensorflow. And install wget to be able to download the datasets within the notebook.
