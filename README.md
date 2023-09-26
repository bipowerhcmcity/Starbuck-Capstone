# Udacity Starbuck Capstone

## Project Overview
Starbuck is one of the global beverage brands developed and sold worldwide. The brand has a large user base, so policies and promotional strategies are implemented to target user needs and increase product sales.

The current data provided gives us an overview of user profiles and the promotions they have received via email, viewed, and completed.

## Project Motivation
We aim to build a model to predict whether users will complete the offered promotions or not.

## Installation
- Python
- Pandas
- Numpy
- Sklearn
## File Description
### 1. Dataset:
Data files are located in folder "data/".

**portfolio.json**
-   id (string) - offer id
-   offer_type (string) - type of offer ie BOGO, discount, informational
-   difficulty (int) - minimum required spend to complete an offer
-   reward (int) - reward given for completing an offer
-   duration (int) - time for offer to be open, in days
-   channels (list of strings)

**profile.json**

-   age (int) - age of the customer
-   became_member_on (int) - date when customer created an app account
-   gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
-   id (str) - customer id
-   income (float) - customer's income

**transcript.json**

-   event (str) - record description (ie transaction, offer received, offer viewed, etc.)
-   person (str) - customer id
-   time (int) - time in hours since start of test. The data begins at time t=0
-   value - (dict of strings) - either an offer id or transaction amount depending on the record

### 2. Code and Blog:
- Starbucks_Capstone_notebook.ipynb: The Jupyter Notebook in which I performed all my work.
- Blog: https://nasal-coyote-665.notion.site/Starbuck-Capstone-Challenge-43b836620db148bf80fe8406ba2fd412
## Acknowledgement
I would like to thanks [Udacity](https://www.udacity.com/) and Starbucks(https://www.starbucks.com/) for providing me with the datasets to use for this project.
