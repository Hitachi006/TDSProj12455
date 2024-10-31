### BASEL: 10

_Insights on Github users based in Basel, Switizerland_. 

- **The data scraping approach** : Executed using python, the list of users was derived from api.github/search with a query to filter on location : Basel and followers:>10 and for each user, the specific information fields
  were scraped from the api.github/users endpoint and finally for each user, iteratively, the latest (upto 500) repos and their information as extracted from the users/{username}/repos endpoint

- **Key insight**: Based on the keywords in the available bio , atleast 18% of the users in Basel can be identified as having a Lifesciences specialisation, contributing to ateast 17% of the total repos and have ~20% higher number of followers per user while Python & Shell are the top 2 preferred languages (vs. Javascript and Python for the others)

- **Recommendation to developers**: Drive greater followers by including details of your bio and making yourself hireable
