# 🔎 Fast File Finder - User Guide

Find files on your PC **10-100x faster** than Windows Search.

---

## 📥 STEP-BY-STEP GUIDE

### Step 1: Download

Download the file: **`DateiFinder.exe`**

### Step 2: Run the Program

1. **Double-click** on `DateiFinder.exe`
2. A black window (terminal) will open
3. Wait 10-30 seconds while it creates an index of your files

### Step 3: Start Searching

The program will show you this screen:

```
============================================================
🔎 FAST FILE FINDER
============================================================

Commands:
  <name>     - Search by filename
  ext:<type> - Search by file type (e.g. ext:pdf)
  rebuild    - Rebuild index
  quit       - Exit

Search: 
```

Now you can start searching!

---

## 🔍 HOW TO USE

### Search for a File by Name

Just type the filename (or part of it):

```
Search: invoice
Search: vacation
Search: report.pdf
```

**Example:**
```
Search: photo

🔍 5 results:

1. photo_2024.jpg
   📁 C:\Users\John\Pictures\photo_2024.jpg
   📊 2.3 MB | 🕒 2024-08-15 14:23

2. vacation_photo.jpg
   📁 C:\Users\John\Desktop\vacation_photo.jpg
   📊 1.8 MB | 🕒 2024-07-22 10:15
```

### Search by File Type

Use `ext:` followed by the file extension:

```
Search: ext:pdf       (find all PDFs)
Search: ext:jpg       (find all images)
Search: ext:docx      (find all Word documents)
Search: ext:xlsx      (find all Excel files)
Search: ext:mp4       (find all videos)
```

**Example:**
```
Search: ext:pdf

🔍 12 results:

1. invoice_2024.pdf
   📁 C:\Users\John\Documents\invoice_2024.pdf
   📊 156.2 KB | 🕒 2024-09-12 09:45

2. manual.pdf
   📁 C:\Users\John\Downloads\manual.pdf
   📊 3.8 MB | 🕒 2024-08-20 16:30
```

### Update the Index

If you added new files, rebuild the index:

```
Search: rebuild
```

Wait 10-30 seconds while it scans your files again.

### Exit the Program

```
Search: quit
```

Or press `Ctrl+C`

---

## ❓ COMMON QUESTIONS

**Q: Where does it search?**  
A: Desktop, Documents, Downloads, Pictures, Videos folders.

**Q: Does it search inside files?**  
A: No, only filenames.

**Q: Do I need internet?**  
A: No, works completely offline.

**Q: Is it safe?**  
A: Yes, it only reads filenames. Nothing is uploaded or shared.

**Q: Why is the first search slow?**  
A: It needs to create an index first. After that, searches are instant.

**Q: Can I search subfolders?**  
A: Yes, it automatically searches all subfolders.

**Q: What if I don't see my file?**  
A: Type `rebuild` to update the index with new files.

---

## 📝 QUICK COMMAND REFERENCE

| Command | What it does | Example |
|---------|--------------|---------|
| `<name>` | Search by filename | `invoice` |
| `ext:<type>` | Search by file type | `ext:pdf` |
| `rebuild` | Rebuild file index | `rebuild` |
| `quit` | Exit program | `quit` |

---

## 💡 TIPS & TRICKS

### Tip 1: Partial Searches
You don't need to type the full filename:
- `photo` will find `photo_2024.jpg`, `my_photo.png`, `vacation_photo.jpg`

### Tip 2: Case Doesn't Matter
- `INVOICE` = `invoice` = `InVoIcE`

### Tip 3: Find All Files of a Type
- `ext:jpg` - All photos
- `ext:pdf` - All PDFs
- `ext:docx` - All Word documents
- `ext:mp3` - All music files

### Tip 4: Keep Index Updated
Run `rebuild` once a week or after adding many new files.

---

## 🚀 WHAT MAKES IT FAST?

Unlike Windows Search, this tool:
1. Creates a complete index of your files
2. Saves the index to disk
3. Searches the index (not your hard drive)
4. Results appear instantly

**Windows Search** needs to scan your hard drive every time.  
**Fast File Finder** searches from memory → 100x faster!

---

## 📧 NEED HELP?

If something doesn't work:
1. Make sure `DateiFinder.exe` is in a folder you can write to
2. Run the program as Administrator
3. Type `rebuild` to recreate the index
4. Check that your folders exist (Desktop, Documents, etc.)

---

Made with ❤️ for finding files fast!
