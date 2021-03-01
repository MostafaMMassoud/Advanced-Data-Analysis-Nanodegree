# About the Data
### TMDB movie data
**The data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.**

Certain columns, like: 
>‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.

>There are some odd characters in the ‘cast’ column. Don’t worry about cleaning them. You can leave them as is.

>The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.


**Main Questions Tried to Answer:**

1- How  production of Animation genre changed through 1960-2015 period?

2- Which actor from the top 9 actors particibate in animation movies more and what is the average of vote for movies he particibate in?¶

# Conclusions

**Many movie's genres show changes over the period of time we analysis like**

> Animation, Documentary and Thriller which show an increasing percentage of the production

> History, Romance and Western which show a decreasing percentage of the production

**Unfortunately some of the 'revenue_adj and 'budget_adj' columns contain zeros entry so I had excluded them 
which result in a huge decrease in the data set from 9773 to 3806 entries that had high empact on the number of movies for each actor which limits my findings. That been said, while the true numbers is not very good indicator but we can rely on the difference between the actors, so we can conclude that:**

> 1- John Goodman was the highest actor to cast in animation movie with about 20% of his movies been animation

>  2- John Goodman came fifth by the average amount of his movies profit
