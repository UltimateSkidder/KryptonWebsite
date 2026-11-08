# Krypton Website

Landing page for the Krypton client, hosted on GitHub Pages.

**Live site:** https://ultimateskidder.github.io/KryptonWebsite/

Everything lives in `index.html` (one file: HTML + CSS + JS). Edit it on GitHub
(pencil icon) or locally, commit, and the site redeploys in ~1 minute.

## Things you'll want to edit

| What | Where |
|------|-------|
| **The download file** | Replace `downloads/Krypton.jar` with your new build (keep the same name and the button keeps working). To point at an external link instead, change the `href` on the `id="dlBtn"` link in `index.html`. |
| **Discord link** | In `index.html`, search for `Join Discord` and set the `href="#"` to your invite. |
| **Logo** | Replace `assets/logo.svg` (or drop a `logo.png` and update the four `assets/logo.svg` references). |
| **Headline / text / FAQ** | All plain text inside `index.html` — search for the words and change them. |
| **Stats numbers** | In the hero, the `data-count` values on the `.stat` elements. |

## Notes

- The download button checks whether the file exists first; if it's ever missing
  it shows a "not up yet" note instead of a broken link.
- Static site only — no server code runs here.
