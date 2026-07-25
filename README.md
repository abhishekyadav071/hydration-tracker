@"
# Hydration Tracker - The Glass IS the Progress Bar

A daily water-intake tracker where the glass itself acts as the progress indicator - no separate progress bar, no external libraries. Built with pure HTML, CSS, and vanilla JavaScript.

## Live Demo
Open ``index.html`` in any browser, or enable GitHub Pages on this repo (Settings -> Pages -> Deploy from ``main`` branch) to get a live link.

## Features

- Glass = progress bar - water level rises as you log glasses, no redundant UI
- Realistic water animation - dual-layer CSS wave animation + rising bubbles
- Goal celebration - glass shifts from blue to gold when the daily goal (8 glasses) is hit
- Weekly streak strip - quick visual of the past 7 days
- Semantic, accessible HTML: meter, data, mark, output tags, aria-live status updates, reduced-motion support

## Tech Stack

- HTML5 (semantic tags: main, header, section, footer, figure, meter, data, output, mark, progress)
- CSS3 (clip-path, custom properties, glassmorphism, keyframe animations)
- Vanilla JavaScript (no frameworks, no dependencies)

## Author

Abhishek Yadav
Full Stack MERN Developer
[GitHub](https://github.com/abhishekyadav071)

## License

MIT - free to use, modify, and share.
"@ | Out-File -FilePath README.md -Encoding utf8
