# MLOps Project Life Cycle

MLOps Project has a Life Cycle which needs to be followed to have an effective business results. In this section we are going to discuss on several phases/stages involved in the MLOps Project Life Cycle.

![image](https://user-images.githubusercontent.com/19406666/206919780-59fae1bd-7b96-4065-8431-10950e0e8696.png)

The stages of MLOps Project Life Cycle are:
- Business Understanding
- Data Understanding
- Data Preparation
- Modeling
- Model Evaluation
- Model Deployment
- Model Consumption
- Continuous Evaluation

Now we are going to discuss on these topics in detail below. Follow us along.

## Business Understanding
- Once we have a business problem, Data Scientists & Machine Learning Engineers will start the actual work.
- The DS/ML Engineer should gain understanding of available data by discussing with Business decision-maker or product owner.

## Data Understanding
- Collect & Process all the relevant data into one place.
- Analyze the data in such a way that 
  - If the question can be answered with the existing data.
  - If the business problem can be solved with the existing data or some extra data is needed?
  - Data is of good quality without the missing values, outliers etc
- Have a continuous discussion with business stakeholders to have good quality of data and good quality of model further down the line.

## Data Preparation
<img width="730" alt="image" src="https://user-images.githubusercontent.com/19406666/207285176-c4b90b18-1afb-4243-a4fc-27c67cdf38db.png">

- Most time consuming task.
- Data preparation is needed for encoding categorical or factor variables as numerical.
### Dependent Variable Preparation
- These variables are used to predict using past data.
- Business decision can be taken based on these predictions.
- Without having clear dependent variable, we cannot move forward with the ML use case.
- This is the first and important step after business understanding.
- The data quantification happens in this step.

### Feature Engineering
- Process of deriving useful features from data set. This enables to predict dependent variables.
- To attain this, creativity and domain/business understanding are required.

### Independent variables
- As part of feature Engineering, we do encoding of categorical variable to numeric or creating multiple variables out of a single numerical variable.
- Feature Engineering, Dependent Variables selection, Independent variables selection work in combination with Feature Selection and this is an iterative process.

### Feature Selection
- Create maximum number of features and elimate them based on statistical relationship or ML Model.
- We need to predict future data based on the past data, instead of just relying on current data. 
  - Ex: To predict if a customer will buy a product after one year or not, we need his/her past data as well instead of just current salary.
- **Garbage In Garbage Out (GIGO)**: If the data is not prepared correctly, any insight coming out of it is garbage.

Data preparation and modeling are something which go back and forth, and this is mainly due to feature engineering and feature selection.

## Modeling
- Happens in parallel with data preparation.
- Diffferent ML algorithms are tried on the same dataset to find the best fit algorithm.
- To identify if a model is good fit on the data, there should be KPIs on which models are trained.

## Model Evaluation
- Once a model is finalised from the previous step, the next step is evaluating that model.
- The data set used to evaluate the model in this step is called test data.
- Depending on the problem type, evaluation technique varies.
  - **Regression problem**: Predictions are continuous values
    - **Ex**: price of a house or sales in the next quarter
    - **KPIs** are: MAE, RMSE, and R-Squared.
  - **Classification**: 
    - **Ex**: Whether the machine will fail or not, multiclass like whether a person is old, middle aged, or young based on a photo.
    - **KPIs** are: Accuracy, Precision, Recall.
- The goal of evaluation process is to find a balance between underfitting and overfitting.
  - **overfitting**: Model memorizes the data and gives best results on training data. But, the performance deteriorates when evaluated on the new data.
  - **underfitting**: Model does not do very well on the training data. 
- The whole idea is to find the best model which is balanced and giving best results on the future data. For that, we need to generalize the model on both training and test data.

## Model Deployment
- Deployed model should have the capability of stream processing and batch processing.
- Once deployed, the ML model should be available for scoring the new data.
- Model needs to be monitored and evaluated continuously.
- If there is a change in the data or change in the business/process, model lifecycle needs to be revisited.

## Model Consumption
## Continuous Evaluation
