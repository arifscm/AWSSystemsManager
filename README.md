# AWS Systems Manager — Session Manager Project

## 🚀 Project Overview
This project demonstrates how to use **AWS Systems Manager (SSM) Session Manager** to securely connect to both **Linux** and **Windows EC2 instances** without needing SSH keys or RDP.

## 🛠️ AWS Services & Roles
- **AWS Systems Manager (SSM)** → Enables Session Manager connections.  
- **IAM Role** → Attached to EC2 instances to allow SSM access.  
- **Amazon EC2 (Linux & Windows)** → Instances managed via Session Manager.  

## 📑 Full Project Report (PDF)
👉 [Click here to view/download the PDF][(https://drive.google.com/your-public-share-link)](https://drive.google.com/file/d/1c2G_KaDHGViFNPpEl4q9YfBGeol3ywvu/view?usp=drive_link)

## 🔧 Steps (Summary)
1. Created an **IAM Role** with `AmazonSSMManagedInstanceCore` policy and attached it to EC2 instances.  
2. Launched a **Linux EC2 instance** and connected via **Session Manager**.  
3. Launched a **Windows EC2 instance** and accessed it first through the **EC2 console**, then through **Systems Manager Session Manager**.  
4. Verified successful connections for both Linux and Windows environments.  

## 📊 Real-time Use Case
- Used in enterprises to provide **secure, keyless access** to EC2 instances.  
- Avoids the need to manage SSH keys or open RDP/SSH ports.  
- Enhances security and compliance with centralized logging of sessions.  


