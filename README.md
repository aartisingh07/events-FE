# 🎟️ Booking Events — Frontend

A MERN-based Event Booking Web Application built with **React + Vite**. Users can browse and book events through a clean, responsive UI that communicates with a dedicated REST API backend.

🔗 **Live Demo:** [events-16-04-2007.web.app](https://events-16-04-2007.web.app)
🔗 **Backend Repo:** [aartisingh07/events-BE](https://github.com/aartisingh07/events-BE)

---

## 🛠️ Tech Stack

| Layer      | Technology                          |
|------------|-------------------------------------|
| Framework  | React 19 + Vite 8                   |
| Routing    | React Router DOM v7                 |
| HTTP Client| Axios                               |
| Styling    | CSS (custom)                        |
| Linting    | ESLint with React Hooks plugin      |

---

## 📁 Project Structure

```
events-FE/
├── src/
│   ├── components/       # Reusable UI components
│   ├── pages/            # Route-level page components
│   ├── App.jsx           # Root component with routing
│   └── main.jsx          # Entry point
├── index.html
├── vite.config.js
├── eslint.config.js
└── package.json
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- npm or yarn
- Backend server running (see [events-BE](https://github.com/aartisingh07/events-BE))

### Installation

```bash
# Clone the repository
git clone https://github.com/aartisingh07/events-FE.git
cd events-FE

# Install dependencies
npm install
```

### Running Locally

```bash
# Start the development server
npm run dev
```

The app will run at `http://localhost:5173` by default.

### Build for Production

```bash
npm run build
```

The production-ready output will be in the `dist/` folder.

---

## ⚙️ Environment Setup

Make sure the backend API URL is configured correctly. You can set it in a `.env` file at the root:

```env
VITE_API_URL= https://your-backend-url.com
```

> Update this URL to point to the deployed backend in production.

---

## 📦 Available Scripts

| Script          | Description                          |
|-----------------|--------------------------------------|
| `npm run dev`   | Start Vite dev server                |
| `npm run build` | Build for production                 |
| `npm run preview` | Preview the production build       |
| `npm run lint`  | Run ESLint checks                    |

---

## 🌐 Deployment

This project is deployed on **Firebase Hosting**.

To deploy your own instance:

```bash
npm run build
firebase deploy
```

---

## 🤝 Related Repository

| Repo | Description |
|------|-------------|
| [events-BE](https://github.com/aartisingh07/events-BE) | Express + MongoDB REST API backend |

---

## 👩‍💻 Author

**Aarti Singh**
[GitHub](https://github.com/aartisingh07)