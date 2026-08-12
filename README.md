# Damian Job Kahamba — Portfolio

Personal portfolio site for Damian Job Kahamba — public health professional,
founder, and data analyst offering services in cancer genomics analysis,
public health analytics, web development, and QMS consulting for medical
laboratories.

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

## Outstanding — links to wire in

Two links are placeholders in the current build (search `pending` in
`index.html`):

- [ ] Wilberforce Technologies company website — About section
- [ ] QualiTracker LinkedIn — Contact section

## To do

- [ ] Move CV, resume, and project/certificate PDFs from Google Drive into
      `docs/` so they load reliably and don't depend on Drive sharing settings.

## License

MIT — see [LICENSE](LICENSE).
