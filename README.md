# 100-Day AWS Security Learning Challenge: From Beginner to Expert

This is a detailed day-by-day plan to advance your AWS security skills from beginner to expert. Each day includes tasks, hands-on activities, and resources. Use the checkboxes (`- [ ]`) to track your progress.

---

## **Week 1-4: AWS Security Fundamentals**

### **Day 1: AWS Security Basics**
- [ ] Complete the **AWS Security Fundamentals** course on AWS Skill Builder (free).  
- [ ] Read the **AWS Shared Responsibility Model** documentation.  
- [ ] **Hands-On:** Create an AWS Free Tier account and enable MFA for the root user.  

### **Day 2: AWS Global Infrastructure**
- [ ] Study **AWS Regions, Availability Zones, and Edge Locations**.  
- [ ] Learn about **AWS Well-Architected Framework**.  
- [ ] **Hands-On:** Explore the AWS Management Console and familiarize yourself with the UI.  

### **Day 3: Identity and Access Management (IAM) Basics**
- [ ] Study **IAM Users, Groups, Roles, and Policies**.  
- [ ] Learn about **IAM Policy Language**.  
- [ ] **Hands-On:** Create an IAM user and attach a policy to grant S3 read-only access.  

### **Day 4: IAM Policies and Permissions**
- [ ] Practice writing **IAM Policies** using the AWS Policy Generator.  
- [ ] Study **IAM Policy Conditions** (e.g., `aws:MultiFactorAuthPresent`).  
- [ ] **Hands-On:** Create a policy that restricts access based on IP address.  

### **Day 5: IAM Roles and Cross-Account Access**
- [ ] Learn about **IAM Roles** and their use cases.  
- [ ] Study **Cross-Account Access** using roles.  
- [ ] **Hands-On:** Create an IAM role for cross-account access and test it.  

### **Day 6: Network Security with VPC**
- [ ] Study **VPC Components** (subnets, route tables, NACLs, security groups).  
- [ ] Learn about **Public vs. Private Subnets**.  
- [ ] **Hands-On:** Set up a VPC with public and private subnets.  

### **Day 7: Securing Data in S3**
- [ ] Study **S3 Bucket Policies** and **Access Control Lists (ACLs)**.  
- [ ] Learn about **S3 Encryption Options** (SSE-S3, SSE-KMS).  
- [ ] **Hands-On:** Create an S3 bucket, enable encryption, and configure bucket policies.  

### **Day 8-10: Review and Practice**
- [ ] Review all concepts learned in Week 1.  
- [ ] **Hands-On:** Deploy a secure web application using EC2, S3, and IAM roles.  

---

## **Week 5-8: Data Protection and Encryption**

### **Day 11: AWS Key Management Service (KMS) Basics**
- [ ] Study **KMS Key Policies, Grants, and Permissions**.  
- [ ] Learn about **Symmetric vs. Asymmetric Keys**.  
- [ ] **Hands-On:** Create a KMS key and encrypt/decrypt a small text file.  

### **Day 12: Envelope Encryption**
- [ ] Study **Envelope Encryption** and its use cases for large data sets.  
- [ ] Learn about **Data Key Caching**.  
- [ ] **Hands-On:** Implement envelope encryption for a large file stored in S3.  

### **Day 13: Key Rotation and Best Practices**
- [ ] Learn about **Automatic vs. Manual Key Rotation** in KMS.  
- [ ] Study **KMS Best Practices** for security and compliance.  
- [ ] **Hands-On:** Enable automatic key rotation for a KMS key.  

### **Day 14: SSL/TLS Termination**
- [ ] Study **SSL/TLS Termination** in ALB, CloudFront, and API Gateway.  
- [ ] Learn about **AWS Certificate Manager (ACM)**.  
- [ ] **Hands-On:** Configure SSL/TLS termination for an ALB.  

### **Day 15: S3 Encryption**
- [ ] Study **S3 Encryption Options** (SSE-S3, SSE-KMS, SSE-C).  
- [ ] Learn about **Bucket Policies** and **Access Control Lists (ACLs)**.  
- [ ] **Hands-On:** Enable SSE-KMS encryption for an S3 bucket.  

