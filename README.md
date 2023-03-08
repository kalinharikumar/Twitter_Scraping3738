
# Twitter Scraping

Twitter Scraping is for scraping the data from Twitter. we can Scrap data like (date, id, url, tweet content, user,reply count, retweet count,language source, like count etc) from twitter.



 
## Snscrape
Here snscrape is used to scrape tweets from Twitters API without any restrictions or request limits. Moreover, we dont even need a Twitter developer account to scrape tweets when you use snscrape.

## MongoDB
With MongoDB here we can upload the scraped data and as we know MongoDB is much more than a database. It’s a complete developer data platform. And with MongoDB Atlas, the cloud offering by MongoDB, Hepls us to establish connection and store data.
## Download Files
We also convert the DataFrames to csv and json files as it will be Downloadable
## Streamlit
As we all know Streamlit turns data scripts into shareable web apps in minutes. All in pure Python. No front‑end experience required. We use it with search box, sliders, buttons, download buttons etc.,
## Workflow
Import libraies like pymongo, pandas, streamlite, snscrape, etc.,
Now using streamlite I've made 2 tabs(Home,About)
With tab1 an form is made to get variables for search with a final submit button.
And if submit button for loop is executed with snscrap with search data.
Now required data is collected into DataFrame which will displayed in ui.
Also 3 buttons are made for upload to database, download as csv and download as json
MongoDB connection is established using pymongo.
Dataframe is converted to csv, json and Dictionary for requirements.
Finally, tab2 an short explationation about the project.
## Execution
Execute through terminal or cmd
streamlit run python file name
It will direct through browser after successful execution.

## Demo
I've made explaination in demo video. please follow the link below.
https://www.linkedin.com/posts/kalin-harikumar-230349140_twitter-guvi-twitterscraping-activity-7039156844476473344-hU9i?utm_source=share&utm_medium=member_desktop


