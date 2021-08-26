

## All clusters

This is a view of all clusters across your organization that you have permissions to view. 
These clusters can exist in different cluster groups and can exist in one or more physical environment

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

<img src="/screenshots/create-cluster.png" width="450"> 

Create Cluster button > Choose Management Cluster > Choose Provisioner > 

  ### Name - Choose your clusters name and assign it to a cluster group
  - Name 
  - Description
  - Labels
  
  ### Configure - Select you Kubernetes version, network and storage options
  
  ### Select Control Plane - choose between a single nore or Highly available
  
  ### Edit and add node pools - Customize the default node pool
