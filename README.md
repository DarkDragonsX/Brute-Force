# Brute-Force Tool

 ## Facebook account password testing utility for ethical penetration testing purposes.


## Overview

The Brute-Force tool is an experimental, free version of "Black Dragon" designed to assess the strength of passwords associated with Facebook accounts. It supports testing via email, phone number, or username.

> **Disclaimer:** This tool is intended solely for ethical penetration testing. Use it only with the explicit permission of the account owner. Unauthorized use may result in severe legal consequences.

---

## Key Features

- **Password Testing:**  
  Systematically tests each password listed in the `passwords.txt` file located in the tool’s directory.

- **Delay Between Attempts:**  
  Implements a delay of 5 to 7 seconds between each attempt to reduce the risk of detection or account lockouts.

- **Identity Concealment:**  
  It is recommended to use a VPN or similar anonymizing tools (e.g., VBN) during operation to mask your origin.

- **System Compatibility:**  
  Designed primarily for Kali Linux, with specific optimizations for Kali Nethunter on Termux for mobile devices.

---

## Setup and Operation Instructions

### 1. Prepare the Password File

- Create a file named `passwords.txt` in the same directory as the tool.
- Ensure the file contains the list of passwords you wish to test.

### 2. Install the Requirements

Open a terminal, navigate to the tool’s directory, and run the following commands:


# Clone the repository
```bash

wget https://raw.githubusercontent.com/dddhhr/Brute-Force/main/brute-force.tar

```



# Unzip the package
```bash
tar -xf brute-force.tar
```
# Go to a folder I have edited 
```bash
cd brute-force
```
# Grant execution permissions to all files

```bash
chmod 777 *
```

# Run the installation script

> Make sure to run this file. If you do not install it,
the tool will not work for you. 
---
```bash
sudo bash install.sh
```

# Launch the tool
```bash
python3 Brute-force.py
```

Note: It is advisable to update your Kali Linux system beforehand:
```bash
sudo apt update && sudo apt upgrade
```

3. Run the Tool
---
After completing the setup and installation:
---
Launch the tool.
---

<img src="https://raw.githubusercontent.com/dddhhr/Brute-Force/main/nethunter.kex.jpg" width="300">

**Input the account details (email, phone number, or username) you wish to test.**

**If you want to create a `password` file, it's best to keep the name as passwords.txt to ensure compatibility with the tool without any extra configuration.**

I also recommend using specialized `password` list generators that tailor the file based on the target account's available information. This approach will help create a more accurate and effective list of potential passwords, thereby improving the overall efficiency of your security testing.

---


---

Usage Guidelines and Ethical Considerations
---
Legal Use:
Use this tool only after obtaining explicit permission from the account owner.

Personal Responsibility:
Unauthorized use of this tool may lead to serious legal repercussions.

Educational Purpose:
The primary goal is to enhance cybersecurity awareness and to emphasize the importance of using strong, secure passwords.



---

## 📍 Stay Updated 

**For the latest cybersecurity tips, ethical hacking techniques, and tool updates, follow me on:**
>  Follow me on Instagram to get all the latest news👨‍💻
> Contact me through my Facebook account 👨‍💻
--- 
- **Instagram: @dddhhr_

- **Facebook: https://www.facebook.com/dddhhhr**










