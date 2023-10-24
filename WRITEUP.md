# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
  + Costs: App Service Costs are generally lower than VMs for similar workloads.
  + Scalability: VMs offer high scalability, but it requires manual configuration. While App Service simplifies scalability with auto-scaling options.
  + Availability: App Service is designed for high availability without significant manual configuration. While VMs achieve high availability requires manual configuration, but they give us more control.
  + Workflow: App Service is ideal for hosting web applications, APIs, and microservices that don't require direct access to the underlying OS. While deploying an app on VMs is more complicated but they give us more control over the OS and configuration.
- *Choose the appropriate solution (VM or App Service) for deploying the app*: App Service
- *Justify your choice*: Currently, CMS is a small webapp with simple APIs (like: view, create, edit), we don't need to control over the infrastructure, custom software installations. So i choose App Service for a simpler and more cost-effective solution and to avoid time consuming in manual configuration.

### Assess app changes that would change your decision.
In the future, If this app become bigger and more complicated which requires complex software dependencies, legacy components, or requires custom networking, hardware access, or specialized resources, I will choose the VMs solution. Because VMs provide better performance and Scaling ability.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 