## Pre-requisites
- Node.js v6.5.0 or later.
- Serverless CLI v1.9.0 or later. You can run npm install -g serverless to install it.
- An AWS account. If you don't already have one, you can sign up for a free trial.
- Set-up your Provider Credentials. (serverless config credentials --provider aws --key <<>> --secret <<>>)

## Create a new Serverless Service/Project
$ serverless create --template aws-nodejs --path my-service

Change into the newly created directory
$ cd my-service

## Deploy
serverless deploy -v
