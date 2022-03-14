# Code with me: Image Segmentation

This repo contains a concrete examples to introduce you the process of image segmentation with the use of convolutional neural networks (CNNs). 

## The data

Imat dataset In this dataset, you are provided a large number of images and corresponding fashion/apparel segmentations. Images are named with a unique ImageId. You must segment and classify the images in the test set. The 2020 version of this dataset uses the same images as the 2019 version, however, the attributes have been relabeled and expanded.

This dataset contains images of people wearing a variety of clothing types in a variety of poses. It may have content that some consider sensitive. Please exercise discretion and maturity when working on the competition.


## Getting Started

### 1. Clone/download this repository
To have access to these files locally, you can clone the repo using the command:
`git clone git@github.com:Seynabou08/technovation-mtl.git`
or go to the *clone* tab on the right and *click download zip*:

<img width="408" alt="image" src="https://user-images.githubusercontent.com/12241848/158026975-dae8aa44-b551-4d96-95d2-e4003e1e0761.png">

Once the zip is downloaded you can use any zip extractors to extract the files.

### 2. Download imaterialist dataset 
You will need to add the training and test data set in your repository in the folder FOLDER_NAME  
Go to the following link to download the imaterialiast dataset: https://www.kaggle.com/c/18237/download-all 

### 3. Upload data on google drive
Upload your repo folder into google drive. It's a very big file (26GB) so it will take a while to be uploaded.

In order to access the data from your google collaboratory notebook, you will have to mount your google drive locally. Follow this documentation to properly mount your drive.
https://colab.research.google.com/notebooks/io.ipynb#scrollTo=c2W5A2px3doP

## Requirements
- Access to a google account and drive with space
- A kaggle account to download the dataset
- Lots of time and patience to train the model

## How To Run Colab Notebook
- Create a technovation directory in google drive.
- Copy content of ./technovation directory in  google drive's technovation directory.
- Execute technovation_notebook.ipynb section **Prepare Environment** to download kaggle dataset in your google drive(Note it might require more than 40GB of availabe disk space to succefully download it). 
- After downlading and unzipping the data the file structure should look like below:
![](file_structure.png)

## References
- https://www.analyticsvidhya.com/blog/2021/06/how-to-load-kaggle-datasets-directly-into-google-colab (Instructions on how to load kaggle data into google drive)
- https://www.kaggle.com/c/imaterialist-fashion-2019-FGVC6 (kaggle data used)
- https://github.com/IlliaOvcharenko/imaterialist-fashion-2019-FGVC6 (Original repo we based our colab)

