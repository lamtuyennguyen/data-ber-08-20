<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>


Housing prices in Berlin

[The Tacos: Alexander, Lam-Tuyen, Leo, Mayowa]

[DAFT August 2020, Berlin]

Content

Project Description
Questions & Hypotheses
Dataset
Database
Workflow
Organization
Links


Project Description

Berlin housing prices have been increasing drastically for the last decade. While implementing the data extraction methods we learnt in the bootcamp, we check the prices currently advertised on a website.

After extracting those data and calculate the average current market price, we compare them with the data we downloaded from kaggle. The dataset we downloaded is from April 2020. Like that we can check whether there was any movement in prices since the start of the Corona crisis and now.


Questions & Hypotheses

How much do prices differ in different neighbourhoods (defined by zipcodes) in Berlin? Has there been an increase or decrease in housing prices compared to the start of the crisis? We assume that there might be a slight decrease in prices, since many people are low on budget and the demand for a new apartment might decrease.


Dataset

1. We downloaded a dataset from kaggle which entails the rental prices in Berlin in Aptil 2020: https://www.kaggle.com/phanindraparashar/germany-housing-rent-and-price-data-set-apr-20?select=apr20_rental_no_duplicates.csv 

2. We webscraped from immonet.de

What dataset (or datasets) did you use? What are the different sources you used (e.g. APIs, web scrapping, etc.)? Provide links to the data if available and describe the data briefly.


Database

What is the structure of your database? Have you created more than one table and if yes, how are they related to each other?


Workflow

Outline the workflow you used in your project. What are the steps you went through?

We decided on the topic of checking the current rental prices in Berlin.
We downloaded a dataset from kaggle where the author webscraped from immobilienscout24.de.
To have comparable data we intended to extract data from immobilienscout24 with API. Since we encounted difficulty with the temporary token and encountered the authorization issue (OAuth1.8) (Leo, plz write something that makes sense here)

We switched to webscraping immobilienscout24 and got 405 error. I couldn't find any walk-arounds. So we changed the plan to webscrape another website: immowelt.de. It seems that the ads there don't follow the same structure, therefore we looked for another website again: immonet.de 


Organization

We used Trello to outline the list of tasks.
We divided the work 

How did you organize your work? Did you use any tools like a kanban board?

What does your repository look like? Explain your folder and file structure.



Links

Include links to your repository, slides and kanban board. Feel free to include any other links associated with your project.

Repository: https://github.com/Lsacy/real_estate 
Slides
Trello








