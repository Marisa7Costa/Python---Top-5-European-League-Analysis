# Python---Top-5-European-League-Analysis
Introduction to structured and unstructured machine learning

# Data Source
The dataset that has been selected will provide me with the necessary information/data to answer the main question of my analysis.
From a soccer scouting perspective, where have the highest valued players played before moving into one of the Big5 leagues (Germany, Italy, Spain, France, and England)?
Dataset downloaded from Kaggle on 24 March 2024
*https://www.kaggle.com/datasets/davidcariboo/player-scores?resource=download
About the datasets:
*“How did we build it?
The source code that maintains this dataset, as well as the data pipeline, is available in Github. On a high level, the project uses Transfermarkt-scraper to pull the data from Transfermarkt website and a set of Python scripts and SQL to curate it and publish it here.”
This data has been collected and put together by means of data web scraping from www.transfermarkt.co.uk. This data is automatically updated once a week.
How does Transfermarkt collect its data?
“We rely on the active support of our registered users, who support our voluntary data scouts with information and corrections.”
Transfermarkt aggregates data from multiple sources, including user submissions, official announcements, media reports, and publications like Kicker, a German soccer magazine. It employs a mix of crowdsourcing and manual data entry to compile and update player profiles, market values, and other relevant information.
Transfermarkt has a team of 80 staff members, including journalists, moderators, and data scouts, who oversee the platform's operations, data validation, and content management. It relies on hundreds of volunteers who contribute information and updates to the site.

# Data Limitation
The main limitation with this data set is the collection method relies solely on human input, making room for error. Users/Subscribers can contact the Transfermarkt administration staff to make corrections to data by way for a formal application based according to the type of information being corrected. https://www.transfermarkt.com/intern/datenpflegeGuide These changes are then checked by the administrator and verified before changes to the platform are done.
Transfermarkt Market Values, which estimate the worth of individual players, are determined through a collaborative process involving users, staff members, and country-specific area managers. These values are periodically reassessed based on factors such as player performance, injuries, transfer activity, and user feedback.
Dataset only shows where players played professionally and not amateur/academy clubs.

# Data Ethics
Transfermarkt began as a passion project by Matthias Seidel, a Werder Bremen fan, who started a website to track transfer rumours and player information. Their growth was fuelled by user engagement and community participation. Fans contributed corrections, updates, and additional data, fostering an organic online community interested in soccer statistics and rumours.
Transfermarkt takes pride in the accuracy of its data and market value estimations, considering them as informed guesses based on user input and the site's experience. While there is no algorithmic formula for determining market values, decisions are made through qualitative assessments, discussions, and consensus-building among staff and moderators.
Transfermarkt’s data has become influential within the soccer industry, serving as a reference point for clubs, agents, and stakeholders in player negotiations and transfer deals. Despite its initial intention to reflect the transfer market's state, Transfermarkt's data now holds a significant influence on real-world transactions and financial decisions.
Transfermarkt's data collection methods are rooted in community engagement, user contributions, and a collaborative approach to data validation and estimation. Transfermarkt has evolved into a trusted source of soccer data, shaping discussions and transactions within the global soccer ecosystem.

# Resources:
https://transfermarkt-datasets.fly.dev/
https://github.com/dcaribou/transfermarkt-datasets?tab=readme-ov-file#acquirers
https://www.nytimes.com/2021/08/12/sports/soccer/soccer-football-transfermarkt.html
https://www.transfermarkt.com/intern/faq

# Guidance questions:
•	Who: The client is a sports agent who would like to know where the highest valued players have played before moving into one of the Big5 leagues (Germany, Italy, Spain, France, and England).
•	Why: The client would like to understand which markets/leagues are producing high quality talent. 
•	What: The storyboard will provide more information on what determines the market value of a player and the likelihood that they will move into one of the Big5 leagues based on available data.
•	When: This information will be considered by the agency executives for talent scouting strategies and planning. Integrating a data-driven approach into their existing scouting strategy will enhance decision-making and allow for a more targeted and effective talent acquisition.
•	Where: Tableau Public.

# Storyboard Plan:
•	The Big5 leagues: Serie A - Italy; Premier League – England; Bundesliga - Germany; Ligue1 - France & LaLiga – Spain, jointly hold the highest share of the player market value and are also the dream leagues all players aspire to play in. In this case study, we will explore what characteristics affect player market value and which leagues are the stepping stones into the Big5 leagues.
o	Interactive map graph visualising the number of players in each of the big 5 leagues as well as indicating which leagues these players came from before joining the Big5.
•	The only numerical data variables available to analyse was player’s age, player current market value and player’s highest market value. Based on the exploratory analysis done on these three variables the following hypothesis was picked to test:
‘Age influences the market value- the older the player gets the more his market value increases.’

o	Scatter plot showing correlations. 

•	Show different approaches by way of linear regression results.
  
•	Show different approaches by way of a cluster analysis and results.


Tableau Storyboard Link *https://public.tableau.com/app/profile/marisa.costa5685/viz/Top5EuropeanLeagueAnalysis/Top5?publish=yes
