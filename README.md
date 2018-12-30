# IaC
Various Infrastructure as Code samples

TestingVPCE.yml is pretty complete.  It is a Cloudformation template to createa VPC, a private and public subnet, an EC2 spot instance in both subnets, a SG for SSH access, an instance profile for S3 access an a VPCE to allow the private subnet to access the S3 bucket.  It was pretty useful for me to refamiliarize myself with all the parts necessary to make this work.
