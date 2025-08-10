<div align="center">
  <a href="https://www.youtube.com/watch?v=FkowOdMjvYo" target="_blank">
    <img src="https://github.com/user-attachments/assets/eaaeb1f0-22da-46be-9e29-9bef70e0039d" alt="Project Banner" />
  </a>

  <br />

  <div>
    <img src="https://img.shields.io/badge/-Next_JS-000?style=for-the-badge&logo=nextdotjs&logoColor=white&color=000000" alt="Next.js" />
    <img src="https://img.shields.io/badge/-TypeScript-000?style=for-the-badge&logo=typescript&logoColor=white&color=3178C6" alt="TypeScript" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-000?style=for-the-badge&logo=tailwindcss&logoColor=white&color=06B6D4" alt="Tailwind CSS" />
  </div>

  <h2 align="center">📄 Collaborative LiveDocs</h2>
  <p align="center">Real-time Google Docs Clone built with Next.js, Liveblocks, and TailwindCSS</p>
</div>

---

## 📋 Table of Contents
1. 🤖 [Introduction](#-introduction)
2. ⚙️ [Tech Stack](#%EF%B8%8F-tech-stack)
3. 🔋 [Features](#-features)
4. 🖼 [Preview](#-preview)
5. 🚀 [Quick Start](#-quick-start)

---

## 🤖 Introduction
**LiveDocs** is a **real-time collaborative document editor** inspired by Google Docs.  
It’s built with:
- **Next.js** for UI & routing  
- **Liveblocks** for real-time sync  
- **Tailwind CSS** for styling  

✨ Designed to showcase **real-time collaboration**, **clean architecture**, and **scalable frontend engineering skills**.

---

## ⚙️ Tech Stack
💻 **Frontend**: Next.js + TypeScript  
⚡ **Real-time**: Liveblocks + Lexical Editor  
🎨 **UI Components**: Tailwind CSS + ShadCN  
🔐 **Auth**: NextAuth + Clerk  

---

## 🔋 Features
✅ **Authentication** – GitHub OAuth via NextAuth  
✅ **Collaborative Editing** – Multiple users can edit in real time  
✅ **Document Management**  
   - ➕ Create, 🗑 Delete, 🔗 Share with permissions  
   - 📂 List, 🔍 Search, and Sort documents  
✅ **Comments System** – Inline & general comments with threading  
✅ **Active Presence** – See collaborators editing live  
✅ **Notifications** – For shares, comments, and updates  
✅ **Fully Responsive** – Works on mobile, tablet, and desktop  

---

## 🖼 Preview

<p align="center">
  <img src="./screenshots/Screenshot%202025-08-11%20004733.png" width="45%" />
  <img src="./screenshots/Screenshot%202025-08-11%20004901.png" width="45%" />
</p>
<p align="center">
  <img src="./screenshots/Screenshot%202025-08-11%20005236.png" width="45%" />
  <img src="./screenshots/Screenshot%202025-08-11%20005835.png" width="45%" />
</p>
<p align="center">
  <img src="./screenshots/Screenshot%202025-08-11%20010116.png" width="90%" />
</p>

---

## 🚀 Quick Start

### 📦 Prerequisites
Install the following:
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

---

### 📥 Clone the Repository
```bash
git clone https://github.com/JavaScript-Mastery-Pro/livedocs.git
cd livedocs
```

---

### 📚 Install Dependencies
```bash
npm install
```

---

### ⚙️ Set Environment Variables
Create a `.env` file in the root directory:

```env
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```
🔑 **Get your credentials** from [Clerk](https://clerk.com/) and [Liveblocks](https://liveblocks.io/).

---

### 🏃 Run the Project
```bash
npm run dev
```
Then visit **[http://localhost:3000](http://localhost:3000)** 🚀

---

## 💡 Inspiration
This project was inspired by **Google Docs** and aims to replicate its real-time collaborative experience with modern tools and clean architecture.

---

## 📜 License
This project is licensed under the MIT License – free to use, modify, and distribute.
