# A/B Test for cookie cats game.

This project is from Data Camp Data Analysis projects.

### Overview:

This application is written with Python script using Numpy, Pandas and Matplotlib libraries to import data from csv files and explore it by:

* Gathering, assessing and cleaning data trying to understand more details about it and identify any issues and modify the dataset for easy and fast analysis.
* Making AB test using (conditional probability, p-value, and confidence interval) to check which hypothesis that we can accept.

### The main target from this application is to answer this question:

Should we keep using the old version for cookie cats game or release the new version?

### Dataset descriptions:

*	userid: A unique number that identifies each player.
*   version: Whether the player was put in the control group (gate_30 - a gate at level 30) or the group with the moved gate (gate_40 - a gate at level 40).
*   sum_gamerounds: The number of game rounds played by the player during the first 14 days after install.
*   retention_1: Did the player come back and play 1 day after installing?
*   retention_7: Did the player come back and play 7 days after installing?
