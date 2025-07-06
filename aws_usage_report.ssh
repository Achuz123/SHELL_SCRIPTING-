/bin/
######################################################
# Author :Achuth B
#Date :6/7/24
#
#To report the AWS usage
#AWS EC2
#AWS S3
#AWS Lambda
#AWS IAM USERS
#######################################################

set -x

# list s3 buckets
echo "List Of S3 buckets"
aws s3 ls
# list ec2 instance
echo "List Of EC2 "
aws ec2 describe-instances|jq '.Reservations[].Instances[].InstanceId'
 
# list iam user
echo "List Of Iam"
aws iam list-users

# list lambda
echo "List Of lambda "	
aws lambda list-functions

