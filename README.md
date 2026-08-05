# Janak Neupane — Portfolio Website

A static, single-page portfolio site (HTML/CSS only, no build step). Open
`index.html` directly in a browser, or deploy the whole folder to any static
host (GitHub Pages, Netlify, Vercel, etc.).

## Folder structure

```
janak-neupane-portfolio/
├── index.html                 ← the whole site (HTML + CSS)
├── README.md                  ← this file
└── assets/
    ├── cv/
    │   └── Janak_Neupane_CV.pdf   ← placeholder CV (replace me)
    └── images/
        └── profile.png            ← placeholder headshot (replace me)
```

## Replacing sample files

| Replace this file | With | Recommended size |
|---|---|---|
| `assets/images/profile.png` | Your headshot | Square, ~500×500px+ |
| `assets/cv/Janak_Neupane_CV.pdf` | Your actual CV/resume | Any (PDF) |

Just overwrite the file with the same filename — `index.html` already
points to these exact paths, so no code changes are needed.

## Contact form (Formspree)

The contact form at the bottom of the page submits to your Formspree
endpoint:

```
https://formspree.io/f/xqergpzv
```

Submissions are delivered to whichever inbox you registered with Formspree
(currently set up for janakneupane999@gmail.com). A few notes:

- The first submission from a new form triggers a one-time confirmation
  email from Formspree — you must confirm it before messages start
  arriving normally.
- A hidden `_gotcha` field is included as a honeypot to cut down on spam
  bots; leave it in place.
- The `_subject` field lets you control the subject line of the email you
  receive; it's pre-filled from the "Subject" input on the form.
- Free Formspree plans have a monthly submission cap — check your
  Formspree dashboard if you expect high volume.

## Content included

The page content (About, Experience, Education, Trainings, Publications,
Contact) is pulled directly from your supplied information:

- **Experience:** Mechanical Supervisor (DoTM, Nepal Government),
  Mechatronics Instructor (BSET/CTEVT), Mechanical Engineer (Trishna Hydro),
  and three training placements (Kaligandaki "A" Hydropower, Kaligandaki
  Fish Hatchery, New Shiv Service Centre).
- **Education:** MSc Renewable Energy Engineering (2026), BE Mechanical
  (2018), +2 Science (2014), SLC (2012) — all IOE/Tribhuvan University and
  earlier schools.
- **Trainings:** 9 professional development trainings/certifications listed
  in a card grid.
- **Publications:** "Comparative Analysis of Bieri Vertical and
  Conventional Sediment Flushing..." with a link to the full paper.
- **Contact:** phone, email, address, Facebook, LinkedIn, plus floating
  WhatsApp and Messenger buttons (bottom-right corner of every page).

The "Key Accomplishments" section from your original file was left out
because it was commented out (disabled) in the source you provided. If
you'd like it added back in, send the content and I'll wire it into an
"Achievements" section matching the same style.

## Notes

- All colors and fonts (Playfair Display + Lora headings, navy/teal
  palette) live in the `<style>` block at the top of `index.html` — edit
  the `:root` CSS variables to retheme the whole site at once.
- The dark-mode icon (🌙) in the nav is currently decorative; wire it up
  with a small JS snippet if you want an actual light/dark toggle.
