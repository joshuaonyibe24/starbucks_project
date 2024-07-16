## Starbucks Capstone Project for Udacity Nanodegree

This exploration is the final project challenge from the Data Scientist Nanodegree in Udacity. The dataset to be dealt with is simulated data on how customers make purchases and how their decisions might be affected by promotional offers of Starbucks. People in the simulation are provided with three different types of offers:

buy-one-get-one(BOGO)
discount
informational.
They produced various events, like receiving the offers, viewing the offers and possibly making purchases. Each person will have his or her own hidden traits on their purchasing patterns. The goal of this project is to identify groups of people that share similar purchasing patterns and if they are influenced by promotional offers.


## Getting Started
Please make sure you have a python 3.x version and the following packages installed, before you can launch the code:
import pandas 
import numpy 
import math
import json
%matplotlib inline
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import OneHotEncoder, StandardScaler
from sklearn.pipeline import Pipeline
from sklearn.compose import ColumnTransformer
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import classification_report
from sklearn.ensemble import RandomForestClassifier, GradientBoostingClassifier
