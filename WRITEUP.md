# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

Given that this web application is small and contains deployment from a GitHub repo, my first thought would be to deploy this application on an App Service. App service is often less expensive than a VM, it is HTTP-based, as well as supportive of multiple languages. We want the application to have auto-scaling and high availability. 

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

There would be some instances where I would change my decision on deploying this web app. For one, if there were more users where they would be uploading a lot of custom images, I think a VM would be better. 