# Week 1: AWS EC2 Windows Lab – Steps

## 1. Launch EC2 Instance
- Logged into AWS Management Console.
- Navigated to **EC2 → Instances → Launch Instances**.
- Selected **Windows Server 2019 Base** AMI.
- Chose **t3.micro** as the instance type.
- Created or selected an existing **key pair** for RDP access.
- Configured **security group** to allow **RDP (port 3389)** from my IP (or Anywhere for testing).
- Launched the instance.

## 2. Connect to EC2 via RDP
- Copied the **Public IPv4 address** from the EC2 console.
- Opened **Remote Desktop Connection** on my laptop.
- Entered **IP address**, **username: Administrator**, and decrypted **password**.
- Successfully logged into the Windows Server desktop.

## 3. Install Software (Notepad++)
- Opened **Microsoft Edge** inside the EC2 instance.
- Downloaded **Notepad++ installer**.
- Installed **Notepad++** successfully.
- Verified installation by opening the program.

## 4. Stop, Start, and Terminate Instance
- In EC2 console, selected the instance.
- Clicked **Actions → Instance State → Stop**, verified instance stopped.
- Clicked **Actions → Instance State → Start**, verified instance started again.
- Finally, **terminated the instance** to avoid charges.

## 5. Notes
- Took screenshots at each major step for portfolio purposes:
  - Instance details (ID, state, type, IP)
  - AMI info
  - RDP login window
  - Windows desktop
  - Notepad++ installed
  - Instance stopped/terminated
