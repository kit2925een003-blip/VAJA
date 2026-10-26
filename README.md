# VaJa — Java Learning in Game Format

A simple-to-medium, responsive website prototype for a college Java project. VaJa teaches Java through short missions, puzzles, XP, ranks, a leaderboard and a team-vs-team Code Battle demo.

## Run it
1. Download or clone this repository.
2. Open `index.html` in Chrome, Edge or Firefox. No installation or build tools are required.
3. Open Missions, answer a question, and press **Check answer**.
4. Open Code Battle and press **Start battle**.
5. XP, cleared missions and battle records save in the same browser with `localStorage`.

## Working features
- Responsive dashboard and navigation.
- Nine Java missions across Basics, Loops, Arrays, OOP and Debugging.
- Multiple-choice answers, explanations, retry after wrong answers, completion and XP rewards.
- Topic filter and basic mission unlock progression.
- Rank progression based on XP.
- Timed three-task Code Battle, score comparison against a simulated rival, win tracking and XP rewards.
- Leaderboard with demo players and your live score.
- Reset progress.
- Browser-based progress persistence.

## Prototype limitations
The Code Battle is a **local demo**, not live online multiplayer. The rival is simulated in the browser. Real multi-user battles need a backend/server and shared match state. The battle currently checks answers to task cards rather than compiling arbitrary Java code. This keeps the prototype simple to run and safe for a college demo.

## Technology
HTML, CSS, JavaScript and browser `localStorage`. Google Fonts are optional styling; the site remains functional without them.

## Publish with GitHub Pages
1. Create a GitHub repository named `VaJa`.
2. Upload `index.html`, `style.css`, `app.js` and `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then save.
5. Wait for GitHub Pages to publish your website.
