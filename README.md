# Install AWS CLI 

https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html


# Install Terraform

Install yum-config-manager to manage your repositories.
```
sudo yum install -y yum-utils
```
</br>
Use yum-config-manager to add the official HashiCorp Linux repository.
```
sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo
```
</br>
Install.
```
sudo yum -y install terraform
```