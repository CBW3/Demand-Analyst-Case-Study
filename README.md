# Demand-Analyst-Case-Study
I analyze a large dataset pertaining to geospatial, weather, and customer characteristics to determine bike sharing demand via predictive analysis.

First off, the reason why the PowerPoint Presentation is titled John Smith is because I did this project as part of my 
IBM Data Analytics with Excel & R Professional Certificate. We had to share this project with others, so I chose to remain anonmyous. 

Regardless, as aforementioned, I organized my analysis findings into a PowerPoint Presentation. 

In particular, I utilized a regression model as my experimental design framework. I wanted to explore the relationship between temperature, cities,
available number of bicycles for rent within a given city at a given time, time, seasons, and holidays with respect to bike sharing demand. 

To get all of the data necessary, I utilized the large Bike Sharing Dataset provided, web-scraped data from Wikipedia entries to get city and population data,
and utilized an API called OpenWeather. 

After getting all the data, I had to take appropiate measures to clean, transform, and wrangle the data into a usuable format. 

I first performed exploratory data analysis to see if time, weather, or seasonality influenced bike demand in the first place. Intuitively, I thought it
would; however, I wanted to be sure. To do so, I used R & Python to create visualizations. 

Similarly, I built an experimental model via regression analysis to predit hourly rented bike count based upon a number of factors for a given city. 

I then ran multiple models like Ridge, Lasso, etc. to determine which model might predict hourly rented bike counts the "best." 

Later, I used R Shiny to create a dynamic dashboard to essentially see bike demand in real time. 

Ultimately, the insights from my analysis provide a potential avenue for marketing programs 
and business expanstionary programs into different territories. 

For futher information, please refer to all the files included within this Repository. 
