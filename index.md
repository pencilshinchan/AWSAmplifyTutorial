## AWS Amplify Basic Tutorial

This is a basic tutorial for AWS Amplify that will concentrate on the Auth and API that will be added via the Amplify CLI

A simple, but somewhat contrived example of a purchase order system will be created.

### First things first

Before we can do anything you will require an AWS account, and all software and packages need to be installed and configured.

[Project set up and configuration](https://pencilshinchan.github.io/AWSAmplifyTutorial/AmplifySetupAndConfig)

##Set Up and Configure Authorization and Authentication

[Auth set up and configuration](https://pencilshinchan.github.io/AWSAmplifyTutorial/SetupAndConfigAuth)


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

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### New Link

[Set Up and Config](https://pencilshinchan.github.io/AWSAmplifyTutorial/AmplifySetupAndConfig)

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/pencilshinchan/AWSAmplifyTutorial/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
