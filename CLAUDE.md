# sameerohri.com — notes for Claude

This repo is the public website (GitHub Pages, plain HTML, no build step). The rules for it
live with the code that feeds it: read `~/Developer/NCAAM/CLAUDE.md` ("Where things go" and
the website notes) before changing anything here.

Quick reminders:
- Every page keeps `noindex,nofollow,noarchive`. `robots.txt` allows crawling (Sameer's choice, 2026-11-12), so bots can fetch pages but search engines won't index them.
- Every page has link-preview tags and its own `preview.png` (1200×630).
- Test layouts at phone width; Sameer uses Firefox on Mac and iPhone.
- Data files under `ncaam/*/data/` are written and pushed by the NCAAM pipeline; don't edit
  them by hand.
- Commit only files you changed (never `.claude/`), then push without asking.
