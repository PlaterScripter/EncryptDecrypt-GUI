# 🛡️ E-D Tool (Encryptor / Decryptor)

**E-D Tool** is a powerful offline file encryption and decryption utility built with 💙 Python and converted to a standalone `.exe`.  
No Python required. No internet needed. No ads. Just clean encryption and decryption.  

Whether you're protecting files for trading, archiving sensitive data, or just want peace of mind — this tool is made to be fast, lightweight, and secure.

---

## 🔐 Features

- AES-256 encryption (military-grade)
- Drag-n-Drop coming soon!
- RAM limiter: uses all RAM except 1 GB for safety
- Completely offline
- No bloat, no installer required
- VirusTotal-safe by nature (see explanation below)
- Free for everyone (Apache 2.0 licensed)

---

## ⚠️ VirusTotal Notice

Some antivirus engines might flag this tool as **malicious or unsafe**, especially because it:
- Is an `.exe` generated from Python (often misflagged)
- Handles encryption (some flag any crypto tool as "suspicious")
- Is packed into one file (via `PyInstaller`)

🔗 [VirusTotal Scan Link](https://www.virustotal.com/gui/file/6a4aba290b06b2e8bcb2e381cae9972aa78f708c9c907db8fccb87afc7ba8fc7)

📌 **This is a false positive.**  
The tool contains **no malicious code, backdoors, or networking**. You’re welcome to inspect the source code.

---

## 📦 Download

Check the [Releases](https://github.com/PlaterScripter/EncryptDecrypt-GUI/releases) section for the latest `.exe` builds.

---

## 🧠 How to Use

### 🔒 Encrypt
1. Open the tool
2. Choose a file
3. Select where to save the encrypted file
4. Save the key (you’ll need it for decryption)

### 🔓 Decrypt
1. Open the tool
2. Select the encrypted file
3. Paste the saved key
4. Choose output file location

---

## 🧾 License

This project is licensed under the **Apache License 2.0** — see the [`LICENSE`](./LICENSE) file for details.

---

## 💬 Credits

Created with ❤️ by [PlaterScripter](https://github.com/PlaterScripter)
