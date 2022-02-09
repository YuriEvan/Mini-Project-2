### Mini-Project-2 (Statistical Analysis, using Python) Overview

This is a _Mini Group Project 2_ which consist of 5 members (Evan, Grace, Michelle, Desmond & Pauline). <br>

Roles for this Mini-Project-2 <br>
Evan - data prepration / model development & validation <br>
Grace - data prepration / model iterations <br>
Michelle - data prepration / documentation & presentation  <br>
Desmond - model iterations / documentation & presentation <br>
Pauline - model iterations / model development & validation <br>

#### Introduction - Cookie Cats
- _Play and complete levels_ (Cookie Cats is a popular mobile puzzle g ame where players complete a task and level up)
- _Encounter Gates_ (While players completes levels, they encounter gats after completing certain number of levels)
- _Wait at the gate_ (Gates force players to wait for sometime before they can play further or make in game purcahses)

#### Business Problem
- Even though Cookie Cats overall popularity is gorwing over time with players subscribing to try ou the game, but,
- Revenue from in-game purchases has been declining over time
- Total number of active players are also declining with players uninstalling the game after playing for few days

#### Project objectives
 _Business Objective_ 
 - Increase YoY revenue from game purcahses by increasing retention rate of gamers <br>

 _Hypothesis_ 
- Company CEO believes that players are churning because the first gate encountered at level 30 is too early which forces players to wait before they can proceed further in the game <br>
- In order to increase player retention rate, developers ran AB -test by moving the first gate from level 30 to level 40 for some players <br>
• i.e., group A would encounter the gate at level 30 and group B would encounter the gate at level 40

#### Mini Project 2 questions

1.Detect and resolve problems in the data (Missing value, Outliers, Unexpected value, etc.) <br>

2.Plot summary statistics and identify trends to answer basis business questions <br>
i. What is the overall 7-day retention rate of the game? <br>
ii. How many players never played the game after installing? <br>
iii. Does the number of users decrease as the level progresses highlighting the difficulty of the game <br>

3.Generate cross tab for two player groups to understand the difference in the 1-day and 7-days retention rate & total number of game rounds played <br>

4.Perform two-sample test for groups A and B to test statistical significance amongst the groups in the sum of game rounds played i.e., _if groups A and B are statistically different_ <br>
i. Check the assumptions of two sample test <br>
a.Normal distribution-Apply Shapiro test <br>
b.Homogeneity of variance–Apply Levene's Test <br>
ii. Apply the relevant two sample significance test method based on the results from test for normality and homogeneity <br>

5.Based on significance testing results, if groups A and B are statistically different, which level has more advantage in terms of player retention? <br>

6.Bonus question:Use bootstrap resampling to plot retention rate distribution for both groups to visualize effect of different version of the game on retention <br>


#### Mini Project 2 Answers

*Answers to the questions above, please click on the link below* <br>
[Click here to view code](https://github.com/YuriEvan/Mini-Project-2/blob/main/Mini_project_2_Final_Group%208.ipynb)


#### Remarks

I have graduated from BCG RISE course in October 2021. The answers may not be 100% perfect, as I am a learner and have just started learning python coding <br>
