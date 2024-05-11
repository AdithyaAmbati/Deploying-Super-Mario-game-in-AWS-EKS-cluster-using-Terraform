# Deploying-Super-Mario-game-in-AWS-EKS-cluster-using-Terraform
Deploying Super Mario game in AWS EKS cluster using Terraform

After creating resource using terraform ,

#this AWS CLI command gets the data of latest cluster config
aws eks update-kubeconfig --name EKS_CLOUD --region ap-south-1 
 

kubectl apply -f deployment.yaml
#to check the deployment
kubectl get all

kubectl apply -f service.yaml
#to check the service
kubectl get all
