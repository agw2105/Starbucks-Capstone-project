# Starbucks-Capstone-project
Capstone project for the Udacity Machine Learning Engineer nanodegree


## OVERVIEW

Starbucks is a global coffee chain with millions of customers worldwide. The diversity of these customers is reflected not just in their demographics, location, and coffee preferences, but in how they respond to promotions and advertisements. The Starbucks app is a platform to reach the broadest possible customer base and entice them to choose Starbucks as their caffeinator of choice. This is achieved through seamless online ordering, customer service, and special offers. Special offers, such as discounts, BOGO, and bonus points, can boost sales by encouraging a user to purchase a product that they otherwise might not have.

## DATASETS AND INPUTS

There are 3 main sources of data from which the model will be built:

 1.)  portfolio.json: Contains offer IDs and meta data about each offer (duration, type, etc.)
      Contains the following fields: 
   * id (string) - offer ID
   * offer_type (string) - type of offer (BOGO, discount, etc.)
   * difficulty (int) - minimum required to spend
   * duration (int) - days offer is open
   * channels (list of strings)

2.) profile.json: Demographic data for each customer
    Contains the following fields:
   * age (int) - age of customer
   * became_member_on (int) - date when customer created app account
   * gender (str) - customer gender (M/F/O)
   * id (str) - customer ID
   * income (float) - customer’s income

3.) transcript.json: Records for transactions, offers received, offers viewed, and offers completed. 
    Contains the following fields:
   * event (str) - record description (transaction, offer received, etc.)
   * person (str) - customer ID
   * time (int) - time in hours since start of test (at time t=0)
   * value (dict of strings) - offer ID or transaction amount depending on the record


## REQUIREMENTS
pandas
numpy
scikit-learn
matplotlib
seaborn
math
json

## ADDITIONAL FILES
* Starbucks_capstone_notebook.ipynb: The Jupyter notebook where all of the work is shown
* proposal.pdf: Project proposal file
* report.pdf: A summary of the project and findings
