# Luke Morris Fly Fishing

Marketing site for Luke Morris, fly fishing guide based in Aspen, Colorado.

**Live site:** https://a799608.github.io/luke-morris-fly-fishing/

## What this is

A static six-page website hosted on GitHub Pages. No build step, no framework, no
database. Edit the HTML/CSS files directly and push — the site updates within a
minute or two.

## Pages

- `index.html` — Home
- `about.html` — Luke's story (Pennsylvania roots, Penn State, Aspen)
- `trips.html` — Trip types and rates
- `waters.html` — The rivers Luke has fished, PA to CO
- `testimonials.html` — Stylized testimonials (real ones coming as clients send them)
- `contact.html` — Phone, email, Instagram, inquiry checklist

## Things to fill in before serious promotion

Open the pages and search for these placeholders:

- `(XXX) XXX-XXXX` — Luke's actual phone number (appears in header, contact page, tel: links)
- `$XXX` — actual trip rates (trips.html and home page tiles)
- `luke@lukemorrisflyfishing.com` — actual email address
- `lukemorrisflyfishing` — actual Instagram handle (footer and contact page)

## How to edit text

Open any `.html` file in any text editor (Notepad, VS Code, anything). Find the
words you want to change. Type new words. Save. Commit. Push.

```bash
git add -A
git commit -m "Update rates"
git push
```

GitHub Pages will rebuild the live site within ~1 minute.

## How to add real photos

Replace the placeholder stream photos by dropping a new `.jpg` file in the matching
`images/waters-*/` folder, using the same filename. Example: to replace the
Roaring Fork photo, save your photo as `images/waters-co/roaring-fork.jpg`.

For Luke's portrait, place it at `images/luke/luke.jpg` and uncomment / add the
`<img>` tag in `about.html` if you want it shown.

For client catch photos and scenery, drop them in `images/gallery/` — a gallery
page can be added later.

Recommended size: 1200-1600px wide JPEG, ~200-500KB per image.

## Tech notes

- Pure HTML + CSS + a tiny JS file for mobile nav. No frameworks.
- Google Fonts (Playfair Display + Inter) loaded from Google CDN.
- All stream images on Wikimedia Commons. See `ATTRIBUTIONS.md`.
- Hosted free on GitHub Pages.

## Custom domain (later)

When ready to use `lukemorrisflyfishing.com` or similar:

1. Buy the domain (Namecheap, Google Domains, Cloudflare).
2. In repo Settings → Pages, enter the domain.
3. Create a `CNAME` file in the repo root containing just the domain name.
4. Point the domain's DNS at GitHub Pages (CNAME record to `a799608.github.io`).

## Credit

Built as a gift from Will Morris (dad) to Luke. May it bring booked trips and
big browns.
