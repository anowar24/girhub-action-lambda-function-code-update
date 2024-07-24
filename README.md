# Github Action Lambda Function Code Update
The GitHub Lambda Deploy Action is a streamlined GitHub Action designed to facilitate the deployment of AWS Lambda functions directly from your GitHub repository. This action automates the process of packaging your Lambda function code and deploying it to AWS, simplifying continuous integration and continuous deployment (CI/CD) workflows.


## Secrets and variables
Add the following Secrets to Repo Settings > Secrets and variables > Actions > Repository secrets

- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY
- AWS_REGION


## Configure the function details 
- Modify .github/workflows/serverless.yml with function name and branch name 
