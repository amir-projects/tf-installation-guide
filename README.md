<!-- 🚀 Advanced Terraform Installation Guide (Windows 11) -->

<p align="right">
# Installing Terraform on Windows 11
</p>

## 💾 **Step 1: Download Terraform Binary**
- Navigate to the [Terraform official site](https://developer.hashicorp.com/terraform/install).
- Scroll down to the **Windows** section.
- Choose the processor type (**386** or **ARM**).
- Download the latest ZIP file (`terraform_1.x.x_windows_amd64.zip`).

> ⚠ **Note:** Version numbers change over time. If following this guide later, ensure you're downloading the most recent version.

---

## 📂 **Step 2: Extract `terraform.exe`**
- Locate the downloaded ZIP file.
- Right-click and choose **Extract All…**.
- Select your target directory (**Recommended:** `C:\Programs\Terraform\`).
- Click **Extract**.
- Verify that `terraform.exe` is inside the chosen folder.

---

## 🔗 **Step 3: Configure Environment Variables**
The **Path Environment Variable** allows Terraform commands to be recognized globally.

1. Open **Start Menu** and search for `Environment Variables`.
2. Click **Edit the system environment variables**.
3. In the **System Properties** window, click **Environment Variables**.
4. Under **User variables**, select `Path` and click **Edit**.
5. Click **New**, then enter your Terraform installation folder (e.g., `C:\Programs\Terraform\`).
6. Click **OK** to save changes.

---

## ✅ **Step 4: Verify Installation**
Close all instances of **PowerShell**, **Command Prompt**, or **Git Bash**, then reopen them.

Run:
```
terraform --version
