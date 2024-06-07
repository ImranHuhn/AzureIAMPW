<h1 align="center">Login and password reset Your IAM User Account</h1>

<h2>TLDR: Create IAM role for user</h2>

- <b>Introduction: </b>
  - Guide to logging into the IAM user account, including setting up credentials and 2FA.

- <b>Login to IAM user: </b>
  - Ensure you have the username and password.
  - If logged in, log out and sign in with the IAM user credentials (e.g., "labuser2").

- <b>Microsoft Authenticator App: </b>
  - Install the app on your smartphone or tablet.
  - Follow instructions to set up 2FA and create a new password.

- <b>Reset Password: </b>
  - If needed, follow steps to reset and record a new password.
  - Return to the beginning of the guide after resetting.

<h2>How to read each section (in this order)</h2>

<b>Section-Intro</b> 
- <b>Title: </b>Name of the section.
- <b>Description: </b>Describe what the section entails. Some sections won’t have descriptions. 

<b>Image</b> 
- <b>Numbering: </b>Within the images are sequential numbers, with corresponding text explanations directly below each image.
- <b>Yellow highlights: </b>Yellow highlights are navigation aids to help identify your current section in the Azure portal.

<b>Text numbers</b> 
- <b>Numbers: </b>Each number provides a brief explanation of the image directly above it.

<b>Side notes</b> 
- <b>Notes: </b>Any extra details you should be aware of.

<h2>Introduction</h2>

&nbsp;&nbsp;&nbsp;&nbsp;Welcome to this guide on logging into the IAM user account. In this tutorial, we will walk you through the steps to log in using the IAM user credentials that you have set up. It is essential to ensure that you have both the username and the provided password handy. If you do not have the password, there is a section on resetting it that you can refer to.

<h2>Login to IAM user</h2>

<b>Description: </b>Now that we've created a user and assigned a role, we can log in using the IAM user credentials. Ensure you have the username and have copied the provided password. If you haven't copied the password, please refer to the "reset password" section below. I'll show you how to reset the password at the end of this guide.

![01_Capture](https://github.com/ImranHuhn/AzureRGIAM/assets/52342912/53f4e086-7aea-438c-a0ca-1fb44edcd56b)

0.  If you're currently logged in, please log out.
1.  Now, sign in by clicking on "Use another account" and entering the IAM user credentials that were set up earlier. In this case, use "labuser2".

<h2>Microsoft authenticator app</h2>

<b>Description: </b>Before successfully logging into the IAM user account, you need to set up two-factor authentication (2FA) for this account. To do this, install the "Microsoft Authenticator" app on your smartphone or tablet and complete the verification process.

![02_Capture](https://github.com/ImranHuhn/AzureRGIAM/assets/52342912/f621b17e-5584-4f96-a176-9b21e37e8911)

0.  Ensure you install and set up the "Microsoft Authenticator" app on a smartphone or tablet.
1.  Click "Next" to begin the authentication process and follow the provided instructions.

Note: After completing the authentication, you will be prompted to create a new password. Once you have successfully logged in, proceed to the cost management section. It should display "access denied," which is expected since this account is intended to have limited access.

<h2>How to reset the password</h2>

<b>Description: </b>If you don't have the password for the initial login, this portion of the guide will take you through the process of resetting it. Follow these steps to reset and record the new password. Once the password has been reset and noted, return to the beginning of this guide and follow the steps from the start.

![03_Capture](https://github.com/ImranHuhn/AzureRGIAM/assets/52342912/c33f5a67-61ba-479e-8c74-41d4ee52b84e)

1.  Go to the users section and select the specific user whose password you want to reset.
2.  Click on "Reset Password," and a panel will appear on the right.
3.  Click on "Reset Password" and copy the provided password.

Note: Now you can restart the guide from the beginning.

<h2>Conclusion</h2>

&nbsp;&nbsp;&nbsp;&nbsp;By following this guide, you should now be able to log into your IAM user account with ease. We covered the essential steps, including resetting your password if needed. If you encounter any difficulties, refer back to the relevant sections for detailed instructions. Ensuring you have both the username and the provided password handy is crucial for a smooth login process. Thank you for using this guide, and we hope it has helped you access your IAM user account successfully.
