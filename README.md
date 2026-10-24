# Bajrang · बजरंग

**An exercise buddy for young champions.** A single-page web app that guides a child
through a workout with animated figures, live timers and gentle sound cues — built to
be opened on an iPad, iPhone or laptop.

Named after Bajrang (Hanuman), the symbol of strength and discipline — a fitting
companion for dands, surya namaskar and pull-ups. The guide figure itself is an
ordinary monkey, so every pose can be copied as a movement rather than a mascot.

## What it does

- **Real demonstration artwork.** Every exercise is shown as a clear anatomical
  illustration of a person performing it — three frames per movement, played as a
  flip-book in step with the timer, so the form can be copied rep for rep. Surya
  Namaskar walks through all twelve positions; the hip flow holds each pose.
- **Correct form.** The artwork is drawn from real human proportions (the
  Everkinetic exercise library), not approximated: the push-up holds a straight
  line from head to heels, the plank keeps the hips level, and Butterfly shows the
  soles together with the knees dropping out.
- **How-to cues.** Short instructions appear under each exercise while it runs
  ("Hands under your shoulders, body in ONE straight line").
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
| ⬆ **Unnati · Growth** | Hanging, stretching and posture work | ~5 min |
| 🛡 **Balam · Muscle** | Bodyweight strength — legs, core, arms | ~4 min |
| 🔥 **Urja · Stamina** | Heart and lungs | ~6 min |

> **A note on "height gain".** No exercise makes a child taller — height is mostly set
> by genetics, food and sleep. What the growth routine *can* do is help him stand at
> his full height: hanging and stretching decompress the spine, and the posture work
> (Superman, Bridge, side stretch) strengthens the back and shoulders so he does not
> slump. Pair it with good sleep and food; the app is not a substitute for those.

## The exercises

**Original set** — Skipping (300) · Spot Jogging (300) · Surya Namaskar (10 rounds) ·
Push-ups (10) · Hanuman Dand (10) · Burpees (10) · Pull-ups (10) · Dead Hang (120 s) ·
Knees to Chest, hanging (10) · Hanging Leg Raise (10) · Hip Yoga Flow
(Baddha Konasana · Butterfly, Cat-Cow, Child's Pose, Seated Forward Fold,
Anjaneyasana · Hip Flexor, Torso Twist).

**Growth & posture** — Active Hang (30 s) · Standing Side Stretch (10) ·
Calf Raises (20) · Superman (10) · Bridge (10).

**Muscle** — Squats (15) · Lunges (10) · Mountain Climbers (20) · Wall Sit (30 s) ·
Leg Raises (12).

**Stamina** — Jumping Jacks (30) · High Knees (40) · Skater Hops (16) ·
Squat Jumps (10) · Fast Feet (40).

## Credits

Exercise illustrations by **Bryl Lim** ([workout-guide](https://github.com/bryllim/workout-guide)),
derived from the **Everkinetic** pose artwork, licensed
**[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)**. The illustrations
are used unmodified and credited here and in the app footer.

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
