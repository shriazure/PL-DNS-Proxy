# Deploy VMSS of a NGINX DNS Proxy into an existing Virtual Network.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fshriazure%2FPL-DNS-Proxy%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
    
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fmicrosoft%2FPL-DNS-Proxy%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>




![alt text](https://github.com/jgmitter/images/blob/master/SharedScreenshot.jpg)


## Prerequisites

- Name of the existing VNET and subnet you want to connect the new virtual machine to.
- Name of the Resource Group that the VNET resides in.
- Depending on region deployed you might need to adjust template for vm SKU size supported. 


This template allows deploying two Ubuntu/NGINX VMs using an existing resource for the Virtual Network and subnet. It also allows for choosing between SSH and Password authenticate. 


# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
