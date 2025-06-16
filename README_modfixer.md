# ModFixer for Sims 4

**ModFixer** is a Python tool that automatically cleans, backs up, and organizes your Sims 4 Mods folder.

---

## 💡 Features

- 🔄 Creates a full backup before making changes
- 🧹 Removes duplicate and broken mod files
- 🗂️ (Optional) Organizes mods by type into subfolders
- 🚮 Deletes `.DS_Store`, `thumbs.db`, and other garbage files
- 💬 CLI + GUI versions available
- ✅ Safe mode prevents unwanted deletions

---

## 🖥️ How to Run

Make sure your virtual environment is activated:

```bash
source ~/sims4env/bin/activate
fixmods
```

If that doesn't work, try running the script directly:

```bash
python ~/Documents/sims4_mod_fixer.py
```

Make sure your alias is properly set up in your shell profile (e.g., `.bashrc`, `.zshrc`, or `.bash_profile`).

---

## 📁 Folder Setup

- **Mods folder path:**  
  `~/Documents/Electronic Arts/The Sims 4/Mods`

- **Backups saved to:**  
  `~/Documents/Sims4Backups/ModFixer/YYYY-MM-DD/`

- **Quarantined files moved to:**  
  `~/Documents/Sims4Quarantine/`

These locations can be changed in the script if needed.

---

## 🔧 Requirements

- Python 3.10+
- No external packages needed (uses built-in modules like `os`, `shutil`, `datetime`, and `argparse`)
- (Optional) Virtual environment: `~/sims4env`

To set up your environment (if not already done):

```bash
python3 -m venv ~/sims4env
source ~/sims4env/bin/activate
```

---

## 📋 Future Plans

- Add mod version checker using a central JSON file
- Auto-reorganize mods by category or file type
- Export mod list to CSV
- Add GUI mode using Gradio or PySimpleGUI
- Trash bin system for deleted mods
- Read and process MCCC crash logs
- Add dry-run mode for safe previews

---

## 🙋 Author Notes

This project was built as part of a hands-on learning journey into Python scripting, modular design, and local AI integration. It’s part of a larger goal to build self-maintaining, AI-assisted tools for gamers and developers.

---

## 📝 License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute this software.  
There is no warranty or liability for issues that may arise from use.