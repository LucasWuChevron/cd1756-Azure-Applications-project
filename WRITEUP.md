# Recommendation: Use Azure App Service

### Justifications

Lower cost: Azure App Service allows for lower cost tiers to be available, which is beneficial if the app is not heavily used.  With a Virtual Machine, cost is needed 24/7 even when the app is not used, as there are costs for the OS, Storage, and Networking.

Quicker way to scale: Load balancing is easily handled if more usage and traffic to the app is needed. To scale with a Virtual Machine solution, you must add more VM's and manage scaling rules which could be complex.

Ease of support: Since Azure App Service is on a managed platform, there is built-in redundancy and ease to deploy multiple instances to scale.  A Virtual Machine solution will require set up for backups and failovers. 

### Assess app changes that would change your decision.

Changes that would lead me to choose a Virtual Machine solution instead, would be if this app requires customized OS specifications that an Azure App Service cannot meet. Example of this could be that the application is software and requires configuration and OS specs that may no longer be supported by conventional Azure infrastructure.   
