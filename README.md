# 🎵 Video to Audio Extractor

A simple Python desktop app that lets you select one or multiple video files and extract their audio as `.mp3`.  
Useful for language practice, podcasts, or just saving the audio from videos.  

Built with **Tkinter** (for GUI) and **MoviePy** (for video/audio handling).  
Can be exported as a standalone `.exe` with **PyInstaller**.

---

## ✨ Features
- Select one or multiple video files.
- Extract audio in `.mp3`, `.wav` and `.ogg` format.
- Progress bar and status messages during conversion.
- Error handling (e.g., videos without audio).
- Works on Windows, Mac, and Linux (Python required).
- Can be bundled into an `.exe` for easy use.

---

## 🖥️ Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/video-to-audio-extractor.git
   cd video-to-audio-extractor
   ```

## 🚀 Usage

Run the script:

```bash
python extractor.py
```

- Click "Select and Convert"
- Choose one or more video files (.mp4, .mkv, .avi, .mov, .flv)
- Choose an output folder
- The audio will be extracted as .mp3

## 📦 Export as .exe (Optional)

To create a standalone executable:

```bash
pip install pyinstaller
pyinstaller --onefile --noconsole extractor.py
```
- The .exe will be available inside the dist/ folder.

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Feel free to open issues or submit pull requests.
