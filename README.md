# Deploy on Clever Cloud

## Create an account on Clever Cloud

You'll first need an account.
Go to the [console](https://console.clever-cloud.com/) and follow the instructions.

## Deploy in the console

Create a new application, select "Java + Maven"
Add these environment variables when prompted to do so:

-   `CC_JAVA_VERSION=graalvm-ce`
-   `CC_MAVEN_PROFILES=native`
-   `CC_RUN_COMMAND=target/quarkus-quickstart-1.0-runner`

## Deploy using the CLI

Install the [clever cli](https://www.clever-cloud.com/doc/reference/clever-tools/getting_started/),
it is packaged for npm and for every possible OS.

Within this cloned repository, do:

    clever create --type maven quarkus-example

Export them using the `.env` file:

    source .env

Import them on the clever CLI

    clever env import-vars CC_JAVA_VERSION,CC_MAVEN_PROFILES,CC_RUN_COMMAND

## Enjoy

Push your code and enjoy your application being online
