Objective : POC for complete end to end ML pipeline which covers follwoing

1. model creation & deployment to Azure Container Instance with and end-point
2. real time data publish to Azure Event Hub
3. real time data injestion from Azure Event Hub to Cosmos db
4. flask app for real time api call to an user request -> fetches data from cosmos db, make real time inference and diplay predictions

Scope:

1. These are not production grade codes
2. The purpose is for a demo considering all integrations

Future Work:

1. deploy model in AKS
2. deploy flask app in Azure Functions
3. more work on scaling

Disclaimer: 

1. This is an independent personal work where personal resources are used.
2. Gen AI tools are also leveraged 

Architecture :

![image](https://github.com/user-attachments/assets/b5bbd9d0-a102-41f4-b63e-cb54688d3845)
