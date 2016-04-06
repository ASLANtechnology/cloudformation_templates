# Chef Compliance Lab CloudFormation Templates (WIP)

## Purpose
Chef Compliance Lab Setup Template that uses a Chef Compliance AMI provided by Chef.

## Setup Instructions
Run each of the following CloudFormation templates in order as needed to setup the Chef Compliance Lab.
Look at the VPC CloudFormation output for any needed values for the other template parameters.

1. [VPC](https://github.com/stelligent/cloudformation_templates/blob/master/infrastructure/vpc/vpc.template)
2. [NAT Gateway](https://github.com/stelligent/cloudformation_templates/blob/master/infrastructure/nat/natgateway.template)
3. [Bastion Host](https://github.com/stelligent/cloudformation_templates/blob/master/infrastructure/bastion/bastion.template)
4. [Chef Compliance Lab](https://github.com/stelligent/cloudformation_templates/blob/master/labs/chef_compliance/chef-compliance-lab.template)
5. [Chef Compliance Lab Test Instances](https://github.com/stelligent/cloudformation_templates/blob/master/labs/chef_compliance/chef-compliance-lab-test-instances.template)
