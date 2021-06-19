<!--
# NERegiondemos
# Purview 
-->

# Deploy Azure Purview (Preview)  {Testing ONLY}

This template creates a single instance of Azure Purview (Public Preview)
<br>
<br>
Create An Azure Purview Instance 
<br>
<a href="https://azuredeploy.net" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<br>
<br>
Vizualize the Deployment
<br>
<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/DarylsCorner/ARM-Templates/master/vm-from-user-image/azuredeploy.json" target="_blank">
  <img src="http://armviz.io/visualizebutton.png"/>
</a>
<br>

Note:
1) You can deploy a maximum of 3 Purview instances during the public preview of Azure Purview. 
   Typically an orginization works off of one master data catalog for governance, so typically only one is needed... or two if you want to create a test instance.

2) You can deploy Azure Purview instance in any Azure Region currently supported by the Purview Preview. Recommend Brazil for testing, due to large Purview capacity at this time during public preview.

For more information, see here:
https://docs.microsoft.com/en-us/azure/purview/overview
