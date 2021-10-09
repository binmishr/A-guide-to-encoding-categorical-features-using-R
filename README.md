# A-guide-to-encoding-categorical-features-using-R
The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

A Brief Introduction
=====================

In this article, we will look at various options for encoding categorical features. We will also present R code for each of the encoding techniques. Categorical feature encoding is an important data processing step required for using these features in many statistical modelling and machine learning algorithms.

The material in the article is heavily borrowed from the post Smarter Ways to Encode Categorical Data for Machine Learning by Jeff Hale. The linked article provides many useful tips along with Python code. Our aim is to implement each of the encoding techniques using R while minimizing the use of additional packages. Please note that the code provided in this article is illustrative and does not follow any software engineering best practice. It may also not be suitable for production, though my hope is that some of you readers will find it useful in your own work. 

The words – features, variables or columns – are used interchangeably throughout the rest of the article. The same is true for the words observations or rows to represent each individual data point.
