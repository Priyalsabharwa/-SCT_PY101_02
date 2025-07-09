# 🔐 SkillCraft Task 02 – Image Encryption Tool
**Project ID:** SCT_PY101_02  
**Created for:** SkillCraft Python Program (PY101)  
**Project Type:** Command-line image encryption/decryption using pixel manipulation

---

## 📌 Overview

This is a simple yet powerful **image encryption and decryption tool** built with **Python and Pillow (PIL)**.  
The project applies a Caesar-style shift to the RGB channels of each pixel, making the image unreadable until decrypted.

It was created as part of **SkillCraft PY101 Task 02 (`SCT_PY101_02`)** to explore:

- File handling
- Image processing
- Pixel-level manipulation
- CLI-based tool development

---

## 🛠 Features

- ✅ Encrypt and decrypt `.png` images using a numeric key
- 🔁 Supports both RGB and RGBA image formats
- 🔐 Uses pixel-wise Caesar cipher logic
- 📂 Saves encrypted and decrypted images to the same folder
- 🧠 Simple CLI interaction — no GUI required
- 💡 Includes error handling for common mistakes

---

## 📷 How It Works

### 1. You input:
- `encrypt` or `decrypt`
- A **numeric key**
- A `.png` image filename (e.g., `sample_image.png`)

### 2. The tool:
- Reads each pixel
- Applies the Caesar shift (on R, G, B)
- Keeps Alpha (`A`) channel unchanged
- Saves output as:
  - `encrypted_image.png`
  - `decrypted_image.png`

---

## 🚀 How to Run

### ▶️ Prerequisites

Install Pillow:
```bash
pip install pillow

