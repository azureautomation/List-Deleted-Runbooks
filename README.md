# SYNOPSIS 
    This PowerShell script lists deleted runbooks in an Azure Automation account. This script requires system identity enabled for the automation account with 'Automation Contributor' role assignment on the identity.

# DESCRIPTION

    This PowerShell script is designed to list deleted runbooks in an Azure Automation account. 

# PARAMETER subscriptionId
    Required. Subscription of the Azure Automation account in which the runbook needs to be listed.
 
# PARAMETER resourceGroupName
    Required. The name of the resource group of the Azure Automation account.
    
# PARAMETER automationAccountName
    Required. The name of the Azure Automation account in which the runbook needs to be listed.
