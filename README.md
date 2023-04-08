# aws-eks-cluster
## After cluster creation please run below:
```
aws eks update-kubeconfig --name YOURCLUSTERNAME --region CLUSTER-DEPLOYMENT-REGION
```
```
aws eks describe-cluster --name <cluster-name> --query cluster.status
```