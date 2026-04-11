NAME: Kennedy Ndung'u Mbugua 
STUDENT ID: INF/002/2022
DEPLOYMENT URL: https://excelskennedy2.github.io/-inf424-multimedia-hub/
## 🎬 EduStream Multimedia Learning Hub
A web-based multimedia learning platform built for INF 424: Multimedia Programming, demonstrating modern browser-based media processing using HTML5, JavaScript APIs, CSS animations, and component-based architecture.

## 📌 Project Overview

EduStream is an interactive multimedia application that simulates a modern learning environment where users can engage with:

*🎧 Custom Audio Player (HTML5 + Web Audio API)
*🎥 Custom Video Player (HTML5 Video API + Event Handling)
*🎨 CSS Animation & SVG Creative Lab
*📷 Live Camera Filter (MediaDevices + Canvas API)
*🖼️ Dynamic Media Gallery (Component-based rendering)

The project demonstrates how browsers handle temporal and non-temporal media, event-driven programming, and real-time media processing.

## 🧠 Key Concepts Demonstrated
*Temporal vs Non-temporal media
*Event-driven programming (play, pause, waiting, ended, etc.)
*Web Audio API signal processing
*Media streaming & buffering
*Canvas pixel manipulation
*SVG animation techniques
*Component-based UI architecture (vanilla JS)
*Responsive grid layouts

## 📁 Project Structure
EduStream/
│
├── index.html              # Home page
├── audio-player.html       # Custom audio player + tone generator
├── video-player.html       # Custom video player
├── animations.html         # CSS & SVG animation lab + camera filter
├── gallery.html            # Dynamic media gallery
├── style.css               # Shared stylesheet
│
├── assets/
│   ├── images/
│   ├── audio/
│   └── video/
│
└── README.md
## 🎧 Audio Player Features
Custom play/pause controls (no default browser UI)
Real-time progress bar with seeking
Volume control + mute toggle
Keyboard shortcuts:
Space → Play/Pause
M → Mute
Arrow Left/Right → Seek ±10s
Web Audio API tone generator:
OscillatorNode (sine, square, triangle, sawtooth)
GainNode with smooth envelope
Musical frequency buttons (C4, A4, etc.)
## 🎥 Video Player Features
Custom controls (no default controls attribute)
Poster image support
Playback speed control (0.75x – 2x)
Fullscreen mode
Event-driven status system:
play, playing, pause, waiting, ended, error
Accessible transcript panel
## 🎨 Animations Lab (CSS + SVG)
Infinite CSS loading spinner using @keyframes
Hover card transitions (scale + color effects)
SVG path drawing animation using:
stroke-dasharray
stroke-dashoffset
Animated SVG elements (opacity, transforms)
## 📷 Camera Filter (Live Processing)
Start camera using getUserMedia()
Live video stream display
Error handling:
NotAllowedError
NotFoundError
NotReadableError
Frame capture using Canvas API

Greyscale filter using luminance formula:
```
0.299R + 0.587G + 0.114B
```

Download processed image as PNG
🖼️ Media Gallery (Component Architecture)
Data-driven rendering using mediaLibrary[]

Pure function:

renderMediaCard(item)
Array.map() based rendering
Live search filtering
Event delegation for performance optimization
Media types:
Video
Audio
Image
## ⚙️ Technologies Used
*HTML5
*CSS3
*JavaScript (ES6+)
*Web Audio API
*MediaDevices API
*Canvas API
*SVG
*Bootstrap (optional UI components)

## 🚀 How to Run the Project
Option 1: Live Server (Recommended)
Open project in VS Code
Install Live Server extension
Right-click index.html
Click "Open with Live Server"
Option 2: Direct Browser
Open index.html in any modern browser

## 🌐 Deployment


https://excelskennedy2.github.io/-inf424-multimedia-hub/


## 📚 Academic Context

This project was developed for:

INF 424 – Multimedia Programming
BSc Informatics, Year 4

It demonstrates applied knowledge of:

Multimedia system architecture
Event-driven programming
Media encoding and processing
Real-time rendering systems
Component-based frontend design
## 👨‍💻 Author

Kennedy Ndung'u Mbugua
School of Information, Communication and Media Studies
BSc Informatics