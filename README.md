# Auto Wordle Guesser 🟩🟨⬛

A completely automated, 100% client-side Wordle solver. Let the computer do the thinking.

## How It Works
1. The app starts by suggesting the mathematically optimal word: **SALET**.
2. Type that word into the real Wordle game.
3. Tap the tiles in this app to match the gray/yellow/green colors Wordle gave you.
4. Click **Generate Next Guess**. 
5. The algorithm filters a 14,000+ word dictionary and calculates the highest frequency letters to provide the optimal next move.

## Features
* **Zero Configuration:** Automatically downloads the official 14,000-word Wordle dictionaries on load. No JSON files required in the repository.
* **Flawless Logic:** Accurately mimics Wordle's double-letter and partial-match algorithms using forward-pattern matching.
* **Static Hosting:** Built with pure HTML/CSS/JS. Deployable to GitHub Pages in seconds with zero build steps.
