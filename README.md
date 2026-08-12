# Damian Job Kahamba — Portfolio

Personal portfolio site for Damian Job Kahamba, public health professional and
laboratory scientist specializing in epidemiology, biostatistics, and quality
management systems.

**Live site:** add your GitHub Pages URL here once enabled (Settings → Pages).

## Structure

```
.
├── index.html              Main site
├── privacypolicy.html      Privacy policy
├── favicon.svg              Site icon
├── css/
│   └── style.css            Single stylesheet, no build step required
├── assets/
│   └── images/
│       └── profile.jpg      Profile photo
├── docs/                    (optional) local copies of CV/resume/certificates
└── .github/workflows/
    └── static.yml            Deploys to GitHub Pages on push to main
```

## Local development

No build step — it's plain HTML/CSS. Open `index.html` directly in a browser,
or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Pushing to `main` triggers `.github/workflows/static.yml`, which deploys the
repository to GitHub Pages. Enable Pages under **Settings → Pages → Source:
GitHub Actions** if it isn't already on.

## To do

- [ ] Move CV, resume, and certificate PDFs from Google Drive into `docs/`
      so they load reliably and don't depend on Drive sharing settings.
- [ ] Point the "Contact" section at a real form backend (e.g. Formspree)
      if a form is wanted in addition to the direct contact links.
- [ ] Add a custom domain under Settings → Pages, if desired.

## License

MIT — see [LICENSE](LICENSE).