### **Day 16: Data Backup and Recovery**
- [ ] Study **AWS Backup** for centralized backup management.  
- [ ] Learn about **S3 Versioning** and **Lifecycle Policies**.  
- [ ] **Hands-On:** Set up a backup plan for an S3 bucket using AWS Backup.  

### **Day 17-21: Review and Practice**
- [ ] Review all data protection concepts learned in Week 5-7.  
- [ ] **Hands-On:** Deploy a secure data pipeline with encryption at rest and in transit.  

---

## **Week 9-12: Advanced Network Security**

### **Day 22: VPC Peering and Transit Gateway**
- [ ] Study **VPC Peering** and **Transit Gateway**.  
- [ ] Learn about **VPC Endpoints** for private access to AWS services.  
- [ ] **Hands-On:** Set up a VPC peering connection between two VPCs.  

### **Day 23: NACLs and Security Groups**
- [ ] Study **NACLs vs. Security Groups** and their use cases.  
- [ ] Learn about **Stateful vs. Stateless Firewalls**.  
- [ ] **Hands-On:** Configure NACLs and security groups for a VPC.  

### **Day 24: AWS WAF and Shield**
- [ ] Study **AWS WAF (Web Application Firewall)**.  
- [ ] Learn about **AWS Shield** for DDoS protection.  
- [ ] **Hands-On:** Configure AWS WAF to block SQL injection attacks.  

### **Day 25: Firewall Manager**
- [ ] Study **AWS Firewall Manager** for centralized WAF rule management.  
- [ ] Learn about **Security Automations**.  
- [ ] **Hands-On:** Use Firewall Manager to enforce WAF rules across multiple accounts.  

### **Day 26: Network Monitoring**
- [ ] Study **VPC Flow Logs** for network traffic monitoring.  
- [ ] Learn about **CloudWatch Logs** and **Metrics**.  
- [ ] **Hands-On:** Enable VPC Flow Logs and analyze traffic patterns.  

### **Day 27-28: Review and Practice**
- [ ] Review all network security concepts learned in Week 9-11.  
- [ ] **Hands-On:** Deploy a secure multi-tier application in a VPC.  

---

## **Week 13-16: Threat Detection and Incident Response**

### **Day 29: AWS GuardDuty**
- [ ] Study **AWS GuardDuty** for threat detection.  
- [ ] Learn about **GuardDuty Findings** and **Remediation**.  
- [ ] **Hands-On:** Enable GuardDuty and analyze findings.  

### **Day 30: Amazon Inspector**
- [ ] Study **Amazon Inspector** for vulnerability assessments.  
- [ ] Learn about **Inspector Rules Packages**.  
- [ ] **Hands-On:** Run a vulnerability scan on an EC2 instance.  

### **Day 31: AWS Security Hub**
- [ ] Study **AWS Security Hub** for centralized security findings.  
- [ ] Learn about **Security Standards** and **Compliance Checks**.  
- [ ] **Hands-On:** Enable Security Hub and review findings.  

### **Day 32: Incident Response with Lambda**
- [ ] Study **AWS Lambda** for automating incident response.  
- [ ] Learn about **Event-Driven Architectures**.  
- [ ] **Hands-On:** Create a Lambda function to remediate GuardDuty findings.  

### **Day 33: AWS Systems Manager**
- [ ] Study **AWS Systems Manager** for patch management and automation.  
- [ ] Learn about **Run Command** and **Automation Documents**.  
- [ ] **Hands-On:** Use Systems Manager to patch an EC2 instance.  

### **Day 34: AWS Step Functions**
- [ ] Study **AWS Step Functions** for orchestrating workflows.  
- [ ] Learn about **State Machines** and **Error Handling**.  
- [ ] **Hands-On:** Create a Step Function to automate incident response.  

### **Day 35-42: Review and Practice**
- [ ] Review all threat detection and incident response concepts.  
- [ ] **Hands-On:** Build an automated incident response pipeline.  

