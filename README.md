# Kryn
🚀 Kryn – Hash Cracker Premium Edition is a powerful, GUI-based hash cracking tool built with Python and Tkinter, designed for ethical hackers, cybersecurity researchers, and digital forensics enthusiasts. 💻✨

<img width="1920" height="1172" alt="Kryn" src="https://github.com/user-attachments/assets/8fdccc6d-da07-4d43-9088-c2f222cc5d51" />


# 🔐 Kryn - Hash Cracker Premium Edition

**Kryn** is a modern **GUI-based hash cracking tool** built using **Python (Tkinter)**.  
It combines a **sleek metallic interface** with advanced **hash detection** and **multi-mode attack support** — including **Wordlist**, **Numeric**, and **Crunch Pattern Generator** modes.

---

## ✨ Features

- 🎨 **Premium Metallic GUI** — Gold-accented dark theme with terminal-style typography.  
- 🧠 **Smart Hash Detection** — Automatically identifies MD5, SHA1, SHA256, and SHA512.  
- ⚙️ **Attack Modes**
  - **Wordlist Attack** – Uses dictionary-based password lists.
  - **Numeric Attack** – Brute-force through numerical ranges.
  - **Crunch Mode** – Integrates with the `crunch` utility for dynamic pattern-based cracking.
- 🔡 **Pattern Generator Support**
  - `@` → Lowercase letters (a-z)  
  - `,` → Uppercase letters (A-Z)  
  - `%` → Numbers (0–9)  
  - `^` → Symbols (!@#$%^&*()_+...)  
- 💾 **System Log Export** — Save the output log as `.log` or `.txt` files.
- 📋 **Clipboard Copy** — Copy cracked passwords instantly.
- 🖥️ **Real-Time Console Output** — Color-coded terminal-style feedback.
- 🔍 **Auto Algorithm Validation** — Warns if selected algorithm doesn’t match hash format.

---

## 🧰 Supported Hash Algorithms

| Algorithm | Hash Length | Example |
|------------|--------------|----------|
| MD5        | 32 chars     | e10adc3949ba59abbe56e057f20f883e |
| SHA1       | 40 chars     | 40bd001563085fc35165329ea1ff5c5ecbdbbeef |
| SHA256     | 64 chars     | 9c56cc51b374c3ba4a4c9862b41c6c7f7b8d7cfc39e43cf62f4b3b8db5a5b9c1 |
| SHA512     | 128 chars    | e7cf3ef4f17c3999a94f2c6f612e8a888e5b56a8039c75e0... |

---

## 🧩 Pattern Mode Reference

Use Crunch-style pattern generation with flexible syntax:

| Symbol | Description | Example |
|---------|-------------|----------|
| `@` | Lowercase (a–z) | `pass@%@%` → passa1a1 |
| `,` | Uppercase (A–Z) | `ADMIN%,` → ADMINA1 |
| `%` | Numbers (0-9) | `%2024` → 12024 |
| `^` | Symbols (!@#$) | `admin%^` → admin1! |

**Examples:**
```
@@@@%%%%   → abcd1234
admin%^^   → admin1!?
%%%%@%%%%  → 2024@2024
```

---

## ⚙️ Installation & Usage

### 🧱 Requirements
- Python 3.8 or higher  
- Tkinter (comes pre-installed with Python on most systems)  
- Crunch (optional, required for pattern and generator mode)

### 💿 Install Crunch
#### On Debian / Ubuntu / Kali:
```bash
sudo apt install crunch
```

#### On Termux:
```bash
pkg install crunch
```

#### On Windows:
Download Crunch from the official repository or use via WSL.

---

### ▶️ Run Kryn
```bash
python3 Kryn.py
```

Once launched, you’ll see the **main cracking interface**:
1. Enter your **target hash**.
2. Select the **algorithm** (MD5/SHA1/SHA256/SHA512).
3. Choose **attack mode** — Wordlist / Numeric / Crunch.
4. Set wordlist or pattern as needed.
5. Click **START** and monitor progress in the live console.

---

## 💡 Example Workflow

1. **Detect and Validate Hash**
   - Paste your hash — Kryn will detect its type automatically.  
   - If mismatch occurs, it offers to auto-switch the algorithm.

2. **Wordlist Attack**
   - Load any `.txt` file with potential passwords.
   - Kryn will iterate and compute hashes until a match is found.

3. **Pattern Mode**
   - Use symbols like `@%@%` to generate patterns through Crunch.  
   - Easily switch between **custom** and **preset** templates.

4. **Results**
   - If a password is found, it’s displayed, copied to clipboard, and saved in logs.

---

## 📸 (Optional) Preview Ideas
> Add screenshots here when publishing

- **Main Cracker UI** (Dark metallic design)  
- **Pattern Mode Tab**  
- **Cracking Log Output**

---

## 🧑‍💻 Author

**Created by:** [Tricks2erCl0wn](https://github.com/)  
💻 Python Developer | 🔐 Security Enthusiast  

Follow for more open-source cybersecurity tools and GUI applications.

---

## ⚠️ Legal Disclaimer

This project is intended **for educational and ethical testing purposes only**.  
Using it for unauthorized access, credential cracking, or illegal activities is **strictly prohibited**.  
The author assumes **no responsibility** for misuse or damage caused by this software.

---

## 🏷️ Tags

`hash-cracker` · `tkinter` · `python` · `cybersecurity` · `crunch` · `md5` · `sha256` · `gui-tool` · `ethical-hacking`

---

## 📜 License

```
MIT License

Copyright (c) 2025 Tricks2erCl0wn

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```
