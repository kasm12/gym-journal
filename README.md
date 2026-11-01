# Gym Journal

A golden-era gym log for your phone. Free, no account, works offline.

**Live app:** https://kasm12.github.io/gym-journal/ (deployed with GitHub Pages from the `main` branch, updates automatically on every push)

## Features

- **A / B / C full-body plan**, 3× a week, under 45 min. It's my own gym plan, set as the default. Each day opens with Squat, Deadlift or Bench, and the app tracks which day is next.
- **Set logging** with last session's numbers next to each exercise.
- **Progression hints.** Add weight once every set hits the top of the rep range. Rate each exercise Easy / Good / Hard to fine-tune.
- **Rest timer** with sound and a full-screen flash.
- **Plate calculator**, **history** and **progress charts** (estimated 1RM).
- **Make it yours.** Don't like my plan? Plan → Edit plan: swap exercises, sets, reps, rest, weight steps and supersets, rename days. Reset to default any time.

## Install

- **iPhone:** Safari → Share → Add to Home Screen
- **Android:** Chrome → ⋮ → Install app

## Your data

Everything is stored in your browser on your device. Nothing is sent anywhere, so every user sees only their own log. There is no sync between devices.

- Back up with **Plan → Your data → Export backup**. **Import backup** restores it on any device.
- Use the app from the home screen. Safari may clear data of websites you haven't opened in 7 weeks.

## Tech

One `index.html` with plain HTML, CSS and JS. No build, no dependencies. `manifest.json` and `sw.js` make it installable and offline. Hosted on GitHub Pages (Settings → Pages → Deploy from branch `main`, root).

Run locally: `python3 -m http.server` and open http://localhost:8000

MIT License
