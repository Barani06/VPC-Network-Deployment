🌐 VPC-Network-Deployment

📌 Project Overview

Designed and implemented a secure and scalable Virtual Private Cloud (VPC) using Amazon Web Services. This project demonstrates how to build a production-style cloud network by separating public-facing services from private backend systems.

🏗️ Architecture Diagram

Architecture Explanation:

VPC → Isolated cloud network
Public Subnet → Hosts internet-facing EC2 instances
Private Subnet → Hosts secure backend instances
Internet Gateway (IGW) → Enables public internet access
NAT Gateway → Allows private instances outbound internet access
Route Tables → Control traffic flow between components

⚙️ Implementation Steps

🔹 Step 1: AWS Console Access
Logged into AWS Management Console and navigated to the VPC dashboard to begin the setup.

🔹 Step 2: Create VPC
 
 Click either the “Create VPC” button or “Your VPC” on the left-side pane. Created a custom VPC with CIDR block 10.0.0.0/16, providing a private and isolated environment for resources.
