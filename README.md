# Deployment of Red Hat Enterprise Linux VM (RHEL 7.2 or RHEL 6.7)

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2bitbucket.telstrahealth.com.au%2Fprojects%2FARM%2Frepos%2Fdevops-public%2Fbrowse%2Fsynchronicity%2Fazuredeploy.json?at=ff1928032dc22636d52d01c54f554b176447013e&raw" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2bitbucket.telstrahealth.com.au%2Fprojects%2FARM%2Frepos%2Fdevops-public%2Fbrowse%2Fsynchronicity%2Fazuredeploy.json?at=ff1928032dc22636d52d01c54f554b176447013e&raw" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>


Sample Comments


```
azure config mode arm
azure group create TestCLIRG EastUS
azure vm quick-create TestCLIRG vm1 EastUS Linux RedHat:RHEL:7.2:latest azureuser
```