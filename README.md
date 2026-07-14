<div align="center">
<img src="https://img.shields.io/badge/JAVASCRIPT-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/REST_API-005571?style=for-the-badge&logo=json&logoColor=white" alt="REST API" />
  <br/>
  <br/>

  <h1>⚡ Pulse Music</h1>
  <p><b>A dynamic, state-driven music streaming interface and custom web audio player.</b></p>
  
  <a href="https://pulse-awazii.netlify.app/"><strong>🛑 View Live Demo</strong></a>
</div>

<br/>

> **Pulse** is a frontend-focused web application designed to deliver a seamless, high-fidelity music browsing and playback experience. It focuses heavily on persistent global state management and custom media controls.

---

## 📸 Interface Preview

<img width="1907" height="917" alt="Screenshot 2026-07-14 084039" src="https://github.com/user-attachments/assets/d892ba6b-a5af-4e5d-9753-1d4472ddaae7" />


---

## 🧠 Frontend Architecture & Logic

Building a music player requires complex synchronization between the browser's native APIs and the React component tree. 

### 1. Persistent Global Audio State
The biggest challenge in a media application is preventing audio from resetting during navigation. Pulse utilizes a global state management architecture (Redux/Context) to separate the audio playback logic from the UI rendering. This ensures tracks continue playing seamlessly while the user browses different views, playlists, or artist pages.

### 2. Custom Media Engine
Bypassed the limitations of standard HTML5 `<audio>` controls by engineering a completely custom playback interface. This includes building custom logic for progress bars, volume sliders, track skipping, and real-time timestamp formatting, fully synchronized with the browser's media API.

### 3. Responsive Grid Layouts & Theming
Engineered a fluid, responsive UI using Tailwind CSS grid and flexbox utilities to manage a complex layout (fixed sidebars, scrollable main content, and a persistent bottom player). The UI is designed to feel like a native desktop application rather than a static webpage.

---

## 🚀 Core Features

- **Custom Playback Controls:** Play, pause, skip, seek, and volume adjustments built entirely from scratch.
- **Dynamic Track Tracking:** Real-time progress bar synchronization.
- **Fluid Layout:** Native-feeling application structure that perfectly scales down to mobile viewports.
- **State Preservation:** Uninterrupted audio playback across route changes.

---
