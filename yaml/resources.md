

Operating Tanzu Kubernetes Clusters


https://docs.vmware.com/en/VMware-vSphere/7.0/vmware-vsphere-with-tanzu/GUID-6B21C37B-91ED-4218-B7B8-C40417ADBF8A.html


## commands

Tanzu Kubernetes Cluster
```
k get tkc -A
```


Tanzu Kubernetes Release
```
k get tkr
```

run during update
```
k describe tkn -n <namespace> <clustername>
```


Cluster Role Binding for Pod Security Policy
```
kubectl create clusterrolebinding psp:authenticated --clusterrole=psp:vmware-system-privileged --group=system:authenticated
```


create secret then patch service account
```
kubectl create secret docker-registry regcred --docker-server=<harbor IP> --docker-username=<username> --docker-password=<password>

kubectl patch serviceaccount default -p '{"imagePullSecrets": [{"name": "regcred"}]}'
```


