# Notes on "How Google Does Machine Learning"

## Quotes

- Avoid the trap of thinking of building monolithic "one model solves the whole problem" solutions.
  - models are built to solve smaller problems
- What kind of problems can it solve?
  - hard-coded rules are difficult to maintain, so try machine learning
  - RankBrain: search ranking for google search
  - Replacing heuristic rules by ML, that's what ML is about.
  - You don't think about coding up rules, you think about training models based on data.
  - You don't think about fixing bug reports by adding new rules, you think in terms of continuously training the model as you get new data.
  - You start by thinking about how to collect the data to make it an ML problem?

## Resources

- [Frame a problem as a machine learning problem or otherwise](https://www.datasciencecentral.com/frame-a-problem-as-a-machine-learning-problem-or-otherwise/)
  - What am I trying to predict?
  - What are my outcomes?
  - What data can I use to train my model, and what are my inputs?
  - What market factors can I train my model with to predict the outcomes?
- [Creating a Data Strategy for Machine Learning as a Product Manager](https://medium.com/agileinsider/creating-a-data-strategy-for-machine-learning-as-a-product-manager-b56b7890ecf7)
- [9 Real-World Problems that can be Solved by Machine Learning](https://marutitech.com/problems-solved-machine-learning/)
  - Identifying Spam
  - **Making Product Recommendations**
    - recommender system
  - **Customer Segmentation**
    - Customer segmentation, churn prediction and customer lifetime value (LTV) prediction
    - Prediction for individual marketing offers and incentives
    - e.g. given the pattern of behavior by a user during a trial period and the past behaviors of all users
      - identifying chances of conversion to paid version can be predicted
  - Image & Video Recognition
  - Fraudulent Transactions
  - Demand Forecasting
  - Virtual Personal Assistant
  - **Sentiment Analysis**
  - Customer Service Automation
- [Data validation for machine learning](https://blog.acolyer.org/2019/06/05/data-validation-for-machine-learning/)
- [4 Stages of ML Modelling Cycle](https://www.linkedin.com/pulse/4-stages-machine-learning-ml-modeling-cycle-maurice-chang)
- [ML Strategy for Machine Learning Projects](https://medium.com/@ssatyajitmaitra/ml-strategy-for-machine-learning-projects-7b674e3bbb9)
- [Before You Can Have a Machine Learning Strategy, You Need a Data Strategy](https://medium.com/machine-learning-in-practice/first-things-first-you-need-a-data-strategy-before-you-can-have-a-machine-learning-strategy-366f8439aedf)
- [The Surprising Truth About What it Takes to Build a Machine Learning Product](https://medium.com/thelaunchpad/the-ml-surprise-f54706361a6c)
  - Defining KPIs
  - Collecting Data
  - Infrastructure
  - Optimizing ML Algorithm
  - Integration
