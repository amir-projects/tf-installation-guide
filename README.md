<!-- Terraform Installation Guide -->

<p align="right">
# Terraform Installation Guide for Windows 11
</p>

<p align="right">
I have been using Terraform to deploy infrastructure on AWS, Google Cloud, and Azure. It simplifies multi-cloud provisioning with a unified syntax.
However, the official installation guide lacks details. Here’s a step-by-step tutorial with instructions and screenshots.
</p>

---

## **Steps to Install Terraform on Windows 11**

### **1. Download Terraform Binary**
<p align="right">
- Go to [Terraform official site](https://developer.hashicorp.com/terraform/install).
- Scroll down to the Windows section.
- Select processor type (386 or ARM).
- Download the latest version (e.g., `terraform_1.1.36_windows_amd64.zip`).
</p>

---

### **2. Extract Terraform Executable**
<p align="right">
- Locate the downloaded ZIP file.
- Right-click and select **Extract All**.
- Choose a target folder (e.g., `C:\Programs\Terraform`).
- Click **Extract** to complete the process.
</p>

---

### **3. Add Terraform to Path Environment Variable**
<p align="right">
- Open **Start Menu** and search for `Environment Variables`.
- Click on **Edit the system environment variables**.
- In the Environment Variables window:
  - Under **User Variables**, select `Path` and click **Edit**.
  - Click **New**, then enter your Terraform folder path (e.g., `C:\Programs\Terraform`).
  - Click **OK** to save changes.
</p>

---

### **4. Verify Installation**
<p align="right">
- Close all instances of PowerShell, Command Prompt, or Git Bash.
- Open a new terminal and run:
  ```sh
  terraform --version
