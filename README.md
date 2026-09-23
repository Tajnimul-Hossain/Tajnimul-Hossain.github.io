# Tajnimul Hossain — Portfolio (single-file, GitHub-editable)

Everything is in **one `index.html`** (styles and scripts inlined), plus an `assets/` folder for
images. No build step, no compiler. You edit the HTML directly on GitHub, commit, and the live site
updates on its own.

## Files

```
site/
├── index.html      # the whole site: edit text/structure here
└── assets/
    ├── profile.jpg              # hero portrait  (replace, keep the name)
    ├── project-drone-swarm.jpg  # Project 01 image
    ├── project-formation.jpg    # Project 02 image
    └── project-uav.jpg          # Project 03 image
```

## Launch on GitHub Pages (one time)

1. Create a repo named exactly `yourusername.github.io` and set it **Public**.
2. Click **Add file, then Upload files**. Drag in `index.html` **and** the `assets` folder, then
   **Commit changes**. (`index.html` must sit at the repo root.)
3. Go to **Settings, then Pages**. Under Source pick **Deploy from a branch**, branch `main`,
   folder `/ (root)`, then **Save**.
4. Open `https://yourusername.github.io`. The first build takes a few minutes.

## Edit later, entirely on GitHub

1. Open `index.html` in your repo and click the **pencil (Edit)** icon.
2. Change the text you want (see the list below), scroll down, **Commit changes**.
3. The site rebuilds automatically in a minute or two. Refresh to see it.

To swap an image: open the `assets` folder on GitHub, **Add file, then Upload files**, and upload a
new picture with the **same filename** as the one you are replacing.

## What to personalise (search inside `index.html`)

- `your.email@example.com` — your email (hero button target and Contact).
- the LinkedIn / GitHub links — replace `#` and the bare `github.com` URLs.
- `assets/profile.jpg` — your real portrait.
- the three `assets/project-*.jpg` — real screenshots or a simulation still.
- the **Publications** block — add a real entry, or delete the block until you have one.
- the `og:url` / `og:image` lines near the top — set your real address once the site is live.

## Notes

- Fully responsive, keyboard-accessible, respects reduced-motion.
- The only thing loaded from the internet is the Google Fonts stylesheet; everything else is local.
