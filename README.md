# DS4002_Project3
Project 3 github repo for group 16

## Contents

A convolutional neural network running a binary classification whether a snake is venomous or nonvenomous based on images from 4 different North American species. The snakes images used to build the model are the diamondback, sidewinder, green snake, and gartner snake.

## Software and Platform 

The platforms used to run this project are Google Colab and Jupyter Notebook, with the following packages utilized: zipfile, os, ImageDataGenerator from tensorflow.keras.preprocessing.image, pandas, numpy, matplotlib.pyplot, tensorflow. The image data was downloaded from images.cv and manipulated into one snake.zip file with all four species of snake. The zipfile and os functions were used to read the zip file into the coding platforms. A GPU through UVA Rivanna systems was used with 56 gigabytes of storage, 1 core, and 2 hours of run time. 

## Map 

### DATA folder:
- snake_data.zip: zip file of all snake images divided into training and testing sets and classified as venomous or nonvenomous within each set
- Data_Appendix.pdf: The data appendix with all data sets and variables explained.

### SCRIPTS
- 1_Preprocessing_and_EDA: 

