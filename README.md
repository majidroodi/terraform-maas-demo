# Terraform
Terraform is an open-source infrastructure as code software tool that provides a consistent CLI workflow to manage hundreds of cloud services. Terraform codifies cloud APIs into declarative configuration files.
- Write
- Plan
- Apply

## Acronyms
- IAC: Infrastructure as code (IaC) tools allow you to manage infrastructure with configuration files rather than through a graphical user interface. IaC allows you to build, change, and manage your infrastructure in a safe, consistent, and repeatable way by defining resource configurations that you can version, reuse, and share.


## How to install `terraform` :

### Manual installation

After downloading Terraform, unzip the package. Terraform runs as a single binary named terraform. Any other files in the package can be safely removed and Terraform will still function.

```
 $ mv ~/Downloads/terraform /usr/local/bin/
```
## What is terraform_maas_demo

provisioning and make real infrastracture with maas

- step 1 : A way to manage the power of VirtualBox virtual machines via the MAAS webhook driver.
[github link for help](https://github.com/ssbostan/vboxpower)
- step 2 : git clone terraform_maas_demo project
- step 3 : run the following command.

```
$ terraform init

$ export TF_VAR_MAAS_API_URL=http://192.168.56.3:5240/MAAS

```
### crate API_KEY in maas and following more command
```
$ export TF_VAR_MAAS_API_KEY="maas API_KEY gnerated"

$ terraform plan

$ terraform apply -auto-approve
```

--------------------------------------------------
#### Write by Majid Roodi     
[majidroodi.github.io](majidroodi.github.io)  
[majidroodi.mr@gmail.com](majidroodi.mr@gmail.com) 

---------------------------------------------------
This is a part of DevOps with Saeid class 
(`DWS-OPS-002-TERRAFORM`)  
See more on:  
[www.devops-with-saeid.com](www.devops-with-saeid.com)

