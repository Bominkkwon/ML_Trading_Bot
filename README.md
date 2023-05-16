# Machine Learning Trading Bot


## Table of Contents
* [Project title](#project-title)
* [Technologies](#technologies)
* [Overview](#overview)
* [Required Libraries](#required-library)
* [Methodology](#methodology)





## Overview

The project focuses on algorithmic trading and involves implementing a series of steps to establish a baseline performance, tune the trading algorithm, evaluate a new machine learning classifier, and create an evaluation report.

To establish a baseline performance, the provided code is executed in a Jupyter notebook. This includes importing an OHLCV (Open, High, Low, Close, Volume) dataset into a Pandas DataFrame. Trading signals are generated using short- and long-window SMA (Simple Moving Average) values. The data is then split into training and testing datasets.

The trading algorithm is implemented using the SVC (Support Vector Classifier) model from SKLearn's support vector machine learning method. The algorithm is trained on the training dataset and used to make predictions on the testing dataset. The classification report associated with the model's predictions is carefully examined.



