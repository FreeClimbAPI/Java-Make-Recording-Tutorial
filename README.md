# Java - Make a Recording Tutorial

This project serves as a guide to help you build an application with Persephony. Specifically, the project will:

- Make a call
- Prompt the participant to leave a message

## Setting up your new app within your Persephony account

To get started using a persephony account, follow the instructions [here](https://persephony-docs.readme.io/docs/getting-started-with-persephony).

## Setting up the Tutorial

1. Configure environment variables.

   | ENV VARIABLE            | DESCRIPTION                                                                                                                                                                           |
   | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
   | ACCOUNT_ID              | Account ID which can be found under [API Keys](https://www.persephony.com/dashboard/portal/account/authentication) in Dashboard                                                       |
   | AUTH_TOKEN              | Authentication Token which can be found under [API Keys](https://www.persephony.com/dashboard/portal/account/authentication) in Dashboard                                             |
   | TUTORIAL_APPLICATION_ID | Appliction IDs can be found under [Apps](https://www.persephony.com/dashboard/portal/applications)                                                                                    |
   | TO_PHONE_NUMBER         | The phone number which is being called. [Must be a verified phone number](https://docs.persephony.com/docs/using-your-trial-account#section-verifying-outbound-numbers)               |
   | PERSEPHONY_PHONE_NUMBER | The persephony number that is being used to make a phone call. To learn more go [here](https://docs.persephony.com/docs/getting-started-with-persephony#section-2-get-a-phone-number) |
   | HOST | URL where your app is being hosted |

## Building and Runnning the Tutorial

1. Build and run the application using command:

   ```bash
   $ gradle build && java -Dserver.port=3000 -jar build/libs/gs-spring-boot-0.1.0.jar
   ```
