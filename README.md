# Standard Managed Disk - S6 VM with Standard S2 SQL Database

Deploys a Single 2016 Datacentre VM with a 64GB managed OS disk
- Standard LRS Storage
- Single NIC
- Single VNET with 1 Subnet (10.0.0.0/22 Address space, 10.0.1.0/24 subnet
- Single 64GB managed data disk

Also deploys a Standard S2 SQL Server and database, NSG, Load balancer with Public IP and backup repository 

Use the following in a powershell prompt

.\deploy.ps1 -subscriptionId [SubscriptionId] -resourceGroupName [ResourceGroupName]

To run from a command prompt:

powershell -f deploy.ps1 -subscriptionId [SubscriptionId] -resourceGroupName [ResourceGroupName]

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)
