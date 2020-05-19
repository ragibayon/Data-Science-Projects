# Data Science Projects

## 1. [TV, Halftime Shows, and the Big Game](https://github.com/ragibayon/Data-Science-Projects/blob/master/Python/TV%2C%20Halftime%20Shows%2C%20and%20the%20Big%20Game/TV%2C%20halftime%20shows%2C%20and%20the%20Big%20Game.ipynb)

Whether or not you like football, the Super Bowl is a spectacle. There's drama in the form of blowouts, comebacks, and controversy in the games themselves. There are the ridiculously expensive ads, some hilarious, others gut-wrenching, thought-provoking, and weird. The half-time shows with the biggest musicians in the world, sometimes riding giant mechanical tigers or leaping from the roof of the stadium. And in this project, I have tried to find out how some of the elements of this show interact with each other. I have answered questions like:

* What are the most extreme game outcomes?
* How does the game affect television viewership?
* How have viewership, TV ratings, and ad cost evolved over time?
* Who are the most prolific musicians in terms of halftime show performances?

> The dataset used in this project was scraped and polished from Wikipedia. It is made up of three CSV files, one with [game data](https://raw.githubusercontent.com/ragibayon/Data-Science-Projects/master/Python/TV%2C%20Halftime%20Shows%2C%20and%20the%20Big%20Game/datasets/tv.csv), one with [TV data](https://raw.githubusercontent.com/ragibayon/Data-Science-Projects/master/Python/TV%2C%20Halftime%20Shows%2C%20and%20the%20Big%20Game/datasets/tv.csv), and one with [halftime musician data](https://raw.githubusercontent.com/ragibayon/Data-Science-Projects/master/Python/TV%2C%20Halftime%20Shows%2C%20and%20the%20Big%20Game/datasets/halftime_musicians.csv) for all 52 Super Bowls through 2018.

## 2. [The Android App Market on Google Play](https://github.com/ragibayon/Data-Science-Projects/blob/master/Python/The%20Android%20App%20Market%20on%20Google%20Play/The%20Android%20App%20Market%20on%20Google%20Play.ipynb)

Mobile apps are everywhere. They are easy to create and can be lucrative. Because of these two factors, more and more apps are being developed. With more than 1 billion active users in 190 countries around the world, Google Play continues to be an important distribution platform to build a global audience. In this project, I have done a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. I have looked for insights in the data to devise strategies to drive growth and retention, and mined user review data to determine how people feel about a product, brand, or service using a technique called sentiment analysis.

In this project I have tried to find answers for these following questions using a data driven approach.

* Which category has the highest share of (active) apps in the market?
  * Is any specific category dominating the market?
  * Which categories have the fewest number of apps?

* How can we effectively come up with strategies to size and price our app?
  * Does the size of an app affect its rating?
  * Do users really care about system-heavy apps or do they prefer light-weighted apps?
  * Does the price of an app affect its rating?
  * Do users always prefer free apps over paid apps?

> The dataset used in this project is made up of two CSV files, one with [apps.csv](https://raw.githubusercontent.com/ragibayon/Data-Science-Projects/master/Python/The%20Android%20App%20Market%20on%20Google%20Play/datasets/apps.csv) which contains all the details of the applications on Google Play. There are 13 features that describe a given app. and one with [user_reviews.csv](https://raw.githubusercontent.com/ragibayon/Data-Science-Projects/master/Python/The%20Android%20App%20Market%20on%20Google%20Play/datasets/user_reviews.csv) which contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity.

## 3. [The GitHub History of the Scala Language](https://github.com/ragibayon/Data-Science-Projects/blob/master/Python/The%20GitHub%20History%20of%20the%20Scala%20Language/The%20GitHub%20History%20of%20the%20Scala%20Language.ipynb)

Open source projects contain entire development histories - who made changes, the changes themselves, and code reviews. In this project, I had to read in, clean up, and visualize the real-world project repository of Scala that spans data from a version control system (Git) as well as a project hosting site (GitHub). With almost 30,000 commits and a history spanning over ten years, Scala is a mature language.

In this project, I have tried to find out:

* Is the project still actively maintained?
* Who has had the most influence on its development?
* Who are the experts?
* Is there mutual trust and friendship among people  in the project?

> The dataset includes the project history of Scala retrieved from Git and GitHub as a set of CSV files. Which has been previously mined and extracted from GitHub, is comprised of three files: [pulls_2011-2013.csv](https://raw.githubusercontent.com/ragibayon/Data-Science-Projects/master/Python/The%20GitHub%20History%20of%20the%20Scala%20Language/datasets/pulls_2011-2013.csv) contains the basic information about the pull requests, and spans from the end of 2011 up to (but not including) 2014. [pulls_2014-2018.csv](https://raw.githubusercontent.com/ragibayon/Data-Science-Projects/master/Python/The%20GitHub%20History%20of%20the%20Scala%20Language/datasets/pulls_2014-2018.csv) contains identical information, and spans from 2014 up to 2018. [pull_files.csv](https://raw.githubusercontent.com/ragibayon/Data-Science-Projects/master/Python/The%20GitHub%20History%20of%20the%20Scala%20Language/datasets/pull_files.csv) contains the files that were modified by each pull request.

## 4. [A Visual History of Nobel Prize Winners](https://github.com/ragibayon/Data-Science-Projects/blob/master/Python/A%20Visual%20History%20of%20Nobel%20Prize%20Winners/A%20Visual%20History%20of%20Nobel%20Prize%20Winners.ipynb)

The Nobel Prize is perhaps the world's most well known scientific award. Every year it is given to scientists and scholars in chemistry, literature, physics, medicine, economics, and peace. The first Nobel Prize was handed out in 1901, and at that time the prize was Eurocentric and male-focused, but nowadays it's not biased in any way. Surely, right? In this project, I got to explore patterns and trends in over 100 years worth of Nobel Prize winners.

I tried to find answers to these following questions in this project using a data-driven approach:

* What characteristics do the prize winners have?
* Which country gets it most often and is there any USA dominance?
* And has anybody gotten it twice or more?
* Age distributions between prize categories.
* Oldest and youngest winners

> The dataset used in this project is [nobel.csv](https://raw.githubusercontent.com/ragibayon/Data-Science-Projects/master/Python/A%20Visual%20History%20of%20Nobel%20Prize%20Winners/datasets/nobel.csv) which was downloaded from The Nobel Foundation on [Kaggle](https://www.kaggle.com/nobelfoundation/nobel-laureates).
