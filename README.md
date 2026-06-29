# QR-Based-Secured-Password-Vault-
 A secure web-based password management system with multi-layer authentication and  encrypted storage
# 🔐 Secured Password Vault with QR-Based Multi-Layer Authentication

## Overview

The **Secured Password Vault with QR-Based Multi-Layer Authentication** is a secure web-based password management application developed to provide users with a reliable platform for storing, organizing, and protecting sensitive credentials. Unlike traditional password managers that rely solely on a master password, this system integrates multiple security layers including **AES-256 encryption**, **dynamic QR-based authentication**, **security logging**, **password strength evaluation**, **breach detection**, and **device verification**.

The primary objective of this project is to strengthen password security while maintaining ease of use. Every stored password is encrypted before being saved to the database, ensuring that even if the database is compromised, confidential information remains protected. Sensitive passwords are never displayed directly to the user without successful QR-based verification from a registered mobile device.

---

# Problem Statement

With the increasing number of online services, users are required to maintain dozens of passwords for banking, education, social media, healthcare, cloud services, and enterprise applications. Many users either reuse passwords across multiple websites or store them insecurely in text files or browsers.

Traditional password managers improve usability but still suffer from several limitations:

* Dependence on a single master password
* Vulnerability to phishing attacks
* Exposure through screenshots or shoulder surfing
* Lack of real-time monitoring
* No visibility into password breaches
* Weak auditing mechanisms

The proposed system addresses these issues by introducing multiple security mechanisms working together to protect user credentials.

---

# Key Features

## AES-256 Encryption

All passwords are encrypted using AES-256 before storage. Sensitive information never exists in plaintext inside the database.

## QR-Based Multi-Layer Authentication

Whenever a user attempts to reveal a stored password, the system generates a unique QR code that must be scanned using a registered mobile device. Passwords are displayed only after successful verification.

## Secure Password Vault

Users can securely:

* Add passwords
* Update passwords
* Delete passwords
* Restore deleted passwords
* Permanently remove passwords

Each operation is securely logged.

## Password Strength Analyzer

The vault evaluates password strength in real time using entropy calculations and complexity analysis. Users receive immediate feedback regarding:

* Password score
* Password entropy
* Estimated cracking time
* Security recommendations

## Password Breach Checker

Passwords are checked against publicly known breached password databases without exposing the user's actual password. This enables users to identify compromised passwords before using them.

## Security Audit Logs

Every important activity inside the vault is recorded, including:

* Login
* Logout
* Password creation
* Password deletion
* Password restoration
* QR verification
* Failed authentication attempts

These logs provide complete accountability and help detect suspicious activity.

## Last Access Location

The application records the user's last successful login location using geolocation services. This allows users to verify whether their account was accessed from an expected location.

## Recently Deleted Password Recovery

Instead of immediately deleting passwords, the system moves them to a recycle bin where they can either be restored or permanently deleted.

## Dark Mode

A modern dark interface improves usability while reducing eye strain during extended usage.

---

# System Modules

The application consists of several integrated modules:

### Authentication Module

* User registration
* Secure login
* Session management
* QR verification

### Password Vault Module

* Password encryption
* Password storage
* Password retrieval
* Password updates

### QR Authentication Module

* Dynamic QR generation
* Mobile verification
* Device validation
* Token expiration

### Security Module

* AES-256 Encryption
* Password hashing
* Secure session management
* Access control

### Monitoring Module

* Security logs
* Login history
* User activity tracking
* Event auditing

### Password Intelligence Module

* Password strength analysis
* Password breach detection
* Security recommendations

---

# Technologies Used

## Frontend

* HTML5
* CSS3
* Bootstrap
* JavaScript

## Backend

* PHP
* MySQL

## Security Technologies

* AES-256 Encryption
* QR Code Authentication
* Secure Sessions
* Password Hashing

## APIs & Libraries

* QR Code Generator
* Leaflet Maps
* Bootstrap Icons
* Have I Been Pwned API
* PHP OpenSSL Extension

---


## Configure Database

Update database credentials inside the configuration file.

## Run Application

Start Apache and MySQL using XAMPP.

Open:

```
(http://localhost/qr-based-secured-password-vault/)
```

---

# Project Workflow

1. User logs into the application.
2. Authentication is verified.
3. Dashboard displays encrypted credentials.
4. User selects a password to reveal.
5. System generates a time-limited QR code.
6. Registered mobile device scans the QR code.
7. Device verification is completed.
8. Password is decrypted and displayed.
9. Every activity is recorded in Security Logs.
10. Password strength and breach status can be analyzed.

---

# Security Features

* AES-256 Encryption
* QR-Based Multi-Layer Authentication
* Secure Session Handling
* Device Verification
* Password Strength Analyzer
* Password Breach Checker
* Audit Logging
* Last Login Location Tracking
* Recently Deleted Recovery
* Dark Mode Interface

---

# Future Enhancements

* Biometric Authentication
* Face Recognition
* Fingerprint Login
* Secure Cloud Synchronization
* AI-Based Threat Detection
* Browser Extension
* Mobile Application
* Password Sharing Between Trusted Devices

---

# Project Screenshots

The repository contains screenshots demonstrating:

* Login Interface
* Password Vault Dashboard
* QR Authentication
* Security Logs
* Password Strength Analyzer
* Password Breach Checker
* Last Access Location
* Recently Deleted Passwords
* Mobile QR Verification

---

# Author

**O. V. Yogeswar Reddy**

Department of Computer Science and Engineering
(IoT & Cyber Security including Blockchain)

BMS College of Engineering

---

# License

This project is developed for academic and educational purposes as part of the Mini Project curriculum at BMS College of Engineering.

---

⭐ If you found this project useful, please consider giving it a **Star** on GitHub.
