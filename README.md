# Dynamic JavaScript File Runner for Node.js

This repository contains a small Node.js utility to automatically detect and run the most recently modified `.js` file in your project, regardless of whether it's in the root folder or any subdirectory.

## **Features:**
- **Automatic File Detection**: Detects the most recently modified `.js` file in your project, including subdirectories.
- **No Need to Manually Navigate**: You don’t have to manually select the file to run; the script will do it for you.
- **Works Across Multiple Subdirectories**: The script recursively scans all directories in your project.

---

## **How It Works**

The script recursively searches through the project folder and all subdirectories for `.js` files. It sorts them based on the last modified timestamp and runs the most recent file.

---

## **Installation & Setup**

### 1. Clone this repository to your local machine:
```bash
git clone <https://github.com/AyushSingh-Tomar/Automatic-Recent-JS-file-Executer>
cd <Automatic-Recent-JS-file-Executer>

