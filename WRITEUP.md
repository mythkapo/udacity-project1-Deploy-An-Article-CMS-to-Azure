# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

For this excercise, App Service is the best approach because it is cheaper compare to VM and we do not need to maintain the Operation System. However, if we think about the scalability, app service is not the best option as it is used for lightweight application. When this CMS app get more users, the memory and CPU might not be enough to handle all the traffic. Both VM and App Service can achive high availability. Azure App service has built-in workflow using GitHub Azure DevOps or any Git repo.


### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If there are change in our IT goveranance policy such as network requirement or Operating System Policy etc, then we will not want to use app service but virtual machine as it gives us control on OS. In additional, if the web app is already built on premise server, it will also make it easier for migration. The other factors is performance, VM does not have any limitation on memory, CPU and storage.