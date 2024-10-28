Iris dataset:
https://archive.ics.uci.edu/dataset/53/iris

Read about XGBoost hyperparameters:
https://docs.aws.amazon.com/sagemaker/latest/dg/xgboost_hyperparameters.html

Use POST method for API

Platform used to test API:
https://www.postman.com/

to test API:

request body:
    {"x1": 7.0,"x2": 3.2,"x3": 4.7,"x4": 1.4}
go to stages and copy invoke URL

Platform used to test API:
https://www.postman.com/

create new collection. select POST method and paste the invoke URL

output:
{
    "prediction": 2
}
