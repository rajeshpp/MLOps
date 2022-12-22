# Model Drift

Model performance on a longer run (sometimes very quickly) gets deteriorated due to the changes in the data and relationships between input and output variables.

There are certain ways that can be followed to detect and mitigate drift:
- Monitor and manage model performance.
- Continuous tracking of metrics such as accuracy and consistency and alert if there is a drift.
- Automate drift monitoring and minimize model degradation.
- Track targets through development, validation and deployment. 

Model Drift can be categorised into:

1. **Concept Drift**: When the statistical properties of the target variable itself change.
2. **Data Drift**: When the statistical properties of the predictors (underlying variables) change. </br>
    Example: Flight demand surges during the holiday seasons, airlines struggle to maintain occupancy in the off-seasons.

## How to Address this?
Only way to address this is to have a MLOps pipeline which will keep on re-training the model and giving the results of the model experiments. As soon as a model drift is identified, ML Engineer or Data Scientist needs to re-develop the model, train & test it, Deploy that into production.

Since, this is a cyclic process, automate your process as much as possible and build pipelines to do all this processes in an automated approach.
