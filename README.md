# Daegan Layman: writing, research and resume

A static site (plain HTML and CSS) published with GitHub Pages at **https://daegan97.github.io/**
(this repository, `Daegan97.github.io`). The creative-strategy site is a separate repository,
`Daegan97/creative`, served at https://daegan97.github.io/creative/.

Until 2026-10-21 this site lived at `/daeganlayman/` and the creative-strategy site at the root.
`404.html` and the home page forward those old links to their new addresses.

| Page | Address |
|---|---|
| Home | https://daegan97.github.io/ |
| Writing | https://daegan97.github.io/writing/ |
| Research | https://daegan97.github.io/research/ |
| Strategy | https://daegan97.github.io/strategy/ |
| About & resume | https://daegan97.github.io/about/ |
| Resume PDF | https://daegan97.github.io/assets/Daegan_Layman_Resume.pdf |

Each piece has its own address too, e.g. `/writing/scalding-coffee/`.

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
