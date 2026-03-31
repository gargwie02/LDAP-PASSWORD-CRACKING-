# LDAP-PASSWORD-CRACKING-
# 🔐 LDAP Enumeration Lab (CEH v12)

This repository contains a hands-on lab demonstrating **LDAP Enumeration techniques** using multiple tools in a simulated Active Directory environment.

---

## 📌 Overview

LDAP (Lightweight Directory Access Protocol) is used to access and manage directory services like **Active Directory**. This lab focuses on extracting valuable information such as:

- Domain structure
- User accounts
- Attributes
- Naming contexts

---

## 🛠 Tools Used

- AD Explorer (GUI-based enumeration)
- Nmap (LDAP scanning & brute-force scripts)
- Python (ldap3 library for manual enumeration)
- ldapsearch (command-line LDAP queries)

---

## 🚀 Lab Tasks

### 1️⃣ LDAP Enumeration using AD Explorer
- Connected to target domain controller
- Explored directory structure (`DC=CEH,DC=com`)
- Viewed user objects and attributes

---

### 2️⃣ LDAP Enumeration using Nmap & Python

#### 🔹 Nmap Scan
```bash
nmap -sU -p 389 <Target-IP>
