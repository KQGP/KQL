# KQL — Web Link & Resource Manager

A **web app** for organizing, searching, and tracking links/resources by category, with likes/clicks counters and an admin dashboard. Backed by Firebase (Firestore, Auth, Analytics).

## ✨ Features

- 🔍 Search resources, tags, or URLs
- 🗂️ Categories with show/hide
- ❤️ Like & click tracking
- 📊 Admin dashboard
- 🔐 Firebase Auth
- 📱 Responsive (Tailwind CSS)

## 🧱 Tech Stack

- HTML, Tailwind CSS (CDN), vanilla JavaScript
- Firebase v9 (Firestore, Auth, Analytics)

## 📁 Project Structure

```
index.html          # Public view
dashboard.html      # Admin dashboard
firebase-config.js  # Firebase configuration
```

## 🚀 Getting Started

1. Create a Firebase project and enable Firestore + Auth.
2. Update `firebase-config.js` with your Firebase config.
3. Serve the folder with any static server, e.g.:
   ```bash
   npx serve .
   ```
4. Open `index.html`.

## ⚙️ Configuration
Firebase keys are in `firebase-config.js`. Replace with your own project credentials.
