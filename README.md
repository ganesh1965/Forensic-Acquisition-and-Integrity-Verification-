# 🕵️‍♂️ **Forensic Acquisition and Integrity Verification of a Suspect’s Computer**

This repository contains my academic forensic project demonstrating the complete process of **acquiring a forensically sound disk image**, **verifying its integrity**, and **analyzing the evidence** using industry-standard forensic tools.

---

## 📂 **Repository Structure**

| Folder                           | Description                                                                    |
| -------------------------------- | ------------------------------------------------------------------------------ |
| **/practical-work**              | Contains step-by-step commands for forensic imaging, hashing, and verification |
| **/forensic_acquisition_report** | Contains the complete project report (PDF) with documentation and analysis     |

---

## ⚙️ **Tools Used**

* **Operating System:** Kali Linux
* **Commands:** `dd`, `md5sum`, `sha256sum`, `fdisk`, `umount`
* **Forensic Software:** Autopsy

---

## 🔍 **Workflow Summary**

1. **Identified the target storage device** using disk inspection tools.

2. **Unmounted the drive** to prevent data modification.

3. **Created a bit-by-bit forensic image** using:

   ```
   dd if=/dev/sdX of=/evidence/suspect.img bs=4M
   ```

4. **Verified image integrity** using MD5 and SHA-256 hashes.

5. **Loaded the forensic image into Autopsy** for analysis.

6. Recovered, examined, and documented digital evidence.

---

## 📄 **Report**

👉 **[Download Complete Forensic Report (PDF)](./forensic_acquisition_report/Forensic_Report.pdf)**

---

## 👨‍💻 **Author**

**Ganesh Patil**
BCA Student <br>
Cybersecurity & Digital Forensics Enthusiast <br>
**Tilak Maharashtra Vidyapeeth, Pune**

