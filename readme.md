# Analyzing Twitter Data on the 2018 Texas Senate Race 

## TL;DR

Using data from Twitter's API collecting data for the 2018 Texas Senate Race, we identified that the key issues for the particular election were the following:

1. Trump
2. Health
3. Justice
4. Immigration

Performing lift and sentiment analysis regarding the identified issues for both candidates we concluded the following:

Lift Values:
1. While both candidates touch on the identified issues and record significant ilfts, Beto appears to have higher lift values across all issues, even marginally in regards to health, despite the fact that Cruz appeared in more tweets than Beto (1756 compared to 1551).
2. The most related candidate and issue are Cruz and Trump. Cruz should really carefully assess the influence of trump on his image and utilize trump's effect and power on public opinion in his favor.
3. We could see that in small cities, Beto and Cruz's sentiments are very close, while in bigger cities the sentiment towards beto is more positive. This shows that Beto has a slight advantage on Cruz in bigger cities. 
4. We can see that in general, there are more mentions of the candidates in big cities then in smaller cities, and this is interesting given the fact that small cities total population is 2 times the population of the big cities we chose. This might mean that people in smaller cities are less involved in politics then in bigger cities, and so the candidates would want to emphasize on bigger cities.

All the steps of the process are thoroughly presented in the project's report.

## Tools used

- Python 3
- Jupyter Notebook
- Vader 


## Key take-aways

- Beto should aim his focus on connecting to the voters of small cities since his "large city popularity" is not enough due to the small number of voters (2 to 1 compared to small cities)
- Cruz should focus on politics and try to strongly affiliate his candidacy with Trump, tapping into his Trump's popularity in order to retain his small city votes.


## Areas for improvement

- Use of a larger dataset over a longer period of time
- Analysis of the gerrymandering effect taking into account district boundaries
