# We Rate Dogs, a data wrangling project

The aim here is to wrangle data coming from a twitter account called "We rate dogs". This twitter account rates and comments dog pictures shared by people.

The first challenge will be to gather data from a variety of sources in different formats :
- Manually (downloading a csv).
- Programatically through url (tweet image predictions file in tsv format).
- Programatically through Twitter's API tweepy (tweet in Json format) --> **In order to have a functionnal code you will need to enter your personal authentification key, pwd and token to access tweepy**, to get some check this [page](https://developer.twitter.com/en/docs/developer-portal/overview).

In the second step we will be assessing the data visually and programatically for both quality (reated to content) and tidiness (related to structure) issues. The aim is to find at least 8 quality issues and two tidiness issues. At the end, our data should follow the basic rules of tidiness :
- Each variable forms a column.
- Each observation forms a row.
- Each type of observational unit forms a table.

The last part is dedicated to analyzing the data to try to get some insights out of it through vizualisation and plotting. Finally, we will issue two documents. One to explain to wrangling effort "wrangle_report" and one to communicate the findings of the analysis "act_report".
