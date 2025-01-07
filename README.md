# 30DayDevOpsProject

Day2

1. Create AWS Account if you don't have already.
2. Create Account for https://sportsdata.io/ and copy API key
3. Clone this repo.
4. Configure SNS service with a topic subscribed to EMAIL or SMS.
5. Create IAM Role and attach a policy placed in policies folder.
6. Deploy LAMBDA Function for python src code and setup environments variables in the lambda function, attaching the newly created role.
7. Create Eventbridge for the newly created LAMBDA function to schedule.