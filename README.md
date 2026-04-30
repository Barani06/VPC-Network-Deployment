# 🌐VPC Network Deployment

## 📌 Project Overview
This project demonstrates the creation of a Virtual Private Cloud (VPC) using Amazon Web Services.  
It includes subnet configuration, routing, internet connectivity, and DNS setup.

---

## 🏗️ Architecture Diagram

<p align="center">
  <img src="images/vpc_architecture.png" width="800"/><br>
  <em>AWS VPC Architecture with Public & Private Subnets, IGW, and NAT Gateway</em>
</p>

---

## ⚙️ Implementation Steps

## 🔹 Step 1: Create VPC
Created a Virtual Private Cloud (VPC) with a defined CIDR block to establish an isolated network.  
This forms the foundation for deploying all cloud resources securely.
.

<p align="center">
  <img src="images/step1-login.png" width="700"/>
</p>

---

## 🔹 Step 2: Create VPC  
Created a VPC with a defined CIDR block to establish an isolated network.  
This acts as the foundation for all AWS resources.

<p align="center">
  <img src="images/step2-vpc.png" width="700"/>
</p>

---

## 🔹 Step 3: Create Subnets
Created subnets within the VPC to divide the network into smaller sections.  
This improves organization and allows better control over resources.


<p align="center">
  <img src="images/step3-vpc-setup.png" width="700"/>
</p>

<p align="center">
  <img src="images/step3.1-vpc-created.png" width="700"/>
</p>

---

## 🔹 Step 4: Configure Route Table
Created and configured route tables to manage network traffic flow.  
Defined rules for internal and external communication.


<p align="center">
  <img src="images/step4-subnet-setup.png" width="700"/>
</p>

<p align="center">
  <img src="images/step4.1-subnet-created.png" width="700"/>
</p>
---

## 🔹 Step 5: Create & Attach Internet Gateway
Created an Internet Gateway and attached it to the VPC.  
This enables communication between the VPC and the internet.


<p align="center">
  <img src="images/step5-routetable-setup.png" width="700"/>
</p>

<p align="center">
  <img src="images/step5.1-routetable-created.png" width="700"/>
</p>

---

## 🔹 Step 6: Configure Public IP
Enabled automatic public IP assignment for subnet resources.  
This allows instances to be accessed from the internet.


<p align="center">
  <img src="images/step6-create-igw.png" width="700"/>
</p>

<p align="center">
  <img src="images/step6.1-attach-igw.png" width="700"/>
</p>

---

## 🔹 Step 7: Configure Route Table Association  
Updated route tables and associated them with subnets.  
Ensured proper routing of traffic within the VPC.

<p align="center">
  <img src="images/step7-confg-routetable.png" width="700"/>
</p>

<p align="center">
  <img src="images/step7.1-edit-subnets.png" width="700"/>
</p>

---

## 🔹 Step 8: Configure Public IP  
Enabled automatic public IP assignment for subnets.  
This allows instances to be accessed from the internet.

<p align="center">
  <img src="images/step8-public-IP-confg-subnets.png" width="700"/>
</p>

<p align="center">
  <img src="images/step8.1-public-IP-created.png" width="700"/>
</p>

---

## 🔹 Step 9: Enable DNS Settings  
Enabled DNS resolution and hostname support.  
This allows communication using domain names.

<p align="center">
  <img src="images/step9-enable-DNS-vpc.png" width="700"/>
</p>

<p align="center">
  <img src="images/step9.1-edit-vpc.png" width="700"/>
</p>

<p align="center">
  <img src="images/step9.2-DNS-vpc-created.png" width="700"/>
</p>

---

## 🔹 Step 10: Create NAT Gateway  
Created a NAT Gateway to allow private subnet access to the internet.  
Ensures secure outbound connectivity.

<p align="center">
  <img src="images/step10-create-NAT.png" width="700"/>
</p>

---

## 🔹 Step 11: Configure Private Route Table  
Updated private route table to route traffic through NAT Gateway.  
This enables internet access for private subnet resources.

<p align="center">
  <img src="images/step11-edit-private-routetable.png" width="700"/>
</p>

<p align="center">
  <img src="images/step11.1-add-NAT.png" width="700"/>
</p>

---

## 🔹 Step 12: Launch EC2 Instance  
Launched an EC2 instance within the configured subnet.  
This instance will be used to test network connectivity.
Connected to the EC2 instance using AWS connection methods.  
Verified that the instance is accessible and running.

<p align="center">
  <img src="images/step12-launch-EC2.jpeg" width="700"/>
</p>

<p align="center">
  <img src="images/step12.1-connect-EC2.jpeg" width="700"/>
</p>

---

## 🔹 Step 13: SSH Access  
Accessed the EC2 instance via SSH for remote management.  
This allows executing commands securely on the server.

<p align="center">
  <img src="images/step13-SSH.jpeg" width="700"/>
</p>

---

## 🔹 Step 14: EC2 Terminal Operations  
Executed commands inside the EC2 instance terminal.  
Verified system functionality and environment setup.

<p align="center">
  <img src="images/step14-EC2-terminal.jpeg" width="700"/>
</p>

---

## 🔹 Step 15: Final Output  
Displayed the final output from the EC2 instance.  
This confirms successful setup of networking and instance connectivity.

<p align="center">
  <img src="images/step15-output.jpeg" width="700"/>
</p>



## 🛠️ Tech Stack
- Amazon Web Services (AWS)  
- VPC, Subnets, Route Tables  
- Internet Gateway, NAT Gateway  

---

## 📊 Skills Demonstrated
- Cloud Networking  
- AWS Infrastructure Setup  
- Network Configuration & Security  

---


