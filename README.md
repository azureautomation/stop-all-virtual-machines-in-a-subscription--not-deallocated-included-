Stop All virtual machines in a subscription (not deallocated included)
======================================================================

            

Stop Azure resource manager virtual machines in a subscription. An Azure Automation RunAs account is required for this runbook.


This Azure Automation runbook runs on Azure to stop Azure vms in a subscription



This script provides:  


  *  Stop execution of VM in running state 
  *  Stop execution of VM in poweroff state (not deallocated)  
  *  List all resource groups for a subscription 
  *  Location filtering on resource groups (westeurope in example)  
  *  List all Azure RM Virtual Machines of those resource group 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
