# AI Recipe Generator

AI Recipe Generator is a serverless web application that lets users generate creative recipe ideas from a list of ingredients. It leverages AWS Amplify to manage frontend hosting, backend APIs, authentication, and continuous deployment. The backend integrates with Amazon Bedrock using the Claude 3 Sonnet foundation model to process ingredient inputs and generate recipe suggestions.

![Video Demonstration](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExaTAzZ3A4am03NGl5Y3k5OWwzY2t6eGR6Mnozc3BsYTdyMHllc2NjZSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/TDUCo2iSpos0iVeoHG/giphy.gif)


## Project Architecture

The architecture of this application leverages multiple AWS services. The diagram below shows how the services connect:

![Architecture Diagram](https://i.imgur.com/GOwUQFY.png)

