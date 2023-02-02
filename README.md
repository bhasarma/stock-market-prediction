# Stock Market Prediction

This repository contains the notebook, code and documentation related to this project **Stock Market Prediction**. Idea of this project is to continue my learning after two previous projects on [Predicting Term Deposit](https://github.com/bhasarma/mlcoursezoom-camp/tree/main/WK08-09-midterm-project)(tabular data) and [kitchenware classifier](https://github.com/bhasarma/kitchenware-classification-project) as part of the [Machine Learning Zoomcamp Course](https://github.com/bhasarma/mlcoursezoom-camp).

## Table of Contents:
1. Business Problem Description
2. About the Dataset
3. Approach to solve the problem
	3.1 EDA to understand dataset
	3.2 Model training
	3.3 Model Deployment in the cloud
4. About files and folders in this repo
5. Development System
6. How to reproduce this project
7. Conclusions
8. References

## 1. Business Problem Description

## 2. About the Dataset

## 3. Approach to solve the problem
### 3.1 EDA to understand dataset

### 3.2 Model training

### 3.3 Model Deployment in the cloud

## 4. About files in this repo

Below is a description of the key files:

|  File name |      Description       |
|:--------:|:-----------------------------------:|
|    **README.md**   |  The file you are reading now, meant for the user as an introduction to help navigating the project| 
|    **notebook.ipynb**   |  Jupyter notebook file where EDA, training models, parameter tuning etc. are done during development in Saturn Cloud|
|    **train.py**   |  python script converted from `notebook.ipynb` |

## 5. Development System

OS: Ubuntu 20.04.5 LTS<br>
Architecture: x86_64<br>
conda virtual environment for development<br>
pipenv for deployment<br>


## 6. How to reproduce this project

In order to reproduce this project, first of all, clone this repo in your local machine with the command:

```
git clone  https://github.com/bhasarma/stock-market-prediction.git
```

Now go inside the project directory with the command:

```
cd stock-market-prediction
```

### 6.1 Development
Development part i.e. till training the models in Jupyter notebook, finding the best model and saving it, is done in a conda environment. If you want to run the notebook localy, then you have to recreate the conda environment that I used for development. For this, you first have to install Anaconda on your system, if you have not done it already. 

**Installing Anaconda**
Install Anaconda by following these instructions in this [Anaconda](https://www.anaconda.com/products/distribution) page. This site automatically detects the operating system and suggest the correct package. Just download it into your local machine by simply clicking on **Download**. Once download is completed, go to the directory where bash (.sh file) installer is donwloaded.

```bash
bsarma@turing:~$ cd Downloads/
bsarma@turing:~/Downloads$ ls
Anaconda3-2022.10-Linux-x86_64.sh
```

Next, run the bash installer script (.sh script) to install Anaconda3:

```bash
bsarma@turing:~/Downloads$ bash Anaconda3-2022.10-Linux-x86_64.sh
```
Follow the instructions during installation.

Then, source the .bash-rc file to add Anaconda to your PATH:

```
$ cd ~
$ source .bashrc
```

To verify the installation is complete, open Python from the command line:

```
(base) bsarma@turing:~$ python
Python 3.9.13 (main, Aug 25 2022, 23:26:10) 
[GCC 11.2.0] :: Anaconda, Inc. on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 

```

If you see Python 3.9 from Anaconda listed, your installation is complete. To exit the Python REPL, type:

```
>>> exit()
```

## 7. Conclusions

## 8. References

1. https://github.com/alexeygrigorev/mlbookcamp-code/blob/master/course-zoomcamp/01-intro/06-environment.md
2. https://clouds.eos.ubc.ca/~phil/docs/problem_solving/01-Orientation/01.05-Installing-Anaconda-on-Linux.html
