# IntegoTech Rwanda — Website

Single-page website for IntegoTech Rwanda, the outsourced IT partner for schools,
clinics and small businesses in Kigali and across Rwanda.

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire website — HTML, CSS and JS in one file, no dependencies |
| `logos/` | Drop real client logo images here (see `logos/README.txt`) |
| `.nojekyll` | Stops GitHub Pages from processing the files |

## Publish to GitHub Pages

1. Go to **github.com** → **+** → **New repository** → name it `integotech` → **Public** → **Create**
2. Click **uploading an existing file**
3. Unzip this folder and drag in **everything inside it** (including the hidden `.nojekyll`)
4. Commit the changes
5. **Settings → Pages** → Source: **Deploy from a branch** → `main` + `/ (root)` → **Save**
6. Wait ~2 minutes, then refresh — your live URL appears at the top

Your site will be live at `https://YOURUSERNAME.github.io/integotech/`

> Tip: if hidden files don't appear when dragging, press `Ctrl+H` (Windows) or `Cmd+Shift+.` (Mac).

## Editing the site

Everything you'd normally change is marked with a comment tag. Open `index.html`
in any text editor and search for:

| Search for | Changes |
|---|---|
| `EDIT: COLOURS` | The whole colour palette — one `:root` block |
| `EDIT: MOTTO` | The tagline "Smart Systems · Reliable Cloud · Real Global Reach" |
| `EDIT: BRAND` | Company name and logo mark |
| `EDIT: CONTACT` | Phone, email, address, WhatsApp |
| `EDIT: PACKAGES` | The three support packages |
| `EDIT: PARTNERS` | Client / school logo strip |
| `EDIT: PROFILE` | CV, experience and skill chips |
| `EDIT: STATS` | The four headline numbers |

## Before sharing the link

The phone number `785654811` appears in **four** places — three visible links and
once inside the `sendIt()` function at the bottom of the file. Search and replace
all four if the number changes.