---

## **Week 17-20: Security Governance and Compliance**

### **Day 43: AWS Organizations**
- [ ] Study **AWS Organizations** for multi-account management.  
- [ ] Learn about **Service Control Policies (SCPs)**.  
- [ ] **Hands-On:** Set up AWS Organizations and apply SCPs.  

### **Day 44: AWS Control Tower**
- [ ] Study **AWS Control Tower** for secure multi-account setups.  
- [ ] Learn about **Landing Zones**.  
- [ ] **Hands-On:** Use Control Tower to create a secure landing zone.  

### **Day 45: AWS Config**
- [ ] Study **AWS Config** for compliance monitoring.  
- [ ] Learn about **Config Rules** and **Remediation**.  
- [ ] **Hands-On:** Enable AWS Config and create custom rules.  

### **Day 46: AWS Audit Manager**
- [ ] Study **AWS Audit Manager** for compliance assessments.  
- [ ] Learn about **Audit Frameworks**.  
- [ ] **Hands-On:** Use Audit Manager to assess compliance with PCI DSS.  

### **Day 47: AWS Artifact**
- [ ] Study **AWS Artifact** for compliance reports.  
- [ ] Learn about **Artifact Reports** and **Agreements**.  
- [ ] **Hands-On:** Download a compliance report from AWS Artifact.  

### **Day 48: Security Best Practices**
- [ ] Study **AWS Security Best Practices**.  
- [ ] Learn about **Well-Architected Framework**.  
- [ ] **Hands-On:** Perform a security review using the Well-Architected Tool.  

### **Day 49-56: Review and Practice**
- [ ] Review all governance and compliance concepts.  
- [ ] **Hands-On:** Deploy a secure and compliant multi-account environment.  

---

## **Week 21-25: Certification Prep and Hands-On Projects**

### **Day 57-63: Certification Readiness**
- [ ] Complete the **AWS Certified Security – Specialty Exam Readiness** course.  
- [ ] Review **AWS Whitepapers** and **FAQs**.  
- [ ] Take **Practice Exams** on TutorialsDojo or WhizLabs.  
- [ ] **Hands-On:** Simulate the exam environment with a full-length practice exam.  

### **Day 64-70: Advanced Hands-On Projects**
- [ ] Work on **Cloud Security Projects for Experts** from GitHub.  
- [ ] Explore **#100daysofAWS** projects.  
- [ ] **Hands-On:** Implement a multi-account AWS environment with SCPs.  
- [ ] **Hands-On:** Deploy a secure serverless application.  

### **Day 71-77: Review and Final Prep**
- [ ] Review all notes and hands-on exercises.  
- [ ] Take a full-length practice exam.  
- [ ] Join the **AWS Emerging Talent Community**.  
- [ ] **Hands-On:** Deploy a secure, compliant, and scalable architecture.  

---

## **Week 26-30: Expert-Level Mastery**

### **Day 78-84: Advanced Threat Detection**
- [ ] Study **AWS Detective** for threat investigation.  
- [ ] Learn about **Machine Learning in Security**.  
- [ ] **Hands-On:** Use AWS Detective to analyze security findings.  

### **Day 85-90: Real-World Projects**
- [ ] Work on **Real-World Cloud Security Projects** (e.g., securing a multi-region architecture).  
- [ ] Explore **Open-Source Security Tools** (e.g., CloudSploit, Prowler).  
- [ ] **Hands-On:** Deploy a secure, multi-region architecture with automated incident response.  

---

## **How to Use This Checklist**
1. Create a new file in your GitHub repository (e.g., `aws-security-100-day-challenge.md`).  
2. Copy and paste this checklist into the file.  
3. Use checkboxes (`- [ ]`) to mark tasks as incomplete and (`- [x]`) to mark them as complete.  
4. Commit changes regularly to monitor your advancement.  

Example:  
```markdown
- [x] Study **IAM Policy Language** and practice writing policies.  
- [ ] Learn about **IAM Roles** and their use cases.  
