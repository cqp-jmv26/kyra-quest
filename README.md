# Kyra's Secret Quest 🚗🎸

An 8-bit road-trip riddle game (Santa Barbara → Inglewood) that reveals a secret concert, one clue at a time.

## Before you send it
Open `index.html` and edit the `CONFIG` block at the top of the `<script>`:
- `time`: the show time from the ticket
- `section`, `row`, `seat`: the seat details from the ticket

## Publish on GitHub Pages (free)
1. Create a new repo on github.com (e.g. `kyra-quest`). If you make it **private**, Pages needs a paid plan, so a public repo is the free option. Give it a name that won't give the surprise away.
2. Upload `index.html` (and this README) to the repo root.
3. Repo → **Settings → Pages** → Source: *Deploy from a branch* → Branch `main`, folder `/ (root)` → Save.
4. After about a minute, the site is live at `https://<your-username>.github.io/kyra-quest/`.

## Notes
- Progress is saved on her phone, so she can close Safari and pick up where she left off.
- Sound plays after she taps PRESS START (the iPhone silent switch mutes it).
- **RESET** link at the bottom clears progress (use it after you test!).
- Answers are in the page source, so a determined snooper could peek.
