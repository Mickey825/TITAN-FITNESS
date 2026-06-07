# 🏋️ Titan Fitness Website

A complete, self-contained gym website with Admin Panel, Member Portal, and Analytics.

## 🚀 How to Run in VS Code

### Option 1 – Live Server (Recommended)
1. Open VS Code
2. Install the **Live Server** extension (by Ritwick Dey)
3. Open the `titan-fitness-website` folder in VS Code
4. Right-click `index.html` → **Open with Live Server**
5. Opens at `http://127.0.0.1:5500`

### Option 2 – Just open in Browser
- Double-click `index.html` directly — works in Chrome, Edge, Firefox

---

## 🔐 Admin Access

| Field    | Value          |
|----------|----------------|
| Username | `titanadmin`   |
| Password | `Titan@2026`   |

**How to access Admin Panel:**
- Click "Admin Login" in the footer
- OR press **Ctrl + Shift + A** anywhere on the site

---

## 📋 Features

### 🌐 Public Website
- Homepage with hero, features, stats
- About Us section
- Membership Plans (INR pricing)
- Fitness Blog
- Contact form

### 👤 Member Portal
- Sign Up / Login
- Attendance tracker with chart
- Membership status & expiry
- Streak counter
- Plan upgrade/change

### 🛡️ Admin Dashboard
- **Overview** – Live stats, charts
- **Users** – All registered members table
- **Members** – Active/expired with attendance bars
- **Analytics** – Page views, signups, revenue charts
- **Sessions** – Login time, duration, device tracking
- **Edit Website** – Change any text content live
- **Manage Blogs** – Add/edit/delete blog posts
- **Membership Plans** – Edit prices & features
- **Export Data** – 4 CSV exports (Users, Sessions, Analytics, Attendance)

---

## 💾 Data Storage
All data is stored in **localStorage** (browser) — no backend or internet required.
Data persists between sessions automatically.

## 📦 Tech Stack
- Pure HTML + CSS + JavaScript (zero dependencies)
- Chart.js (loaded from CDN — needs internet for first load)
- Google Fonts (loaded from CDN)

> **Tip:** For fully offline use, open in browser once with internet to cache fonts & Chart.js, then it works offline.

