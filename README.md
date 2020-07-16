# Disaster Response Pipeline Project

## Table of Contents
1. [About the Project](#about)
2. [Installation](#installation)
3. [Author](#author)
5. [References](#ref)

<a name="about"></a>
# Project Overview
### Background
Whilst researching possible ideas for this project, the majority of simple use-cases for data science appeared to be focused around business problems such as financial forecasting, churn prediction or channel optimisation. However, as a data analyst already, this is my day job. So I decided to find something instead that mattered to me, and could be applied to benefit society.

The past 10 years have seen an explosion in the phenomena of 'Fake News'. Whilst misinformation and lies have existed for as long as humans have had the ability to talk, the rise of the internet has allowed misinformation to propegate like never before.

Therefore, I wanted to create a model which would be able to 'call out' fake news articles.

### Proposal
The aim of this workbook will be to build a model which classifies a webpage as either real or fake, to a reasonable degree of accurancy.

I think a degree of leniancy should be afforded when talking about accuracy, due to the highly specific nature of this problem.

### Data
Finding quality datasets which classify real and fake news was quite a challenge. However, luckily I was able to identify one such dataset on Kaggle, uploaded by user Hassan Amin. The dataset can be found here: https://www.kaggle.com/hassanamin/textdb3.

I was able to check several of the records that are still available on the web, and can validate the ones I checked seemed correctly labeled.

The dataset covers real and fake news articles, generally centred around American politics and the 2016 election cycle. This will affect which types of articles the model can hope to classify.

### Method
First we will prepare the data. This will not involve much transformation (but I do not consider this important as I generally do this in my day-job), but will include vectorising the text data into a format readable by the model.

Then, we will compare a range of models and select the best one based on the accuracy score.

Finally, we will test the model "in the wild" by webscraping articles from a range of sources I can vouch for as being either real, fake, or questionable.

I thoroughly recommend that the reviewer try a few articles of their own!

<a name="installation"></a>
## Installation
The app uses Python 3.7 only.

### Libraries
*numpy
*pandas
*itertools
*requests
*matplotlib
*bs4
*sklearn

### Installation
Clone the following GIT repository:

https://github.com/Benk195/FakeNews.git

This will provide the notebook, and the csv required to run it.

<a name="author"></a>
## Author

 - [Ben Kelly](https://github.com/Benk195)

<a name="ref"></a>
## Kaggle

 - [Hassan Amin](https://www.kaggle.com/hassanamin/)
 - Thanks to Hassan Amin for providing the data for this project

## Udacity

 - [Udacity](https://www.udacity.com/)
 - Thanks to Udacity for the support during this project & course
