# Payday Countdown - Salary Budget Planner & Expense Tracker

[![PWA](https://img.shields.io/badge/PWA-ready-blue)](https://web.dev/progressive-web-apps/)
[![Offline](https://img.shields.io/badge/works-offline-green)](#)
[![No Login](https://img.shields.io/badge/no%20login-required-brightgreen)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Know exactly what you can spend today until payday.** 

Payday Countdown is a free, offline-first budget planner and salary calculator. Track days until payday, calculate your daily safe-to-spend budget, and avoid running out of money. No login, no ads tracking, no data leaves your phone.

Perfect for anyone managing personal finance, monthly salary, or side hustle income. Works worldwide with USD, EUR, GBP, NGN, GHS, KES, INR, and 100+ currencies.

### 📱 [Try it live](https://yourdomain.com) | [Install on Android](https://play.google.com/store/apps/details?id=your.app) | [Add to iOS Home Screen](https://yourdomain.com)

---

## ✨ Features

- **Payday Countdown** - See days left until your next salary in real-time
- **Safe-to-Spend Calculator** - Daily budget = current balance ÷ days left
- **Expense & Income Logging** - Track spending with one tap
- **Custom Payday Rules** - Last day, 25th, 28th, last Friday, or custom date
- **Daily Reminders** - 9AM push notifications with your budget
- **100% Offline** - Works in airplane mode. No internet required after install
- **No Login / No Tracking** - All data stored locally on your device only
- **Worldwide Currencies** - ₦, $, €, £, ₹, GHS, KES, and more
- **Lightweight PWA** - < 50KB. Installs in 2 seconds

## 📸 Screenshots

| Countdown Screen | Setup Screen | Daily Reminder |
| --- | --- | --- |
| ![Countdown](screenshot1.png) | ![Setup](screenshot2.png) | ![Notification](screenshot3.png) |

## 🚀 Install

### Web / PWA
1. Open https://yourdomain.com on your phone
2. Tap "Add to Home Screen" 
3. Use like a native app

### Android / Google Play
Search "Payday Countdown - Budget Planner" or [install here](https://play.google.com/store/apps/details?id=your.app)

### iOS
Open in Safari → Share → Add to Home Screen. Works offline after first load.

## 🔧 How It Works

1. **Setup**: Enter monthly salary, current balance, payday rule
2. **Track**: App shows "14 days left, safe to spend ₦2,300 today"
3. **Log**: Tap "- Log Expense" when you spend money
4. **Remind**: Enable notifications for daily 9AM budget ping

**Formula**: `Safe to Spend Today = Current Balance ÷ Days Until Payday`

This prevents you from overspending early in the month.

## 🛡️ Privacy & Safety

- **Zero data collection** - We don't have servers. Nothing to hack.
- **Local storage only** - Your salary/balance never leaves your device
- **No analytics, no ads SDKs, no trackers** - See [Privacy Policy](privacy.html)
- **Open source** - Audit the code yourself
- **Not financial advice** - This is a calculator only. For debt/investment help, consult a licensed financial advisor.

## 🛠️ Tech Stack

- **Frontend**: Vanilla JS + Alpine.js + TailwindCSS CDN
- **PWA**: Service Worker + Web Manifest
- **Storage**: localStorage API
- **Size**: 48KB total. Loads in <1s on 3G
- **Dependencies**: Zero build step. Zero npm. One `index.html` file.

## 📂 File Structure
