# Wordle Solver 🟩🟨⬛

A blazing-fast, interactive Wordle assistant that calculates the optimal next guess based on tile colors. 

## Features

* **Zero-Lag Calculations:** Filters the candidate pool and calculates letter frequency instantly.
* **100% Client-Side:** Runs entirely in the browser using Vanilla JavaScript with no backend or API required.
* **Interactive UI:** Clickable tiles let you seamlessly toggle through Wordle's gray, yellow, and green states.
* **Dynamic Dictionary:** Powered by a clean `solutions.json` file, making it easy to swap or expand the valid word list.

## Tech Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Hosting:** GitHub Pages
* **Data:** JSON

## How the Algorithm Works

1. **Strict Filtering:** When you submit a guessed word and its color pattern, the engine aggressively filters the remaining candidate pool. It removes any words that don't perfectly align with the known green, yellow, and gray constraints.
2. **Frequency Analysis:** It dynamically recalculates the exact letter frequency across all *remaining* possible solutions.
3. **Smart Ranking:** Words are scored based on how many high-frequency unique letters they contain. The word with the highest score is presented as your optimal next guess to maximize information gain.

## Local Setup

Because this is a static, dependency-free web app, no build tools (like npm or Vite) are needed.

1. Clone the repository:
   ```bash
   git clone [https://github.com/](https://github.com/)[your-username]/wordle-solver.git
