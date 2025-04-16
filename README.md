# 🐧 Setting Up an Ubuntu Virtual Machine using VirtualBox

This guide will help you set up an Ubuntu virtual machine from scratch using [VirtualBox](https://www.virtualbox.org/). You'll go from downloading the required software to logging into your new Ubuntu installation.

---

## 📦 Requirements

Before you begin, make sure you have the following:

- ✅ [VirtualBox](https://www.virtualbox.org/wiki/Downloads) installed
- ✅ Ubuntu ISO file downloaded ([Download Ubuntu](https://ubuntu.com/download/desktop))
- ✅ At least **25 GB of free disk space**
- ✅ At least **4 GB RAM** available (2 GB minimum)

---

## 🛠️ Step-by-Step Setup

### 1. Install VirtualBox

Download and install VirtualBox for your operating system from the official website:

> 💡 Optional: Download and install the **VirtualBox Extension Pack** from the same page for additional features like USB 2.0/3.0 support and better integration.

---

### 2. Download the Ubuntu ISO
https://www.virtualbox.org/wiki/Downloads

Visit the official Ubuntu website:
https://ubuntu.com/download/desktop

Choose the latest **LTS version** (e.g., Ubuntu 22.04 LTS) and download the `.iso` file. It will be around 4.5 GB in size.

---

### 3. Create a New Virtual Machine in VirtualBox

- Open VirtualBox and click the **"New"** button.
- Enter a name like `Ubuntu-22.04`.
- Set:
  - **Type:** Linux
  - **Version:** Ubuntu (64-bit)
- Click **Next**.

---

### 4. Allocate Memory (RAM)

- Choose how much memory to allocate to the VM.
- **Recommended:** 4096 MB (4 GB)
- **Minimum:** 2048 MB (2 GB)
- Click **Next** when done.

---

### 5. Create a Virtual Hard Disk

- Select **"Create a virtual hard disk now"** and click **Create**.
- Choose **VDI (VirtualBox Disk Image)** → Click **Next**.
- Choose **Dynamically allocated** → Click **Next**.
- Set the disk size:
  - **Minimum:** 25 GB
  - **Recommended:** 30–50 GB if you plan to install software
- Click **Create**.

---

### 6. Load Ubuntu ISO and Start the VM

- In the VirtualBox dashboard, select your new VM and click **Start**.
- A window will appear asking you to **Select a start-up disk**.
- Click the **folder icon** and browse to the Ubuntu ISO you downloaded.
- Select the ISO file and click **Start**.

---

### 7. Install Ubuntu

Once the ISO boots inside the VM, you'll see the Ubuntu welcome screen:

- Click **Install Ubuntu**.
- Choose your **language** and click **Continue**.
- Select your **keyboard layout** and click **Continue**.
- Choose installation type:
  - Select **Normal installation**.
  - (Optional) Check **Download updates while installing Ubuntu**.
  - (Optional) Check **Install third-party software**.
  - Click **Continue**.
- On the **Installation Type** screen:
  - Choose **Erase disk and install Ubuntu**.
  - *(This only affects the virtual hard drive, not your actual computer.)*
  - Click **Install Now**.
  - Confirm changes by clicking **Continue**.

---

### 8. Set Up Your User Account

- Select your **time zone** (e.g., New York, London, etc.).
- Create your user account:
  - **Your Name:** e.g., John Doe
  - **Computer Name:** e.g., ubuntu-vm
  - **Username:** e.g., john
  - **Password:** Create a secure password
- Choose whether to **log in automatically** or **require a password** to log in.
- Click **Continue**.

---

### 9. Wait for Installation to Complete

Ubuntu will now install. This typically takes **10–20 minutes** depending on your system.

Once installation is complete:

- You’ll see a prompt: **"Installation Complete. Please remove the installation medium..."**
- Click **Restart Now**.
- If VirtualBox asks, remove the ISO file:
  - Go to: **Devices > Optical Drives > Remove Disk from Virtual Drive**

---

### ✅ Done! Log into Ubuntu

After rebooting, you'll be taken to the Ubuntu login screen:

1. Select your username
2. Enter your password
3. Click **Sign In**

Welcome to your new Ubuntu Virtual Machine! 🎉

### ⚙️Server Configuration
![UBUNTU CONFIG](https://github.com/user-attachments/assets/4677a955-beb3-4cc7-9fa7-a900cbc6f923)

![UBUNTU Screenshot](https://github.com/user-attachments/assets/bc52f9f5-0218-429d-a92c-482b39d8a4b9)
![UBUNTU Screenshot](https://github.com/user-attachments/assets/eb2dcc91-84b0-465c-9149-93a6acb0a1db)
![UBUNTU Screenshot](https://github.com/user-attachments/assets/38dd706c-7d3c-4375-910a-61a900a3695e)
