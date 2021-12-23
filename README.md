# kafka-ui-msk
kafka-ui for MSK

prerequisite: 
1. AWS MSK installed with IAM priviliges (see https://aws.amazon.com/blogs/big-data/securing-apache-kafka-is-easy-and-familiar-with-iam-access-control-for-amazon-msk/)
2. set all env variable according to configuration :
$BOOTSTRAP_SERVERS - the IAM servers from the kafka configuration
$AWS_PROFILE_NAME/$AWS_ACCESS_KEY_ID/$AWS_SECRET_KEY - the aws usermname of the priviliged account (with the priviliges to access MSK)

3. docker-compose up -d
4. localhost:8080
