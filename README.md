# Thinker Arcade

A single-file, arcade-cabinet-themed web app for a research + writing sprint game: pull a lever to get a random philosopher, thinker, or author, research them for 5 minutes, then write about them for 5 minutes — no notes allowed.

## How to use it

1. Open `index.html` in any modern browser (double-click the file, or drag it into a browser window). No install, server, or internet connection required.
2. Click **PULL LEVER**. The reel spins through random names with an arcade tick sound and lands on your pick with a chime.
3. Click **START 5:00** in the Research panel. Look up your name — era, core ideas, one famous work, one thing they're remembered for.
4. When the research timer hits zero (or you click **SKIP TO WRITING**), the Writing panel unlocks. Click **START 5:00** there.
5. Write about the thinker from memory in the text box until the timer runs out. A word counter tracks your progress as you type.
6. Click **INSERT COIN — PLAY AGAIN** to reset and pull a new name.

## Features

- **Slot-machine reel** with a decelerating spin animation and a pool of ~70 philosophers, thinkers, and authors spanning different eras and traditions.
- **Arcade sound effects** — shuffle ticks, a landing chime, and a round-end buzzer — generated live with the Web Audio API, so no external audio files are needed.
- **Two built-in timers** (5:00 research, 5:00 writing) with pause/resume, a progress bar, and a color change when time is running low.
- **Skip to writing** if you finish research early.
- **Live word count** while writing.
- Fully responsive and works offline once the file is downloaded (aside from loading the Google Fonts used for the pixel/marquee styling).

## LICENSE
This Project is under MIT License
