# Ansible-Web-Deployment

## Description
This project uses Ansible to automate the setup of a web server. It includes tasks to update the apt cache, install Apache, create a directory for an eCommerce website, install Git, clone a repository from GitHub, and restart the Apache service.

Additionally, the infrastructure is provisioned using Terraform, which sets up two EC2 instances and a load balancer.

## Prerequisites
- Ansible installed on the control node
- Python 3 installed on the managed nodes
## Usage
1. Clone this repository to your local machine.
   ```bash
   [git clone https://github.com/yourusername/Ansible-Web-Deployment.git](https://github.com/AyaOmer/Ansible-Web-Deployment/tree/master)
   cd Ansible-Web-Deployment
1. Update the inventory file with the IP addresses or hostnames of your web servers.
1. Run the playbook.
   ```bash
   ansible-playbook -i inventory web.yaml
![image](https://github.com/AyaOmer/Ansible-Web-Deployment/blob/master/snap%20shot/Ubuntu-2024-10-05-19-35-45.png)
##
 ![image](https://github.com/AyaOmer/Ansible-Web-Deployment/blob/master/snap%20shot/website%20photo.PNG)
## Infrastructure Details
The infrastructure for this project is provisioned using Terraform. It includes:

- Two EC2 instances
  ![image](https://github.com/AyaOmer/Ansible-Web-Deployment/blob/master/snap%20shot/ec2.PNG)
- A load balancer
  ![image](https://github.com/AyaOmer/Ansible-Web-Deployment/blob/master/snap%20shot/load%20balancer.PNG)
 
  
#### You can find the Terraform configuration and more details in this repository.
https://github.com/AyaOmer/Secure-Cloud-Architecture_using-Terrraform  
