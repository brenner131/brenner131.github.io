## Using Clustering Methods to Characterize Player Types for Executive Function Training Games

**Project description:** The [CREATE Lab] (https://create.nyu.edu) at NYU studies how digital games can be used to improve specific executive function skills like inhibition, switching, and working memory. The game "All You Can E.T." was designed to improve the executive function skill of switching. Switching ability is measured by a separate task, adminstered before starting the game, and after playing the last sessions.

In the game, players have to feed hungry aliens either cupcakes or milkshakes -- but the aliens' preferences keep changing. As the rules switch and become more complicated, players hone their ability to 'switch' between rule sets.

But when we look at the change in switching before and after playing the game, not everyone who plays the game seems to improve. Previous analyses focused on changes in the executive function measure and age of the players, but that did not totally describe the pattern of results. 

To help figure out why gameplay seems to affect some players, but not others, we wanted to see if there are any patterns in the way players approach and play the game. We would expect players who get better at the game to also improve in the switching skill we see afterwards.

### 1. Exploring the data

We know a few things about the participants, like their gender and age.

<img src="images/GenderAge.png?raw=true"/>

We can also start to investigate how they performed in the game, in terms of the percent of correct items per level. 
<img src="images/PercentCorrect.png?raw=true"/>

However, the game adjusts based on performance. When players make mistakes, the game slows down. Instead of using a proportion of correct responses as a measure of performance, we'll use speed to keep track of player performance over four levels of the game. 

### 2. Latent Class Mixed Modeling

Players have to feed 20 aliens per level; perhaps we can use information about the adjustments in speed to describe different kinds of players.  Latent Class Mixed Modeling allows us to use the trajectory of performance within each level to describe groups of participants. 


<img src="images/CombinedLevels.png?raw=true"/>

In this iteration of our tests, putting aside some anomalous responses in Level 1, it looks like we can describe 3 'types' of players. One group, Latent Class 3 in blue, tends to improve their performance over the level, Latent class 2 in green may start making mistakes as the level goes on; and Latent Class 1 tends to perform steadily across each level.


### 3. Is Game Performance Related to Executive Function?

When we look at the change in switching ability as measured by the DCCS task separated by age group, it looks like most players score about the same, and age does not seem to influence the amount of change.

<img src="images/dccs_age_plot_black.png?raw=true"/>

However, when we also look at which 'class' each player belonged to, it looks like there are some trends in executive function. Latent Class 3, the group that kept improving their gameplay, also tends to improve the most at switching, across the age categories.
<img src="images/dccs_age_class_plot.png?raw=true"/>

### 4. Ongoing Questions

A version of this work was presented at the [2018 Subway Summit] (https://www.tc.columbia.edu/human-development/news/stories/hud-subway-summit/).

This dataset is a toy example for ongoing work in the CREATE Lab. We are measuring different groups of students, different games, and different executive function skills to better understand why we see certain patterns of engagement with games for learning, and why some participants benefit more than others.
