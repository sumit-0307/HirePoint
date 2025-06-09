# Hello Guys! 

![Silly Car](https://wallpapers-clan.com/wp-content/uploads/2022/07/funny-cat-1.jpg)

#  HirePoint

## Demo Website:
https://hire-point-izumi.vercel.app/

---

**HirePoint** is a modern, full-stack online interview platform built to streamline the hiring process. Think of it as your custom GMeet for hiring — but with powerful features designed specifically for interviews and candidate evaluations.

---

## 🌟 Features

- 🎥 **Real-time Video Interviews** – Powered by [Stream.io](https://getstream.io) for high-quality video calls.
- 🔐 **Authentication** – Seamless login/signup with [Clerk](https://clerk.dev).
- 📅 **Schedule Interviews** – Set up interviews in advance with date/time selectors.
- ⚡ **Quick Direct Meetings** – Instantly generate and join one-click meeting rooms.
- 📼 **Interview Recordings** – Rewatch and review candidate interviews anytime.
- 🧑‍💼 **Candidate Evaluation Dashboard** – Interviewers can leave **1–5 star ratings** and comments on performance.
- 💬 **Live Coding Questions Tab** – View real coding questions during interviews.
- 🧠 **Integrated Code Editor** – Write, edit, and test code in multiple programming languages during interviews.
- 🌐 **Language & Question Type Selector** – Choose language (e.g., JavaScript, Python, etc.) and question category.
- 🖥️ **Screen Sharing Support** – Share your screen in real-time for deep collaboration.
- 🪄 **Serverless Backend** – Managed with [Convex](https://convex.dev) for live syncing data.
- 💅 **Modern UI/UX** – Built with [Next.js](https://nextjs.org), [ShadCN UI](https://ui.shadcn.com), and [Tailwind CSS](https://tailwindcss.com).

---

## 🧰 Tech Stack

| Tech           | Description                              |
|----------------|------------------------------------------|
| **Next.js**     | React framework with App Router          |
| **Clerk**       | Authentication & User Management         |
| **Convex**      | Real-time Backend & DB                   |
| **Stream.io**   | Video/Audio Streaming API                |
| **Tailwind CSS**| Utility-first styling framework          |
| **ShadCN UI**   | Reusable UI Components                   |
| **Monaco Editor**| VS Code-style code editor               |

---

## 📸 Screenshots

> _Screenshots coming soon. Stay tuned!_

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sumit-0307/HirePoint.git
cd HirePoint
```

### 2. Setup .env file

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

### 3. Run the app

```bash
npm run dev
```

### 4. Open Another Terminal and Run the Convex Database

```bash
npx convex dev
```
