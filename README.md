# Secure User Access Management in Linux  

This repository contains project documentation and solutions for managing secure user access in Linux environments. It demonstrates fundamental Identity and Access Management (IAM) concepts and practical scenarios using Linux commands and tools like FACL (File Access Control List).

---

## Overview  

Linux powers much of the modern digital infrastructure due to its reliability and security. Effective user and access management are crucial for protecting sensitive data and ensuring compliance in both personal and professional environments. This repository provides practical examples of secure user access management, addressing real-world scenarios.

---

## Objectives  

1. **Understand Identity and Access Management (IAM)** in Linux.  
2. **Implement access controls** to manage file permissions and user privileges securely.  
3. **Demonstrate practical solutions** for scenarios involving file handling and group/user permissions.

---

## Scenarios  

### **Lab 1: Managing User Access for Individual Files**  

- **Scenario**:  
  Save a file on a Linux machine, create a user account, and set up secure file access using FACL so only the designated user can access the file.  

- **Tasks**:  
  - Create user accounts.  
  - Set up directories and assign permissions using `chown`, `chmod`, and `setfacl`.  
  - Test and verify permissions by logging in as different users.  

### **Lab 2: Group and Multi-User File Access Management**  

- **Scenario**:  
  Manage file permissions for multiple users and groups representing a government census department. Assign varied levels of access (read, write, execute) to users from different states for specific files.  

- **Tasks**:  
  - Create users and groups using `useradd` and `groupadd`.  
  - Apply recursive permissions to directories and specific access rights using `chmod` and `setfacl`.  
  - Validate permissions by testing access levels for various users.  

---

## Prerequisites  

- A Linux distribution (Kali preferred).  
- Basic understanding of Linux commands and user management.  
- Root privileges for executing administrative tasks.  

---

## Key Commands Used  

- `useradd`: Create new users.  
- `groupadd`: Create new groups.  
- `chown`: Change file ownership.  
- `chmod`: Modify file and directory permissions.  
- `setfacl`: Manage Access Control Lists for advanced permission settings.  
- `su`: Switch users for permission testing.  

---

## Files  

1. **noida.txt**: Sample file used in Lab 1.  
2. **government.zip**: Contains files for managing access in Lab 2.  
3. **Reports**: Includes detailed steps, commands, and screenshots for both labs.  

---

## Disclaimer

This repository is created for educational purposes only. The content and instructions provided are intended to help learners understand and implement secure user access management practices in Linux environments.

## Usage Guidelines:

- Do not use this material for malicious purposes or activities that violate ethical standards or legal regulations.
- Ensure you have appropriate permissions before applying these techniques in any environment.
- The author is not liable for any misuse of the content provided in this repository.

