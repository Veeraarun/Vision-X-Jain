# Vision-X — VR Therapy Prototype 🥽

A browser-based **Virtual Reality therapy prototype** built with **A-Frame and JavaScript**. The project explores immersive therapy scenarios for different phobias through interactive 360° video experiences.

## ✨ Features

- Browser-based VR scene using A-Frame.
- Interactive therapy scenario selection.
- Three prototype scenarios:
  - Fear of Height
  - Fear of Ocean
  - Fear of Driving
- 360°/immersive video playback.
- Background lobby ambience.
- Start and return controls.
- In-scene cursor interaction.
- Basic therapy status message.
- Prototype heart-rate/stress information panel.
- Mobile gyroscope permission handling.

## 🧠 How It Works

The application starts in a virtual lobby scene. The user selects a therapy scenario, after which the lobby background is replaced by the corresponding therapy video.

When the therapy video ends, the application returns to the lobby automatically. Users can also exit a session manually using the **Go Back** control.

```text
Virtual Lobby
     │
     ├── Fear of Height
     ├── Fear of Ocean
     └── Fear of Driving
              │
              ▼
      Immersive Video Session
              │
       ┌──────┴──────┐
       ▼             ▼
   Video ends     Go Back
       │             │
       └──────┬──────┘
              ▼
        Virtual Lobby
```

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript
- A-Frame 1.4.2
- WebXR/WebVR browser capabilities
- HTML5 Audio and Video APIs
- Device Motion API

## 📁 Project Structure

```text
Vision-X-Jain/
├── index.html       # A-Frame VR scene
├── script.js        # Therapy controls and interactions
├── style.css        # UI styling
├── assets/
│   └── models/
│       ├── videos/  # Therapy video assets
│       └── ...      # Audio and environment assets
└── README.md
```

## 🚀 Run Locally

Because the project loads local media assets, serving it through a local HTTP server is recommended.

```bash
git clone https://github.com/Veeraarun/Vision-X-Jain.git
cd Vision-X-Jain
```

Then start a local static server. For example, with VS Code Live Server, open `index.html` through the server URL.

## 📱 Device Notes

- Desktop browsers can use mouse/cursor interaction.
- Mobile devices may support device-motion/gyroscope interaction depending on browser permissions.
- Browser autoplay policies may require a user interaction before audio/video can play.

## 📌 Project Status

Prototype/research project created to explore the use of browser-based VR for exposure-therapy concepts. It is not a clinical treatment system.

## 👤 Author

**Veeraarun V** — [GitHub](https://github.com/Veeraarun)
