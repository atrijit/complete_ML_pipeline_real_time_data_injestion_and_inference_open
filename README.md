Objective : POC for complete end to end ML pipeline which covers follwoing

model creation & deployment to Azure Container Instance with and end-point
real time data publish to Azure Event Hub
real time data injestion from Azure Event Hub to Cosmos db
flask app for real time api call to an user request -> fetches data from cosmos db, make real time inference and diplay predictions
Scope:

These are not production grade codes
The purpose is for a demo considering all integrations

Future Work:

deploy model in AKS
deploy flask app in Azure Functions
more work on scaling
Architecture :

![image](https://github.com/user-attachments/assets/b5bbd9d0-a102-41f4-b63e-cb54688d3845)
