# AI Recipe Generator

AI Recipe Generator is a serverless web application that lets users generate creative recipe ideas from a list of ingredients. It leverages AWS Amplify to manage frontend hosting, backend APIs, authentication, and continuous deployment. The backend integrates with Amazon Bedrock using the Claude 3 Sonnet foundation model to process ingredient inputs and generate recipe suggestions.

## Interface

### Authentication

The registration process is managed by AWS Cognito.

<div align="center">
    <img src="images/register.png" alt="Registration" width="50%"/>
</div>

### Interaction

Once authenticated, users can enter a list of ingredients to generate creative recipe ideas. The application processes the input and provides suggestions using the Claude 3 Sonnet foundation model.

<div align="center">
    <img src="images/tutorial.gif" alt="Video Demonstration" width="100%"/>
</div>

## Project Architecture

The architecture of this application leverages multiple AWS services. The diagram below shows how the services connect:

![Architecture Diagram](https://i.imgur.com/GOwUQFY.png)
