# 🖥️ Automated VM and Apache2 Website Deployment with Vagrant

This project demonstrates how to automatically provision a virtual machine using **Vagrant** and **VirtualBox**, and deploy a static website using **Apache2** on an **Ubuntu** VM. The setup installs necessary packages, configures networking, and downloads a ready-made website template for deployment.

---

## 📦 Tech Stack

- **Virtualization:** VirtualBox  
- **Provisioning Tool:** Vagrant  
- **Operating System:** Ubuntu Trusty 64 (`ubuntu/trusty64`)  
- **Web Server:** Apache2  
- **Website Template:** [Kool Form Pack by Tooplate](https://www.tooplate.com/view/2136-kool-form-pack)

---

## 🚀 Features

- Automatically creates and provisions a VM
- Installs and starts Apache2
- Downloads and deploys a ready-made website
- Sets up a private and public network
- Apache2 runs on startup and serves the website on VM boot

---


## ⚙️ How to Use

> 📌 Prerequisites:  
> - [Vagrant](https://www.vagrantup.com/downloads)  
> - [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

### 🔧 Step-by-Step

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/Automate_Website_Setup_Vagrant.git
   cd Automate_Website_Setup_Vagrant

2. **Start the Virtual Machine**
  ```bash
    vagrant up

3. **Access the Website**

Open your browser and go to:
http://192.168.33.55

4. SSH into the VM (optional)
  ```bash
vagrant ssh

## 📝 Notes
  - The VM uses a private network IP: 192.168.33.55. Ensure this IP doesn't conflict with other devices on your network.
  - Apache2 is configured to start automatically on VM boot and serves the static website located at /var/www/html.





