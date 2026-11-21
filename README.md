# week3-Password-cracking-with-JTR-NETWORKWALKS-tools
# Password Cracking with John the Ripper and Networkwalks Tools

## Project Overview

This project demonstrates password recovery techniques using John the Ripper (JTR) and Networkwalks password-cracking tools.

The practical exercises were completed as part of a Cybersecurity and Ethical Hacking project.

The project consists of two modules:

- Module 1: Password Cracking with John the Ripper
- Module 2: Password Cracking with Networkwalks Tools

## Objectives

- Understand password hashing and encryption.
- Extract password hashes from protected PDF files.
- Learn how password-cracking tools work.
- Perform dictionary attacks using password hashes.
- Understand the importance of strong passwords.

## Tools Used

| Tool | Purpose |
|---|---|
| John the Ripper | Password recovery |
| Johnny GUI | Graphical interface for John the Ripper |
| Networkwalks Hash Calculator | Extracting PDF password hashes |
| Networkwalks Password Cracker | Recovering passwords |
| Windows | Operating system |

## Module 1: Password Cracking with John the Ripper

### Description

This module demonstrates how John the Ripper and Johnny can be used to recover the password of a protected PDF file.

### Procedure

1. Download and install John the Ripper.
2. Download and install Johnny GUI.
3. Configure Johnny by locating the `john.exe` executable.
4. Obtain the password-protected PDF file.
5. Extract the PDF password hash using an online hash extractor.
6. Save the extracted hash in a text file named `hash1.txt`.
7. Open Johnny and load the saved hash file.
8. Start a new password-cracking attack.
9. Retrieve the recovered password.
10. Use the password to open the protected PDF file.

## Module 2: Password Cracking with Networkwalks Tools

### Description

This module uses the Networkwalks Hash Calculator and Password Cracker to recover the password of a protected PDF file.

### Procedure

1. Download the protected PDF file.
2. Open the Networkwalks Hash Calculator.
3. Upload the PDF file.
4. Extract the password hash.
5. Copy the complete hash beginning with `$pdf$`.
6. Open the Networkwalks Password Cracker.
7. Paste the extracted hash.
8. Start the password-cracking process.
9. Wait for the password to be recovered.
10. Use the recovered password to open the PDF file.

## Key Concepts

### Password Hashing

Password hashing converts a password into a fixed-format value called a hash.

### Encryption

Encryption transforms readable information into an unreadable format using an encryption key.

### Dictionary Attack

A dictionary attack attempts to recover a password by testing different words and password combinations against a stored hash.

### Password Strength

Password strength depends on factors such as length, complexity, and unpredictability.

## Learning Outcomes

Through this project, I gained practical experience in:

- Extracting password hashes from protected PDF files.
- Using John the Ripper for password recovery.
- Using Johnny GUI to perform password-cracking attacks.
- Using browser-based password-cracking tools.
- Understanding dictionary attacks.
- Identifying security risks associated with weak passwords.
- Applying cybersecurity concepts in a practical environment.

## Repository Structure

```text
password-cracking-project/
│
├── README.md
│
├── Module-1-JTR/
│   └── screenshots/
│
└── Module-2-Networkwalks/
    └── screenshots/
