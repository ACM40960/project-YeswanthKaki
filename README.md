# AI image recognition of sign language and sentiment analysis using NLP

To classify images of static letter hand posture using neural networks and thereby using a text classification model to analyse the emotions of handicapped people

[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](http://forthebadge.com)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

# Table of Contents

- [About the Project](#about-the-project)
- [Installation](#installation)
- [Custom Installation](#custom-installation)
- [Implementation](#implementation)
- [Example](#example)
- [Authors](#authors)

# About the Project

1) **Abstract**

     For persons who have hearing loss and trouble communicating, sign language is vital. Also, understanding the emotions from the sign language could be tricky. So, here, we employ machine learning techniques to build a computational platform that identify emotions from words that are extracted from images.

2) **Results**

- Plot of Training and Validation Accuracy of Sign Language Model.

     ![TestImage1](/Images/SignTrainingValAccuracy.jpeg)
 
- Accuracy of Sign Language Model.

     ![TestImage2](/Images/SignTrainingAccuracy.jpeg)
     
- Accuracy results of Natural Language Processing model.

     ![TestImage3](/Images/NLPTrainingAccuracy.PNG)

3) **Conclusion**

     We described a method for classifying images of alphabet sign language in real-time. This approach made advantage of a considerably larger dataset with 87000 rows that included every letter of the alphabet as well as three more classes like delete, nothing, and space. Due to this, there was a better generalization of the model. On our test dataset, the suggested MobileNet Architecture deep learning model performed with an accuracy of 98.83%. Our work also included concatenating the combination of letters that make up a word.

# Installation

1) **Install Python (Preferably Version>3.8.8)**
    Refer the [Installation Guide](https://docs.python.org/3/contents.html ) for more.

2) **Update pip**
    - Check if pip is already installed
    `pip help` (if pip is not recognised intsall pip using
    [Pip Documentation for windows](https://phoenixnap.com/kb/install-pip-windows)
    [Pip Documentation for macOs](https://phoenixnap.com/kb/install-pip-mac))

    - If pip is already installed use `pip install --upgrade` to update pip version.

3) **Install Jupyter Notebook**
     - Install the classic Jupyter Notebook with
       `pip install notebook`
     - To run the notebook
        `jupyter notebook`
    _(Note :  Can launch Jupyter from Anaconda)_

# Custom Installation

**Installing conda packages**

1) Go to conda package path
2) Open Python.exe
3) Run the following commands:
     - **Install text_hammer**
        `pip install text_hammer --user`
     - **Install text tranformers**
        `pip install transformers --user`
     - **Install open cv**
        `!pip install opencv-python`
     - **Install tensor flow**  (preferable version  > 2.6)
        `pip install tensor flow`
        note: If tensorflow is already available update tensor flow using the command `pip install --upgrade tensorflow --user`

**Install python packages**

1) Open command prompt
2) Move to python directory
3) Run the following commands
    - **Install en_core_web_sm**
        - go to the python path and execute command
        `py -m spacy download en_core_web_sm`

# Implementation

1) Save all the project_test data and the saved models in a common folder.
2) Unzip the project_test folder.
3) Open the Final_project_test.ipynp file to test the project.
4) The project_test folder contained three separate samples of test data.
5) Any sample can be tested by altering the path in accordance with the selected sample.

# Example

**Steps Involved**

1) A Sample test data of letters that combine to make up a word 'WORRY' is tested using the Final_project_test.ipynb file.
2) The letters of the word 'WORRY' are retrieved in a sequence and added to a empty list. 
3) Each letter is processed, predicted and appended to a empty string.
4) Now the resultant word's emotion is predicted using Emotion Predictor model.
5) For the 'WORRY' word the emotion predicted is 'fear'.
6) Similarly different samples of test data can be predicted.

# Authors

1) Reshma Ravindran - 21200391
2) Yeswanth Kaki - 21200266
