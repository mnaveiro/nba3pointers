## Three-pointers in the NBA 

![Image](https://expo.advance.net/img/10bbbddc34/width960/c4d_3pointline.jpeg)

This study tries to analyze, using a dataset containing players stats since 1950, if players are shooting more and more beyond the three point line because the line is too close and is easier for the current players. 

### Motivation

Of a time to this part some people has been arguing about NBA and the role three-pointers are playing in the game. Some are asking for moving back the three point line while others are requesting a new 4-point line.

Since there is a general perception about that this characteristic is having an impact in the way that teams are playing the game we are trying to find out whether those insights can be supported with data. 

### Dataset(s)

#### NBA Players stats since 1950

The data-set contains aggregate individual statistics for 67 NBA seasons.

3000+ Players over 60+ Seasons, and 50+ features per player from basic boxscore attributes such as points, assists, rebounds etc., to more advanced moneyball like features such as Value Over Replacement.

It can be find at [Kaggle](https://www.kaggle.com/drgilermo/nba-players-stats) and the data was scraped from [Basketball-reference](http://www.basketball-reference.com/)

### Data Preparation and Cleaning
* The data-set used contains the players’ stats from 1950. However the threepoint line was introduced in the NBA in the season 1979-1980. Besides, the data for the first two seasons are clearly outliers therefore the study is focused in the seasons later than 1982.

* On the other hand, the data for the seasons 1998-99 and 2010-11 has been impacted due to lockouts in the league. And, during seasons 1994-95 to 1996-97, the NBA shortened the distance of the line with also impact in the numbers. 

### Research Question(s)
* Is the game too much 3-point centric?
  * In other words, are the players ‘abusing’ of this kind of field goal?
* Is becoming too easy for the players score from the three point line?
  * If so, it is worth to move the three-point line back? 
  
### Methods
* Descriptive statistics
* Visual analysis
* Correlation 

### Findings
As the time goes by both, the overall attempts and the 3-pointers has been increasing in number but this increment seems to be higher in the later ones. 

![Image](https://raw.githubusercontent.com/mnaveiro/nba3pointers/master/img/1.png)


The percentage of 3-pointers attempted has been growing quickly last years. In the 2016/2017 season 1/3 of the FGA was a 3-pointer. 

![Image](https://raw.githubusercontent.com/mnaveiro/nba3pointers/master/img/2.png)


While the trend in the number of 3-point shoots is clearly up…

![Image](https://raw.githubusercontent.com/mnaveiro/nba3pointers/master/img/3.png)


The number of 2-point shoots decreases year after year 

![Image](https://raw.githubusercontent.com/mnaveiro/nba3pointers/master/img/4.png)


The accuracy of the 3-pointers has also increased with time but, in average, is still far from the 2-point field goals.

![Image](https://raw.githubusercontent.com/mnaveiro/nba3pointers/master/img/5.png)

### Limitations
With this data-set we can analyze the players’ performance inside and beyond the three-point line but to learn if it is worth to move the line back and how far we would also need the coordinates of each attempt. 

### Conclusions
* Is the game too much 3-point centric?
  * According to the analysis one third of the current field goal attempts are made beyond of the three-point line. It is too much? That is not clear. We would need other information as the number of possessions per game or how long those possessions last.

* Is becoming too easy for the players score from the three point line?
  * It is a matter of fact that players are shooting more and with better percentages than ever but the lever of success is still far from the two point shoots. 

### Acknowledgements
This analysis was inspired by ["NBA 3 Point Percentages Through the Years"](https://www.kaggle.com/akeemtlking/nba-3-point-percentages-through-the-years) published by Akeem King in Kaggle.

Header image taken from [expo.advance.net](https://expo.advance.net/)

### References
* Should the NBA move back the 3 Point Line? [Discussion at Reddit](https://www.reddit.com/r/nba/comments/5wkbke/discussion_should_the_nba_move_back_the_3_point/)
* Stephen Curry, for 4! [Post at Slate](http://www.slate.com/articles/sports/sports_nut/2016/06/the_4_point_line_could_be_coming_to_the_nba_here_s_where_to_put_it.html)
* Wikipedia: [Three-point field goal](https://en.wikipedia.org/wiki/Three-point_field_goal), [1998–99 NBA lockout](https://en.wikipedia.org/wiki/1998%E2%80%9399_NBA_lockout), [2011 NBA lockout](https://en.wikipedia.org/wiki/2011_NBA_lockout)

