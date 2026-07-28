# File Organizer

## Overview
A Python automation script that automatically organizes files into folders based on their file extensions.

## Features
- Organizes videos, images, audio, and documents.
- Creates folders automatically if they do not exist.
- Ignores existing folders.
- Supports multiple file extensions.
- Handles uppercase and lowercase file extensions.

## Technologies Used
- Python
- os module
- shutil module

## Supported File Types

### Videos
- .mp4
- .mkv
- .avi
- .mov

### Images
- .jpg
- .jpeg
- .png

### Audio
- .mp3
- .wav

### Documents
- .pdf
- .docx
- .txt

## How to Run

1. Change the `folder_path` variable to the folder you want to organize.
2. Run:

```bash
python organizer.py
```

The script will automatically organize supported files into their respective folders.