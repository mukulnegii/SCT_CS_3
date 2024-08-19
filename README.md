# SCT_CS_3
This repository contains a collection of projects developed as part of the Cyber Security Internship Program at SkillCraft Technology. The projects demonstrate various techniques and applications in the field of cybersecurity, including encryption, image processing, and password security.

# Task 1:🚀Caesar Cipher Encryption and Decryption🚀

Welcome to the Caesar Cipher Encryption and Decryption project! This Python program allows users to encrypt and decrypt text using the classic Caesar Cipher algorithm.

## Table of Contents
1)Introduction
2)Features
3)How It Works

## Introduction
The Caesar Cipher is one of the simplest and most widely known encryption techniques. This project demonstrates a Python implementation that enables users to encrypt and decrypt messages by shifting the letters by a specified number of positions in the alphabet.

## Features
Encryption: Convert plain text into encrypted text using a shift value.
Decryption: Convert encrypted text back to plain text using the same shift value.
File Handling: Read input messages from a file and write the output to another file.

## How It Works

### User Interface:
The user is prompted to choose between encryption and decryption.
The user inputs the key value (shift value).
The program processes the message based on the user's choice and key value.

### Encryption:

Shifts each letter in the message by the key value.
Handles wrap-around for letters at the end of the alphabet.

### Decryption:

Shifts each letter in the encrypted message back by the key value to restore the original text.

# 🔒Task 2: Pixel Manipulation for Image Encryption🔒

## Overview
This project provides a simple image encryption tool using pixel manipulation. Users can encrypt and decrypt images using two methods: pixel swapping and mathematical operations.

## Features
- **Image Encryption**: Encrypt images by altering pixel values.
- **Image Decryption**: Decrypt images back to their original state.
- **User-Friendly Interface**: Command-line interface for selecting images and applying encryption/decryption.

  ## How It Works.
### Encryption Methods
1. **Pixel Swapping**:
    - Pixels are swapped based on a pseudo-random sequence generated using the provided key.
    - The sequence ensures that the same key will always result in the same encrypted image.
2. **Mathematical Operations**:
    - Each pixel value is transformed using a mathematical operation and the provided key.

### Decryption Methods
1. **Pixel Swapping**:
    - The pixel swapping operation is reversed using the same key to restore the original image.
2. **Mathematical Operations**:
    - The mathematical transformation is reversed to restore the original pixel values.


# 🔍 Task 3: Password Complexity Checker Tool 🔍 
## Overview
This repository contains a Python-based tool designed to assess the strength of passwords. The tool evaluates passwords against several key criteria to determine their complexity and provide a strength rating.

## Features
- **Length Check**: Ensures the password is at least 8 characters long.
- **Uppercase Check**: Verifies the presence of at least one uppercase letter.
- **Lowercase Check**: Verifies the presence of at least one lowercase letter.
- **Number Check**: Verifies the presence of at least one digit.
- **Special Character Check**: Verifies the presence of at least one special character (e.g., !, @, #, $, etc.).

## Password Strength Classification
- **Strong Password**: Meets all five criteria.
- **Good Password**: Meets three or four of the criteria.
- **Weak Password**: Meets less than three criteria.

## Usage
### To use the password complexity checker tool:

1. Clone the repository to your local machine.
2. Run the Python script password_complexity_checker.py.
3. Enter a password when prompted.
4. The tool will output the strength of the password as "Strong Password," "Good Password," or "Weak Password."

## Contributions

### Feel free to contribute to this project by:

- Improving the criteria for password strength.
- Adding more features to enhance the tool.
- Optimizing the code for better performance.
