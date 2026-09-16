# Archived-project pin review evidence

Issue: https://github.com/apache/maka/issues/5398

Synthetic task/project names rendered in Chromium through the production SessionRail, SessionListPanel, and project grouping function, with the production theme and CSS. Each capture is a reachable sidebar state; the fixture is a review aid.

- before.png: origin/main at c87651e23d; By project hides two pins inside an archived project.
- after.png: proposed fix; the same two pins remain in the top-level Pinned section.
- after-expanded.png: expanding Archived projects reveals only the unpinned task, with no duplicate pins.

The capture also switches both implementations to By time and checks that both pins are visible. No user task content or local paths are included.

Generated-by: OpenAI Codex
