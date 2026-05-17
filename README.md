# album-journal

my personal album tracker. paste a netease/qq music link, add the tracklist, star the good tracks, rank it in a tier list. that's it.

live at: `https://your-name.github.io/album-journal`

---

## how it works

single html file hosted on github pages. album data gets auto-saved to a separate private repo as a json file every time you make a change. works across devices as long as you set up the token on each one.

no frameworks, no backend, no accounts.

---

## setup

**1. enable github pages**

push `index.html` to this repo, then go to Settings → Pages → Deploy from branch → main → Save.

**2. create a private repo for your data**

just call it `album-data` or whatever. can be empty.

**3. make a personal access token**

GitHub → Settings → Developer settings → Fine-grained tokens → Generate new token

- repository access: `album-data` only
- permissions → contents: **read and write**

**4. open the app and connect**

first visit auto-opens the setup screen. fill in your token, username, repo name, and hit save. repeat on each device you want to use.

---

## tiers

T0 → T1 → T2 → T3 → T4 → T5 → Trash
