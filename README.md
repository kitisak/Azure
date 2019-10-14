# Azure
Microsoft Azure Knowledge

Demo - Create an Azure virtual machine

Steps
1. Sign in to the Azure portal at https://portal.azure.com
2. Choose Create a resource in the upper left-hand corner of the Azure portal.
3. In the search box above the list of Azure Marketplace resources, search for and select Windows Server 2016 Datacenter, then choose Create.
4. In the Basics tab, under Project details, make sure the correct subscription is selected and then choose to Create new resource group. Type myResourceGroup for the name.
5. Under Instance details, type myVM for the Virtual machine name and choose East US for your Location. Leave the other defaults.
6. Under the Administrator account section, provide a username, such as azureuser and a password. The password must be at least 12 characters long and meet the defined complexity requirements.
7. Under Inbound port rules, choose Allow selected ports and then select RDP (3389) and HTTP (80) from the drop-down. These are to allow us to connect to the virtual machine using RDP over port 3389 and then to see a web page display over HTTP on port 80.
