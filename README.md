---
services: app-service, functions
platforms: dotnet
author: yochay
---

# C# Azure Functions for uploading and processing images
Upload an image that includes some text in it, run an OCR on the image to extract the text, store the text, and finally retrieve both image and text.
 
![alt text](https://msdnshared.blob.core.windows.net/media/2016/10/testingWitaSPAAndFunctionLayout.jpg "Logo Simple Azure Functions SPA and image processing example")


## How to run the sample
To run this sample you will need the following:

* An Internet Connection
* An Azure subscription is optional. You can run the entire sample from [Try Azure Functions](https://functions.azure.com/try)
* You can use an Azure subscription 

<!--
## Deploy this sample to Azure (only for Azure Subscription)

1. Click on the Deploy to Azure button above
1. Login to your Azure Subscription
1. Fill out a few details in the Portal
1. Kick off your shoes, put your feet up, lean back and enjoy as this sample deploys itself.
-->
## Use this sample in Try Functions (doesn't require an Azure Subscription)

1. Go to [https://functions.azure.com](https://functions.azure.com) and click the green Try-It-For-Free button)
2.	Choose Webhook + API scenario (many other templates are available for other scenarios) 
3.	Choose your programming language between C# or JavaScript (node.js). 
4.	Click “Create this function” button, which will prompt you to login
5.	Login with your selected social identity, wait for few seconds… and you have an HTTP trigger function ready for use
6.	Only in Try Functions experience you need to manually copy & paste the code from the repo 

## Walk-through

A full walk-through of the scenario and functions is available in the [App Service Team Blog](https://aka.ms/tryazurefunctionblog)
