---
layout: page
title: Newborn Sleep
permalink: /baby-sleep/
---
We started tracking our newborn baby's sleep about two weeks after birth. We stopped tracking when he entered daycare, at around six months.

|![sleep over time](/assets/sleep-overall.png)|
|---|
|Code for this visualization taken from [here](https://github.com/jiuguangw/Agenoria), discovered through [this reddit post](https://www.reddit.com/r/dataisbeautiful/comments/e1kg7t/visualization_of_sleeping_patterns_in_a_newborns/).|

### Sleep Training
We started sleep training when our son was about 4 months old. Within a week it had had the expected benefit of making the bedtime routine faster, easier, and calmer. A less expected benefit was that he improved in his ability to sleep over the course of the night. Starting at around 7 weeks, he had plateaued at ~6 hours of uninterrupted sleep. After sleep training this started to steadily increase. This trend continued even after we stopped tracking, reaching ~11 hours a night, where it has held since. If he woke in the night and cried for more than a couple minutes, we would still go to comfort and feed him as we had before beginning sleep training. This was a result of changes at naptime and bedtime, not throughout the night. 

|![effect of sleep training](/assets/sleep-training.png)|
|---|
|Vertical red line indicates the day we started sleep training.|



### Method
Sleep was recorded with a slack app. Slash commands "/asleep" and "/awake" were used to mark changes in state, and the optional message after the command was used to note if the time he woke up or fell asleep was different from the time when we recorded it. 

Data entered in slack was sent to a google sheets file. Subsequent analysis and visualizaton of the spreadsheet was done in python.