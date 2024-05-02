---
layout: post
title:  "Azure Basics"
author: iliana
categories: [ Articles, Tutorial ]
image: assets/images/19.jpg
tags: [sticky]
---
Today my goal is to present a common scenario of VM accessed from Azure Bastion and use of Azure Key Vault to store VM's credentials. Experimented with usage of multiple modules in terraform and setting environmental variables to store the sensitive values of username and password - administrator credentials set at creation VM.
[My Github Repo](https://github.com/ilicloudy/azurebasics.git)

## Solution Architecture

One VNET is created with 2 subnets. One for Azure Bastion and one for Servers. VM is created in Servers Subnet with only one private IP. 
Azure Key Vault is created and Key Vault policy is the chosen authorization method to access secrets. 


## Terraform code
Areas of focus in code 
- modules structure and variables declaration
- output of modules and their usage in root module
- use of module



![walking]({{ site.baseurl }}/assets/images/19.jpg)

