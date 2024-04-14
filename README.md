# Banking Dataset Analysis

This analysis is based on a banking dataset from a Portuguese banking institution that contains data related to direct marketing campaigns (phone calls) from May 2008 to November 2010. The goal is to predict if the client will subscribe to a term deposit or not.

## Data Overview

The dataset contains 45,211 rows and 18 columns, with the following variables:
- **Client Information**
  - age: Age of the bank client
  - job: Type of job the client has
  - marital: Marital status of the client
  - education: Level of education of the client
  - default: Whether the client has credit in default
  - balance: Average yearly balance in euros for the client
  - housing: Whether the client has a housing loan
  - loan: Whether the client has a personal loan
- **Communication Information**
  - contact: Type of communication used to contact the client
  - day: Last contact day of the month
  - month: Last contact month of the year
  - duration: Duration of the last contact in seconds
  - campaign: Number of contacts performed during this campaign and for this client
  - pdays: Number of days that passed by after the client was last contacted from a previous campaign
  - previous: Number of contacts performed before this campaign and for this client
  - poutcome: Outcome of the previous marketing campaign
- **Target Variable**
  - y: Whether the client has subscribed to a term deposit

## Questions

1. What is the distribution of age among the clients?
2. How does the job type vary among the clients?
3. What is the marital status distribution of the clients?
4. What is the level of education among the clients?
5. What proportion of clients have credit in default?
6. What is the distribution of average yearly balance among the clients?
7. How many clients have housing loans?
8. How many clients have personal loans?
9. What are the communication types used for contacting clients during the campaign?
10. What is the distribution of the last contact day of the month?
11. How does the last contact month vary among the clients?
12. What is the distribution of the duration of the last contact?
13. How many contacts were performed during the campaign for each client?
14. What is the distribution of the number of days passed since the client was last contacted from a previous campaign?
15. How many contacts were performed before the current campaign for each client?
16. What were the outcomes of the previous marketing campaigns?
17. What is the distribution of clients who subscribed to a term deposit vs. those who did not?
18. Are there any correlations between different attributes and the likelihood of subscribing to a term deposit?

## Data Analysis

The analysis will involve exploratory data analysis, data preprocessing, feature engineering, and machine learning model building to predict if the client will subscribe to a term deposit or not. The analysis will also include insights and recommendations for the bank to improve their marketing campaigns.
