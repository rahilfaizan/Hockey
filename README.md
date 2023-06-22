# Hockey
Hockey game assesment for sportlogiq
Introduction
Important Info:

Hi and welcome to the Sportlogiq DA Questionnaire! The goal with this questionnaire is to assess your problem solving, hockey knowledge, and coding/stats abilities and your (hopeful) fit with some of our day-to-day tasks. If you find yourself stuck or unsure on a question, showing your work and explaining your problem solving/decision making is still highly recommended.

Libraries:

You'll want to import libraries such as numpy, pandas, a plotting library like plotly/matplotlib, and a stats library of your choosing (sklearn for example)
Data Info:

There are two data files. One has a condensed event set from a randomly chosen hockey game and the other contains Expected Goals values (xg) provided only for shots that successfully hit the net. If an xg value doesn't correspond to a shot event, it should not be counted

X and Y Coordinates are in Feet and are adjusted such that both teams shoot in the same direction

Line Carry events are tagged when the puck is carried over either blue line or the centre ice red line

Binary columns that have values of 0 or 1 indicate 0=No, 1=Yes

Successfull passes are completed passes, successful shots are shots on net

Please show all work, keep written answers succinct and to the point and most of all, thanks for your time and good luck!

 
Q1)
a) Who won the game & what was the score?
b) Who won the Expected Goals (xg) battle & what was each team's total xg?
c) What do these two answers tell us about how the two teams played?
A1)
a)
b)
c)
 
Q2)
a) Which possessionid had the highest total successful passes?
b) How many successful passes were there and why do you think this specific possession had so many?
A2)
a)
b)
 
Q3)
a) Using the event data provided along with x/y coordinate columns, can you identify the likely xCoord of each blueline?
A3)
a)
 
Q4)
a) Create a subset of all shot attempts in the game and then with the plotting library of your choice, produce one scatter plot per team to illustrate where their shots were located and highlight any goals that were scored.
b) Describe in 2-4 sentences your findings for each team.
A4)
a)
b)
 
Q5)
a) If the centre of the net that teams shoot at is located at xCoord=89, yCoord=0, create a column for the distance from each shot to this point. What is the distance of the furthest goal scored in the game?
b) What is the expected goals (xg) value of this furthest goal and what do you think contributed to this xg value?
A5)
a)
b)
 
Q6)
a) If a "Shot Assist" is defined as a sequence of events with the same possessionid where there is: 1) a successful pass followed by 2) a successful reception by a teammate and then without giving up the puck 3) the receiving player has a shot attempt, create a column flagging shots that have a Shot Assist. Which player(s) had the most assisted shots in the game and how many assisted shots did they have?
Hint: This can be done using iterrows() or using shift() logic. Consider if you should include ALL event rows and beware of sorting!
A6)
a)
 
Q7)
a) What is highest xg among the goals that were scored and why do you think it was this high?
b) Did this goal have a shot assist?
A7)
a)
b)
 
Q8)
a) Consider other shots with high xg values, without engineering any additional features (aside from the columns you've already been asked to create in the questions above), use a statistical technique of your choice to show the highest predictors of a goal within this dataset.
b) Please explain your reasoning for choosing this technique and explain your findings
Hint: look back at the columns you were asked to create, along with the columns already provided in the event dataset, what would lead to dangerous shot attempts?
A8)
a)
b)
 
Before you submit:
Please check that you have answered all questions (and sub-questions) to the best of your ability and that every answer can be clearly traced back to work that is shown. If you were unable to produce an answer, please describe and show the work you tried.

Thanks for your time, effort and interest!
