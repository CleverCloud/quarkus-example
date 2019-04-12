# Deploy on Clever Cloud

## Create an account on Clever Cloud

You'll first need an account.
Go to the [console](https://console.clever-cloud.com/) and follow the instructions.

## Create the application

Create a new application, select "Java + Maven"
Add these environment variables when prompted to do so:
- `CC_JAVA_VERSION=graalvm-ce`
- `CC_MAVEN_PROFILES=native`
- `CC_RUN_COMMAND=target/quarkus-quickstart-1.0-runner`

## Enjoy

Push your code and enjoy your application being online
