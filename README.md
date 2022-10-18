# Project Name
> We will build a multiclass classification model using a custom convolutional neural network in TensorFlow to identify the presence of melanoma (type of a skin cancer). 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The dataset is of about 2357 images of skin cancer types
- The dataset contains the images of 9 skin cancer types
- Model without dropouts - The training dataset marks 62% accurancy and where as validation dataset at 52%
- Model with dropouts - The training dataset marks 46% accurancy and where as validation dataset at 50%
- seborrheic keratosis class has least number of samples
- pigmented benign keratosis has highest number of samples
- After recifying class imbalance and tunning the model
	- Accuracy increased from 46% to 93%

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow - version 2.9.2
- keras - version 2.9.0
- matplotlib - version 3.2.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@srikanth24y] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->