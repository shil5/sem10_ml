# Assignment 2: 
## _Logistic Regression_ 

Shilpa Soni (2017IMSST008)

## Setting up workspace
As my data and other files are in the D: drive, I opened my Jupyter notebook in the D: Drive by running the following command in Anaconda Prompt:
```cmd
jupyter notebook --notebook-dir=D:
```
http://localhost:8889/tree opens up. (Since it is locally hosted, it helps if the data is big, unlike Google Colab.) 

## Dataset description
The UNSW-NB15 data set description:  Data set has nine families of attacks, namely, Fuzzers, Analysis, Backdoors, DoS, Exploits, Generic, Reconnaissance, Shellcode and Worms. The total number of records is stored in the  CSV file, namely, UNSW-NB15_2.csv
##### ✨Features:
1(A).....47(AU) different features
48 column(AV): The name of each attack category. In this data set , nine categories e.g. Fuzzers, Analysis, Backdoo..
49 column(AW) : 0 for normal and 1 for attack records.

## Problem Statement
Apply Logistic Regression algorithm to categories different attacks and calculate confusion matrix. Also prepare a  report to compare with different features. Like result when you consider  47 features Vs 40 features Vs 35 Features.

```python
import numpy as np
import pandas as pd
```
