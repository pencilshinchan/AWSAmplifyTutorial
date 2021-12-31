## AWS Amplify Basic Tutorial

This is a basic tutorial for AWS Amplify that will concentrate on the Auth and API that will be added via the Amplify CLI

A simple, but somewhat contrived example of a purchase order system will be created.

## Step 1: Prerequisites

Before you get going - if you are unfamiliar with React or Tailwind... it would be a good idea to get your feet wet with some React and Tailwind knowledge.

First get to know React and React Hooks
- [Free React YouTube Course](https://www.youtube.com/watch?v=QFaFIcGhPoM&list=PLC3y8-rFHvwgg3vaYJgHGnModB54rxOk3)

Next get to know Tailwind
- [Free Tailwind Course](https://www.youtube.com/watch?v=4wGmylafgM4&t=1276s)
- [From the Creators of Tailwind](https://www.youtube.com/watch?v=elgqxmdVms8&list=PL5f_mz_zU5eXWYDXHUDOLBE0scnuJofO0)


## Step 2:  First things first

Before we can do anything you will require an AWS account, and all software and packages need to be installed and configured.

[Project set up and configuration](https://pencilshinchan.github.io/AWSAmplifyTutorial/AmplifySetupAndConfig)

## Step 3: Set Up and Configure Authorization and Authentication

- [Auth set up and configuration](https://pencilshinchan.github.io/AWSAmplifyTutorial/AuthConfig)

## Step 5: Create a custom authentication system

Create files for SignUp, ConfirmSignUp, SignIn and ForgotPassword
- Add routes to App.js
- Test that the routes are working

Add code to SignUp, ConfirmSignUp, SignIn and ForgotPassword components.
- [Create Auth Pages](https://pencilshinchan.github.io/AWSAmplifyTutorial/AuthPages)

## Step 6: Create an Admin system to add and remove users from groups

Using the Admin Actions API see what groups users belong to and add and remove them from groups


### What kind of stuff will we do?

- Create a React application using npx create-react-app
- Install all necessary npm packages including the AWS Amplify command line interface (CLI)
- Create and configure an AWS Account and AWS Amplify project
- Add Auth via the CLI
  - Create Admin Actions API
  - Create user groups and precedence
  - Create a post confirmation lambda function to automtatically add users to the Everyone group on sign up
- Create custom components for SignIn, SignUp, ForgotPassword, ConfirmSignUp and an ErrorNotification
- Create custom components to use Admin Actions
  - View all the members of a group
  - Add or remove group members
- Understand the access patterns for the application
- Use noSQL workbench to visualize the access patterns and assist in designing a single table design
- Create a GraphQL API

