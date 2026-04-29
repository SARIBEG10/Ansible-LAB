Ansible LAB
- Setup 3 Node RedHat Centos 7.9 linux Server
- Install Ansible on all 3 Nodes => https://docs.ansible.com/projects/ansible/latest/installation_guide/installation_distros.html
- Configure Passwordless SSH on them
- Configure Hostname and Host DNS files for All 3 Nodes
- Run Different Playbooks on 2 Worker Nodes From 1 Master

LAB SETUP STEPS:

ON client and server hosts:
1- hostnamectl set-hostname ansible-server
2- hostnamectl set-hostname ansible-client1/host_1
3- hostnamectl set-hostname ansible-client2/host_2
4- source /etc/.bash_completion.d/


ON Ansible server :
1- ssh-keygen -t rsa
2- ssh-copy-id [client-ip]
3- /etc/hosts
	[host_1 ip add]  host_1
	[host_2 ip add]  host_2


THIS LAB CONTAINS 3 PRODUCTION READY TOOLS SETUP BY EXAMPLE:
1- Apache tomcat
2- IIS on windows Server
3- Nginx + HAproxy

NOTE: YOU CAN RUN ALL PLAYBOOKS IN REPO: https://github.com/SARIBEG10/SariBeg-Ansible ON THIS LAB 
  
