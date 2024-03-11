# Nikola Jokic Machine Learning Project

## Question: Can I predict whether the Denver Nuggets will win a regular season game solely based on Nikola Jokic's performance? 

### This was my first experience with building machine learning models. The HTML file walks through my thought process, code, and conclusions. Below is a summary of my work:

- Built a logistic regression, support vector machines, random forest, and boosted trees model
- Support vector machines model performed the best, correctly predicting about 90% of wins and 90% of losses solely based on Jokic's stats
- Caveats: games where Jokic did not play were omitted, missing values were imputed using median, signs of overfitting, model performance may be dependent on how valuable the player is for his team
