# American Express Default Prediction Competition

Whether out at a restaurant or buying tickets to a concert, modern life counts on the convenience of a credit card to make daily purchases. It saves us from carrying large amounts of cash and also can advance a full purchase that can be paid over time. How do card issuers know we’ll pay back what we charge? That’s a complex problem with many existing solutions—and even more potential improvements, to be explored in this competition.

Credit default prediction is central to managing risk in a consumer lending business. Credit default prediction allows lenders to optimize lending decisions, which leads to a better customer experience and sound business economics. Current models exist to help manage risk. But it's possible to create better models that can outperform those currently in use.

In this competition, I’ll apply my machine learning skills to predict credit default. Specifically, I will leverage an industrial scale data set to build a machine learning model that challenges the current model in production. Training, validation, and testing datasets include time-series behavioral data and anonymized customer profile information. It's encouraged to explore any technique to create the most powerful model, from creating features to using the data in a more organic way within a model. The final model will help create a better customer experience for cardholders by making it easier to be approved for a credit card.

## Description

•	Predicted credit default probability using an industrial scale dataset including time-series behavioral data and anonymized millions of customer information to optimize lending decisions and minimize credit risk

•	Conducted feature engineering to construct more than 2200 features, including summary statistics features such as order statistics, lagging features, and MoM behavior shifting among 13 consecutive monthly credit card statements

•	Considered feature combinations and used LightGBM, CatBoost, and transformers with weighted average ensembles and pseudo label to get credit default predictions with mean rank ordering measures around 0.799 and ranked 105/4875 (top 2%) on Kaggle



## Getting Started

### Dependencies

* Kaggle Notebook

## Authors
Siquan Wang

sw3442@cumc.columbia.edu

## License

N/A

## Acknowledgments

competition website:
* https://www.kaggle.com/competitions/amex-default-prediction
