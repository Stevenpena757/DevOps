# UiPath Robot

This template creates a Virtual Machine (VM) in a resource group, then deploy **UiPath Robot**.
Based on the Virtual Machine (VM) name, following components are created : 
    -public IP (vmname-pip), 
    -VM network interface (vmname-nic), 
    -Network security group (vmname-nsg with following open ports : 80,443 and 3389),
    -Virtual network (vmname-vnet).

[![Deploy to Azure](https://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FUiPath%2FDevOps%2Ffeature%2Fuirobot_arm_template%2FARM%2Fuirobot%2Fazuredeploy.json)