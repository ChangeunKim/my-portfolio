# My Portfolio

Korean CV and project portfolio artifacts for Kim Changeun.

Portfolio: <https://changeunkim.github.io/my-portfolio/>

## Main outputs

- `output/online_cv/index.html`: vertical CV layout based on `online-cv`.
- `output/startbootstrap_resume/index.html`: portfolio site based on Start Bootstrap Resume.

The profile image is embedded directly in `output/online_cv/index.html`, so the CV can be shared as a single HTML file. An internet connection is still required for its Google Fonts and Font Awesome assets.

## Deployment

GitHub Pages is deployed from `main` through `.github/workflows/pages.yml`. A push to `main` that changes `output/startbootstrap_resume/**` automatically publishes that directory to the portfolio URL above.

## Notes

- `reference/` is intentionally ignored because it contains private source materials.
- `vendor/` is intentionally ignored because external templates are cloned locally only for adaptation.
- Template license/attribution files used by generated outputs are included under `output/`.
