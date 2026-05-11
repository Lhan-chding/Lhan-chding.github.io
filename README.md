# Personal Academic Homepage

Personal academic homepage for OpenReview / ARR profile verification.

This repository is designed to be deployed directly from the `main` branch root directory with GitHub Pages. It uses only static HTML and CSS, with no build tools, external fonts, scripts, analytics, or third-party tracking.

## Replace Placeholders

Before publishing, replace these placeholders in `index.html`:

- `<YOUR_ENGLISH_NAME>`
- `<YOUR_EMAIL>`
- `<YOUR_AFFILIATION>`
- `<YOUR_CITY_OR_COUNTRY>`
- `<YOUR_ORCID_URL_OR_EMPTY>`
- `<YOUR_GOOGLE_SCHOLAR_URL_OR_EMPTY>`
- `<YOUR_GITHUB_URL_OR_EMPTY>`
- `<YOUR_OPENREVIEW_PROFILE_URL_OR_EMPTY>`

The visible placeholders in `index.html` are HTML-escaped as `&lt;YOUR_ENGLISH_NAME&gt;`, `&lt;YOUR_EMAIL&gt;`, and similar values so that they display correctly in a browser. Replace the displayed values with your real information.

For optional links such as ORCID, GitHub, Google Scholar, and OpenReview, only uncomment and publish a link after replacing the placeholder with a real URL. Do not publish empty or fake profile links.

## GitHub Pages Deployment

1. Create a repository named `<github_username>.github.io`.
2. Upload `index.html`, `styles.css`, `README.md`, and `.gitignore` to the repository root.
3. Open the repository on GitHub and go to Settings &rarr; Pages.
4. Set Source to `Deploy from a branch`.
5. Set Branch to `main` and folder to `/ (root)`.
6. Save, then visit `https://<github_username>.github.io/`.

## Checklist

- The page opens in a browser.
- The page header shows the name.
- The page header shows the email address.
- The Contact section shows the email address.
- There are no false publication claims.
- There is no exposed sensitive personal information such as phone number, home address, national ID, WeChat, or QQ.
