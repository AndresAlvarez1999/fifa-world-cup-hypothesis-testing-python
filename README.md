# Hypothesis testing of Goals in FIFA World Cup vs FIFA World Cup Qualifiers

**Background**

Football is a sport that unites people across the globe, with the FIFA World Cup standing as the pinnacle of international competition. However, the journey to the World Cup is just as intense, with teams battling through the qualifiers to secure a spot in the prestigious tournament. As a football fan from Spain, I’ve always been curious about the scoring dynamics in these different stages of the competition. This project aims to explore whether there are more goals scored on average in the FIFA World Cup compared to the FIFA World Cup qualifiers.

![fifaworldcup](https://github.com/user-attachments/assets/c6cd80c7-8c64-4f61-860e-8574542ce04e)

**About the Dataset**

The dataset used in this project includes 47,126 international football match results, starting from the first official match in 1872 and extending up to 2024. It covers a wide range of competitions, but for this project, we will focus specifically on matches from the FIFA World Cup and the FIFA World Cup qualifiers. The data is restricted to men’s full international matches and does not include Olympic Games or matches involving B-teams, U-23 squads, or league select teams.

The dataset can be accessed on Kaggle at the following link: [International Football Results from 1872 to 2017](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017)

**The dataset (results.csv) includes the following columns:**

* Date: The date the match was played.

* Home Team: Name of the home team.

* Away Team: Name of the away team.

* Home Score: Full-time score of the home team (including extra time but excluding penalty shootouts).

* Away Score: Full-time score of the away team (including extra time but excluding penalty shootouts).

* Tournament: Name of the tournament.

* City: City where the match was held.

* Country: Country where the match was held.

* Neutral Venue: Boolean indicating whether the match was played on neutral ground.


**Project Objective**

The goal of this project is to analyze whether more goals are scored on average in FIFA World Cup matches compared to FIFA World Cup qualifiers. By comparing the goal-scoring trends in both tournament stages, we will use hypothesis testing techniques to determine if the difference in average goals is statistically significant.

By the end of this project, we will have gained insights into whether the high stakes of the World Cup lead to more goals compared to the competitive, yet more frequent, qualifier matches.

This project demonstrates the use of non-parametric hypothesis testing to analyze and compare the average goals scored in FIFA World Cup qualifiers and the FIFA World Cup tournament. Using the Wilcoxon-Mann-Whitney test with the pingouin library in Python, we test whether the average goals scored in the qualifiers are greater than those scored in the main tournament.

* Project Overview:
  
Hypothesis Test: Right-tailed Wilcoxon-Mann-Whitney test

**Null Hypothesis (H₀): The average goals scored in the FIFA World Cup qualifiers are the same as the average goals scored in the FIFA World Cup.**

**Alternative Hypothesis (H₁): The average goals scored in the FIFA World Cup qualifiers are greater than the average goals scored in the FIFA World Cup.**

Significance Level (α): 0.05

Result Summary
p-value: 0.23

* **Conclusion:**

**In conclusion, since the p-value is greater than the significance level of 0.05, we fail to reject the null hypothesis. This means there is no statistically significant evidence to suggest that the average number of goals scored in the FIFA World Cup qualifiers is greater than those scored in the FIFA World Cup. While some may have expected a difference, the data shows that both competitions are quite similar in terms of goal-scoring.**

**With no clear advantage in average goals, we’ll leave these games to be watched and appreciated by the most passionate fans, who enjoy the thrill regardless of the scorelines.**
