# Profitables Apps for the AppStore and GooglePlay Markets
A project that analyzes data from Kaggle datasets using Python.


In this project, I analyze two datasets of IOS and Android apps, in order to have useful insights in making a decision to launch apps for a new company.

Kaggles datasets were used:
[Aplestore](https://www.kaggle.com/datasets/ramamet4/app-store-apple-data-set-10k-apps)
[Googleplaystore](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

The tools userd were Python and Jupyter Notebook.

## Exploring datasets and Cleaning data

The datasets are cleaned to improve accuracy, check user engagement, and allow us to evaluate the kinds of apps that are likely to attract more users and, consequently, increase our revenue.

1- Detect duplicate data, and remove the duplicates: to reduce errors and risks

2- Detect inaccurate data, and correct or remove it:
- Removes non-English apps
    > Most of the users use apps in English and keeping only with this language, we reach most users and reduce machine costs in evaluating. <br><br>
    > To classify the apps as English or not, ASCII is used.
    > English texts are encoded using the ASCII standard. Each ASCII character has a corresponding number between 0 and 127 associated with it, so we can build a function that checks an app name and tells us whether it contains non-ASCII characters.

- Remove apps that aren't free
    > I keep with the free apps. Most of the apps make money inside the app, having free installations. This business type makes sense for new apps like ours new apps.

3- Examining genres of apps.
- Most reviewed genres
    > Reviews are used to find user engagement index with the app. Reviews are a benchmark for measuring user acceptance of an app.<br>

- Most installed genres
    > By the number of apps installed in certain genres, we can identify demand by genre, considering different platforms.<br>



### Conclusion

**Which has the most profitable apps: Android or IOS?** We know that the percentage of mobile over desktop is only increasing. Android holds about 53.2% of the smartphone market, while iOS is 43%. Based on these datasets, I can't answer this question. But I can highlight points and make some observations.

Free apps from IOS (2017) and Android(unknown data) were analyzed. A Cleaning was made to detect and remove missing and duplicate data, and detect and fix or remove inaccurate data. Duplicate entries were removed, keeping with entries with the higher number of reviews, that can represent the more recent records. Non-English apps and non-free apps were excluded from this work. Percentages for genres in both platforms were found. And the game with more reviews was shown.


- **Games are the strong point of IOS apps.**
Games and Entertainment are strong points of IOS apps. These types of apps are quite profitable, even though they are initially free and have different business models. Unlike functional apps, users spend a lot of time using gaming and entertainment apps, which makes room for selling space for marketing and also selling features. <br><br>

- **Business and Productivity are the most important genres in Android apps.**
Only requires time and focus as input. We can say that business apps are profitable, even if they don't have many users, and that they run profitably with a small mumber of users. Because these only require time and focus as input, they do not require upfront capital, nor do they require an extended business network [(source)](https://www.appypie.com/app-business-model). <br><br>

- **Clash of Clans** is the game with more reviews on both platforms, but the engagement on Android is 22 times higher for this game.

**What are the most popular genres?**

- `book and reference`, `communication`, `entertainment`, and `game` are the most installed categories with more.<br><br>

- `Communication` category was shown to be a higher proportion of apps with 100,000,000+ more disproportionate than the average of those with less installs. This makes me believe that this category is dominated by big and famous apps, while the other three categories are more competitive.

With these general insights, I can prioritize the platform I choose to launch my company's app on, according with the company's niche.