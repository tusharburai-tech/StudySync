# 📚 StudySync

A collaborative student productivity platform — Pomodoro timers, live study rooms, group chat, leaderboards, and premium tools, all in one place.

---

## 🚀 Features

- **Pomodoro Timer** — Focus sessions with custom intervals, animated circular progress, streak tracking, and a built-in task list
- **Live Study Rooms** — Join or create topic-focused rooms (JEE, UPSC, Web Dev, NEET, etc.) and study alongside peers
- **Group Chat** — Real-time messaging across dedicated channels (`#general`, `#math`, `#science`, `#coding`, `#motivation`)
- **Rank Leaderboard** — Weekly, Monthly, and All-Time rankings with gold/silver/bronze podium display
- **Verified Profile** — Personalized student identity with avatar color, daily study goal, session stats, day streak, and earned badges
- **Premium Plans** — Free, Pro (₹49/mo), and Study Group (₹149/mo) tiers with monthly/yearly billing toggle
- **Ambient Sounds** — Rain, Café, and Forest background audio for active study rooms
- **Responsive Design** — Dark-themed UI with smooth section navigation and mobile hamburger menu

---

## 🧠 How It Works

```
User Creates Profile (Name + Avatar Color + Daily Goal)
        ↓
Navigate via Navbar (Home / Features / Timer / Room / Leaderboard / Chat / Premium)
        ↓
Start a Pomodoro Session (Focus → Short Break → Long Break)
        ↓
Join a Live Study Room (search by topic, see member count)
        ↓
Chat in Group Channels (send messages, switch channels)
        ↓
Earn Study Minutes → Climb the Leaderboard → Unlock Badges
```

---

## 📁 Project Structure

```
StudySync/
├── index.html    # Full SPA layout — navbar, all sections, modals, footer
├── style.css     # Dark theme, glassmorphism cards, animations, responsive styles
└── app.js        # State management, timer logic, room/chat/leaderboard rendering
```

---

## ⏱️ Timer Modes

| Mode        | Default Duration |
|-------------|-----------------|
| Focus       | 25 minutes       |
| Short Break | 5 minutes        |
| Long Break  | 15 minutes       |
| Custom      | User-defined (hrs + mins) |

---

## 🏆 Leaderboard

Students are ranked by total study minutes logged.

| Filter     | Description                        |
|------------|------------------------------------|
| This Week  | Minutes logged in the current week |
| This Month | Minutes logged in the current month|
| All Time   | Cumulative lifetime minutes        |

---

## 💎 Pricing

| Plan         | Monthly | Yearly    | Key Perks                                        |
|--------------|---------|-----------|--------------------------------------------------|
| Free         | ₹0      | ₹0        | Timer, 2 rooms, basic chat, public leaderboard   |
| Pro          | ₹49     | ₹24/mo    | AI insights, unlimited rooms, ad-free, Gold badge|
| Study Group  | ₹149    | ₹74/mo    | Up to 20 members, admin dashboard, team analytics|

> 💡 Yearly billing saves **50%** on Pro and Study Group plans.

---

## 🗂️ Sections

| Section      | Description                                                        |
|--------------|--------------------------------------------------------------------|
| Home         | Hero banner with stats (2.4K+ students, 18K+ hours, 580+ rooms)   |
| Features     | Overview cards linking to each major tool                          |
| Timer        | Pomodoro timer + task list                                         |
| Study Room   | Browse, search, create, and join live study rooms                  |
| Leaderboard  | Podium + ranked table with weekly/monthly/all-time filter          |
| Chat         | Multi-channel group chat with online user list                     |
| Premium      | Pricing cards with billing toggle                                  |

---

## ⚙️ Setup

No build step required. Open `index.html` directly in any modern browser.

**External dependencies (loaded via CDN):**

- [Google Fonts – Outfit](https://fonts.google.com/specimen/Outfit) — Typography

---

## 🖥️ Usage

1. Open `index.html` in any modern browser
2. Click **Create Profile** — set your name, avatar color, and daily study goal
3. Navigate to **Timer** — pick a mode or set a custom interval and start focusing
4. Head to **Study Room** — search by topic and join an active room
5. Open **Chat** — switch channels and message with peers
6. Check the **Leaderboard** — see how your study time stacks up

---

## 🔥 Potential Improvements

- Persist session data with `localStorage` or a backend (currently resets on page reload)
- Real-time multi-user sync via WebSockets or Firebase
- Actual audio files for ambient sounds (Rain, Café, Forest)
- Push notifications when a Pomodoro session ends
- Export leaderboard and session stats as CSV
- OAuth login (Google / GitHub) for persistent profiles
- Mobile app version (React Native / PWA)

---

## 👨‍💻 Authors

Built as a **2nd Year Frontend Project Prototype** by our team.  
*Designed to help students study smarter — together.*

---

## ⭐ Support

If you found this useful:

- ⭐ Star the repo
- 🍴 Fork it
- 📢 Share it with your classmates
