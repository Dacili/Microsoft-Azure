# Microsoft-Azure

Expanding my knowledge in Microsoft Azure. 
Preparing for my Azure fundamentals exam (AZ-900).

Currently learning the most commonly used Microsoft Azure services, such as resource groups, subscriptions, API Management, db servers, databases, storages, key vaults, virtual machine, app service, web jobs, application insights, serverless functions, app configurations...

After you get your subscription we can start.
In order to be able to create almost anything from the services you should firstly create your resource group.

**API MANAGEMENT** - manage all your APIs, entry point for requests (from frontend) to backend
![alt text](https://github.com/Dacili/Microsoft-Azure/blob/main/api%20management.PNG)

**VM - virtual machine** - your remote pc, choose specifications, and do whatever you want to (in AWS something like EC2) :D
![alt text](https://github.com/Dacili/Microsoft-Azure/blob/main/VM.PNG)

**App service** - your deployed app. You can create/activate web jobs (triggered or continuos execution of some code, usually used for some triggering stuff, like sending emails on a daily basis) for your app
![alt text](https://github.com/Dacili/Microsoft-Azure/blob/main/Pictures/app%20service.PNG)

**App service - configuration** - your variables for deployed app (they can be connected with Azure Pipelines-> your ARM - Azure Resource Manager files)
![alt text](https://github.com/Dacili/Microsoft-Azure/blob/main/Pictures/app%20service%20configuration.PNG)

**App service - IAM** - similar to AWS IAM, you are managing access control (roles, permissions, admins, user groups...)
![alt text](https://github.com/Dacili/Microsoft-Azure/blob/main/Pictures/IAM-microsoft.PNG)

**Database server** - for hosting your databases
![alt text](https://github.com/Dacili/Microsoft-Azure/blob/main/Pictures/db%20server.PNG)

**Function app** - serverless yeaah that's it! :D (as lambda in AWS)
Execute your code when you want, pay only for duration of your function app.
![alt text](https://github.com/Dacili/Microsoft-Azure/blob/main/Pictures/Function%20App%20Azure.PNG)

**Key vault** - we use them for some sensitive data, for example passwords, that we don't want to have plain in our ARM files.
![alt text](https://github.com/Dacili/Microsoft-Azure/blob/main/Pictures/Key%20vault.PNG)

**Storage account** - storage account used for uploading files. We have 4 functionalities to use: tables, queues, containers and file shares.
![alt text](https://github.com/Dacili/Microsoft-Azure/blob/main/Pictures/storage%20account.PNG)

**Application insights** - check the state of your application! Logging exceptions, events, failures, application map and a lot of other interesting metrics with a really nice UI presentations of the data. (similar to Cloudwatch in AWS)
![alt text](https://github.com/Dacili/Microsoft-Azure/blob/main/Pictures/App%20Insights.PNG)
