# AWS EC2


## Preventive Controls

- [ ] EBS Volume Encryption for all EC2
- [ ] Encryption at Rest
- [ ] EC2 Instance Connect instead of plain SSH
- [ ] Implement AWS WAF (Web Application Firewall) through Amazon CloudFront
- [ ] Setup NACL with allowing only the necessary ports
- [ ] Allow Users to Launch Approved Images and Use Existing Security Groups Only
- [ ] Turn on AWS Detective
- [ ] Use CA signed certificates with SSH using AWS Secrets Manager
- [ ] Encryption in transit (SSL)
- [ ] AWS Systems Manager Patch Manager
- [ ] Automation for Instance Patching (Use CloudFormation)
- [ ] AMI Security Monitoring Package
- [ ] Creating a security group for EC2
- [ ] Require the Use of IMDSv2 When Launching EC2 Instances
- [ ] Require MFA to Stop an Amazon EC2 Instance

## Detective Controls

- [ ] Enable Cloudtrail
- [ ] Enable AWS Config
- [ ] AWS Inspector

## Logging and Monitoring

- [ ] Amazon CloudWatch
- [ ] Enable Cloudtrail
- [ ] Flow Logs
- [ ] VPC Traffic Monitoring

## Identity and Access Management

- [ ] Grant least privilege policy
- [ ] Define IAM policy to launch EC2 instances only in a specific subnet and VPC
- [ ] Limit Terminating EC2 Instances to an IP Address Range
- [ ] Generate Policy based on CloudTrail Activity


## Future work

* Add more detailed description for the checklist (The why?)
* Add the automation to perform these checks using Infrastructure as Code (IaC) (The How?)

## References

* [AWS EC2 Security](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security.html)
* [asecure.cloud](https://asecure.cloud/l/s_ec2/)
