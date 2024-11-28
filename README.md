
# iOS Sideloading Without Jailbreak (No PC Required)

**A comprehensive guide to sideload apps on iOS without requiring a jailbreak or a computer. Follow these steps to install apps using DNS, Esign, and certificates effortlessly!**

![Showcase](https://github.com/opsec-bot/IOS-Sideloading-No-Jailbreak/blob/main/pictures/IMG_9476.png)

---

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Step-by-Step Guide](#step-by-step-guide)
4. [Prerequisites](#prerequisites)
5. [Setup Instructions](#setup-instructions)
   - [Set Up DNS](#1-set-up-dns)
   - [Install Esign](#2-install-esign)
   - [Set Up Esign](#3-set-up-esign)
   - [Get Certificates](#4-get-certificates)
   - [Add App Source Repositories](#5-add-app-source-repositories)
   - [Install Apps](#6-install-apps)
6. [Extra Features](#extra-features)
7. [FAQ](#faq)
8. [Disclaimer](#disclaimer)
9. [Credits](#credits)

---

## Introduction

This repository provides an easy-to-follow method for sideloading apps on iOS devices without requiring a jailbreak or a PC. The process involves configuring DNS, using the Esign app, and importing certificates to bypass traditional restrictions.

---

## Features
- No jailbreak required.
- No PC or Mac needed.
- Support for multiple IPA files and apps.
- Ability to duplicate apps and modify bundle identifiers.

---

## Step-by-Step Guide

### Prerequisites
Before starting, ensure you have:
1. An iOS device running the latest compatible version.
2. Internet access.
3. Sufficient storage space for the apps and certificates.

---

### Setup Instructions

#### 1. Set Up DNS
- **Download DNS Profile:** [Click here](https://github.com/khoindvnDNS/iOS/raw/main/DNS/khoindns.mobileconfig).  
- **Install Profile:**  
  - Go to **Files -> Click the downloaded profile -> Close the popup -> Settings -> General -> VPN & Device Management**, then tap **Install**.

#### 2. Install Esign
- **Download Esign:** [Click here](https://khoindvn.io.vn/) and scroll to the bottom to download the app.  
- **Trust Certificate:**  
  - Go to **Settings -> General -> VPN & Device Management -> Enterprise App**, tap **Trust**, then **Allow & Restart**.  
  - Manually restart your iPhone to finalize the installation.

#### 3. Set Up Esign
- Open Esign -> Go to **Download -> ••• -> Settings**.  
- Enable **Auto Import** & **Auto Delete** for efficient file management.

#### 4. Get Certificates
- **Download Certificates:** [Click here](https://khoindvn.io.vn/document/DNS/Esign-Certs.zip).  
- **Extract ZIP File:**  
  - Tap on the downloaded ZIP to extract it into a folder named **Esign Certs**.  
- **Import Certificate into Esign:**  
  - Open Esign -> Go to **Settings -> Import Resource**.  
  - Locate the **Esign Certs** folder and select a certificate to import.

#### 5. Add App Source Repositories
- **Copy Source List:** Use the provided source list:  
  ```
  source[PASTE_FULL_SOURCE_LIST_HERE]
  ```
- **Add Source to Esign:**  
  - Open Esign -> **AppStore -> App Source -> [+]** -> Paste the copied list.

#### 6. Install Apps
- **Download the App:**  
  - Open Esign -> Go to **AppStore** and download the desired app.  
- **Sign and Install:**  
  - Open Esign -> Go to **Apps -> Unsigned**.  
  - Tap the app -> Select **Signature -> Install**.

---

### Extra Features

#### Duplicate Apps
- Edit the app name or bundle identifier to install duplicates.  
  - Example: Change `com.burbn.instagram` to `com.burbn.instagram1`.

#### Install IPA Files
- Import custom IPA files into Esign:  
  - Go to **File -> ••• -> Import**.  
  - Select the IPA, then follow the **Sign and Install** steps.

---

### FAQ

#### Q: What happens if a certificate is revoked?
A: You can download and import a new working certificate from the resources provided.

#### Q: Does this work on all iOS versions?
A: This method is compatible with most iOS versions, but newer updates may affect compatibility.

#### Q: Is this process safe?
A: While this method is commonly used, sideloading apps always carries risks. Use at your own discretion.

---

### Disclaimer
This repository is for educational purposes only. By following this guide, you agree to take full responsibility for any changes made to your device. The contributors are not liable for any damage, revoked certificates, or misuse.

---

### Credits
- [Khoindvn.io.vn](https://khoindvn.io.vn/) for providing resources and tools.
- The open-source community for guidance and support.

---
