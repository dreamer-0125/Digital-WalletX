# 🚀 WalletX - Digital Wallet System Management - with Role Based Dashboard

This is the **frontend** of the project, built with **React (Vite + TypeScript)**,  
**Redux Toolkit Query** for state management, and **Shadcn/UI + TailwindCSS** for UI components.

---

## 📖 Project Overview

- 🔐 **Role-based dashboard** for admins & users
- 📊 **Admin Analytics** with:
  - Total users
  - Total agents
  - Transaction count
  - Transaction volume
- 💳 **Transactions Management**
  - Paginated transaction list
  - Loading skeletons for better UX
  - User-specific transaction history
- 🎨 **Modern UI** with TailwindCSS + Shadcn UI
- ⚡ Optimized API requests with **Redux Toolkit Query**

---

## 🚀 Live Demo

🔗 **Live URL:** [https://walletx-digital-wallet-system-management.vercel.app](https://walletx-digital-wallet-system-management.vercel.app)

---

## 🛠️ Technology Stack

- **React 18 + Vite** → Fast build tool and modern React setup
- **TypeScript** → Strong typing for better developer experience
- **Redux Toolkit Query (RTKQ)** → Data fetching, caching, and global state
- **TailwindCSS** → Utility-first CSS framework
- **Shadcn UI** → Accessible and customizable UI components
- **Sonner Toasts** → Notification system

---

## 📂 Folder Structure

```bash
src/
├── components/       # Reusable UI components
│   └── ui/           # Shadcn components
├── pages/            # Page components (AdminAnalytics, Transactions, etc.)
├── redux/            # Redux Toolkit setup
│   ├── baseApi.ts    # RTK Query base API
│   └── feature/      # API slices & reducers
├── types/            # TypeScript interfaces
├── App.tsx           # Root component
└── main.tsx          # Entry point
```

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/dreamer-0125/Digital-WalletX.git
cd frontend
```

### 2️⃣ Install Dependencies

npm/yarn/pnpm:

```bash
npm install
# or yarn install
# or pnpm install
```

### 3️⃣ Environment Variables

Create a .env file in the project root:

```bash
Create a .env file in the project root:
```

### 4️⃣ Start Development Server

```bash
npm run dev
```

### 5️⃣ Build for Production

```bash
bun build

```
