# apigateway-cloudformation


demo 

aws cloudformation deploy --template-file test.yaml --stack-name apigateway --capabilities CAPABILITY_NAMED_IAM --parameter-overrides S3Name=<s3> stage=<stage> 
