# 🎬 Shorts Vibe Searcher

A high-performance, mobile-responsive web application for discovering YouTube Shorts. Designed with a **Dual-Engine** approach to provide instant access for casual users and high-data precision for Pro users.

[Live Demo](https://shortsvibe.vercel.app/)

---

## ✨ Features

- **Dual-Vibe Toggle**: 
  - **☁️ FREE Mode**: Uses public Invidious/Piped mirrors for instant, no-setup searching.
  - **🚀 PRO Mode**: Connects directly to Google's YouTube Data API v3 for real-time views, likes, and faster speeds.
- **Compact UI**: Optimized for quick "thumb-scrolling" on mobile and efficient list-viewing on desktop.
- **Privacy First**: API keys are stored in your browser's `localStorage`. They are never sent to a server.
- **Dynamic Themes**: Light mode for the Free vibe, Midnight mode for the Pro experience.

## 🛠️ Tech Stack

- **Frontend**: HTML5, Tailwind CSS
- **APIs**: YouTube Data API v3, Invidious/Piped Public Instances
- **Hosting**: Vercel (Continuous Deployment)

## 🚀 How to Use

1. **Enter a Keyword**: Type any vibe like "Mechanical Keyboards" or "Street Food".
2. **Hit Search**: Browse through 30+ curated YouTube Shorts.
3. **Upgrade to Pro**:
   - Go to [Google Cloud Console](https://console.cloud.google.com/).
   - Enable "YouTube Data API v3".
   - Generate an API Key and paste it into the Pro settings.

---

*Built with Vibe Coding principles.*
