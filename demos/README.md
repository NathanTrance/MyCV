# Demo projects

Static demo page: `demos/index.html` (currently a work-in-progress page).

Scratch space for demo projects, mainly audio samples for the CV: voice
cloning, voice design, paralinguistic generation, cross-lingual TTS.

## Layout

Each demo gets its own folder:

```
demos/
  index.html      # the landing page
  zero-shot-tts/
    samples/        # audio files
    README.md       # what it shows, model, date
  voice-design/
  ...
```

Keep individual audio files small (a few seconds, mono, 22-44 kHz). If a demo
grows into a real project, move it to its own repository and link it from here.

## Publishing

Enable GitHub Pages with source = `main` / root. The page is then at:

```
https://nathantrance.github.io/MyCV/demos/
```

The root `.nojekyll` file keeps Pages from running Jekyll over the assets.

## Purpose

These are evidence for applications, so each folder should answer three
questions: what was the task, what did the model do, and what is worth
listening for. A short README per demo is enough.
