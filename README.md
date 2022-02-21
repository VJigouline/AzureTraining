# Azure Training

Scripts, templates stored during Azure training courses

## Overview

This repository is to store different resources acquired during Azure training courses for future review. A lot of garbage. Feel free to use them if you find them useful.

## Exams

**Exam AZ-104: Microsoft Azure Administrator** - <https://docs.microsoft.com/en-gb/learn/certifications/exams/az-104>

## Training courses

**Fundamentals of Bicep** - <https://docs.microsoft.com/en-gb/learn/paths/fundamentals-bicep/>  
New language to specify Azure resources instead of JSON templates.
**AZ-104: Prerequisites for Azure administrators** - <https://docs.microsoft.com/en-gb/learn/paths/az-104-administrator-prerequisites/>

## PowerShell commands

_**Connect-AzAccount**_ - connect to Azure account  
_**Get-AzSubscription**_ - get available Azure subscriptions  
_**New-AzResourceGroupDeployment** -Name &lt;deployment_name&gt; -TemplateFile &lt;template_name&gt; -storageName &lt;storage_name&gt;_ - deploy Azure resource group through template  
_**Set-AzDefault** -ResourceGroupName &lt;name&gt;_ - set default resource group  
_**New-AzureADUser** - &lt;parameters&gt; - create new user  
_**Remove-AzureADUser** - &lt;parameters&gt; - delete user  

## CLI commands

_**az keyvault secret show** --name &lt;name&gt; --vault-name &lt;vault-name&gt; --query value --output tsv_ - retrieve password from secure vault  
_**az vm create** &lt;parameters&gt; - create virtual machine  
_**az vm extension set** &lt;parameters&gt; - run extension set  
_**az vm list-ip-addresses** &lt;parameters&gt; - list IP addresses  
_**az vm list-ip-addresses** &lt;parameters&gt; - list network security groups  
_**az network nsg rule list** &lt;parameters&gt; - list network security group list  
_**az network nsg rule list** &lt;parameters&gt; - create network security group  
_**az ad user create** &lt;parameters&gt; - create new user  
_**az ad user delete** &lt;parameters&gt; - delete new user  

## To review

Microsoft Intune <https://docs.microsoft.com/en-us/mem/intune/fundamentals/what-is-intune>
AZ-400: Develop a security and compliance plan <https://docs.microsoft.com/en-gb/learn/paths/az-400-develop-security-compliance-plan/>  
Implement resource management security in Azure <https://docs.microsoft.com/en-gb/learn/paths/implement-resource-mgmt-security/>  
Prerequisites for Azure administrators <https://docs.microsoft.com/en-gb/learn/paths/azure-administrator-prerequisites/>  
Architect infrastructure operations in Azure <https://docs.microsoft.com/en-gb/learn/paths/architect-infrastructure-operations/>  
Learn how Microsoft supports cloud adoption as part of a cybersecurity solution <https://docs.microsoft.com/en-gb/learn/paths/secure-cloud-adoption-cybersecurity/>  
Plan and manage your Azure costs <https://docs.microsoft.com/en-us/learn/modules/plan-manage-azure-costs/>  
Manage resources in Azure <https://docs.microsoft.com/en-gb/learn/paths/manage-resources-in-azure/>  
AZ-400: Facilitate communication and collaboration <https://docs.microsoft.com/en-gb/learn/paths/az-400-facilitate-communication-collaboration/>  
Microsoft Azure Fundamentals: Describe Azure cost management and service level agreements <https://docs.microsoft.com/en-gb/learn/paths/az-900-describe-azure-cost-management-service-level-agreements/>  
Azure for Researchers part 2: Cloud Security and Cost Management <https://docs.microsoft.com/en-gb/learn/paths/researcher-cloud-security-cost-management/>  
Control Azure spending and manage bills with Azure Cost Management + Billing <https://docs.microsoft.com/en-gb/learn/paths/control-spending-manage-bills/>  
Manage identities and governance for Azure administrators <https://docs.microsoft.com/en-gb/learn/paths/azure-administrator-manage-identities-governance/>  

## Things to remember

Accelerate your cloud adoption journey by using the Cloud Adoption Framework for Azure <https://docs.microsoft.com/en-gb/learn/modules/build-cloud-governance-strategy-azure/9-accelerate-cloud-adoption-framework>  

## Useful tools

Total Cost of Ownership (TCO) calculator <https://azure.microsoft.com/en-gb/pricing/tco/calculator/>  
Pricing calculator <https://azure.microsoft.com/en-gb/pricing/calculator/>  

## Next lesson

<https://docs.microsoft.com/en-us/learn/paths/az-104-manage-identities-governance/>
<https://docs.microsoft.com/en-gb/learn/modules/secure-azure-resources-with-rbac/>
