# Beetle Eyes Clothing — Brand Site

Brand-awareness site for Beetle Eyes Clothing, operating inside Curious Magpie at 9 Market Place, Mountsorrel.

## Files

```
beetle-eyes/
├── index.html
├── img/
│   ├── logo.png            # blackletter wordmark, transparent BG (black)
│   ├── logo-cream.png      # cream version for dark backgrounds (footer)
│   ├── logo-maroon.png     # maroon variant (spare)
│   ├── corrine.jpg         # portrait of Corrine
│   ├── shopfront.jpg       # mustard yellow shopfront
│   ├── window-display.jpg  # window: orange dress, red boots, cranes
│   ├── interior-1.jpg      # plants & zines table
│   ├── interior-2.jpg      # tulips & ceramics interior
│   └── rail.jpg            # clothing rail closeup
└── README.md
```

## Running it

Open `index.html` in a browser, or drop the whole folder onto Netlify Drop / GitHub Pages / any static host.

For local preview:
```bash
cd beetle-eyes
python3 -m http.server 8080
# open http://localhost:8080
```

## Sections

1. Hero — collage of shopfront + window display, with rose No. 9 stamp
2. Marquee — scrolling tape of vintage-shop keywords
3. About Corrine — portrait + stylist's-eye copy
4. Wares — what's on Beetle Eyes' rails (deep beetle green)
5. Inside — gallery of 5 shop photos (asymmetric bento)
6. The shop — Curious Magpie (host shop, homewares/books/candles)
7. Visit — address, hours, map
8. Footer

## Mobile

Full burger menu — slides open into a beetle-green overlay with large Fraunces serif menu items, italic rose numbers, and contact details in the foot. ESC closes it. Body scroll locks while open.

## Palette

- `--paper #f4ede0` — cream background
- `--maroon #5a3a32` — deep warm brown (body, hover background)
- `--mustard #d4a04a` — kept in CSS variables but no longer used visually (was the shopfront-sign yellow; replaced with rose)
- `--beetle #1f3a2e` — deep green (wares, footer, mobile menu)
- `--rose #b87a82` — dusty rose (primary accent — italic emphasis, section numbers, hover states, FIND US button)
- `--rose-2 #9d626b` — deeper rose (hover/pressed)
- `--rose-soft #e0c4c7` — feather-soft rose (underlines, address stamp, magpie tag)
- `--ink #1c1d18` — body text

## Things to verify before launch

- Opening hours (currently Tue–Sat 10–4, Mon/Sun closed — guessed)
- Google Maps pin location
- Instagram handles: `@beetleeyesclothing` and `@corrinekaenzigstylist`
