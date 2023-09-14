# **PROJECT DESCRIPTION**

*Mobile apps are everywhere. According to state counter global stats over 71.86% of mobile operating system market is shared by android worldwide - 'july 2022', so clearly andriod dominates in global market share.They are trouble free to create, profitable or booming & are very useful and because of all these factors, apps are being developed progressively. In this project, We will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Playstore all across different categories. We'll look for different insights in the data to conceive strategies to operate and grasp info. The data for this project was taken from the Google Play Store website.The given data files are as follows:*


# Here we have 2 csv files in the current version of the dataset:



**1. googleplaystore.csv** :

* Above file holds all the details of the apps on Google Play.*

Here i have taken 9 important features out of 13 that describe a given app.

**App**: Name of the app

**Rating** : Gives current average rating (out of 5) of the app on Google Play

**Reviews** : Number of user reviews given on the app

**Category** : Category of the app. for examples are: FAMILY, SOCIAL, TOOLS, COMMUNICATION etc.

**Size** : Size of the app in MB (megabytes), KB (kilobytes), GB (gigabytes)

**Type** : paid or free

**Price** : Price of the app in US$ on Google Play Store

**Last Updated** : Date on which the app was last updated on Google Play

**Installs** : NO. of times any given app is or was downloaded/installed from Google Play




**2. googleplaystore_user_reviews.csv :**

* Above file holds 100 reviews for each app, passed and accepted via sentiment investigator engine & it's sentiment score.*

**Review** : Preliminary processed user review text

**App** : Name of the app on which the user review was provided. Matches the `App` column of the `apps.csv` file

**Sentiment Category** : User review - Positive, Negative or Neutral

**Sentiment Score** : Sentiment score of the user review.
