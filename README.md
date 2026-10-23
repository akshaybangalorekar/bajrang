# Bajrang · बजरंग

**An exercise buddy for young champions.** A single-page web app that guides a child
through a workout with animated figures, live timers and gentle sound cues — built to
be opened on an iPad, iPhone or laptop.

Named after Bajrang (Hanuman), the symbol of strength and discipline — a fitting
companion for dands, surya namaskar and pull-ups. The guide figure itself is an
ordinary monkey, so every pose can be copied as a movement rather than a mascot.

## What it does

- **Animated guidance, shown from the right angle.** Each exercise is demonstrated by
  a slim, lifelike monkey — seen from the **side** for push-ups, planks, lunges,
  squats, burpees and the whole Surya Namaskar flow, and from the **front** for
  skipping, jogging, pull-ups and the seated hip poses. The movement matches the
  timer exactly, so the form can be copied rep for rep.
- **Correct form.** Poses are built on real joint angles, not approximations: the
  push-up holds a straight line from head to heels with the elbows folding back,
  the plank keeps the hips level, and Butterfly shows the soles together and the
  knees dropping out.
- **How-to cues.** Short instructions appear under each exercise while it runs
  ("Hands under your shoulders, body in ONE straight line").
- **Motion arrows.** A pulsing arrow marks the direction of movement on the lifts.
- **Timers for everything.** Rep counts tick up, holds count down, and Surya Namaskar
  walks through all 12 steps.
- **Gentle sound cues.** A soft tone marks every rep, every Surya Namaskar step and
  every change of exercise. A short "get ready" countdown precedes each move.
- **Start / Pause / Stop.** One big button to start; pause any time; stop returns home.
- **Five routines to choose from.**
- **Made for phones, tablets and laptops** — the layout adapts, and it can be added to
  the home screen on iPhone/iPad like a native app.

## The five routines

| Routine | Focus | Roughly |
| --- | --- | --- |
| 🐒 **Hanuman Full** | The complete set, in order | ~17 min |
| ⚡ **Quick Power** | A short burst before school | ~6 min |
| 💪 **Veer Upper Body** | Arms, shoulders and grip | ~5 min |
| 🌅 **Surya & Cardio** | Warm-up, Surya Namaskar, cardio finish | ~12 min |
| 🧘 **Hips & Calm** | Hip openers and gentle holding | ~4 min |

## The exercises

Skipping (300) · Spot Jogging (300) · Surya Namaskar (10 rounds) · Push-ups (10) ·
Hanuman Dand (10) · Burpees (10) · Pull-ups (10) · Dead Hang (120 s) ·
Knees to Chest, hanging (10) · Jerky Swings (10) · Hip Yoga Flow
(Baddha Konasana · Butterfly, Malasana · Deep Squat, Utkata Konasana · Goddess,
Skandasana · Side Lunge, Upavistha Konasana · Wide Angle, Prasarita · Standing Wide).

## Using it

Open the page, pick a routine, and press **Start**. That's it — the figure shows what
to do, the ring and the big number show how far along you are, and the tones keep the
rhythm. Press **Pause** to rest, **Stop** to leave.

**Add to home screen (iPhone/iPad):** open the page in Safari → Share → *Add to Home
Screen*. It will then launch full-screen with its own icon.

## Running it locally

It is a static site — no build step or server required. Open `index.html` in a browser.

## Deploying

The app is published with **GitHub Pages** from this repository. Any push to the
default branch updates the live site.

## Notes

- Sound uses the browser's Web Audio API (no audio files), so the first tap on the
  page enables audio — this is a browser rule on iOS.
- The sound preference is remembered on the device.
- Built as a single self-contained `index.html` so it works offline once loaded.

Made with care for a young champion. Stay strong. 💪
