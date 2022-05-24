# Collaborative-Problem-Solving


**Levels_PP_Logs_Lab.csv**
Level attempts with start/end times, level duration, and if trophy was won
- 1220 examples

**equally_weighted_60_10.csv**
This file is a modified version of "Levels_PP_Logs_Lab.csv" according to the description from:
- 789 examples

Multimodal, Multiparty Modeling of Collaborative Problem Solving Performance
https://www.dropbox.com/s/pf3kwr08c9j5s0j/subburaj-icmi20.pdf?dl=0

First, we adjusted the end time of the level-attempt by 10s in order to avoid peeking into the behaviors that occurred when the team wins the trophy or quits the level (e.g. celebration of level completion or clicking to exit the level). We deemed 10s to provide a sufficient buffer by analyzing level attempts from 20 teams at random. End times were not adjusted if time ran out in the block. We then selected data from 60s prior to the end time. We chose a 60s interval after comparing model performance (Section 4) on intervals of different sizes (15, 30, 45, 60, 90s), which all yielded similar performance. Level attempts under 60s (431 instances out of 1220) were not considered germane for modeling purposes since they reflect exceedingly easy levels or cases where the team entered a level and immediately exited. This resulted in 789 instances, of which 53.2% were successfully solved.
