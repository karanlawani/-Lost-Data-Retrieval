# Task 3: Lost Data Retrieval
### Arch Technologies Internship — Cyber Security Domain | Month 2

---

## 👤 Intern Details
| Field | Details |
|-------|---------|
| **Full Name** | Karan Kumar |
| **Domain** | Cyber Security |
| **Domain ID** | ARCH-2603-125177 |
| **Email** | karanlawani188@gmail.com |

---

## 📌 Task Overview
This task involves simulating accidental file deletion from a storage device and using data recovery tools to retrieve the lost files. The experiment was conducted in a safe, controlled test environment using a virtual disk formatted with the NTFS file system.

---

## 🛠️ Tools Used
- **Recuva v1.54.120 (64-bit)** — File recovery tool by Piriform
- **Windows Disk Management** — To create and format the virtual TestDrive
- **NTFS File System** — Used on the TestDrive (D:)
- **Windows 11 Pro** — Operating System

---

## 📋 Steps Performed
1. Created a virtual disk (TestDrive D:) formatted with NTFS
2. Copied 10 test files (PNG, CSV, WINMD types) to the drive
3. Permanently deleted all files using **Shift + Delete**
4. Verified the drive was completely empty
5. Ran **Recuva** with Deep Scan on the TestDrive
6. Recovered all 10 files to a separate folder on Local Disk (E:)

---

## 📸 Screenshots

**Files Before Deletion**
![Files](screenshots/Files.png)

**Permanent Deletion**
![Deleting](screenshots/Deleting.png)

**Empty Drive After Deletion**
![Empty](screenshots/empty_folder.png)

**Recuva Scan Results**
![Recuva](screenshots/Recuva_scan.png)

**Recovered Files**
![Recovered](screenshots/Recoverd_Files.png)


---

## ✅ Results
- **Files Deleted:** 10
- **Files Detected:** 10 (100%)
- **Recovery Status:** Excellent ✅
- **Overwritten Clusters:** None
- **Scan Time:** 1.95 seconds
- **Files Successfully Recovered:** 10/10

---

## 📁 Repository Contents
- `Karan_CyberSecurity_Month2.docx` — Full detailed report with screenshots

---

## 🏢 Submitted To
**Arch Technologies**
📧 submissions.archtech@gmail.com
