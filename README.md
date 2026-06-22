# 🚀 AWS EC2 Website Deployment using Apache

## 📌 Project Overview

This project demonstrates how to deploy a static website on an AWS EC2 Ubuntu instance using the Apache Web Server.

The objective was to launch a cloud server, install Apache, deploy a website, verify it through the public IP address, and configure an Elastic IP for a static public address.

---

## 🛠️ Technologies Used

- AWS EC2
- Ubuntu Linux
- Apache2 Web Server
- HTML
- CSS
- SSH
- Elastic IP

---

## 📋 Project Tasks

- Launch an Ubuntu EC2 instance
- Configure Security Groups
- Connect to the server using SSH
- Install Apache Web Server
- Deploy website files to `/var/www/html`
- Verify website using the Public IP
- Allocate and Associate an Elastic IP
- Verify website accessibility

---

## 📂 Project Structure

```
.
├── index.html
├── style.css
└── README.md
```

---

## ⚙️ Commands Used

### Update Package List

```bash
sudo apt update
```

### Install Apache

```bash
sudo apt install apache2 -y
```

### Check Apache Status

```bash
sudo systemctl status apache2
```

### Navigate to Web Directory

```bash
cd /var/www/html
```

### Copy Website Files

```bash
sudo cp -r * /var/www/html/
```

---

## 🌐 Verification

Open the following in your browser:

```
http://<Public-IP>
```

or

```
http://<Elastic-IP>
```

If the deployment is successful, the website loads correctly.

---

## 📸 Screenshots

- EC2 Instance Running
- Apache Installed
- Website Successfully Deployed
- Elastic IP Associated

---

## 🎯 Skills Learned

- AWS EC2
- Linux Administration
- Apache Web Server
- SSH
- Security Groups
- Website Deployment
- Public IP
- Elastic IP
- Basic Troubleshooting

---

## 📚 What I Learned

Through this project, I learned how to launch and manage an EC2 instance, configure security groups, connect securely using SSH, install Apache, deploy a website, understand the purpose of `/var/www/html`, verify deployment through a browser, and configure an Elastic IP for a static public address.

---

## 👨‍💻 Author

**Yash Pawar**

Aspiring DevOps & Cloud Engineer 🚀

Learning AWS, Linux, Shell Scripting, Docker, Kubernetes and CI/CD.


<img width="1280" height="832" alt="Screenshot 2026-06-22 at 15 53 20" src="https://github.com/user-attachments/assets/58dfb445-59ac-43b5-acab-9e62fdbbe306" />


