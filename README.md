# Digital Exposure Calculator (Weekly)

A simple, static website that estimates your **weekly** exposure to:
- **Time online**
- **Ads seen (range)**
- **Sponsored persuasion (range)**
- **Tracking events (range)**
- **Attention Tax Score (0–100)**

It also includes a **Save & Compare** feature that stores your last saved week locally in your browser (no accounts, no backend).

## Live Site (GitHub Pages)
After you enable GitHub Pages (Settings → Pages), your site will be available at:

`https://YOURUSERNAME.github.io/digital-exposure-calculator/`

## Files
- `index.html` — The calculator + Save & Compare (localStorage)
- `about.html` — About page (AdSense-friendly)
- `privacy.html` — Privacy policy (AdSense-friendly)
- `contact.html` — Contact page (replace the placeholder email)
- `README.md` — This file

## How it works (high level)
You enter your usage from the last 7 days (daily average or weekly totals). The calculator applies conservative **per-hour ranges** for:
- ads/hour by category (social, video, browsing)
- tracking events/hour by category

Outputs are shown as **ranges** to avoid fake precision.

## Data & Privacy
- The calculator runs entirely in your browser.
- If you click **Save this week**, the site stores a summary locally using `localStorage`.
- No user accounts and no server-side storage.

## Deploy for free on GitHub Pages
1. Create a GitHub repo named `digital-exposure-calculator` (public).
2. Upload the files in this project.
3. Go to **Settings → Pages**
4. Under “Build and deployment”:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
5. Save — GitHub will provide your public URL.

## AdSense (optional)
When approved for Google AdSense, paste your AdSense snippet into `index.html` at the marked **AdSense insertion point** comment.

Before applying, make sure:
- About / Privacy / Contact pages are live
- Your contact email in `contact.html` is updated


---

**Disclaimer:** This tool provides informational estimates only and does not provide legal, medical, or financial advice.
