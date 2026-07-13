# Mental Math Gym

A mobile-friendly trainer for lightning mental calculation — a study companion to
Arthur Benjamin's Great Courses series *The Secrets of Mental Math*.

Twelve lessons mirror the twelve lectures. Each one recaps the techniques in
original wording, then offers **unlimited randomly-generated drills** with
instant feedback, step-by-step explanations, streaks, and progress saved
locally on your device (nothing is uploaded anywhere).

- Multiply by 11, squares ending in 5, complements, making change
- 2×1 / 3×1 / 2×2 / 3×2 multiplication (addition, subtraction, factoring, close-together methods)
- Mental division, divisibility tests, Vedic division
- Guesstimation: digit counts, Rule of 70, square roots by divide-and-average
- Casting out nines, the Major memory system, peg words
- Calendar calculating (day of the week for any date, 1600–2099)
- 3- and 4-digit squares, cubes, cube roots

Everything is a single `index.html` — no build step, no dependencies, works offline
once loaded.

## Deploy on GitHub Pages (free)

1. Create a new repository on GitHub (e.g. `mental-math-gym`), public.
2. Push this folder to it:

   ```bash
   git remote add origin https://github.com/<your-username>/mental-math-gym.git
   git push -u origin main
   ```

3. On GitHub: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / root → Save**.
4. After ~a minute your app is live at:

   `https://<your-username>.github.io/mental-math-gym/`

Open that URL on your phone and use your browser's **Add to Home Screen** for an
app-like icon.

## Local preview

Just open `index.html` in any browser, or:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Notes

- Progress lives in your browser's localStorage per device.
- Light/dark theme follows your system setting.
- Lesson text is an original summary of the techniques; the guidebook and
  lectures remain the definitive source — this app is for drilling until the
  methods become reflex.
