Role Name
=========

Ansible playbook to create a basic VPC,Subnet,IGW and ec2 to deploy an Servian Application 


Requirements
------------

* AWS credentials to create resources.
* AWS Configured in console
* Ansible and python 

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

* Please update vars section with aws credentials and other parameters 
* Run below playbook...  

```
ansible-playbook install_servian_app.yaml
```
  
