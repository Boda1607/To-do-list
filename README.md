# 📋 To-Do List App

A modern, responsive, and feature-rich To-Do List Progressive Web App (PWA) designed to help users stay organized and productive—on desktop or mobile. It supports real-time task management, category customization, and dynamic charts.

## 🚀 Features

- ✅ Add, edit, complete, and delete tasks
- 📅 Set deadlines and categorize tasks 
- 🎨 Light and dark themes (auto and manual toggle)
- 📦 LocalStorage-based persistence (no backend needed)
- 📱 Fully iPhone-compatible – works as a native app via Safari
- ⚙️ Installable PWA with offline functionality

## 📱 iPhone Compatibility

- Optimized for iOS Safari
- Can be **added to the Home Screen** and used like a native app
- Fully functional **offline**
- Supports iOS-style icons and splash behavior

## 🛠️ Tech Stack

- HTML5, CSS3
- JavaScript (ES6+)
- Chart.js for data visualization
- LocalStorage for task persistence
- Web App Manifest for PWA features

## 🌐 Installation (PWA)

1. Open the app in Safari on iPhone
2. Tap **Share > Add to Home Screen**
3. Launch it from the Home Screen like a regular app

## 📁 Project Structure

```bash
├── index.html               # Main app interface
├── manifest-light.json      # Light theme manifest (loaded dynamically)
├── manifest-dark.json       # Dark theme manifest (auto-detected)
├── favicon.ico              # App icon
├── icon-dark.png            # iOS/Android dark mode icon
├── icon-light.png           # iOS/Android light mode icon
├── style.css                # App styling (not included here)
├── service-worker.js        # Enables PWA offline support and caching
