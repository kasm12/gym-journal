# Gym Journal

A golden-era gym log for your phone. Free, no account, works offline.

**Open:** https://kasm12.github.io/gym-journal/

## Features

- **A / B / C full-body plan**, 3× a week, under 45 min. Each day opens with Squat, Deadlift or Bench. The app tracks which day is next.
- **Set logging** with last session's numbers next to each exercise.
- **Progression hints.** Add weight once every set hits the top of the rep range. Rate each exercise Easy / Good / Hard to fine-tune.
- **Rest timer** with sound and a full-screen flash.
- **Plate calculator**, **history** and **progress charts** (estimated 1RM).
- **Editable plan.** Plan → Edit plan: swap exercises, sets, reps, rest, weight steps and supersets. Reset to default any time.

## Install

- **iPhone:** Safari → Share → Add to Home Screen
- **Android:** Chrome → ⋮ → Install app

## Your data

Everything is stored in your browser on your device. Nothing is sent anywhere, so every user sees only their own log. There is no sync between devices.

- Back up with **Plan → Your data → Export backup**. **Import backup** restores it on any device.
- Use the app from the home screen. Safari may clear data of websites you haven't opened in 7 weeks.

## Tech

One `index.html` with plain HTML, CSS and JS. No build, no dependencies. `manifest.json` and `sw.js` make it installable and offline. Hosted on GitHub Pages.

Run locally: `python3 -m http.server` and open http://localhost:8000

MIT License
