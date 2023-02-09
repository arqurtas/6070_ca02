# CA02: Spam eMail Detection using Naive Bayes Classification Algorithm
____________________________________________________________
**About the Program**

The following program in summary reads through emails and detects wether the email classifies as a "Spam" or "Not Spam". 

In further detail 702 emails are divided in Spam and Not Spam Categories. Using Naive Bayes Classification algoryths and a test model of 260 emails the classication will be predicted and compared to the accuracy of the classifications that are already knowm.

**Data Needed**
![image](https://user-images.githubusercontent.com/123341543/217940676-8712f990-c8a7-49bd-a789-804019685a65.png)
- Download and extract the following files into a shared file with the .ipynb
These following files posted are also required in order to successfully run the codes, However it is important to note that all the files including the .ipynb should be in the same folder as it is more efficient to run the files on a relative path.

**Libraries Needed**
- import os
- import numpy as np
- from collections import Counter
- from sklearn.naive_bayes import GaussianNB 
- from sklearn.metrics import accuracy_score
- from sklearn.model_selection import train_test_split
