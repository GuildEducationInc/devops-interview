# DevOps Interview Challenge

This repo keeps the instructions for the DevOps interview challenge.

## Scenario

An engineer has recently deployed the `cfn-vpc-template.yml` template to our AWS
account. The DevOps team then deployed a bastion server (`Bastion`) to the account
and a separate squad (`squad-A`) deployed an EC2 instance called `WebServer`.

### Tools

For this interview we've created a Cloud9 environment that has access to the AWS CLI
and has access to the code deployed. You can make the necessary changes through the
AWS console, but we prefer you use the AWS CLI through the Cloud9 environment if
you are updating the Cloudformation Stack.

The interviewer will give you the following information:
1. AWS console sign-in url
1. Username
1. Password
1. Name of Cloud9 environment
1. Name of cloudformation stack created with `cfn-vpc-template.yml`
1. SSH key for `Bastion` and `WebServer`

If you run into any permission issues when making changes, please ask the
interviewer to add the specific permission you need to IAM user or role.

### Issue
1. `squad-A` reached out to our team (DevOps) and said they could not reach the `WebServer`. `squad-A` also said that their goal was to run `yum update` on the `WebServer`.
1. After we got the request, the DevOps on-call engineer tried to SSH into the `Bastion` and was unsuccessful. He has requested help from the rest of the team a he is working on an incident.


### Goal
1. SSH into `WebServer` through the `Bastion` and successfully run `yum update`.


### Notes
* Ask any questions you might have to the interviewer.
* Google any questions that the interviewer cannot answer or that you feel more comfortable googling.
* There are multiple solutions to this issue. You just need to find one.
