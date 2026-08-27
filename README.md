# Benovrix Global Groups — Website

A single-page website for **Benovrix Global Groups**, built with plain HTML/CSS/JS — no build tools, no dependencies, no backend required.

## What's inside

- `benovrix-global-groups.html` — the entire website (structure, styling, and scripts all in one file)

Sections included: home slider, business verticals (services), global presence, and a contact / get-a-quote form.

## Publish it on GitHub Pages (free hosting)

1. **Create a repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it anything (e.g. `benovrix-website`)
   - Keep it **Public** (required for free GitHub Pages)
   - Click **Create repository**

2. **Add the file**
   - Rename `benovrix-global-groups.html` to **`index.html`** — GitHub Pages looks for this filename by default
   - On the repo page, click **Add file → Upload files**
   - Drag in `index.html`
   - Click **Commit changes**

3. **Turn on GitHub Pages**
   - In the repo, go to **Settings → Pages**
   - Under **Build and deployment → Source**, choose **Deploy from a branch**
   - Branch: `main`, Folder: `/ (root)` → **Save**

4. **Visit your site**
   - GitHub will show a link like:
     `https://<your-username>.github.io/<repo-name>/`
   - It usually goes live within 1–2 minutes. Refresh if it doesn't load immediately.

## Using a custom domain (optional)

If you want the site at `www.benrovixglobalgroups.com` (or your correct domain) instead of the github.io link:

1. In **Settings → Pages → Custom domain**, enter your domain and save
2. At your domain registrar, add a `CNAME` record pointing to `<your-username>.github.io`
3. Wait for DNS to propagate (can take up to 24 hours), then enable **Enforce HTTPS** in the same Pages settings once it's available

## Making edits later

The whole site is one HTML file, so any text, contact detail, or service can be edited directly by opening `index.html` in a text editor (or via GitHub's built-in editor — click the pencil icon on the file). After saving, GitHub Pages automatically redeploys the updated version within a minute or two.

## Before going live — please double-check

- The brand name reads **"Benovrix"** but the email/website use **"benrovixglobalgroups.com"** — confirm which spelling is correct and update both consistently.
- The quote form currently opens the visitor's email client (`mailto:`) rather than submitting to a server — this works without any backend, but if you'd like a proper submission form that emails you automatically, a service like Formspree or a small backend would be needed.
