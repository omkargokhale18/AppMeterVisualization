# AppMeterVisualization
URL to AppmeterAnalytics Dashboard -
https://app.powerbi.com/view?r=eyJrIjoiZjI2YTY3MDQtMWY3ZC00Mzc2LWEzNTAtYmU0NzNjYTczODBhIiwidCI6Ijc5OTgxYjAxLTE5NDQtNGRhMC1hYTlhLWZiOWY2M2JkZGI1ZSIsImMiOjZ9


This is one of the premium feature of AppMeter where the user is exposed to all the analytical insights about
the App ecosystem. All the 450,000+ applications and their detailed analysis is available on just one click. The
user-friendly and intuitive dashboard can get the answers to App-ecosystem related questions on the fly!
For example,
Even without applying any filter, user can get answers to questions like-
● What’s the average number of downloads in the App store?
● What’s the average file-size of the apps?
● Out of total 450,000+ apps, how many apps are free? How many are paid? What’s the percentage of
Paid and Free apps?
● How many of the total apps have good quality? (Average rating 4+)
● Show me time series of apps launched over the years

We can apply filters for Genre, Free/Paid, Rating bucket, and get statistics like Average number of apps,
Average downloads, Average app size, number of apps launched in recent years etc.
We can get answers to some complex questions like-
● What’s the average downloads for Apps in “Social Networking” genre which are free and have average
rating between 3 and 4?
● What’s the average file-size for apps in “Business” Genre and which are highly rated (4+)?
● What’s the average downloads for “Games” Genre and apps which are free and poorly rated (1-2)?
● What’s the number of apps launched over years in certain genre and are paid?
● Does poorly rated “Games” also have high downloads?
● Apps in “Social Networking” genre have higher average downloads; but what’s the average rating for
that genre? Is the file-size for those apps very less? Is the average file size for social networking apps
less than that of apps in all the genres combined?


Design considerations:
● Modification to the Data
As any executive would like some insight instead of just numbers, we made buckets for the app data in terms
of Ratings and File-size. Also, price should have a flag-indicator as Paid or Free. We created the buckets using
conditional columns function of the Power BI and used those fields in the dashboard. Due to data modifications,
information delivery to the targeted user is made efficient.
● Ease of Use
The dashboard does not involve any repetition of information. All the complex questions can be answered by
just a click. Resetting the filters is easy. The response time for the dashboard is extremely low (almost zero).
The integration of the web application with Microsoft Power BI is very simple and newly added apps in the
ecosystem can be maintained easily by the administrator on the backend; independent of the user.
