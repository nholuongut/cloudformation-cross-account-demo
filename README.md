# Cloudformation Cross Account Access Demo

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

This is a collection of CloudFormation templates, wrapped around Python Jinja2 templating.

## Introduction

CloudFormation yaml lacks control statements such as for-loops and conditional.
This makes organizing your AWS resources a bit tad repetitive.
Rather than using a 3rd party product like Terraform, which at the point of this writing does not support rollback, we thought we should just wrap CloudFormation files with Jinja templates.

*This is not a replacement of CloudFormation, but rather an addition*.
You still have to take the output yaml to CloudFormation whether through the AWS console or CLI.

## How to Use

Install [jinja2-cli](https://github.com/nholuongut/jinja2-cli)

    pip install jinja2-cli
    pip install jinja2-cli[yaml]

Fill in your own variables into a yaml file (example variables can be found in `vars.yml` files).
Then pass both the template and the variables to `jinja2`

    jinja2 vpc/template.yml vpc/vars.yml

Each folder contains a CloudFormation stack template and its variables.
They serve as examples of how to provision various AWS resources, and are not necessarily related to each other.
Your usage and needs may vary, but we hope these can help you in provisioning your resources.


# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: Nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)
* [PayPal.me](https://www.paypal.com/paypalme/nholuongut)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
