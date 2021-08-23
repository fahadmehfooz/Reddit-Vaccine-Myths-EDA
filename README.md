# Reddit-Vaccine-Myths-EDA

* Predicting myths related to vaccine.
* Dataset contains 1566 rows and 8 columns.
* Found out polarity and sensitivity of categorical columns.
* Built a corpus and removed the stopwords.

## Languages Used 
**Python Version:** 3.9.0

## Resources and Tools Used
**Tools:** Jupyter Notebook

**Packages:** Pandas, NumPy, sklearn, Matplotlib,spacy, textBlob and seaborn.

## Data Used
**Data Source**: https://www.kaggle.com/gpreda/reddit-vaccine-myths
Data contains both posts and comments.
Both posts and comments contains the following fields:

title - relevant for posts
score - relevant for posts - based on impact, number of comments
id - unique id for posts/comments
url - relevant for posts - url of post thread
commns_num - relevant for post - number of comments to this post
created - date of creation
body - relevant for posts/comments - text of the post or comment
timestamp - timestamp

## Data Wrangling 
* Plotting heatmap to find the correlation between continuous features.
* Plotting Pairplots, barplots and kdeplots for the features and scatterplots.

## Data Visualization
Some of the visualizations are shown here:

![alt text](https://github.com/fahadmehfooz/EDA-Modelling-On-Rain-In-Australia/blob/main/images/__results___36_2.png?raw=true)
![alt text](https://github.com/fahadmehfooz/EDA-Modelling-On-Rain-In-Australia/blob/main/images/__results___38_0.png)
![alt text](https://github.com/fahadmehfooz/EDA-Modelling-On-Rain-In-Australia/blob/main/images/__results___46_0.png)


