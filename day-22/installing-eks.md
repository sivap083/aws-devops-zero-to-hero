# Install EKS

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name demo-cluster --region us-east-1 --fargate
```
eksctl create cluster --name qc-demo-cluster --region us-east-1 --fargate --zones=us-east-1a,us-east-1b


## Delete the cluster

```
eksctl delete cluster --name demo-cluster --region us-east-1
```



