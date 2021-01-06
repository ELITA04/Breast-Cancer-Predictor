# Breast Cancer Prediction
> Predicts whether the type of breast cancer is Malignant or Benign

![Issues](https://img.shields.io/github/issues/srimani-programmer/Breast-Cancer-Predictor)
![Pull Requests](https://img.shields.io/github/issues-pr/srimani-programmer/Breast-Cancer-Predictor)
![Forks](https://img.shields.io/github/forks/srimani-programmer/Breast-Cancer-Predictor)
![Stars](https://img.shields.io/github/stars/srimani-programmer/Breast-Cancer-Predictor)
[![License](https://img.shields.io/github/license/srimani-programmer/Breast-Cancer-Predictor)](https://github.com/srimani-programmer/Breast-Cancer-Predictor/blob/master/LICENSE)

## :round_pushpin: Please follow the [Code of Conduct](https://github.com/srimani-programmer/Breast-Cancer-Predictor/blob/master/CODE_OF_CONDUCT.md) for contributing in this repository
# Aim of the Project
#### :dart: To predict if a breast cancer is Malignant or Benign using Image Dataset as well as Numerical Data
#### :dart: Apply ML and DL Models to predict the severity of the Breast-Cancer
#### :dart: Create a Wonderful UI for this project using Front End Languages and Frameworks (Like Bootstrap)
#### :dart: Create the Backend using Flask Framework.
#### :dart: Deploy on Cloud and make this wonderful project available to public


## :clipboard: Table of contents
* [About Project](#about-project)
* [Languages or Frameworks Used](#languages-or-frameworks-used)
* [Setup](#project-setup)
* [How To Contribute ?](https://github.com/M-PRERNA/Breast-Cancer-Predictor/blob/master/Contribution-Guide.md)
* [Application UI](#Application-ui)

## About Project:

Breast cancer is the most common type of cancer in women. When cancers are found early, they can often be cured. 
There are some devices that detect the breast cancer but many times they lead to false positives, which results 
is patients undergoing painful, expensive surgeries that were not even necessary. These type of cancers are called 
**benign** which do not require surgeries and we can reduce these unnecessary surgeries by using Machine Learning. 
I have taken the dataset of the previous breast cancer patients and train the model to predict whether the cancer is **benign** or **malignant**. These predictions will help doctors to do surgeries only when the cancer is malignant, thus reducing the unnecessary surgeries for woman. 

For building the project I have used Wisconsin Breast cancer data which has 569 rows of which 357 are benign and 212 are malignant. 
The data is prepossessed and scaled. I have trained with Random forest Classifier gives best accuracy of 95.0%. To provide the easy to use interface to doctors I have developed a website that will take the data and display the output with accuracy and time taken to predict.


## Languages or Frameworks Used 

  * Python: language
  * NumPy: library for numerical calculations
  * Pandas: library for data manipulation and analysis
  * SkLearn: library which features various classification, regression and clustering algorithms
  * Flask: microframework for building web applications using Python.
  
  <img src="https://github.com/M-PRERNA/Breast-Cancer-Predictor/blob/master/static/images/python-icon.png" width=100 height=100> <img src="https://github.com/M-PRERNA/Breast-Cancer-Predictor/blob/master/static/images/numpy-icon.png" width=100 height=100> <img src="https://github.com/M-PRERNA/Breast-Cancer-Predictor/blob/master/static/images/pandas-icon.png" width=100 height=100> <img src="https://github.com/M-PRERNA/Breast-Cancer-Predictor/blob/master/static/images/sklearn-icon.png" width=100 height=100>  <img src="https://github.com/M-PRERNA/Breast-Cancer-Predictor/blob/master/static/images/flask-icon.png" width=100 height=100>
  
## Project Setup
  
  * First Clone the repository.
  * Create the virtual environment for the project. 
  ```sh
  $ conda create -n myenv python=3.6
  ```
  * Install the required packages using requirements.txt inside the environemnt using pip.
  ```sh
  $ pip install -r requirements.txt
  ```
  * run the app.py as `python app.py`
  * Web Application will be hosted at  `127.0.0.1:5000`
  * Enter the URL in the browser Application will be hosted.
  * Enter the details of the tumor to detect the type of the cancer with more than 95% accuracy.

<div align="center">
<h1>Application UI</h1>
</div>

<div align="center">
<p>Home Page</p>
</div>

<img src="static/images/homepage1.png" width="1200" height="600">

<div align="center">
<p>Tumor Data form</p>
</div>

<div align=""center>
<img src="static/images/HomePage2.png" width="1200" height="600">
</div>

<div align="center">
<p>Tumor Data form</p>
</div>

<img src="static/images/homepage3.png" width="1200" height="600">

<div align="center">
<p>Prediction Output</p>
</div>

<img src="static/images/predict.png" width="1200" height="600">

## Awesome contributors :star_struck:
<a href="https://github.com/srimani-programmer/Breast-Cancer-Predictor/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=srimani-programmer/Breast-Cancer-Predictor" />
</a>

Made with [contributors-img](https://contributors-img.web.app).
