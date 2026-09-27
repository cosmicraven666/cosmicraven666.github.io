# Hermes V public pages

Static public information pages for Hermes V at `https://cosmicraven666.github.io/` and `https://cosmicraven666.github.io/privacy/`. The site has no build step or installed dependencies.

## Preview

From this directory, run `python3 -m http.server 8000` and visit `http://localhost:8000/` and `http://localhost:8000/privacy/`.

## Before publishing or using the URLs in Google Auth Platform

Review the privacy policy against Hermes V’s actual implementation, especially which Google content remains on the private system, how it is deleted, and which OpenAI service handles submitted content. The policy uses broad wording because those implementation details have not been confirmed. Check the described Google services against the permissions actually requested by the desktop app. Do not add a personal name or email, and do not upload OAuth client files, tokens, credentials, or Google data to this public repository.

## GitHub Pages

In **Settings → Pages**, choose **Deploy from a branch**, then `main` and `/ (root)`. The root `index.html` is the homepage, and `privacy/index.html` serves `/privacy/`. The `.nojekyll` file lets GitHub Pages serve the static files directly.

GitHub's setup steps: <https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site>

## Google Auth Platform

Use the two published URLs as the homepage and privacy policy in Branding, and add `cosmicraven666.github.io` as an authorized domain if Google accepts it. Do not treat Search Console HTML-tag verification of a `github.io` URL-prefix property as a guarantee that Google's OAuth domain verification requirement is met. If Google requires a DNS-verified Domain property, use a domain you own, point it to GitHub Pages, and verify it with DNS. Keep any Search Console verification tag in `index.html` if one is added later.

Google's policy and domain guidance: <https://developers.google.com/terms/api-services-user-data-policy>, <https://support.google.com/cloud/answer/13804266?hl=en>
