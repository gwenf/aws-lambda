# Instructions:

1. cd into this folder: `cd serverless`
1. Install the serverless framework globally: `npm install -g serverless@beta`
1. Create the scaffold: `serverless create --template aws-nodejs`
1. You need your 'Access Key ID' and 'Secret Access Key' from your user when you create a new user in IAM (Identity and Access Management).
1. *Make sure the user has a policy attached that allows for administrator access.*
1. (Follow this tutorial on AWS to configure the AWS command line interface.)[http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html]
1. Deploy to AWS Lambda (and any other microservices, if configured): `serverless deploy`

*It will automatically deploy and create S3 Bucket and Lambda for you.*