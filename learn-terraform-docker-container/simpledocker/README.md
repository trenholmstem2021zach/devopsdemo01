# - terraform basics

## Overview
The terraform {} block contains Terraform settings, including the required providers Terraform will use to provision your infrastructure. For each provider, the source attribute defines an optional hostname, a namespace, and the provider type. Terraform installs providers from the [Terraform Registry](https://registry.terraform.io/) by default.

### Summary of steps.
- Create Terraform 
- terraform init
- terraform fmt
- terraform plan
- terraform validate
- terraform apply
- terraform destory

## First Initialize the directory
When you create a new configuration — or check out an existing configuration from version control — you need to initialize the directory with terraform init.

Initializing a configuration directory downloads and installs the providers defined in the configuration, which in this case is the docker provider.

