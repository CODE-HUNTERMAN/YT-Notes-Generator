# 🎥 YT-Notes Generator — Convert YouTube Lectures into Smart PDF Notes Automatically

YT-Notes Generator is a powerful Python tool that converts YouTube videos and playlists into organized, timestamped PDF notes by automatically extracting important frames. It eliminates the need for manual screenshots and helps students and learners quickly generate revision-ready visual notes from lectures.

---

## ✨ Features

- 📥 Download videos directly from YouTube
- 📚 Supports both single videos and full playlists
- 🧠 Intelligent frame detection using Structural Similarity Index (SSIM)
- 🖼️ Extracts only important frames and removes duplicates
- 🕒 Automatically adds timestamps to each frame
- 📄 Generates clean, high-quality PDF notes
- ⚡ Fully automated process
- 🎯 Perfect for lecture notes and exam preparation

---

## 🚀 How It Works

YouTube Video / Playlist → Download Video → Extract Important Frames → Remove Similar Frames → Add Timestamp → Generate PDF Notes

---

## 🛠️ Tech Stack

- Python
- OpenCV
- yt-dlp
- FPDF
- Pillow (PIL)
- scikit-image

---

## 📦 Installation

Install all required dependencies using:

```bash
pip install opencv-python-headless
pip install scikit-image
pip install fpdf
pip install yt-dlp
pip install pillow


main("#") # Replace with the URL of the video or playlist
