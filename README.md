# 📂 Downloads Organiser (Python)

A Python script designed to help keep your Downloads folder organised by sorting files into category folders based on file type. This project showcases file system automation and practical scripting skills to improve productivity by reducing clutter in a common directory.

---

## ✨ Features

* Automatically scans the Downloads directory
* Sorts files into folders such as Images, Documents, Videos, and Archives
* Handles multiple file extensions
* Easy to customise file categories and destination paths

---

## 🛠 Requirements

* Python 3.x
* No external libraries required (uses Python’s built‑in `os` and `shutil` modules)

---

## 🚀 How to Start

1. Clone the repository:

```bash
git clone https://github.com/kashbyte/DownloadsOrganiser.git
```

2. Navigate into the project folder:

```bash
cd DownloadsOrganiser
```

3. Open `main.py` and update the `DOWNLOADS_PATH` variable to match your system’s Downloads folder
4. Run the script:

```bash
python main.py
```

---

## ▶️ How to Use

1. Update the path in the script to point to your Downloads folder
2. Define or edit file type categories and destination folders
3. Run the script in a terminal or command prompt
4. The script will move files into organised folders automatically

For example, image files like `.jpg` and `.png` might be moved to an `Images/` folder while `.pdf`, `.docx` files go to `Documents/`.

---

## 📚 What This Project Teaches

* Interacting with the file system using Python’s `os` module
* Moving and organising files programmatically with `shutil`
* Writing automation scripts that improve workflow
* Customising logic for different file types

---

## 💡 Possible Improvements

* Add a graphical user interface for easier configuration
* Include a real time watcher that automatically organises new files
* Add logging or dry‑run options
* Package as a desktop utility with executable builds

---

## 🧠 Notes

This script reflects real world problem solving by automating a repetitive task. It helped me strengthen my understanding of file system manipulation in Python and practical scripting workflows that can save time in day‑to‑day computing.
