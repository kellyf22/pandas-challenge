# pandas-challenge

In this project, we look at in-game purchases for Heroes of Pymoli, broken down by gender and age group, as well as briefly looking at popular and profitable items available for purchase within the game. This analysis was completed using the pandas library within python to perform operations on an original dataset provided as a .csv.

Given a dataset of in-game purchases tied to player information, this analysis identifies the number of players who have made purchases, and creates summaries of player demographics by gender and age. Summaries are also created of the purchasing patterns within these groups to identify how many purchases each group is making, and how much they are spending. Finally, a snapshot of the 5 top spending players, most popular items, and most profitable items is provided.

Some conclusions that can be drawn:
1. 576 players have made 780 purchases--less than half of our players are purchasing more than one item. Investigating the reason for this and increasing the number of repeat customers would probably be worthwhile.

2. Unsurprisingly, the vast majority of players who made purchases are male, presumably tracking with our overall population of players. However, purchasing rates of players who identify as female, other, or did not disclose do track and even slightly exceed their percentage of the population at 14.4% and 1.9% respectively, indicating we are successfully engaging those minority groups. The minority groups also spent about 10% more money per player than the male players. 

3. The largest age cohort of players who make purchases is the 20-24 year old range. This group likewise is near the top (#3) in average purchase price and average purchase price per person. The much smaller 35-39 year old group leads in spending per person, a reasonable finding since presumably that age group has more income. A more interesting result is that the under 10 age group is #2 in spending per person, significantly leading the other underage groups. Do these kids' parents set up accounts for them, whereas older kids have to spend precious money earned from chores or an allowance? Are parents playing under their kids' screen names to hide their gaming from a partner? Or do we have outliers caused by a couple of 8 year olds racking up in-game purchases unbeknownst to their parents until the credit card bill comes due?

Questions or areas for further analysis:
1. The provided dataset only gives information on the population of players who have made purchases within the game. How many players have not made in-game purchases, and how can we encourage them to do so?
2. Over what span of time was this data collected? Have purchasing trends increased or decreased over time? Does our offering of items change? 
3. Are players making purchases throughout their gameplay, or are there certain points in the game where players tend to purchase items to help them progress?