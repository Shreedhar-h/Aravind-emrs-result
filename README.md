# EMRS Result Manager

Result-sheet manager for Eklavya Model Residential School, Bandalli.
Single-file web app (`index.html`) — no build step, no server.

## Hosting on GitHub Pages
1. Upload `index.html` (and this README) to the repository root.
2. Settings → Pages → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
3. The site goes live at `https://<username>.github.io/<repo>/` in a minute or two.

## Notes
- Sign-in is required to open the page (ask the owner for the username/password).
- Data is saved in the browser of each device (localStorage). Use *Download Excel* / *Download PDF* for copies you want to keep or share.
- To change the password, edit the `GATE` line near the end of `index.html` with a new SHA-256 hash.
