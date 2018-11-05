# Data Analysis for Google Play Store

![Goole Play Store](https://raw.githubusercontent.com/qiaochen/DataAnalysis4GooglePlayStore/master/appimage.jpg) 

Image Source:[link](https://icdn2.digitaltrends.com/image/play-store-720x720.jpg?ver=1.jpg)

## Motivation
Users download apps for various usage purposes. Given that paid service is usually better at offering pleasant experience, and that free apps are more accesible to everyone, what are the user opinions towards these apps?

More specifically, the following questions are of interest:

- How do the app ratings differ between paid and free apps in general?
- How are the differences distributed across different app categories?
- Are there any categories where the differences are statistically significant?

To expore answers to the above questions, I narrawed the context to Google Play Store and conducted data analysis on the Kaggle dataset [Google Play Store](https://www.kaggle.com/lava18/google-play-store-apps/home).

## Requirements
#### Required packages
```
numpy
pandas
scipy
```
#### Dataset
Download the dataset at Kaggle: [Google Play Store Apps](https://www.kaggle.com/lava18/google-play-store-apps/home).

Extract the data file `googleplaystore.csv` and put it in the project root.

#### Project Folder Structure
```
DataAnalysis4GooglePlayStore
                 |---- AnalyzeGoogleStoreApp.ipynb (The code file for data analysis)
                 |---- AnalyzeGoogleStoreApp.html  (Result of code execution)
                 |---- googleplaystore.csv         (data file)
                 |---- README.md                   (readme file)
```

#### Initial Findings
- In general, Paid apps are more highly-rated than free apps, which appears to support the argument that experience of the paid apps is better.
- In most categories, Paid apps achieve higher ratings than free apps, however, in a few categories such as COMMUNICATION, FINANCE and PHOTOGRAPHY, the average ratings of free apps are higher than those of paid apps. Is this because many popular apps in these categories are free, like facebook and whatsapp in the COMMUNICATION category?
- There are four categories (PERSONALIZATION, TOOLS, FAMILY and GAME) where paid apps are rated significantly higher than free apps.


## Acknowledgement
I would like to thank Google Play Store and Lavanya Gupta for offering the wonderful dataset.
