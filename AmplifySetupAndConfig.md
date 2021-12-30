# Setup and config

## Step 1: Create an AWS Account
The below links are from the ExamPro channel on YouTube

At a minimum create the account, which will require you to entere a credit card number. The free tier limits in AWS are extremely generous, and you should not be charged.

For safety, and to follow best practices follow all of the AWS videos below.

[Create an AWS account](https://www.youtube.com/watch?v=sNByVUDvGTw&list=PLBfufR7vyJJ4fOplWPOtYqRyQ6YPMsBsF&index=13)
[Setting up a budget and billing alert](https://www.youtube.com/watch?v=vUTiJTj4mCg&list=PLBfufR7vyJJ4fOplWPOtYqRyQ6YPMsBsF&index=14)
[Change IAM users sign in link](https://www.youtube.com/watch?v=UY5YoIGHzfE&list=PLBfufR7vyJJ4fOplWPOtYqRyQ6YPMsBsF&index=15)
[Activate MFA on root account](https://www.youtube.com/watch?v=0NxVIyA0KYw&list=PLBfufR7vyJJ4fOplWPOtYqRyQ6YPMsBsF&index=16)
[Create and IAM user](https://www.youtube.com/watch?v=ce9z72cw6J8&list=PLBfufR7vyJJ4fOplWPOtYqRyQ6YPMsBsF&index=17)
[Create a password policy](https://www.youtube.com/watch?v=B3hyqtJBlmU&list=PLBfufR7vyJJ4fOplWPOtYqRyQ6YPMsBsF&index=18)

## Step 2: Install Node and NPM
[Download Node.js installer](https://nodejs.org/en/download/)
[Install Node.js and NPM on Windows](https://phoenixnap.com/kb/install-node-js-npm-on-windows)

## Step 3: Install the Amplify CLI
[Install and configure the Amplify CLI](https://docs.amplify.aws/start/getting-started/installation/q/integration/js/#install-and-configure-the-amplify-cli)

When configuring the Amplify CLI give the profile a unique name like: **us-west-2-tutorial** assuming you are creating the profile in the Oregon region.

## Step 4: Create a React Application
Create a React application using npx create-react-app and install Tailwind css at the same time

[Create a React application and install Tailwind](https://tailwindcss.com/docs/guides/create-react-app)

## Step 5: Install all NPM packages
There are several packages being used for the application that need to be installed install each package using the **npm install package-name** command at the root of your application created using create-react-app

Run the command for each of the following packages
- @headlessui/react
- @heroicons/react
- aws-amplify
- faker
- ksuid
- react-router-dom

## Step 6: Initialize the Amplify Application Backend and Frontend
Using the CLI command **amplify init** initialize the application - be warned this can take a little time after you issue the command - if it is taking a REALLY long time try pressing CTRL + C stop the process and try again. This step will initialize the cloud backend.

[Initialize the backend](https://docs.amplify.aws/start/getting-started/setup/q/integration/react/#initialize-a-new-backend)

Once you have successfully initialized the backend, add some code to the frontend to complete its configuration.

[Setup the frontend](https://docs.amplify.aws/start/getting-started/setup/q/integration/react/#set-up-frontend)

### Now you are ready to create 'Hello World'
Those six steps probably took up a lot of time. Bringing an app up to a level where you can start working is time consuming, but ultimately all the services it provides will save a lot of time, and provide a much more robust application than coding it yourself.

