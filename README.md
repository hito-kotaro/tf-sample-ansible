# tf-sample-ansible
Ansibleハンズオン用の環境を構築するためのテンプレート.EC2を2つ作成する.

# Features
## aws
* VPC
* EC2

# Requirement
* Terraform v1.0.6

# Installation

## git clone

```zsh
$ git clone https://github.com/hito-kotaro/tf-sample-ansible.git
$ cd tf-sample-ansible
```

## create terraform.tfvars
```zsh
$ touch terraform.tfvars
$ vim terraform.tfvars
```

### terraform.tfvars
```
# terraform.tfvars
key_name = <YOUR SECRET KEY NAME FOR EC2 ACCESS>
```

## ecexute terraform 
```zsh
$ terraform init 
$ terraform apply
```
