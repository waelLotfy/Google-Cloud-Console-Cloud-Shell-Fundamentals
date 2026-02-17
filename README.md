# Google-Cloud-Console-Cloud-Shell-Fundamentals
Hands‑on exploration of Google Cloud fundamentals including Compute Engine, Cloud Shell, Cloud Storage, IAM service accounts, and VM‑based web hosting using NGINX.

# Google Cloud Console & Cloud Shell Fundamentals

This project demonstrates core Google Cloud Platform (GCP) concepts through hands‑on exploration of the Google Cloud Console and Cloud Shell. It covers virtual machine provisioning, IAM service accounts, Cloud Storage management, and deploying a simple web application using NGINX.

---

## 🛠 Technologies Used

- Google Cloud Platform (GCP)
- Compute Engine (Virtual Machines)
- Cloud Shell & Cloud Shell Editor
- Cloud Storage
- Identity and Access Management (IAM)
- NGINX Web Server
- gcloud CLI

---

## 📐 Key Concepts Covered

- Google Cloud Console navigation
- Virtual machine creation and configuration
- IAM service accounts and permissions
- Cloud Shell usage and authentication
- Cloud Storage bucket management
- Public object access configuration
- File transfer between Cloud Shell and VMs
- Hosting static content on a VM

---

## 🚀 Implementation Overview

### 1️⃣ Exploring the Google Cloud Console & Compute Engine

- Created a Compute Engine VM instance
- Selected region, zone, and machine type
- Compared VM cost estimates across machine types
- Enabled HTTP firewall access
- Reviewed immutable vs editable VM properties
- Examined VM maintenance and restart behavior

---

### 2️⃣ Creating an IAM Service Account

- Created a service account for application usage
- Assigned project‑level permissions
- Verified service account availability

IAM service accounts allow applications and VMs to securely access Google Cloud resources without using user credentials.

---

### 3️⃣ Using Cloud Shell

- Activated Cloud Shell from the browser
- Verified automatic authentication
- Confirmed active project configuration
- Used environment variables for scripting
- Explored gcloud command help and configuration

Cloud Shell provides a temporary, fully authenticated VM with preinstalled Google Cloud tools.

---

### 4️⃣ Cloud Storage Bucket Management

- Created Cloud Storage buckets using:
  - Google Cloud Console (GUI)
  - Cloud Shell (CLI)
- Copied files between buckets using gcloud
- Configured public access using IAM permissions
- Verified object access via browser

This demonstrated that GUI and CLI tools interact with the same underlying cloud resources.

---

### 5️⃣ Cloud Shell Editor & File Management

- Used the Cloud Shell Editor to:
  - Clone a Git repository
  - Edit shell scripts
  - Create HTML files
- Verified file changes via terminal commands

---

### 6️⃣ Deploying a Web Server on a VM

- Installed NGINX on a Compute Engine VM
- Transferred files from Cloud Shell to the VM
- Deployed a custom HTML page
- Served static content publicly via VM external IP

---

## 🧠 Key Learnings

- Understanding Google Cloud’s resource model
- Managing infrastructure via both GUI and CLI
- Secure access using IAM service accounts
- Cloud Storage access control and public objects
- VM‑based web hosting fundamentals
- Practical use of Cloud Shell and gcloud

---

## 📎 Notes

This project was completed as part of the **Google Cloud Skills Boost** learning path and provides a strong foundation for cloud infrastructure and DevOps workflows.

