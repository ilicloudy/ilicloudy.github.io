---
layout: post
title:  "Azure and Terraform: Static Web Site - Global Azure Greece 2024"
author: iliana
categories: [ Articles, Tutorial ]
image: assets/images/3.jpg
tags: [sticky]
---
There are lots of ways to setup static website. Blogs could be such a case as well as subsite to host media files or even log files.


## Solution Architecture

Static Website is setup using an Azure Storage Account and for achieving performance an Azure CDN endpoint located in the same resource group.
Provisioning is done using Terraform code.


## Terraform code
Areas of focus in code 
- validation of variables
- precondition of resources
- use of module


## Additional Tools
Presented use of static code analysis tools tflint, checkov in local repositories. Can also be used in pipelines.
Use of terraform-docs to generate README file 
Visualization of code with graphviz



### Static Web Site CSS Templates
Presented CSS Templates from www.free-css.com spering template
and changed according to my theme 



![walking]({{ site.baseurl }}/assets/images/8.jpg)


## Reference lists

Tools Links: 

https://github.com/terraform-linters/tflint

https://www.checkov.io/1.Welcome/Quick%20Start.html

https://terraform-docs.io/user-guide/installation/ 

terraform graph command - https://dreampuf.github.io/GraphvizOnline 

## Demo

Short presentation of the demo site! Here's a standard YouTube embed code as an example: