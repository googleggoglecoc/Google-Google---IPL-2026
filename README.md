# Google Google - IPL 2026 Fantasy Leaderboard 🏆

A sleek, elegant, and fully responsive frontend dashboard built to visualize the "Google Google - IPL 2026 Fantasy League" standings. This project fetches live data directly from a public Google Sheet and displays it beautifully using modern web technologies.

## ✨ Features

- **Live Standings**: A detailed leaderboard showing total points, matches played, average points per match, and dynamic gaps between players.
- **Interactive Charts**: Visualizations built with Chart.js, covering:
  - Total Points Full Standings (Horizontal Bar Chart)
  - Average Points per Match
  - Points Distribution (Doughnut Chart)
- **Elegant UI/UX**: Features a premium navy and gold theme, glassmorphic cards, smooth row hover mechanics, and fade-up tab transitions.
- **Serverless Architecture**: Pure frontend application that pulls data securely and directly from a Google Sheet export. Perfect for static hosting platforms like GitHub Pages.

## 🛠️ Tech Stack

- **HTML5 & CSS3** (Custom layout, flexbox, CSS Grid, Glassmorphism)
- **Vanilla JavaScript** (Data fetching, CSV parsing, basic routing)
- **Chart.js** (For robust data visualizations)

## 🚀 Setup & Deployment

1. **Configure Google Sheet**:
   - Ensure your Fantasy Google Sheet is shared with **"Anyone with the link can view"**.
   - Make note of your exact Sheet name (e.g., `Score Sheet`).

2. **Add Environment Variables**:
   - Since this is a static frontend, environment variables are managed via an `env.js` file.
   - Ensure you have an `env.js` file generated in the root folder with the following content:
     ```javascript
     const SHEET_ID = 'YOUR_GOOGLE_SHEET_ID_HERE';
     const SHEET_NAME = 'Score Sheet';
     ```

3. **Deploy**:
   - The application is entirely static and requires no build step. 
   - Simply push the repository to GitHub and enable **GitHub Pages**, or host the files on any standard web server (Netlify, Vercel, etc.).

## 👨‍💻 Credits
- Developer / Crafted by: [@RejoRaina3]
