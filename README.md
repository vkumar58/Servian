Role Name
=========

Ansible playbook to create a basic VPC,Subnet,IGW and ec2 to deploy an application


Requirements
------------

* AWS credentials to create resources.
* AWS Configured in console

Role Variables
--------------

* region: The region which the resources will be created https://docs.aws.amazon.com/general/latest/gr/rande.html#vpc_region
* vpc_cidr: CIDR Block of VPC
* subnet_cidr: CIDR Block of Subnet
* igw_name: IGW Name
* route_name: Route Name
* securitygroup_name: Security Group Name
* ec2_tag: EC2 Name


Example Playbook Run
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

 # ansible-playbook install_servian_app.yaml
