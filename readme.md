
This script is designed to take TV listings from zap2it and convert them to xmltv, run in AWS Lambda, and upload to an S3 bucket for applications like Tivimate.

Simply add zap2it credentials to zap2itocnfig.ini and country, zipcode, historical guide days, and lineup info and upload to AWS Lambda.

Then schedule the Lambda function in AWS EventBridge to run at your desired intervals.

