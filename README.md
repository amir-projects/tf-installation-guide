# 🚀 Terraform Installation Guide for Windows 11

## 📌 Overview
Terraform simplifies **multi-cloud** provisioning across AWS, Google Cloud, and Azure with a unified syntax. However, its installation guide often lacks depth, so here's a **step-by-step** tutorial with optimizations for **Command Prompt, PowerShell, and Git Bash**.

---

## 🔧 Prerequisites
Ensure you have:
- Windows 11 (64-bit recommended)
- Administrator access
- Internet connectivity

---

## 📂 Installation Steps

### **1️⃣ Download Terraform Binary**
- Visit [Terraform official downloads](https://developer.hashicorp.com/terraform/downloads).
- Scroll to **Windows** and select the appropriate processor type (**AMD64**, **386**, or **ARM**).
- Download the latest Terraform ZIP file (`terraform_1.x.x_windows_amd64.zip`).

> 📝 **Note:** The version changes over time. If following these instructions later, make sure to download the latest version.

---

### **2️⃣ Extract `terraform.exe`**
- Locate the downloaded ZIP file.
- Right-click and choose **Extract All...**.
- Select your target directory (**Recommended:** `C:\Programs\Terraform\`).
- Click **Extract**.

> ✅ **Tip:** Ensure that `terraform.exe` is inside the chosen folder before proceeding.

---

### **3️⃣ Configure Environment Variables**
This allows Terraform to be recognized globally by Windows terminals.

1. Open **Start Menu** and search for `Environment Variables`.
2. Click **Edit the system environment variables**.
3. In the **System Properties** window, click **Environment Variables**.
4. Under **User variables**, select `Path` and click **Edit**.
5. Click **New**, then enter your Terraform installation folder (e.g., `C:\Programs\Terraform\`).
6. Click **OK** to save changes.

---

### **4️⃣ Verify Installation**
Close all instances of **PowerShell**, **Command Prompt**, or **Git Bash**, then reopen them.

Run:
```
terraform --version
