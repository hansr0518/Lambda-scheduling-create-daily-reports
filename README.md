# Lambd scheduling job in AWS 
### Here are two examples for Lambda scheduling

Eg1. Create daily summary report using Lambda scheduling
> Count the number of customer per day for the most recent 3 months.

> Create the table into target DB.

Eg2. Stop EC2 instance 
> When you know the instance Id, you can automatically stop it.


# Links
Lambda : https://docs.aws.amazon.com/eventbridge/latest/userguide/run-lambda-schedule.html

Add lambda function to Cloud Watch(using as a trigger)

Cloudwatch : https://www.amazonaws.cn/en/cloudwatch/

# Installation
Eg1. 
```python
import boto3
from datetime import date
```

Eg2. 
```python
import boto3
import pandas
```
