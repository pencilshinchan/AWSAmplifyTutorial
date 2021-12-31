# Authorization JavaScript code

The code will be (mostly) supplied for the Auth pages. We will look at the SignUp page first, and based on it's code we will update the SignIn page code. Other pages such as ForgotPassword, ConfirmSignUp and the ErrorNotification component will be supplied. This is showing a basic workflow with a username and password, and would have to be altered both in code AND in the CLI to support a different workflow.

The Amplify team has provided an out-of-the-box UI for login. In the past, this was meant for quick prototyping only so you are not wasting time standing up a login system, but it was implied that before you went into production you should create your own login system. The documentation for the [Amplify UI](https://ui.docs.amplify.aws/) components has been split off onto its own site. It looks as if they are working on a number of new components that are currently in developer preview - this usually means they are potentially kind of buggy still, and should not be used for production.

There have been a lot of changes in the Amplify UI over the years, and many of them were breaking changes. Updating the aws-amplify package sometimes caused the UI packages to no longer work because they required and older version of aws-amplify. This generally meant you were stuck at the old version until the UI packages caught up. This may be a solved problem, but historically was an issue at times. We have NOT installed the UI packages, and instead will create our own login UI using methods from the Auth compoent that is part of aws-amplify. This makes us more able to move with updates to the aws-amplify package.

## Create Files

Code will be supplied via links to github gists. Javascript files will be created in the project and code from the gists can be copied to the appropriate files.

In the project under the create the directory src/api/auth - create 5 files in the directory
- ErrorNotification.js
- SignUp.js
- ConfirmSignUp.js
- SignIn.js
- ForgotPassword.js

## Create Routes

Using react-router-dom create routes to all of the files created above, and the test the routes to ensure they are working as expected.

## The Gists

Use the code found in the github gists linked below to add code to the appropriate files. 

- [ErrorNotification.js code](https://gist.github.com/pencilshinchan/415c4d09607e8b244e1f3235f699219c)
- [SignUp.js code](https://gist.github.com/pencilshinchan/2b3ce7428d25af49c17e49d38f1006c6)
- [ConfirmSignUp.js code](https://gist.github.com/pencilshinchan/f13eee71cf1c3fc566a2a6c6edf92920)
- [SignIn.js code](https://gist.github.com/pencilshinchan/9f1acc440702040acc0684e3d7288dac)
- [ForgotPassword.js code](https://gist.github.com/pencilshinchan/d4dc969904b7fbe571976378cbf3ad96)
