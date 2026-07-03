# Ishwari Suryawanshi — Portfolio

A one-page portfolio site: About, Skills, Experience, Work, Education and Contact.
Plain HTML/CSS/JS — no build step, so it works directly on GitHub Pages.

## Files
```
index.html          → the page
style.css            → all styling
script.js            → small interactions (menu, scroll reveal)
assets/images/       → your work samples
```

## 1. Put this on GitHub

1. Go to [github.com](https://github.com) → sign in → click the **+** (top right) → **New repository**.
2. Name it exactly: `ishwari-portfolio` (or anything you like — just remember it).
3. Keep it **Public**, don't add a README/gitignore (you already have one), click **Create repository**.
4. On the next page, click **uploading an existing file**.
5. Drag in `index.html`, `style.css`, `script.js`, and the whole `assets` folder (keep the folder structure).
6. Scroll down, click **Commit changes**.

## 2. Turn on GitHub Pages

1. In your repo, go to **Settings** → **Pages** (left sidebar).
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Branch: `main`, folder: `/ (root)` → **Save**.
4. Wait ~1 minute, refresh the page. You'll see a green box with your live link:
   `https://<your-username>.github.io/ishwari-portfolio/`

That link is what you share with recruiters — put it in your resume, LinkedIn and email signature.

## 3. Things to personalize before sharing

Search the files for these and update them:

- **Start date at ServerSage CloudTech** — `index.html`, in the Experience section (currently a placeholder "2024 — Present").
- **LinkedIn URL** — in the Contact section, replace the "Add your LinkedIn URL here" link.
- **Phone number visibility** — it's currently shown in Contact; remove the `tel:` link if you'd rather keep it private and only show email.

## 4. Add your social media & video work

The "Social Media & Video" row currently has placeholder tiles. To replace one:

1. Add your image/thumbnail file into `assets/images/` (e.g. `social-1.jpg`).
2. In `index.html`, find the `work-placeholder` block and swap it for a `work-card` block like the ones above it — copy one of the existing `<figure class="work-card">...</figure>` blocks, point the `src`/`href` at your new file, and update the caption text.

## 5. A privacy note on the ID card sample

The employee ID card image has the phone/email/ID number blanked out on purpose — ID badges are usually
internal-only, unlike visiting cards and brochures which are made for public handout. If you'd like to swap
in a different sample (e.g. a mockup with placeholder info instead of a real colleague's), that's an easy edit —
just replace `assets/images/idcard-1-safe.png`.

## Updating later

Any time you want to change text, open `index.html` in a text editor (even GitHub's own web editor — click
the pencil icon on the file) — no coding tools needed for text changes.
