# 🔗 URL Shortener App

<p align="left">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
</p>

A fast and minimal **URL Shortener** web application built with **React** and **TypeScript**. Paste any long URL, get a short shareable link instantly.

---

## ✨ Features

- 🔗 Shorten any long URL in one click
- 📋 One-click copy to clipboard
- 📊 Clean, minimal UI with instant feedback
- ⚡ Built with Vite for blazing-fast development and builds
- 🔒 TypeScript for full type safety across components
- 📱 Responsive layout — works on all screen sizes

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **React 18** | UI component library |
| **TypeScript** | Type safety & better DX |
| **Vite** | Build tool & dev server |
| **REST API** | URL shortening service integration |
| **CSS/Tailwind** | Styling |

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/yuvrajsinghantino/urlShortner-app.git
cd urlShortner-app

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production

```bash
npm run build
npm run preview
```

---

## 📁 Project Structure

```
urlShortner-app/
├── src/
│   ├── components/
│   │   ├── UrlInput.tsx      # URL input + submit form
│   │   ├── ShortLink.tsx     # Shortened URL display + copy
│   │   └── Header.tsx        # App header
│   ├── hooks/
│   │   └── useUrlShortener.ts  # Custom hook for API logic
│   ├── types/
│   │   └── index.ts          # TypeScript interfaces
│   ├── App.tsx
│   └── main.tsx
├── index.html
└── vite.config.ts
```

---

## 🔧 How It Works

```
User inputs long URL
        ↓
Form validation (checks valid URL format)
        ↓
API call to shortening service
        ↓
Short URL returned & displayed
        ↓
User copies to clipboard with one click
```

---

## 👨‍💻 Author

**Yuvraj Singh** — Frontend Engineer | React · Next.js · TypeScript

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/yuvrajsinghantino)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/yuvrajsinghantino)