## Requirements & Deliverables
The **mandatory** requirements that this project needs to satisfy are:
* The project must be planned. That is why creating a Kanban board and readme documentation is important. You can find a template for Trello [here](https://trello.com/b/kImhfE7w/data-projects).
* Your repository must be clean and organized; this means that it must include a *.gitignore* file and a README file and also have a functional file structure.
* Your project must include data from at least 2 different data sources (APIs & web, dataset & APIs, etc.).
* The project needs to be presented within 5 minutes to your colleagues on the day of the presentation.

The **deadline** to turn in the deliverables is Sunday at 23:59.

## Mentoring
The TAs will be your mentors!

Your mentors will:
* Keep track of your project in general terms. Your mentors will be the next people that know more about the project, after you.
* Check if you are following your plan: are you keeping up with your tasks and deadlines? Do you have any obstacles blocking you?
* Help/support you with specific questions.

Your mentors are **not** meant to:
* Know everything.
* Be your managers. You have to be responsible of your own tasks!

## Schedule  

**Please note** that the following schedule is simply a guideline. Feel free to organize your work as you see fit.

**Step 1**
* Choose a topic for your project.
* Find interesting questions related to your topic.
* Brainstorm to find out what kind of data you can use to answer those questions.
* Research and look for the data you need. Remember that you need to use at least two different sources.
* Create your own repo, assign your group members as contributors, and commit often. You can find a [template](https://github.com/ta-data-bcn/Project-Week-3-Data-Thieves/blob/master/your-project/README.md) for your README file in this repository. Remember to keep the README up-to-date.

**Step 2**
* Plan your project. Remember that we are providing you with a Trello [template](https://trello.com/b/kImhfE7w/data-projects). Define tasks, specifying those to be done individually and those to be done together. Remember that you **CAN'T CODE** until your project is planned.
* Once you finish, start coding!
* Clean your data.
* Design your database.

**Step 3**
* Design your presentation, focusing on techniques, trouble points, and workflow. Analysis and plotting are optional and should not be the focus of the presentation.

**Step 4**
* Presentation time at **14:00** on Friday! There will be a 1-minute dance break between groups!

## Necessary Deliverables
The following deliverables should be pushed to your Github repo and the link should be submitted via the student portal.

* **A Jupyter Notebook (.ipynb) file**:
The structure should be:
1. Title of the project.
2. Introduction to hypothoses.
3. Data used (sources, limitations, cleaning, etc...)
4. Any analysis and plots created.
5. Any insights derived from your basic analysis.
6. Possible further questions and improvements.
* **A data folder**
* **A ``README.md`` file**  
Look [here](https://www.makeareadme.com/) for tips on how to structure a README.md file.


## Presentation
The presentation time limit is **5 minutes**! Our suggestion is to include at least the following slides in your presentation but feel free to add or remove slides:

* Title of the project
* Team presentation
* Goals of the project
* Data - sources, problems and limitations
* Database - data wrangling/cleaning and database structure
* Organization. Did you follow your workflow plan? Did you add something after starting the project? Did you follow your best practices agreements? Did you think about the risk management?
* Any insights
* Questions you were not able to answer and why
* Learnings


## Resources  
### Lists
[AnyAPI](https://any-api.com/)  
[Top 50 Most Popular APIs on RapidAPI](https://blog.rapidapi.com/most-popular-apis/)  
[18 Fun APIs For Your Next Project](https://medium.com/@vicbergquist/18-fun-apis-for-your-next-project-8008841c7be9) 
[reddit datasets](https://reddit.com/r/datasets)
[FiveThirtyEight](https://data.fivethirtyeight.com/)
[FiveThirtyEight on github](https://github.com/fivethirtyeight)
[US Government open data](https://www.data.gov/)

### Some Ideas
[WeatherBit](https://www.weatherbit.io/api)  
[Strava](https://developers.strava.com/docs/reference/)  
[GitHub](https://developer.github.com/v3/)  
[Twitter](https://developer.twitter.com/en/docs.html)  
[LastFM](https://www.last.fm/api)  
[Spotify](https://developer.spotify.com/documentation/web-api/reference/)  
[NYTimes](https://web.archive.org/web/20150325135221/http://developer.nytimes.com/docs/times_newswire_api/)  
[News](https://newsapi.org/docs)  
[Reddit](https://github.com/reddit-archive/reddit/wiki/API)  
[Medium](https://github.com/Medium/medium-api-docs)  
[Twitch](https://dev.twitch.tv/docs/api/reference)  
[IGDB](https://api-docs.igdb.com/)  
[OMDB](http://www.omdbapi.com/)  
[GIPHY](https://developers.giphy.com/docs/)  
[StackExchange](https://api.stackexchange.com/docs)  
[YouTube](https://developers.google.com/youtube/v3/docs/)  
[TheSportsDB](https://github.com/enen92/script.module.thesportsdb)  
[NBA API](https://pypi.org/project/nba-api/)  

### Paper Examples
[Data Analysis with Python](https://medium.com/@williamkoehrsen/data-analysis-with-python-19434f5d6324)  
[The Best Mario Kart Character According To Data Science](https://medium.com/civis-analytics/the-best-mario-kart-character-according-to-data-science-7dfb65d4c18e)  
