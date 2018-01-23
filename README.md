# PresidentialTweets
A project I did in colloboration with a partner at HACKFSU 2017. 
A simple premise was archiving all of Trump's tweets and then we added other features to create interactivity.
Tweets were downloaded using twitter's api but due to limits enforced by twitter many of his older tweets were added by scraping them from others who were also archiving them.
Those features are using markov chains to generate artificial Trump Tweets and a small minigame where users try to guess if it was real or not. A feature where users write their own tweeet and we score it's similarities to Trump's actual tweets, this was implemented in a very crude way by counting how many words successively match one of his actual tweets. Then lastly a feature that just gives the sentimental analysis of a tweet by calling a sentimental analysis api.
This was all encapsulated in a wep app created with a boostrap frontend in a Python Django backend using MYSQL as a DB.
