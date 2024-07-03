# terraform-vpc
Terraform, Infrastructure as Code! 

It creates; 
* 1 VPC, 
* 1 public subnet, 
* 1 Internet Gateway, 
* 1 Security Group
* 1 EC2 (installed a nginx in it)

After cloning the repo, just run these 4 commands

```
ssh-keygen -f london-region-key-pair
terraform init
terraform plan -out terraform.out
terraform apply terraform.out
```