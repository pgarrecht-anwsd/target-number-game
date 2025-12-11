# Target Number Game

Single-file static web app for classroom use (Chromebooks friendly).

## How to use

1. Download the files and upload them to your GitHub repository (or district server).
2. Enable GitHub Pages for the repository (Settings → Pages → select branch `main` / `root`). The site will be available at `https://<your-username>.github.io/<repo>/`.
3. Share that URL with students in Google Classroom.

## Files provided
- `index.html` — single-file web app. No other assets required.
- This README.

## Hosting locally on a Chromebook
- Unzip the files.
- Open the Files app, double-click `index.html` and choose Chrome to open the file. (If your Chromebook/IT blocks local file opening, hosting via GitHub Pages or district server is recommended.)

## Game rules implemented
- You may choose 3 or 4 numbers and a max number (50 easy or 99 full).
- Students click a number, then an operation, then another number. Intermediate results must be whole numbers (integer). Negative intermediate results are allowed.
- Division is only allowed when it divides evenly.
- Hints reveal solution steps incrementally. Scoring: 0 hints = 100, 1 hint = 80, 2 hints = 60, 3 hints = 0.
- Default game length is 16 problems.

## Notes for IT / teachers
- The app is a static HTML file and requires only a web server to host.
- Audio uses WebAudio API and will play only after user interaction due to browser autoplay rules.

