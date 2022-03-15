STA 141B Project Proposal
By Shraddha Jhingan, Sofia Maysenhalder, Tammie Tam

2/13/22

Introduction
In 2020, the number of reported hate crimes in the United States rose 6 percent from 2019, according to the FBI [1]. About 62 percent of reported hate crimes were racially motivated [2]. To get further insight into hate crimes, we can look at a well-studied country like Germany where researchers have examined the role of social media on the frequency of hate crimes. According to a research paper by Karsten Müller and Carlo Schwarz, increased anti-refugee rhetoric and sentiments on social media has been correlated with an increased frequency in anti-refugee hate crimes in Germany [3]. Therefore, we are interested in the role of social media on hate crimes in the United States, while also investigating other aspects of hate crimes such as motivation and location. Some questions we are interested in including:

Who are those most vulnerable to crimes?
What biases are the strongest motivators in hate crimes?
Where are the most crimes taking place (e.g. populated cities, rural towns, etc.)?
Are most of these hate crimes influenced by mob mentality or individually influenced?
Is there a correlation with search trends/social media usage and hate crimes?
Narrowing into specific cities (e.g. Sacramento) and specific hate crimes (e.g. against a racial group), is there an increase in sentiment against a particular group when there is increased hate crime against that particular group in that city?
By answering these questions, we hope to understand ways hate crimes can be prevented and where we can target hate-crime-prevention policies.

Datasets
From the U.S. Department of Justice FBI Crime Statistics, we plan to work with the hate_crime dataset (Link: https://crime-data-explorer.app.cloud.gov/pages/downloads; dataset download under “Hate Crime” dropdown) which provides data on hate crimes committed between 1991 through 2020, including where the crime took place, descriptions of the offender(s), and motivation of the hate crime. Through this dataset, we want to explore which types of biases are the strongest driving factors in hate crimes, how the nature of these hate crimes vary across the United States, who are the most vulnerable to these crimes, and whether these crimes are individually or group influenced. We want to see how these questions differ across the three decades provided in the dataset, since the influence of social media took off around 2004 (roughly the midpoint of the data’s 1991-2020 date range).

In addition, we may want to dive deeper into specific cities and their hate crimes, such as the Sacramento Biased-Related (Hate Crime) dataset from 2017-2021 (Link: http://www.cityofsacramento.org/police/crime). Through this dataset, we want to explore whether there’s a domino effect in particular hate crimes that occur in a particular region. For example, San Francisco’s Chinatown district experienced a 567 percent increase in hate crimes from 2020 (the start of the pandemic) to 2021 [4]. There appears to have been a domino effect in hate crimes that took place in this particular region, with such a dramatic spike in crimes in a very short period of time. Therefore, we want to explore whether other cities / regions have also experienced a domino effect in particular hate crimes.

We will also be using the Twitter API, which is available for download on the Twitter Developer platform (Link: https://developer.twitter.com/en/docs/twitter-api). The API allows us to access information that developers can access to build an app, such as programs about Direct Messages. The most important feature for us however will be access to the Tweets. We will be using the Essential version of the API which we will obtain by signing up for a student account. This will allow us to access 500,000 Tweets which will be sufficient for our topic.

Challenges
The most challenging aspect of this project is merging the data from our multiple sources (hate_crime dataset, Sacramento Hate Crime Incident Data, and Twitter API) to get a comprehensive look at the factors that lead up to hate crime, including social media usage. Getting access to the Twitter API will pose an additional challenge in our 6-week timeline because it can take up to a week to get access to it, which means we will have less time to work with it. We will also have to make requests on the Terminal to get access to the information within the API, which may pose another time constraint for us. Lastly, the scale of our project will be challenging considering the large number of variables we will be working with (15+) and the thousands of tweets that are part of theTwitter API.

Skillsets Required
Prior to gaining deeper insights into the data, we will be conducting an exploratory analysis using techniques that we learnt in STA 141A, such as finding summary statistics in Python or R. As part of the exploratory analysis, we will also be creating basic visualizations to understand any obvious trends in the data, which will be useful given the large scale of our data.

After our exploratory analysis, we expect to use the Pandas and Numpy libraries in Python for data cleaning, data analysis and further data exploration to gain an insight into the data. Using these libraries will allow us to not only view quantitative and qualitative trends and insight in our data, but will also make it easier to manipulate the data for data cleaning and other purposes. Because we are also using an API alongside our data set, we will be able to use web scraping so that we can analyze the content of the tweets contained in the API. As part of our analysis, we will also be creating interactive visualizations in Python, like we have learnt in STA 141B.

Bibliography
Hernandez J. Hate crimes reach the highest level in more than a decade. NPR. https://www.npr.org/2021/08/31/1032932257/hate-crimes-reach-the-highest-level-in-more-than-a-decade. Published September 1, 2021. Accessed February 13, 2022.
Hate crime statistics. Published August 30, 2021. Accessed February 13, 2022. https://www.justice.gov/hatecrimes/hate-crime-statistics
Müller K, Schwarz C. Fanning the flames of hate: social media and hate crime. Journal of the European Economic Association. 2021;19(4):2131-2167. doi:10.1093/jeea/jvaa045
Anguiano D. SF police data shows 567% increase in reports of hate crimes against Asian Americans. The Guardian. https://www.theguardian.com/us-news/2022/jan/26/san-francisco-increase-hate-crime-anti-asian-aapi. Published January 26, 2022. Accessed February 13, 2022.
