# DevOps Interview Challenge

This repo keeps the instructions for the DevOps interview challenge.

### Notes before we start
* Please do not look at `cfn-step1.yml` unless you really have to.
* Please do not look at change sets, if there are any.
* Please do not look at the events or preview in CloudFormation when updating.

If at any point you get stuck, let's revisit these rules. Let us know why
you want to look break them.

## Scenario

### Current State

An engineer has recently deployed the `cfn-step1.yml` template to our AWS
account. Please review the current deployment and we can answer any questions
you have. Stack name is `devops-interview-challenge`. There is an output called
`FQDN` in the stack, make sure you can hit it.

### Future State

A new engineer did some updates and changed the Cloudformation template.
This template is represented by `cfn-step2.yml`. We are going to help this engineer
deploy this template. Once we deploy it, we'll make sure that the we can hit the
`FQDN` from the instance. If we run into any issues, we'll make sure to fix them.

### Tools

For this interview we've created a Cloud9 environment that has access to the AWS CLI
and has access to the code deployed. You can make the necessary changes through the
AWS console, but we prefer you use the AWS CLI through the Cloud9 environment to
update the `cfn-step2.yml` template.

The interviewer will give you the following information:
1. AWS console sign-in url
1. Username
1. Password
1. Name of Cloud9 environment
1. Name of cloudformation stack created with `cfn-step1.yml`
1. SSH key for `DevOps Interview Challenge`.

If you run into any permission issues when making changes, please ask the
interviewer to add the specific permission you need to IAM user or role.

### Issue
1. `squad-A` reached out to our team (DevOps) and said they will need to deploy
the `cfn-step2.yml` template today. Their goal is to make sure the new template
is working as expected. Meaning, that after deployment they are still able to
reach the server through a browser.


### Goal
1. Fix any issues you find. This could be done through the Cloudformation template
or the AWS console.


### Notes
* Ask any questions you might have to the interviewer.
* Google any questions that the interviewer cannot answer or that you feel more comfortable googling.
* There might be multiple solutions to this issue.
