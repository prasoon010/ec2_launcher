# ec2_launcher
This ansible playbook will create a VPC, 3 security groups, 3 subnets: 2 public subnet for bastion and webserver, 1 private subnet for db server. It will also create an ec2 instance and take an AMI and copy it to another region. We will use this playbook in future to build on it and create a simple infrastructure
