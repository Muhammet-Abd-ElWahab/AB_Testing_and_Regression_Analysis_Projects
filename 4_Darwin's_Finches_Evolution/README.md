# Darwin's_Finch_Beaks_Evolution_AB_Testing_&_Regression.

### Overview:

This application is written with Python script using Numpy, Pandas, Statsmodels, Matplotlib and Seaborn libraries to import data from csv files and explore it by:

* Gathering, assessing and cleaning data trying to understand more details about it and identify any issues and modify the dataset for easy and fast analysis.
* Making AB test using (conditional probability, p-value, and confidence interval) to check which hypothesis that we can accept.
* Making regression analysis.


### The main target from this application is to answer this question:

* Has Finches beaks average length been evolved from 1975 to 2012?

* Has Finches beaks average depth been evolved from 1975 to 2012?

* Is there any correlation between Finches beaks length and beak length?

* Is Finches beak length statistically significant in predicting length?


### Dataset descriptions:

 Every year for the past 40-plus years, Peter and Rosemary Grant have gone to the Galápagos island of Daphne Major and collected data on Darwin's finches.We will use this data to study how the beak depth (the distance, top to bottom, of a closed beak) of the finch species Geospiza scandens has changed over time. The Grants have noticed some changes of beak geometry depending on the types of seeds available on the island, and they also noticed that there was some interbreeding with another major species on Daphne Major, Geospiza fortis. These effects can lead to changes in the species over time.In this project we are going to look at the beak depth of G. scandens on Daphne Major in 1975 and in 2012.
 
 
### Dataset columns:

* Band: Index.
* species: Finches species (fortis, scandens).
* Beak_length: Finches beak length.
* Beak_depth: Finches beak depth.
