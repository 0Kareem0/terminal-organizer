# Terminal Organizer 🗂️

A Python script that organizes files in any directory by **file type** — like a mini Shazam for your Downloads folder 😎  
Includes **dry-run preview**, **undo**, and supports folders like `~/Downloads`.

---

## 🚀 Features
- ✅ Organize by file type (Images, Videos, Archives, etc.)
- ✅ Dry run mode (`--dry-run`)
- ✅ Undo mode (`--undo`)
- ✅ Supports any path, safe logging

---

## 📦 How to Use

```bash
# Dry run (preview only)
python3 terminal_organizer.py --dry-run

# Organize current directory
python3 terminal_organizer.py

# Organize Downloads folder
python3 terminal_organizer.py ~/Downloads

# Undo last organization
python3 terminal_organizer.py --undo
