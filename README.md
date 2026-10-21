# Daegan Layman: writing, research and resume

A static site (plain HTML and CSS) published with GitHub Pages at
**https://daegan97.github.io/daeganlayman/**. It's separate from the creative-strategy site at
https://daegan97.github.io/.

| Page | Address |
|---|---|
| Home | https://daegan97.github.io/daeganlayman/ |
| Writing | https://daegan97.github.io/daeganlayman/writing/ |
| Research | https://daegan97.github.io/daeganlayman/research/ |
| Strategy | https://daegan97.github.io/daeganlayman/strategy/ |
| About & resume | https://daegan97.github.io/daeganlayman/about/ |
| Resume PDF | https://daegan97.github.io/daeganlayman/assets/Daegan_Layman_Resume.pdf |

Each piece has its own address too, e.g. `/daeganlayman/writing/scalding-coffee/`.

## Viewing it locally

Open `index.html` from this folder. All links work straight from disk. (The not-found page,
`404.html`, uses site-wide addresses and only works once published.)

## Updating

The pages are generated from source text by `site-build\build.py` in the Job Search folder,
which lives outside this repository.

1. From the Job Search folder, run `python site-build\build.py site`.
2. If the resume changed, re-print `site-build\resume-print.html` to
   `site\assets\Daegan_Layman_Resume.pdf` (Edge: `--headless --print-to-pdf`).
3. From this folder, run `git add -A`, then `git commit -m "Update"`, then `git push`.
   GitHub Pages refreshes within a couple of minutes.

## Notes

- The public resume shows email only (no phone) and years only. The exact month dates are kept
  in `site-build\build.py` for application forms.
- The pet-loss hotline ad is copy only, with no institution name, logo, phone number or image,
  and carries the spec-work label. Keep it that way.
- Typo fixes made to the pieces are listed in `..\portfolio\site-copyedits.md`.
