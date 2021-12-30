# Authorization and Authentication setup and config

## Step 1: Add Auth Via the Amplify CLI
- Add link to Add Auth Video

A number of items were configured by going through the process outlined in the video. A Cognito user pool was created, and 4 user groups were created in the pool and given precedence. The Admin Actions API was created and permissions were given to the members of the Admin group to be able to execute the functions of the API. 

**NOTE:** the IAM users created when creating your AWS account and the Cognito user pool users are seperate.

- Add link to Auth Assets Video

## Step 2: Configure the Post Confirmation Lambda Function

In order for the lambda function to operate correctly (and not throw an error) it needs to have an additional inline policy that we will create.
- Add link to Configure Lambda Policy
