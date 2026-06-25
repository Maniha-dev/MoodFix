# 🎬 Moodflix

> Your Mood, Your Movies — A React.js movie discovery app built with Vite, TailwindCSS v4, and Appwrite.

Built following the [JavaScript Mastery](https://www.youtube.com/@javascriptmastery/videos) tutorial.

## 🔗 Live Demo

[moodflix-sandy.vercel.app](https://moodflix-sandy.vercel.app)

## ⚙️ Tech Stack

- React.js (v18)
- Vite
- TailwindCSS v4
- Appwrite (Trending Movies Algorithm)
- TMDB API

## 🔋 Features

- 🎥 Browse all movies via TMDB API
- 🔍 Real-time search with debouncing
- 📈 Trending movies algorithm powered by Appwrite
- 💅 Modern UI with dark theme
- 📱 Fully responsive design

## 🤸 Quick Start

### Prerequisites
- Node.js (v18+)
- npm

### Installation

```bash
git clone <your-repo-url>
cd moodflix
npm install
```

### Environment Variables

Create a `.env.local` file:

```env
VITE_TMDB_API_KEY=your_tmdb_bearer_token_here

VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
```

Get your TMDB API key: [https://developer.themoviedb.org](https://developer.themoviedb.org)

Set up Appwrite: [https://cloud.appwrite.io](https://cloud.appwrite.io)

### Run

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173)

### Deploy to Vercel

```bash
npm run build
# Push to GitHub and connect to Vercel
```

## 📁 Project Structure

```
moodflix/
├── public/
│   ├── hero.png          # Logo
│   ├── hero-bg.png       # Background
│   ├── search.svg        # Search icon
│   ├── star.svg          # Star icon
│   └── no-movie.png      # Fallback image
├── src/
│   ├── components/
│   │   ├── MovieCard.jsx
│   │   ├── Search.jsx
│   │   └── Spinner.jsx
│   ├── App.jsx
│   ├── appwrite.js
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```
