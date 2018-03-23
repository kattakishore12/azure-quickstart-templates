This template allows you to create a simple e-commerce web application in Azure, which includes the below resources

1. App Service Plan
2. Web application
3. Web Job
4. Azure SQL server and database
5. Stroage account
6. CDN profile, endpoint
7. Keyvault and secret

Script execution:

1. execute the prereqs scripts first. Modify all the required values in the parameter file.
2. Modify the azuredepoy.parameter.json file with "subscription ID", "resource group name" and the "keyvalutname" (which you will get from the prereqs script).
3. execute the main scripts.


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F100-blank-template%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F100-blank-template%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png"/>
</a>

This is the reference architecture for the ARM templates.

<img src="https://raw.githubusercontent.com/kattakishore12/azure-quickstart-templates/master/101-azure e commerce application/images/reference_architecture.jpg"/>
</a>

