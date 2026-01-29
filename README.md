## Day 1 - Cloud & AWS Fundamentals
- What is cloud computing
- Traditional IT vs Cloud
- AWS regions and availability zones
- Why high availability matters
- Free tier and cost awareness
## Day 2 - IAM & Security Fundamentals
- What is IAM
- Root user vs IAM user
- IAM users, groups, roles
- IAM policies (JSON)
- Least privilege principle

## Day 3 - EC2 & Linux Fundamentals
- What is EC2
- AMI, instance type, storage, security group
- How to connect to EC2
- Basic Linux commands on EC2
- Importance of stopping/terminating instances
## Day 4 - VPC & Networking Fundamentals
- What is a VPC
- CIDR block meaning
- Public vs Private Subnets
- Internet Gateway role
- Route Tables and traffic flow
- Why EC2 connectivity fails without proper networking=

## Day 4–5: VPC, Security & EC2 Web Server (Hands-On)

### What I Built
- Custom VPC with public subnet
- Internet Gateway and route table
- Security Groups (instance-level firewall)
- Network ACLs (subnet-level firewall)
- EC2 instance (Amazon Linux)
- Apache (httpd) web server

### Architecture Flow
Internet  
→ Internet Gateway  
→ Route Table (0.0.0.0/0)  
→ Public Subnet  
→ Network ACL  
→ Security Group  
→ EC2 (Apache Web Server)

### Key Learnings
- Difference between Security Groups (stateful) and NACLs (stateless)
- Importance of outbound + ephemeral ports (1024–65535)
- Debugging real connectivity issues (DNS, routing, firewall)
- Installing and managing services on Amazon Linux

### Result
✅ Web server accessible via public IPv4 address  
✅ Page displayed: **AWS Web Server – It Works!**

(Day4-5: VPC, Security layers, and EC2 Apache web server working)
