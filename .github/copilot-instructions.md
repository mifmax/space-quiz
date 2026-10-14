# Project rules

- Keep the quiz self-contained in `index.html`; do not add a server, build step, or external dependency.
- Preserve the existing responsive narrow-column layout and polished visual style.
- Keep interactions accessible: use semantic controls, visible keyboard focus, readable contrast, and status text for feedback.
- Preserve both light and dark themes using `prefers-color-scheme`; keep reduced-motion behavior respected.
- When changing quiz behavior, verify scoring, question progression, answer feedback, results, and restart behavior in the integrated browser.
- Prefer small, focused edits and avoid unrelated refactors.
