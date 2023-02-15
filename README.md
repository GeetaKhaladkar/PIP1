# PIP1

Setup Jenkins automatically (So even if VM crashes, you should be able to spin it back quickly) 
- via user data or other approaches that you can think of

Create terraform code for VPC setup + public subnet + private subnet + EC2 instance (in private subnet)

Create jenkins pipeline to deploy the infrastructure. 
Once deployed, should be able to login to EC2 in private subnet in a cheap / cost optimized way.
