# FItTracker
# 🏋️ FitTracker

### My first app. I actually built a thing. 🎉

Hey 👋 — this is **FitTracker**, the first app I've ever made, and I'm honestly kind of proud of it. It started because I wanted a workout tracker that didn't feel like a spreadsheet or beg me to pay a subscription… so I just built my own. One file, no account, no server. Open it and go.

**Try it here:** https://f-it-tracker.vercel.app/

I'm a solo dev and this was my "learn by actually shipping something" project. It's grown way bigger than I expected, so I figured it was time to put it out there. If you try it, I'd genuinely love to hear what you think. 🙏

---

## So what is it?

It's a fitness tracker that turns working out into a little game. You log your workouts and food, follow your own plans, watch your numbers go up on charts — and along the way you earn XP, level up, clear weekly quests, and spend your XP on real‑life treats. The whole thing has a retro pixel‑art look because, well, I thought it was cool.

Everything runs in your browser. Your data stays on your device (with optional sync to your own GitHub if you want it). No tracking, no ads, no nonsense.

---

## What it can do

**🏋️ Track your workouts**
- Log strength (sets × reps × weight) and cardio (time, distance) sessions.
- A built‑in **rest timer** that pops up between sets with a beep + buzz.
- It remembers your last session for each lift and suggests your next target so you keep progressing.
- Detects new **personal records** and throws confetti when you hit one.

**📋 Build your own plans**
- Make programs like Push/Pull/Legs, set which days they repeat, and log a whole day in one tap.

**📅 Calendar**
- Opens to today, color‑codes your training days, and shows what you did (and ate) on any date. Can export to Google Calendar too.

**📊 See your progress**
- Charts for weekly activity, estimated 1RM per lift, top exercises, and bodyweight over time.

**🍽️ Food + calories**
- A TDEE calculator works out your daily targets, and you can log meals with calories and protein.

**🔥 The fun part — leveling up**
- Earn **XP** every workout across 10 levels (Rookie → FINISH HARD).
- **Weekly Quests** that reset every Monday — clear them all for a big bonus.
- **25 achievements** to unlock.
- An **XP Shop** where you spend XP on real‑life rewards (cheat meal, sleep‑in, new game…). Your level never drops — only your spendable balance does. Whatever you buy shows up on your home screen ready to "use."

**🤖 Stuck?** There's an "Ask Claude" button that opens an AI coach with your stats already filled in.

**💾 Your data**
- Saved locally, with one‑click backup/restore and optional GitHub sync.

---

## Run it yourself

It's literally one file. Download `index.html`, open it in a browser, done. Want it online? Drop it in a GitHub repo and connect it to [Vercel](https://vercel.com) — that's exactly how the live version works.

> 🔒 Heads up: if you turn on GitHub sync, use a **private** repo. Your data file holds personal info, and a public repo would expose it. Your token only ever lives in your browser.

---

## A few honest notes

- It's built with plain HTML, CSS, and vanilla JavaScript — no frameworks, no build step. I wanted to actually understand every line.
- It's my first real project, so there are probably things a more experienced dev would do differently. I'm learning, and I'm open to feedback and ideas.
- No analytics, no ads, no accounts. Ever.
