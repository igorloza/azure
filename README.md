# Deployment of Red Hat Enterprise Linux VM (RHEL 7.2 or RHEL 6.7)

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Figorloza%2Fazure%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Figorloza%2Fazure%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>


Sample Comments


```
azure config mode arm
azure group create TestCLIRG EastUS
azure vm quick-create TestCLIRG vm1 EastUS Linux RedHat:RHEL:7.2:latest azureuser
```