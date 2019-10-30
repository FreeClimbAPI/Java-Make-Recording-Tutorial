# Java - Make a Recording Tutorial

This project serves as a guide to help you build an application with FreeClimb. Specifically, the project will:

- Make a call
- Prompt the participant to leave a message

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb).

## Setting up the Tutorial

1. Configure environment variables.

   | ENV VARIABLE            | DESCRIPTION                                                                                                                                                                        |
   | ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
   | ACCOUNT_ID              | Account ID which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                                     |
   | AUTH_TOKEN              | Authentication Token which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                           |
   | TUTORIAL_APPLICATION_ID | Appliction IDs can be found under [Apps](https://www.freeclimb.com/dashboard/portal/applications)                                                                                  |
   | TO_PHONE_NUMBER         | The phone number which is being called. [Must be a verified phone number](https://docs.freeclimb.com/docs/using-your-trial-account#section-verifying-outbound-numbers)             |
   | FREE_CLIMB_PHONE_NUMBER | The FreeClimb number that is being used to make a phone call. To learn more go [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb#section-2-get-a-phone-number) |
   | HOST                    | URL where your app is being hosted                                                                                                                                                 |

## Building and Runnning the Tutorial

1. Build and run the application using command:

   ```bash
   $ gradle build && java -Dserver.port=3000 -jar build/libs/gs-spring-boot-0.1.0.jar
   ```
