# Mega Millions Project

The aim of this project is to examine the frequencies of all the past winning lottery numbers that were selected and determine whether some numbers were selected disproportionately more than others.

## Introduction
Mega Millions is an American lottery game in which the goal is to select 5 game balls from one pool with an additional ball from a sep pool(Mega Ball).  The aim is to match as many numbers as you can to a bi-weekly drawing result.  The number range of balls in the pools has changes a few times, which I refer to as different "Versions".

There are a total of 4 different versions and the differences are lists as such:

- (Version 1: 05/15/2002 - 06/21/2005) There are 52 white balls and 52 Mega balls
- (Version 2: 06/24/2005 - 10/15/2013) There are 56 white balls and 46 Mega balls
- (Version 3: 10/22/2013 - 10/27/2017) There are 75 white balls and 15 Mega balls
- (Version 4: 10/31/2017 - Present) There are 70 white balls and 25 Mega balls

## Data
- The data was collected from data.gov
(https://catalog.data.gov/dataset/lottery-mega-millions-winning-numbers-beginning-2002)

- This data include drawings dating back to 5/15/2002

## Results
A chi-square analysis was performed on the Mega Balls for each of the versions. The resulting p-values show that the numbers are not significant at the 0.05 threshold.  This indicates that according to the chi-square test, we have failed to reject the null hypothesis and we therefore can conclude that the Mega ball numbers are drawn at random.

- The Mega ball for version 1 had a p-value of 0.108
- The Mega ball for version 2 had a p-value of 0.992
- The Mega ball for version 3 had a p-value of 0.686
- The Mega ball for version 4 had a p-value of 0.923