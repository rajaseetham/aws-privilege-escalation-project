Operation Elevate: Mastering Privilege in the Cloud

> Final Year MSc Computer Science Project  
> PSGR Krishnammal College for Women | Internship @ Jupyter Talent Solutions  
> Jan 2025 – Mar 2025

Project Overview

"Operation Elevate: Mastering Privilege in the Cloud" simulates real-world privilege escalation attacks in AWS using intentionally vulnerable environments. The project highlights how misconfigured IAM roles and policies can lead to unauthorized administrative access.

This red-team simulation explores how attackers can escalate privileges by abusing overly permissive permissions like:

- `iam:ListAccessKeys`
- `iam:CreateAccessKey`
- `iam:UpdateAccessKey`
- `sts:AssumeRole`

Tools & Technologies

- AWS IAM, STS, Secrets Manager
- CloudGoat – vulnerable-by-design AWS environment
- AWS CLI, Pacu (red-teaming tool)
- Terraform – Infrastructure as Code
- Docker (Ubuntu container for simulation)
- Linux, Python 3.9+

---

Attack Simulation Steps

1. Clone and set up CloudGoat** environment
2. Configure IAM users with custom policies
3. Simulate access key enumeration and key rotation
4. Attempt role assumption using `sts:AssumeRole`
5. Bypass MFA using virtual devices
6. Retrieve secrets from Secrets Manager
7. Propose security fixes: least privilege, CloudTrail, MFA, policy review

---

Learning Outcomes

- Understood how attackers exploit IAM misconfigurations
- Implemented Terraform scripts for reproducible infrastructure
- Used ethical hacking tools to perform simulations
- Proposed real-world mitigation strategies** and IAM security best practices

---

Screenshots

> Add screenshots of terminal commands, assumed role responses, Terraform config, etc.

---

References

- [AWS IAM Documentation](https://docs.aws.amazon.com/IAM/latest/UserGuide/)
- [CloudGoat by Rhino Security](https://github.com/RhinoSecurityLabs/cloudgoat)
- [AWS CLI User Guide](https://docs.aws.amazon.com/cli/latest/userguide/)
- [Terraform Docs](https://developer.hashicorp.com/terraform/docs)

---
About Me

I’m Rajaseetha M, a Computer Science graduate passionate about Cloud Security, DevSecOps,andAWS.  
mrajaseetha95@gmail.com  
[LinkedIn](https://www.linkedin.com/in/rajaseetha-m-83b833278)

