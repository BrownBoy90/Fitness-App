# Effortlessly Strong Tracker

A mobile-first offline-capable fitness tracker built from the attached Strength + Grooming + Communication blueprint.

## Run locally
Open `index.html` directly, or run a tiny local server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

For PWA/offline caching, use the local server (service workers do not run from `file://`).

## What is included
- 4-day strength plan with set-by-set logging, weights, reps, RPE and rest timer
- "Rest this day" option and automatic next-workout memory
- Nutrition targets, manual macro logging, blueprint meal-template completion, fruit/veg/fluids/creatine checklists, protein/calorie bars
- Bodyweight, waist, sleep and steps tracking
- 7-day bodyweight trend
- Optional grooming, communication and cardio modules
- Weekly scorecard and Sunday review
- Personal-best extraction from completed sets
- Local memory via `localStorage`
- JSON export/import backups
- Installable mobile-web-app manifest + offline service worker

## Data/privacy
All tracker data stays in the browser on the device unless you export it yourself.
# Fitness-App
