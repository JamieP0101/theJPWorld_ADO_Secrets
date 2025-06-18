# ReadMe
## Overview  
This repo contains the base code to deploy variables/secrets that are set in your Azure DevOps Library into a specified Azure Keyvault. It will also look and compare if the deployment doesn't have any variables/secrets in the Azure DevOps Library that exist in the Azure Keyvault and list them out for you review and then will delete the secret from the Keyvault (Manual Approval required before deleting the secrets it lists).

## Known Challenges  
Purge Protected Keyvaults can interfer with the deletion and recreation steps etc so understanding purge protection is valuable knowledge

### Follow the 
[Setup Guide](/z_documentation/README_SetupGuide.md)  
  
[User Guide](/z_documentation/README_UserGuide.md)
