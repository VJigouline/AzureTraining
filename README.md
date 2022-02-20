# Azure Training

Scripts, templates stored during Azure training courses

## Overview

This repository is to store different resources acquired during Azure training courses for future review. A lot of garbage. Feel free to use them if you find them useful.

## Training courses

**Fundamentals of Bicep** - https://docs.microsoft.com/en-gb/learn/paths/fundamentals-bicep/
New language to specify Azure resources instead of JSON templates.

## PowerShell commands

_**Connect-AzAccount**_ - connect to Azure account
_**Get-AzSubscription**_ - get available Azure subscriptions
_**New-AzResourceGroupDeployment** -Name &lt;deployment_name&gt; -TemplateFile &lt;template_name&gt; -storageName &lt;storage_name&gt;_ - deploy Azure resource group through template
_**Set-AzDefault** -ResourceGroupName &lt;name&gt;_ - set default resource group

## CLI commands 

_**az keyvault secret show** --name &lt;name&gt; --vault-name &lt;vault-name&gt; --query value --output tsv_ - retrieve password from secure vault
_**az vm create** &lt;parameters&gt; - create virtual machine
_**az vm extension set** &lt;parameters&gt; - run extension set
_**az vm list-ip-addresses** &lt;parameters&gt; - list IP addresses
_**az vm list-ip-addresses** &lt;parameters&gt; - list network security groups
_**az network nsg rule list** &lt;parameters&gt; - list network security group list
_**az network nsg rule list** &lt;parameters&gt; - create network security group

## To review

Microsoft Intune https://docs.microsoft.com/en-us/mem/intune/fundamentals/what-is-intune
AZ-400: Develop a security and compliance plan https://docs.microsoft.com/en-gb/learn/paths/az-400-develop-security-compliance-plan/
