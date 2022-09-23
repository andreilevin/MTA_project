# Work-From-Home Trends in NYC

### 	 Project Presentation [Slides](https://github.com/andreilevin/MTA_project/blob/main/AndreiPresentation.pdf) | [Video](https://youtu.be/yqBPyubJo38):

[![Watch the video](https://raw.githubusercontent.com/andreilevin/MTA_project/main/figures/youtube_screen.jpg)](https://youtu.be/yqBPyubJo38)



## An Exploratory Data Analysis project 

Every week, the MTA (New York's subway system) publishes a fresh batch of [commuter usage data](http://web.mta.info/developers/turnstile.html ).  This dataset contains entry and exit counts for each turnstile in every station of the MTA, tallied approximately every four hours.  For my first data science project, I wanted to see if it was possible to use this turnstile data to infer which specific NYC neighborhoods saw the biggest increase in work-from-home rates among their populations as a result of the Covid-19 pandemic.  This information could be useful for an enterprising company that wishes to more precisely target the residents of those neighbohoods; for example, with ads for home office products such as standing desks and external monitors.

My hypothesis was that heavily residential neighborhoods could be identified by higher MTA outflow traffic (entries minus exits) on weekday mornings, caused by residents heading to work.   By exploring differences in morning outflow traffic before and during the pandemic, we could thus figure out which neighborhoods have more residents now staying home in the mornings— a potentially useful proxy for work-from-home rates.

## Tools

* SQL for ingesting the turnstile data into a local database
* SQLAlchemy for extracting the database into Python
* Pandas for data cleaning, filtering and aggregation
* Matplotlib and Seaborn for plotting 

