# Airline-On-Time-Arrivals
Binary classification for Airline arrival delay without using departure delay predictors

Python Notebook is available in the repository
and dataset can be downloaded from the link: https://transtats.bts.gov/DL_SelectFields.asp?Table_ID=236&DB_Short_Name=On-Time
Please download with Prezipped check box selected and Filter setting was
Filter Geography: All
Filter Year: 2017
Filter Month: January

This notebook was created for startupML challenge 2017

Please keep in mind that I only used 2-fold cross validation to save time. Best estimate is given my leave-one-out cross validation. Which uses all samples for training except one sample for validation and repeats for each sample. Unfortunately it is very expensive. Usually 10-fold cv is recommended. So as long as system and time allows go for as many folds as you can afford.

Author: Muaaz Bin Sarfaraz


```
project
│   README.md
│   file001.txt    
│
└───folder1
│   │   file011.txt
│   │   file012.txt
│   │
│   └───subfolder1
│       │   file111.txt
│       │   file112.txt
│       │   ...
│   
└───folder2
    │   file021.txt
    │   file022.txt
```
