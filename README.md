# Deployment-of-NodeJsApp-using-Terraform
Deployment-of-NodeJsApp-using-Terraform

Clone the Repo and perform below steps:

Makesure user has s3 bucket named my-tf-statefiles before running following commands

Terraform init
Terraform plan 
Terraform apply --auto-approve

Output: An EC2 instance will be provisioner with Apache installation,Its gets connected, install the NodeJs SW , gets the NodeJs Application from git and run on port 3000
Once Terraform gets executed, Verify publicip:3000 on browser 
