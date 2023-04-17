# Group-2
Group Collaboration

**We have upload all our code into one master file: Project_1_Group_2_FIFA_Players.ipynb. You will be able to run this one code in respect of all four questions**

**Project Title**: FIFA Soccer Analysis – insights into European clubs and their players 2017 vs 2021 

**Team Members**: 
 * Sandhalie Fernando
 * Cassie Guo
 * Sandy Berahim
 * Graham Meadon 

 
**Project Description**: 
Soccer is a global sport that has billions of followers around the world. The European soccer clubs are of considered some of the best in the world and attracts the best players in the world to their leagues every year. 

The purpose of the analysis is to provide insights on these clubs and their players as to identify if there are any trends that aspiring clubs can adopt if they want to complete at the elite level. 

The analysis will also focus on two of the most influential players of the modern era – Lionel Messi vs Cristiano Ronaldo and identify how their skills have changed over time and the impact that has had on their team’s fortune in the UEFA Champions league. 

**Research Questions to Answer:**

**Question 1:** 
 * Correlation analysis between team players' wage and their overall performance, try to figure out wage will be the key factor to create a   competitive team： high salary will stimulate team players to have high performance.
 Outcome 1: These two variables have a positive correlation by curve fitting because as wage increases, so does overall scores. And Overall performance above 85, their wage increased dramatically.

 * Compared with overall average salary, to find the team players' golden age to have outstanding income (above average wage).
   Outcome 2: Average wage of overall players in Year 2021 is: €8,675.67 and their Golden age: 21-28 years old.

 * By Correlation analysis, to figure out whether Team players’ BMI (body mass index) will affect their Overall performance?
   Outcome 3: There is a weakly positive correlation between Players BMI and their overall performace. The BMI is mainly concentrated around 20-26.

**Question 2:** 
 * Sample analysis of top 5% of the players to see if some important attributes have been important or not across the FIFA dataset e.g. are the top 5% players of FIFA 21 faster (higher Acceleration and Agility) compared to FIFA 17.  
 * The trend of attributes is also an important indication of how some attributes are necessary for players to win games e.g. if top 5% players have higher Ball Control it would indicate that the game is more focused on the technique rather than the physical aspect). 

**Question 3:**
 * Base on the 2021 EPL result, analyse the winning club and its team member performance and how the    club spending affect the performance. 
   * What we are trying to find out if a club were to win the 2021 English Premier League has to do        with the club spending.
   * The type of player each club get based on the spending.
   * How does these players contribute to the club performance.

* Outcome for question 3:
   * Based on the analysis, we can say in this case that having to spend the most money does not equivalent to winning the league. We can also concluded that the older the age, the more experience and performance each player is. Overall, the winning recipe to win in a league is not just how much you spend on the player but to have the experience player playing in the right position in order to maximise the club performance.

**Question 4**:
 * Historical comparison between Messi and Ronaldo between 2017 to 2021 analysing:
   * What skill metrics changed the most over the period?
    * Key findings from the analysis:
      * Messi has had the more consistent overall performance score when compared to Ronaldo however both have maintained the same average overall performance score           over the period
      * Messi has been the higher valued player throughout his career when compared to Ronaldo
      * Ronaldo has scored more goals on average for the period compared to Messi although it is only a marginal difference 
      * Messi has a significantly better goal assists average over the period compared to Ronaldo
   
   * Key attributes comparison for each player
    * Key findings from the analysis:
      * Over the period both Ronaldo and Messi have performed similar across the Key Performance Metrics of Pace, Shooting, Dribbling, Defending and Physicality
      * The data suggests that over the period Ronaldo has performed more consistently across the Key Performance Metrics with less variations between his lower and           upper quartiles when compared to Messi however Messi has the higher Median score across the years
      * Over the periods Defending have been each players’ weakest point and forms the outliers in the data - this will be removed from the analysis going forward
   
   * How the two attributes and performance metrics has impacted their overall performance rating vs goals scored and assists vs value in Euros?
    * Key findings from the analysis:
      * The data suggests that both Messi and Ronaldo have areas within the metrics where they are the top performer over the period:
         * Messi performs best over time in: Passing, Dribbling
         * Ronaldo performs best over time in: Pace, Shooting, Physicality
      * The skills that have changed the most overtime over for each player
         * Improvement 
             * Messi - Passing and Defending where Messi overtook Ronaldo was in Defending
         * Reduction
             * Messi and Ronaldo - Pace has reduced but that is to be expected considering they are aging 5 years in the data
      
      * As identified in the previous analysis, the data suggests that Ronaldo is more consistent over the period in the metrics however the analysis identifies               that Messi has found areas of marked improvement

 * Question 4 conclusion 
   Who the GOAT between Messi and Ronaldo is a topic that has been discussed for a very long time and the hope was with this Data Analysis that this question could be    answered... 

   It is worth noting that the analysis undertaken is limited as it only assesses the two players over the period from 2017 to 2021 but having said that, the data        suggests there are clear distinctions identified between the two players that someone can use to make the case that one player is better than the other... 

   However, it is my position that over this period both have been excellent players with no clear-cut determination on who the best player is:
      * Both players have remarkably similar attributes with Messi being a more skilled player and Ronaldo a more power-based player. 
      * Both players have remained consistent in key metrics with Messi improving in certain areas whilst Ronaldo outperforms Messi in more areas.
      * Both players score a lot of goals for their country and clubs with Ronaldo scoring slightly more on average over the period.
      * The only area where Messi has the edge is on Goal Assist where he significantly outperforms Ronaldo.
 
   The challenge with concluding on who the better player is that whilst data and stats can tell a story, soccer is not a game played on paper and so other attributes    that cannot be measured potentially play a more significant role. 

   As it was noted in the analysis, Messi has always been the higher valued player. A person can potentially conclude that over time Messi has been the more              valued/(better?) player because it is more than just his skill that he brings to the team that makes him so valuable. An example of this could be his relative          performance on goal assists which could indicate his focus is on ensuring his team performs well vs his individual record. But is money really the true measure of      on who the the better player is?

   Fundamentally the debate will continue for a long time and will only really be decided by the passage of time and the future performances of both players.

Datasets used:  
 * https://www.kaggle.com/datasets/stefanoleone992/fifa-21-complete-player-dataset
 * https://www.topendsports.com/sport/soccer/list-league-uefa.htm
 * https://www.messivsronaldo.app/calendar-year-stats/
 * Providing context around Soccer positions: https://the18.com/soccer-learning/soccer-positions-explained-names-numbers-and-roles  

**Defenders:**
 * GK – Goalkeeper
 * SW – Sweeper
 * CB – Centre-back / Centre Full-back / Central Defender
 * RB/LB – Right and Left Full-backs
 * RWB/LWB – Right and Left Wingbacks 

**Midfield**
 * DM – Defensive / Holding Midfielder
 * CM – Centre Midfielders
 * AM – Attacking Midfielders
 * RW/LW – Wide Midfielders / Wingers

**Forwards**
 * CF – Centre Forward/ Second Forward / Second Striker / Support or Withdrawn Striker 
 * S – Striker  
