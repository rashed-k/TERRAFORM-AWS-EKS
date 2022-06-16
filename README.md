# Install AWS CLI 

https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html


# Install Terraform

choose your downloads depending on Operating System - https://learn.hashicorp.com/tutorials/terraform/install-cli



Installation for CentOS/RHEL - 
=======

```
sudo yum install -y yum-utils

sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/RHEL/hashicorp.repo

sudo yum -y install terraform
```

# Download the repo from Github 

https://github.com/hashicorp/terraform-provider-aws

<br />

Once Downloaded, check-in eks-getting-started directory ---> /terraform-provider-aws/examples/eks-getting-started


# Apply Terraform 

Explore the files related to Eks-cluster,Eks-worker,providers,vpc,workstation-external-ip and variables before execution. 
```
terraform init 
terraform plan
terraform apply
```
<br />

confirm the resources are applied.
```
terraform state list
```

