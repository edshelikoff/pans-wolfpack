# Pan's Wolfpack · Miami 2026

> 19 men · 1 BnB · 4 days of chaos

The official trip guide for Pan's Wolfpack Miami. A single-page web app with a live Mission Control dashboard, per-day schedules, outfit recommendations, and a master pack list.

**Live site:** https://edshelikoff.github.io/pans-wolfpack

---

## Features

- **Mission Control** — real-time dashboard showing the current and next event, with a live countdown timer. Automatically tracks where you are in the weekend schedule based on EST time.
- **Day-by-day schedule** — full timeline for Wednesday through Saturday with tagged event types
- **Outfit guide** — per-event outfit recommendations for every part of the trip
- **Pack list** — interactive master checklist with tappable items across clothing, beach, nightlife, and toiletries
- **iMessage preview** — Open Graph tags for a rich link card when shared in Messages

---

## Pages

| Tab | Contents |
|-----|----------|
| Mission Control | Live current/next event + countdown + full schedule |
| Wednesday | Kickoff night — Shotgun, Kahoot, Superlatives |
| Thursday | Boat day — Catamaran, bar crawl, Bus Survivor |
| Friday | Recovery — basketball tournament, South Beach, poker |
| Saturday | Hardrock pool party, rooftops, mandatory skinny dipping |
| Pack List | Interactive checklist for the whole trip |

---

## Trip Dates

| Day | Date |
|-----|------|
| Wednesday | March 18, 2026 |
| Thursday | March 19, 2026 |
| Friday | March 20, 2026 |
| Saturday | March 21, 2026 |

---

## Repo Structure

```
pans-wolfpack/
├── index.html      # The entire site — single self-contained file
├── preview.png     # Open Graph image for iMessage/link previews
└── README.md       # This file
```

---

## Updating the Site

All content lives in `index.html`. The event schedule is defined in the `EVENTS` array in the JavaScript section at the bottom of the file. To update an event, find its entry and edit the `title`, `detail`, `time`, or `tags` fields.

After editing, commit the file to the `main` branch and GitHub Pages will redeploy automatically within ~30 seconds.

---

## Built With

- Vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies
- [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) + [Barlow](https://fonts.google.com/specimen/Barlow) via Google Fonts
- Hosted on GitHub Pages
