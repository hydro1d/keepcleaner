# 👥 KeenKeeper — Keep Your Friendships Alive

A React + Vite app for tracking your closest friendships, logging interactions, and visualizing relationship health. Keep your social connections in one place with a clean, responsive dashboard and timeline.

## 🚀 Features

- Home dashboard with friend cards and quick stats
- Individual friend detail pages with status, bio, and contact goals
- Interaction logging for calls, texts, and video chats
- Timeline feed with filterable interaction history
- Analytics page with visual charts powered by Recharts
- LocalStorage persistence for interaction history
- Responsive UI built with Tailwind CSS and Lucide icons

## 🧩 Project Structure

- `src/App.jsx` — main layout, navigation, and toast notifications
- `src/main.jsx` — router setup and app provider wiring
- `src/context/FriendContext.jsx` — friend/timeline state and local storage logic
- `src/pages/` — route views: `Home`, `Timeline`, `Stats`, `FriendDetails`, `NotFound`
- `src/components/` — reusable UI pieces like `Navbar`, `Footer`, and `FriendCard`
- `public/friends.json` — sample friend dataset loaded by the app

## 🛠️ Tech Stack

- React 19
- Vite
- React Router Dom 7
- Tailwind CSS 4
- Recharts
- Lucide React
- React Hot Toast

## 💻 Setup & Run

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the dev server:

   ```bash
   npm run dev
   ```

3. Open the local URL shown in the terminal to view the app.

## 📦 Available Scripts

- `npm run dev` — start the Vite development server
- `npm run build` — create a production build
- `npm run preview` — preview the production build locally
- `npm run lint` — run ESLint on the source files

## 🔍 Notes

- Friend data is loaded from `public/friends.json`.
- Interaction history is saved to `localStorage` under `keenkeeper_timeline`.
- The "Add a Friend" button on the dashboard is currently a UI placeholder.

## 📄 Routes

- `/` — Home dashboard
- `/timeline` — Interaction timeline with filters
- `/stats` — Relationship analytics and charts
- `/friend/:id` — Friend detail page
- `*` — 404 Not Found

## 👍 Contribution

Feel free to extend KeenKeeper with friend management, editable goals, notifications, or persistent backend storage.
