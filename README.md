**The Android App Market on Google Play**

Mobile apps are everywhere. They are easy to create and can be very lucrative from the business standpoint. Specifically, Android is expanding as an operating system and has captured more than 74% of the total market[[1]](https://www.statista.com/statistics/272698/global-market-share-held-by-mobile-operating-systems-since-2009).

The Google Play Store apps data has enormous potential to facilitate data-driven decisions and insights for businesses. In this notebook, we will analyze the Android app market by comparing ~10k apps in Google Play across different categories. We will also use the user reviews to draw a qualitative comparison between the apps.

The dataset you will use here was scraped from Google Play Store in September 2018 and was published on [Kaggle](https://www.kaggle.com/lava18/google-play-store-apps).

Here are the details:

**datasets/apps.csv**

This file contains all the details of the apps on Google Play. There are 9 features that describe a given app.

**App:**  Name of the app

**Category:**  Category of the app. Some examples are: ART\_AND\_DESIGN, FINANCE, COMICS, BEAUTY etc.

**Rating:**  The current average rating (out of 5) of the app on Google Play

**Reviews:**  Number of user reviews given on the app

**Size:**  Size of the app in MB (megabytes)

**Installs:**  Number of times the app was downloaded from Google Play

**Type:**  Whether the app is paid or free

**Price:**  Price of the app in US$

**Last Updated:**  Date on which the app was last updated on Google Play

**datasets/user\_reviews.csv**

This file contains a random sample of 100 [_most helpful first_](https://www.androidpolice.com/2019/01/21/google-play-stores-redesigned-ratings-and-reviews-section-lets-you-easily-filter-by-star-rating/) user reviews for each app. The text in each review has been pre-processed and passed through a sentiment analyzer.

**App:**  Name of the app on which the user review was provided. Matches the App column of the apps.csv file

**Review:**  The pre-processed user review text

**Sentiment Category:**  Sentiment category of the user review - Positive, Negative or Neutral

**Sentiment Score:**  Sentiment score of the user review. It lies between [-1,1]. A higher score denotes a more positive sentiment.

From here on, it will be your task to explore and manipulate the data until you are able to answer the three questions described in the instructions panel.
