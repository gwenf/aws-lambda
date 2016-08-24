# API Gateway and Dynamo Example

### Create and Upload Function:

1. `aws lambda create-function \`
1. `--region us-east-1 \`
1. `--function-name LambdaFunctionOverHttps  \`
1. `--zip-file fileb://LambdaFunctionOverHttps.zip \`
1. `--role arn:aws:iam::367226884129:policy/service-role/AWSLambdaBasicExecutionRole-b7f9a705-d7ce-4a86-ae62-c9f7dc3b6702  \`
1. `--handler LambdaFunctionOverHttps.handler \`
1. `--runtime nodejs4.3 \`
1. `--profile adminuser`

### Invoke Function:

1. `aws lambda  invoke \`
1. `--invocation-type Event \`
1. `--function-name LambdaFunctionOverHttps \`
1. `--region us-west-2 \`
1. `--payload file://file-path/input.txt \`
1. `--profile adminuser` 
1. `outputfile.txt`