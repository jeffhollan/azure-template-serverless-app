# Azure Resource Template - Serverless App

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fjeffhollan%2Fazure-template-serverless-app%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template will deploy a Serverless app in Microsoft Azure.  It includes:

* A storage account for the Azure Function
* A dynamic App Service plan for the Azure Function
* An Azure Function with code deployed from source control specified
* An Azure Logic App that calls the function and returns the response
