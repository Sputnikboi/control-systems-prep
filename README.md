# Control Systems — Exam Prep

Interactive study tool for a control-systems course (Reguleringsteknik). Each
lecture's test is available with progressive hints and full worked solutions,
plus math crash courses with randomized drills and a scratch whiteboard.

**Live site:** https://sputnikboi.github.io/control-systems-prep/

## Contents

- **Lessons hub** — pick any lecture (1–12); per-question progress is saved on the device.
  - Lessons 1–8, 10–12 follow the official tests.
  - Lesson 9 was an *exercise* sheet, so it ships a custom, by-hand test on the same themes (controllability + state-feedback pole placement).
  - Computational questions get step-by-step solutions; figure-based ones (Bode / Nyquist / root-locus / pole plots) get worked explanations of how to read/draw them — keep the original PDF alongside for the figures.
- **Crash courses** — matrix multiplication, determinant & rank of 2×2, eigenvalues of 2×2; each with a randomized practice generator.
- **Whiteboard** (`whiteboard.html`) — pen/eraser, colors, grid, undo/redo, save-to-PNG. Standalone page, good for a second monitor; also linked from the nav.

Everything is static, self-contained HTML — no build step, no dependencies.
Open the files directly or serve the folder.

## Files
- `index.html` — the lessons hub + crash courses (single-page app).
- `whiteboard.html` — the whiteboard.
