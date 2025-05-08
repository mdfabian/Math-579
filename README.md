# MATH 579 Final Project README

**Fabian Perez**
**ID#: 014126448**

# Files and Dependancies

**Applications**
Jupyter Notebook

**Python Libraries**
numpy as np
pandas as pd
seaborn as sns
tensorflow as tf
matplotlib.pyplot as plt
tensorflow.keras.models import Model
tensorflow.keras.optimizers import Adam
sklearn.model_selection import train_test_split
sklearn.preprocessing import StandardScaler, LabelEncoder
sklearn.metrics import classification_report, confusion_matrix, accuracy_score
tensorflow.keras.layers import Dense, BatchNormalization, Activation, Input, Embedding, Flatten, Concatenate

**Python Dataset**
StarData.csv

**Code**
Fabian_Perez_Math_579_Final_Project.ipynb

**Project Summary**
This project executes a custom neural network to classify stars based on various astrophysical properties. Inspired by concepts from Andrej Karpathy’s video series, the model incorporates techniques such as embedding layers, batch normalization, and dense activations. The dataset, "StarData.csv", includes features that describe stars and their corresponding classes. The final model was trained, validated, and tested using standard ML practices, and benchmark results are included to evaluate performance. 

# Installations

All the Python libraries are included with Jupyter. Be sure to have StarData.csv in the same file location as Fabian_Perez_Math_579_Final_Project.ipynb.

# Instructions

Open terminal and execute the following command.

>jupyter notebook

Jupyter should now be open in the homepage. You may now import the Fabian_Perez_Math_579_Final_Project.ipynb file and execute the code by opening the file and selecting the **Run** button at the top of the page. 


