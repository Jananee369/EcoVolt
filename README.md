# ⚡ EcoVolt — Energy Conservation Game

EcoVolt is a **gamified web application** that encourages users to adopt eco-friendly habits and reduce energy consumption through daily actions, challenges, and rewards.

---

## 🌍 Overview

EcoVolt transforms real-life sustainable actions into a **fun, engaging game experience**. Users can:

* Log eco-friendly activities
* Earn points and level up
* Complete daily & weekly challenges
* Track energy savings (kWh & CO₂)
* Compete on a leaderboard

---

## 🚀 Features

### 🔐 Authentication System

* User registration & login
* Local storage-based data persistence
* Secure password encoding (Base64)

### ⚡ Gamification

* Points (PTS) system
* XP progression & leveling
* Streak tracking 🔥
* Achievements & badges 🏅

### 📊 Dashboard

* Total points, energy saved, CO₂ avoided
* XP progress bar
* Recent activity log

### 🎯 Challenges

* Daily challenges (reset every day)
* Weekly challenges
* Reward claiming system

### 🧾 Action Logging

Users can log actions like:

* Turning off lights 💡
* Reducing AC usage ❄️
* Short showers 🚿
* Using bicycles 🚲
* Recycling ♻️

Each action contributes:

* Points
* Energy saved (kWh)
* CO₂ reduction

### 🏆 Leaderboard

* Compete with simulated users
* Real-time ranking system

### 👤 Profile Page

* User details
* Level & badges
* Achievements grid

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3 (Neon UI / Futuristic Design)**
* **Vanilla JavaScript**
* **LocalStorage (for database simulation)**

---

## 📂 Project Structure

```
index.html
│
├── UI Components (HTML)
├── Styling (CSS)
├── App Logic (JavaScript)
│   ├── Authentication
│   ├── Game Mechanics
│   ├── Challenges System
│   ├── Leaderboard
│   └── UI Updates
```

---

## ▶️ How to Run

1. Download or clone the repository
2. Open `index.html` in your browser
3. Sign up and start playing 🎮

---

## 💾 Data Storage

* All user data is stored in:

  ```
  localStorage → ecovolt_db
  ```
* No backend required

⚠️ Note: Data is browser-specific and will be lost if cache is cleared.

---

## 🎮 Game Mechanics

### 🧠 Points System

* Each action gives points
* Challenges give bonus rewards

### 📈 Level System

| Level | Name         | Points Required |
| ----- | ------------ | --------------- |
| 1     | Spark        | 0               |
| 2     | Fuse         | 200             |
| 3     | Amp          | 500             |
| 4     | Volt         | 1000            |
| 5     | Surge        | 2000            |
| 6     | Reactor      | 4000            |
| 7     | Solar Knight | 7000            |
| 8     | Eco Legend   | 12000           |

---

## 🏅 Achievements

Examples:

* ⚡ First Spark — First action logged
* 🌱 Seedling — 100 points
* 🔥 On Fire — 3-day streak
* 🌍 Earth Defender — 500 points

---

## 🔥 Future Improvements

* 🔗 Firebase integration (real backend)
* 👥 Real multiplayer leaderboard
* 📱 Mobile app version
* 🤖 AI-based energy recommendations
* 📊 Data analytics dashboard

---

## ⚠️ Limitations

* No real authentication (local only)
* Data not synced across devices
* Simulated leaderboard

---

## 💡 Inspiration

EcoVolt is built to promote:

* Sustainable living 🌱
* Energy awareness ⚡
* Habit formation through gamification 🎯

---

## 📜 License

This project is open-source and free to use for learning and development purposes.
Created by user jananee369

---

