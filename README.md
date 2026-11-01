# Gym Journal

A golden-era gym journal for your phone. Log your sets, get told when to add weight, rest between sets with a built-in timer and watch your lifts go up.

**Open it:** https://kasm12.github.io/gym-journal/

## What it does

- **Full body A / B / C plan**, 3× a week, under 45 minutes. Every session opens with a big lift: Squat, Deadlift or Bench.
- **Set logging** with last time's numbers shown next to each exercise.
- **Progression hints.** Double progression: keep the weight until every set hits the top of the rep range, then add. Rate each exercise Easy / Good / Hard and the app adjusts.
- **Plate calculator** for barbell lifts.
- **Rest timer** that starts when you tick off a set, with a sound and a full-screen flash.
- **Progress charts** of your estimated one-rep max per exercise, coloured by how each session felt.
- **History** of every session.

## Install on your phone

- **iPhone (Safari):** Share → Add to Home Screen
- **Android (Chrome):** menu ⋮ → Install app / Add to Home screen

It then opens full screen with its own icon and works offline.

## Your data

Everything stays on your device (browser storage). There is no account and no server. Use **Plan → Your data → Export backup** now and then, and **Import backup** to move to a new phone.

## Tech

Plain HTML, CSS and JavaScript in a single `index.html`. No build step, no dependencies. `manifest.json` and `sw.js` make it an installable, offline-capable web app. Hosted on GitHub Pages.

To run it locally, serve the folder with any static server, for example `python3 -m http.server`, and open http://localhost:8000.

## License

MIT
