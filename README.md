# Udacity-Starbucks

Project 3 of the Udacity Machine Learning Engineer Nanodegree Program.

## Datasets and Inputs

The data was initially contained in three files:
- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
- profile.json - demographic data for each customer
- transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:
portfolio.json
- id (string) - offer id
- offer_type (string) - type of offer ie BOGO, discount, informational
- difficulty (int) - minimum required spend to complete an offer
- reward (int) - reward given for completing an offer
- duration (int) - time for offer to be open, in days
-  channels (list of strings)

profile.json
- age (int) - age of the customer
- became_member_on (int) - date when customer created an app account
- gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
- id (str) - customer id
- income (float) - customer's income

transcript.json
- event (str) - record description (ie transaction, offer received, offer viewed, etc.)
- person (str) - customer id
- time (int) - time in hours since start of test. The data begins at time t=0
- value - (dict of strings) - either an offer id or transaction amount depending on the record

## Files

The stages of the project were Data Wrangling, Feature Engineering, machine learning application. 
Each major stage of the project was implemented in a separate notebook.
1. Starbucks Capstone Challenge.ipynb
2. Starbucks - Data Wrangling.ipynb
3. Exploratory Analysis.ipynb
4. Starbucks - Features Engineering.ipynb
5. Starbucks - Linear Learner.ipynb
6. Starbucks - XGBoost.ipynb 

In addition to the Jupyter Notebooks files, there are two pdf files, one for proposal (`proposal.pdf`) and another for report (`project.pdf`).

## References

UDACITY - Machine Learning Engineer Nanodegree: https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t
