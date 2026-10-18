# Kahkeshan

A Co–Star-style web app with a Persian poetry layer: give your birth date, time and place once, and each
day the app reads today's planets and sends you a line of Persian poetry.

It is also a practice project for full-stack interview preparation (React, TypeScript, APIs, Postgres,
AI integration). The project definition lives in a separate doc.

## Current state

A static landing page (`index.html`) with a waitlist form. The form checks the email in the browser and
sends nothing yet.

`moon.webp` is a placeholder from a reference image and must be replaced before a public launch.

## Run locally

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Static site, no build step. On Vercel: import the repo, Framework Preset "Other", no build command.
