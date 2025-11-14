# terraform-project-kubernetes-cluster-on-AWS-EKS

Create Kubernetes Cluster through Terraform on AWS EKS (Elastic Kubernetes Service)

<img width="524" height="524" alt="image" src="https://github.com/user-attachments/assets/31c6a144-cd44-4046-862b-837f1f47eb0a" />  
## AWS

1. EKS manages Cluster Plane of Kubernetes Cluster
2. VPC needed b/w nodes/service to communicate with each other.
3. We need to maintain EC2 instances, Rest is managed by EKS cluster.
4. In case of EKS, controller manager named as Cloud Controller Manager

Following terraform configuration files needed:

- terraform.tf
- provider.tf
- vpc.tf
- eks.tf
- variables.tf

Execute command to apply:
```bash
  terraform init
  terraform plan
  terraform taint
  terraform apply -auto-approve
```
