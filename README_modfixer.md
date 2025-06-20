# 🧹 FixMods – Secure Sims 4 Mod Folder Cleaner

A Python script that safely backs up, cleans, and secures your Sims 4 Mods folder.  
No installer needed. No sketchy mod manager. Just clean, simple automation.

---

## ✨ Features
- 🔒 **Secure by default** – disables risky behavior
- 📁 **Creates a full backup** before changes
- 🧼 **Cleans up duplicates, bad file types, and broken mods**
- ⚠️ **Detects dangerous scripts like .bat files**
- 📄 **Exports a mod inventory** to CSV and JSON
- 🧩 **Version checks against mod list online**
- 🗃️ **Moves junk to quarantine folder**
- 🧹 **Cleans LastException + Cache files**

---

## 🖥️ How to Use

### 1. Place script here:
```bash
~/Documents/mod manager/modfix.py
```

### 2. Run with alias:
```bash
fixmods
```

This automatically:
- Activates your virtual environment
- Runs the script with all security features on

### 💡 Sample alias (in `.zshrc` or `.bash_profile`):

```bash
alias fixmods="source ~/sims4env/bin/activate && python ~/Documents/mod\ manager/modfix.py"
```

---

## 📂 Output
- Backup: `~/Desktop/ModsBackup-YYYYMMDD.zip`
- Quarantine: `~/Documents/mod manager/quarantine/`
- Mod Inventory: `~/Documents/mod manager/mod info/ModsInventory.csv`

---

## ⚠️ Security Notice

> ⚠️ This script is **not hardened for untrusted mod downloads**.  
> Do **not** run random files or sketchy .zip content.  
> Future versions will include sandboxing and checksum verification.

---

## 💬 Support & Updates

📦 GitHub: [github.com/MissyAI87/modfixer](https://github.com/MissyAI87/modfixer)  
☕ Patreon: [Support & Download on Patreon](https://www.patreon.com/posts/fixmods-script-4-131923374?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=postshare_creator&utm_content=join_link)

---

© MissyAI 2025 — Open-source, secure, and community-friendly
