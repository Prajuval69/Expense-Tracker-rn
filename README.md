# 💸 Cross-Platform Expense Tracker App

A fully functional expense tracker app built with **React Native + Expo**, featuring secure **authentication**, real-time **balance updates**, and a **Neon-hosted PostgreSQL** backend served via **Express**. Designed for beginners with basic React knowledge—no prior React Native experience required.

---

## 🚀 Features

### 📱 Cross-Platform Frontend (React Native + Expo)
- Built with [React Native](https://reactnative.dev/) and [Expo](https://expo.dev/)
- Test on both Android and iOS (real devices or emulators)
- Pull-to-refresh, smooth animations, and mobile-optimized UI

### 🔐 Secure Authentication
- Signup & Login using [Clerk](https://clerk.dev/)
- Email verification with 6-digit code before app access
- Logout functionality to easily switch or sign out

### 🏠 Key Screens
- **Signup**
- **Login**
- **Email Verification**
- **Home (Dashboard)**
- **Create Transaction**

### 💸 Expense Tracking
- Add income or expense entries with category tagging
- Live balance updates based on all transactions
- Delete unwanted or old transactions with a single tap

### 🔄 User Experience
- Pull-to-refresh gesture built from scratch
- Intuitive UI with modern icons and user-friendly interactions

---

## 🧰 Backend API

- Built using **Express.js**
- Hosted on **Render** and connected to **Neon PostgreSQL**
- RESTful endpoints for transaction management
- Protected by **rate limiting** (Redis-based)

---

## 📦 Tech Stack

| Frontend            | Backend            | Database    |
|---------------------|--------------------|-------------|
| React Native + Expo | Express.js         | Neon (Postgres) |
| Clerk Authentication| Rate Limiting (Redis) |              |

---

## 🧪 Testing & Deployment

- Run the app directly on your **real mobile phone** using the **Expo Go** app
- Backend hosted on **Render** with public API access
- Postgres instance managed via **Neon**

---

## 🛠️ Getting Started

### 🔧 Prerequisites
- Node.js & npm
- Expo CLI (`npm install -g expo-cli`)
- Git & GitHub
- Neon DB account
- Clerk account


