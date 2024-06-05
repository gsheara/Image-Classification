# Image-Classification
As both the accuracy of neural networks and their prominence in popular perception rapidly increase, many people may be familiar with interfacing with neural networks such as chatbots without even knowing it. Understanding the algorithms behind and how to conscruct a neural network model has many practical technological applications, one such being image classification. 

The purpose of this notebook is to create an image classification algorithm for the CIFAR-10 dataset, which includes images of ten distinct animals and objects.

# Description
The data for this project was analyzed using logistic regression and a neural network to try and correctly classify 10 different types of images. Ultimately, neither the regression nor the neural network model performed particularly well, both with an accuracy of about 40-50%. However, this does show at least a significant accuracy above if the model were just randomly guessing, which would be an accuracy of about 1 in 10. Isolating different classes into pairs may lead to a higher accuracy classification system. 

# Requirements
This project utilizes the dataset linked above, Google Colab as a Python IDE, and a few common Python libraries for math and data visualization (numpy, seaborn, scikitlearn). All tools and data used are free and open-source.

# Data
This data was found on kaggle, an online platform for open source data. However, as part of the keras datasets, the data was imported directly using the keras libarary in Python.

A link to the dataset can be found here: https://www.kaggle.com/datasets/fedesoriano/cifar100 

# Data processing
The data was first reshaped and normalized and then divided into a train/test split so that it could be used in a logistic regression analysis. Then, a neural network model was built and 8 iterations of 8 epochs were run. The highest-performing iteration was evaluated and visualized using a confusion matrix and a heatmap.

# Authors
This project and corresponding repository was created by Genny Sheara for an assignment in DATA 3320: Data Methodologies at Seattle University. LinkedIn: https://www.linkedin.com/in/genny-sheara/ 

# License
All data and tools utilized for this project are open source and reproducible by anyone.
