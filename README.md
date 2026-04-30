# Ansible LAB
### :one: Setup 3 Node RedHat Centos 7.9 linux Server
### :two: Install Ansible on all 3 Nodes => [Ansible Install](https://docs.ansible.com/projects/ansible/latest/installation_guide/installation_distros.html)
### :three: Configure Passwordless SSH on them
### :four: Configure Hostname and Host DNS files for All 3 Nodes
### :five: Run Different Playbooks on 2 Worker Nodes From 1 Master


# ⚛️Overview
## 🫀:THIS LAB CONTAINS 3 PRODUCTION READY TOOLS SETUP BY EXAMPLE:
### 1. **Apache tomcat**
### 2. **IIS on windows Server**
### 3.  **Nginx + HAproxy**

## ⬇️LAB SETUP STEPS:
#### **Client and Server hosts:**
- Server
```powershell
   hostnamectl set-hostname ansible-server
```
- host_1
```powershell
   hostnamectl set-hostname ansible-client1/host_1
```
- host_2
```powershell
   hostnamectl set-hostname ansible-client2/host_2
```
- bash auto complete activation
```powershell
   source /etc/.bash_completion.d/
```

#### **ON Ansible server:**
```powershell
  ssh-copy-id [client-ip]
```
```powershell
 vi /etc/hosts
	[host_1 ip add]  host_1
	[host_2 ip add]  host_2
```

 
>[!NOTE]
>**YOU CAN RUN ALL PLAYBOOKS IN [REPO](https://github.com/SARIBEG10/SariBeg-Ansible) ON THIS LAB** 
  
