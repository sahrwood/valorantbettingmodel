# valorantbettingmodel
Valorant Betting Models

This project started back in 2022, where I was working at a sportsbook with myriad offerings that had a non-betting clause for every sport it offered. I had been playing Valorant for a bit at this point with my friends, and being into the esports scene I came up with the idea of creating a betting model.

At first, not much went through my head besides the idea of scraping a bunch of valorant statistics, and throwing them into a soup with linear regression in excel. The scraping entails using vlr.gg, a site that has access to the Riot Games API (Valorant Developer) for competitive esports match statistics. This code is within the repository, where I use selenium and beautifulsoup to extract text from website elements, and pandas to organize this scraped data and save match stats/economy data to .csvs. 

Finally in 2024 I am here with (at the moment) finished machine learning models. You won't be able to run the models code itself. It requires the .csv files referenced in the code, with one file containing records of past valorant matches, and the other team statistics for upcoming matches I am trying to predict. The notebooks for map 1 stats/economy show how you could go about creating map by map code, and the .csvs running these notebooks create are aggregated into excel, where you could then create the required .csv files. Not everyone is shown here but I can be reached at sahrwood@gmail.com with questions

