# AWS Cognito (w/ Google) template

#### About
This template is for use with [AWS SAM CLI][1]. You will require a Google developer account to setup a Google OAuth. You will also require an AWS developer account which has sufficient access for SAM and the SAM CLI must be configured locally.

#### Setup
- Configure Google OAuth Consent Screen for a Project
- Configure Credentials for Project which will provide a Client ID and Client Secret
- Run `sam build && sam deploy` locally inside this project and provide the required information
- Go back to the Google OAuth configuration and add the provided "Google Redirect URL" which was output after deployment of the SAM template.
- Login should now be possible via the "Authentication URL" provided in the output of the deployment



[1]: https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/install-sam-cli.html
