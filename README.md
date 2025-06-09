# Hello Guys! 

![Silly Car](https://wallpapers-clan.com/wp-content/uploads/2022/07/funny-cat-1.jpg)

#  HirePoint

**HirePoint** is a modern, full-stack online interview platform built to streamline the hiring process. Think of it as your custom GMeet for hiring — but with powerful features designed specifically for interviews and candidate evaluations.

---

## 🌟 Features

- 🎥 **Real-time Video Interviews** – Powered by [Stream.io](https://getstream.io) for fast and reliable video calls.
- 🔐 **Authentication** – Secure and smooth login/signup via [Clerk](https://clerk.dev).
- 📅 **Schedule Meetings** – Easily schedule upcoming interviews with calendar-like interface.
- ⚡ **Direct Meeting Links** – One-click meetings for spontaneous interviews.
- 📼 **Interview Recordings** – Automatically save and access past interview videos.
- 🧑‍💼 **Candidate Evaluation Dashboard** – Interviewers can rate candidates (1–5 stars) and leave detailed feedback.
- 🧠 **Serverless Backend** – Powered by [Convex](https://convex.dev) for real-time data storage and sync.
- 💅 **Clean UI/UX** – Built with [ShadCN UI](https://ui.shadcn.com), [Tailwind CSS](https://tailwindcss.com), and [Next.js](https://nextjs.org).

---

## 🧰 Tech Stack

| Tech        | Description                              |
|-------------|------------------------------------------|
| **Next.js** | React Framework with server-side support |
| **Clerk**   | Authentication & User Management         |
| **Convex**  | Serverless DB & Backend Logic            |
| **Stream.io**| Video Calling & Streaming               |
| **Tailwind CSS** | Utility-first CSS Framework         |
| **ShadCN UI** | Pre-built, themeable UI components     |

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
