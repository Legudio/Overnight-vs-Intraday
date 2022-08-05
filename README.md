# Overnight-vs-Intraday

Project inspired by this link: https://bruceknuteson.github.io/spy-day-and-night/ and the paper within titled "They Still Haven't Told You" (2022). Reading the paper, I didn't believe the main conclusion: that most major stock indices experience the majority of their growth overnight. 

Testing was fairly straight forward, however, scraping component data was not. Though certain websites were friendlier than others. I then created a dataframe with equities from each index tested. To do this, I first found the overnight returns of all equities, excluded those with overnight returns less than intraday, then sorted the overnight returns greatest to least. I then took the top quintile of these sorted equities. 

I will use this list of high performing equities in another project.
