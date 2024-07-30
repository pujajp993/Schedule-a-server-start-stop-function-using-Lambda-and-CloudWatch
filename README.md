# Schedule-a-server-start-stop-function-using-Lambda-and-CloudWatch

Goal: Automate the start/stop of ec2 instance using lambda and CloudWatch services.

1. Create required IAM policies and Roles
2. Create function under aws-lambda which determines the start/stop process of specific ec2-instance.
3. Test the function created under lambda
4. Create rules inside CloudWatch services which trigger the functions created in lambda {cron}
