# CREATE-A-RESOURCE-GROUP-IN-MICROSOFT-AZURE-USING-THE-CLI

* 1.	Log in using ```az login```
* 2.	We'll use the Azure CLI command ```az group create``` and pass in two flags:
```	--resource group --name```
```	--location``` which is the same as the "region" field on the Azure portal.
* 3.	If you want to see a list of all locations, you can run ```az account list-locations -o table``` to output the list in table format.
* 4.	I want to create my resource group in the West US 2 region:
```az group create --name resource-group-west --location westus2```


The resource group will be created and a JSON response will be returned with the status.
