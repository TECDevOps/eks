# eks
Creating an Amazon Elastic Kubernetes Service Cluster using Terraform

AWS Virtual Private Cloud (VPC)
Three public and three private AWS Subnets in different AWS Cloud availability zones.
One AWS Route Table.
Two AWS Route Table Association.
AWS Internet Gateway attached to the VPC.
AWS EKS Cluster. It will have one master node to manage the Kubernetes application.
AWS EKS Node Group with two worker nodes.
AWS Security Group with an Ingress rule.
IAM Role for the AWS EKS Cluster with two policies.
IAM Role for the Node Group with three policies.

1. Create variables.tf file
2. Create a terraform.tf file
3. Create a vpc.tf file
4. Create an eks-cluster.tf file
5. Create a main.tf file
6. Create outputs.tf file

commands
terraform init
terraform plan
terraform apply
kubectl cluster-info
kubectl get nodes


