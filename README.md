# StudyPath

An interactive mobile-app **prototype** that fights chronic absenteeism in secondary‑school students (ages 14–18) by reframing every school subject as a concrete step toward the student's dream career — turning attendance and studying into a progression game.

> Single self‑contained `index.html`. No build step, no dependencies to install — just open it in a browser.

## ✨ Features

- **Pick a dream path** — choose from 6 career tracks (Game Dev, Bio‑Medical Engineer, Founder, Lawyer, Physician, Civil Engineer).
- **Add your class timetable** — tap to build a Mon–Fri schedule (or add a custom *Other* subject).
- **AI curriculum mapping** — each class is reframed as a direct step toward the chosen career.
- **Gamified attendance calendar** — full‑month view; tap today to confirm attendance (XP + streak), tap past days to correct them.
- **Daily micro‑study plan** — burnout‑aware task chunking with XP rewards.
- **AI Catch‑Up** — simulate uploading a classmate's notes to get an instant summary + practice quiz.
- **XP, levels, and streaks** — with confetti and level‑up moments.

## 🚀 Run it

**Locally:** double‑click `index.html`, or serve the folder:

```bash
python -m http.server 8137
# then open http://localhost:8137
```

**GitHub Pages:** push this repo, then enable **Settings → Pages → Deploy from branch → `main` / root**. The prototype will be live at `https://<your-username>.github.io/<repo-name>/`.

## 🛠 Tech

- Plain HTML + vanilla JavaScript (a small state engine that re‑renders screens).
- [Tailwind CSS](https://tailwindcss.com) via CDN, with a custom palette remap.
- Fonts: Fraunces (display) + Plus Jakarta Sans (body) via Google Fonts.

## 📌 Status

This is a clickable design prototype for user testing — the "AI" responses and data are mocked, not wired to a live model.
