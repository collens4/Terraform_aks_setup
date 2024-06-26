# Terraform_aks_setup
Azure provider is defined to connect Terraform to Azure.
The variables defined are the resource group name, location, AKS cluster name, and node count.
AKS cluster is provisioned with the specified configurations, including high availability, scalability, and security settings.
A default node pool is created with auto-scaling enabled, which allows the cluster to automatically scale based on resource utilization.
Network plugin and policy are configured for network security and communication within the cluster.
Service principal credentials (myid and mysecret) are provided to authenticate Terraform with Azure.
Role-based access control (RBAC) is enabled for security.
Azure File storage class is created for persistent storage using Azure Files.
