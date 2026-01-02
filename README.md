
---

## Deployment Summary
The application is deployed using the AWS Management Console (initial version):

1. Launch an EC2 instance using Amazon Linux 2
2. Configure a security group to allow:
   - SSH (port 22)
   - HTTP (port 80)
3. Connect to the instance via SSH
4. Install and start Apache
5. Deploy a static HTML page
6. Verify access via the EC2 public IP

Automation scripts and Terraform will be added in later phases.

---

## Security Considerations
- SSH access is restricted via key-based authentication
- No AWS credentials or private keys are stored in this repository
- Sensitive files (e.g., `.pem`, `.aws/`, Terraform state) are excluded using `.gitignore`

---

## Cost Awareness
- EC2 instances are stopped or terminated when not in use
- Free Tier–eligible instance types are used when possible
- Future improvements will include cost monitoring

---

## Planned Enhancements
This project will evolve to include:

- Infrastructure provisioning using **Terraform**
- Application deployment via **AWS Elastic Beanstalk**
- Monitoring and logging with **Amazon CloudWatch**
- Load balancing and high availability
- CI/CD integration
- Security hardening and IAM best practices

---

## Skills Demonstrated
- AWS EC2 and networking fundamentals
- Linux server administration
- Cloud security awareness
- Git and GitHub workflow
- Infrastructure planning and documentation

---

## Author
Jeff Smith  
Cloud Computing & AWS Portfolio Project
