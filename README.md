## Final Solution for JanataHack HR Analytics Hackathon
#### Private LB Rank - 37 [competition link](https://datahack.analyticsvidhya.com/contest/janatahack-hr-analytics/)

### Approach
- Mapped features like experience, company_size, last_new_job to integers to mainrtain their order in the data
- All other categorical features were one hot encoded
- Used 5-fold Lightgbm and Catboost to make predictions.Feature selections was used to remove redundant or less imporatnt features
- Blend Lgb and Catboost to get final predictions

