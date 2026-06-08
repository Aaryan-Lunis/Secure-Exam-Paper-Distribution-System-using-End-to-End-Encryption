# Secure Exam Paper Distribution System

## Overview

This project was developed as an exploration of practical cybersecurity concepts in web applications. The goal was to design a secure method for distributing examination papers while reducing the risk of unauthorized access, tampering, or leaks.

The system uses a hybrid encryption approach that combines AES-256 and RSA-2048 to protect sensitive exam content before it is shared with authorized users.

## Problem Statement

Traditional digital distribution methods often rely on simple file sharing mechanisms that can expose examination papers to unauthorized access. This project demonstrates how modern cryptographic techniques can be applied to improve the security of document distribution.

## Features

- AES-256 encryption for securing examination papers
- RSA-2048 public-key encryption for key exchange
- Browser-based implementation using the Web Crypto API
- Role-based workflow for teachers and students
- Secure encryption and decryption process
- Simple and lightweight frontend built with vanilla JavaScript

## Technologies Used

- HTML
- CSS
- JavaScript
- Web Crypto API

## Project Structure

```text
.
├── index.html
├── teacher.html
├── student.html
├── crypto.js
├── store.js
├── ui.js
└── style.css
How It Works
A teacher uploads or prepares an examination paper.
The paper is encrypted using AES-256.
The AES key is protected using RSA-2048 encryption.
Authorized users receive the encrypted content and encrypted key.
The document can only be decrypted by users with the appropriate credentials and keys.
Learning Objectives

This project was created to gain practical experience with:

Symmetric and asymmetric encryption
Hybrid cryptographic systems
Secure key management concepts
Browser-based cryptography
Web application security fundamentals
Disclaimer
