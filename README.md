## Cluster Groups

Cluster groups can be used to group clusters and apply a common set of policies to these clusters. Clusters in a cluster group can exist in one or more physical environments, and can be shared across teams.



## All Clusters

This is a view of all clusters across your organization that you have permissions to view. 
These clusters can exist in different cluster groups and can exist in one or more physical environment.

We upgrade clusters from here, or retreive the kubconfig file as well.


<img src="/screenshots/sort-by.png" width="650"> 

## Sort by:

 ### name
 - aws-prod-cluster
 - azure-prod-cluster
 
 ### Health
 - Healthy
 - Unhealthy
 - Warning
 - Disconnected
 - Unknown

 ### Status
 - Ready
 - Creating
 - Detaching
 - Pending
 - Deleting
 - Unkown
 
 ### Version
  - 1.19.3-1-amazon2
  - v1.18.15+vmware.1-tkg.2.ebf6117
  - etc..
 
 ### Cluster Group
 
 By specifying a cluster group, this will automatticly apply and polices from that group to the cluster.
 
 ### Type
 - Provisioned
 - Attached
 - Tanzu Kubernetes Grid Service
 - Tanzu Kubernetes Grid
 - Unkown
 
 ### Managment Cluster
 - aws-hosted
 - tanzu


## Create Cluster

<img src="/screenshots/create-cluster.png" width="650"> 

Create Cluster button > Choose Management Cluster > Choose Provisioner > 

  ### Name - Choose your clusters name and assign it to a cluster group
  - Name 
  - Description
  - Labels
  
  ### Configure - Select you Kubernetes version, network and storage options
  
  ### Select Control Plane - choose between a single nore or Highly available
  
  ### Edit and add node pools - Customize the default node pool
  
  We can scale nodes up or down as well as change the instance type.
  
  
  
## WorkSpaces
 
Workspaces can be used to group namespaces from one or more clusters, and can be shared across teams.

## Namespaces

## Workloads

## Policies
 
 ### Assignments
 
 - Access
 - Image Registries
 - Network
 - Security
 - Quota
 - Custom

 ### Templates
 
A custom policy template provides a declarative definition of a custom policy using the Open Policy Agent (OPA) framework and its policy language (Rego). You can define the template here, and then implement it using a custom policy. For information about OPA, go to openpolicyagent.org/docs/latest.
 
 ### Insights
 
 ### Inspections
 
 ### Events
 
## Administration

 ### Acounts
 
 ### Access
 
 In the access section of our Administration tab, we can set who has what level of access to the workload clusters.
 
 ### Integrations
 
 ### Managment clusters
 
Register Supervisor clusters in Vsphere 7 here. Give it a name, then select a cluster group, Then take the generated URL and input it into the Supervisor cluster.
You should then see the cluster show up in the list of managment clusters.

## Automation Center

## Audit Logs

## Dark Mode




## Resources

https://www.youtube.com/watch?v=6IIu_ADecDo - 12/1/20 Demo: Tanzu Mission Control Integrated with Tanzu Kubernetes Grid Service
 
https://www.youtube.com/watch?v=SwummrRK1F8 - 2/1/21  Demo: Tanzu Mission Control for Hybrid Cloud with Azure
