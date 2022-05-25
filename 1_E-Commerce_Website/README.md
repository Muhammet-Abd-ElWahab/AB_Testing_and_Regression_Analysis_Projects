# AB Test for e-commerce website.

This project is from Udacity's Data Analysis Nanodegree Advanced track.

### Overview:
This application is written with Python script using Numpy, Pandas and Matplotlib libraries to import data from csv files and explore it by:


* Gathering, assessing and cleaning data trying to understand more details about it and identify any issues and modify the dataset for easy and fast analysis.
* Making AB test using (conditional probability, p-value, z-score and logistic regression) to check which hypothesis that we can accept.

### The main target from this application is to help the company understand if they should:

*   Implement the new webpage.
*   Keep sing the old webpage.
*   Perhaps run the experiment longer to make better decision.

### Dataset descriptions:

*	user_id: the unique identifier for each patient.
*   timestamp: Time stamp when the user visited the webpage.
*   group: In the current A/B experiment, the users are categorized into two broad groups
        - The control group users are expected to be served with old page.
        - The treatment group users are matched with the new page.
*   landing_page: It denotes whether the user visited the old or new webpage.
*   converted: It denotes whether the user decided to pay for the company's product. Here, 1 means yes, the user bought the product.	
