# Class Command — Version 1

A self-contained, touch-first, classroom agenda and CHAMPS screen intended for iPad screen mirroring. It uses **one HTML file** with no server, dependencies, subscriptions, external fonts, or student data.

## Try it on a computer

Open `index.html` in a modern browser. The sample Government lesson appears automatically. Use the blue **Next activity** button, voice-level buttons, timer controls, or **⚙ Setup**.

## Use it on your iPad (recommended)

The simplest dependable way to open it in Safari is to publish this static file with GitHub Pages:

1. Sign in to GitHub and create a **new public repository** called `class-command` (do not include real student information; GitHub Pages sites are public).
2. Upload `index.html` to the repository's top level.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main`, choose `/(root)`, and save.
4. Open the GitHub Pages URL shown in Settings → Pages on your iPad in Safari.
5. Optionally use Safari's Share menu → **Add to Home Screen** and enable **Open as Web App**.
6. Mirror the iPad using Control Center → **Screen Mirroring** → the room's compatible AirPlay receiver, or connect it with a supported display adapter.

Since this is ordinary mirroring, whatever is on the iPad—including Setup when opened—will also appear on the projector. Keep Setup closed during instruction. If you later want private teacher controls, that requires a second screen/device arrangement rather than basic mirroring.

## In class

- **Agenda:** Tap any activity (or Previous / Next) to change the highlighted step. The new activity loads its saved CHAMPS expectations and timer duration.
- **Timer:** Start/pause, add or subtract a minute, add five minutes, or reset. The timer remains accurate if Safari briefly goes into the background.
- **Voice:** Tap 0–4 to change Conversation. Tap individual CHAMPS cards to cycle through Help, Movement, Participation, and Success choices.
- **Focus:** Temporarily hide the agenda and CHAMPS, making the current directions and timer bigger.
- **Setup:** Change class title, subtitle, activities, directions, durations, and CHAMPS expectations. Add, delete, or reorder steps, and show/hide sections.
- **Backups:** Export/import lessons as JSON using the Setup panel.

## Data storage and limitations

- Changes save to the current browser's `localStorage`. No login, no cloud storage, no syncing between devices.
- Export a JSON backup if you want to move a lesson to another browser/device or protect against browser data clearing. Safari private browsing may not preserve changes.
- The voice level is a **displayed expectation**, not an actual microphone volume measurement.
- Timer auto-start on step change is enabled by default; switch it off in Setup if preferred.
- No automatic advance when the timer ends. You decide when the lesson progresses.
- No student or identifying data should be placed in the lesson title, directions or public repository.
- Timers stop visually at 00:00 (they do not count into negative time). The screen does not prevent device auto-lock; set your iPad's Auto-Lock appropriately under school policy.

## Version 2 ideas

Saved named class templates; a lesson library; individually customizable CHAMPS choices; longer instruction cards; quick timer presets; private remote control via second device; customizable layouts; optional sound-level meter; optional sync/backups.
