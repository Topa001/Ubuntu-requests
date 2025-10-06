# Ubuntu-requests

# 🌍 Ubuntu_Requests

A mindful Python program for safely fetching multiple images from the web — built around Ubuntu principles of **Community**, **Respect**, **Sharing**, and **Practicality**.

---

## 🧠 Overview
This program allows users to download one or more images from valid URLs while:
- Respecting web resources
- Avoiding duplicates
- Checking for safe content types
- Organizing all images neatly inside a `Fetched_Images` folder

It’s a demonstration of ethical and practical software design in Python using the `requests` library.

---

## ⚙️ Features
✅ Fetch multiple image URLs in a single run  
✅ Automatically create the `Fetched_Images` directory  
✅ Verify each file is a valid image via HTTP headers  
✅ Gracefully handle network and timeout errors  
✅ Prevent duplicate downloads using hash comparison  
✅ Follow Ubuntu principles for respectful coding practices  

---

## 🚀 Usage

### 1️⃣ Requirements
Install Python 3 and ensure the `requests` library is installed:

```bash
pip install requests
