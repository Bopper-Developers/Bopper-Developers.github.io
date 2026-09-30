# Bopper Finance public pages

GitHub Pages serves this repository at https://bopper-developers.github.io/.
Google OAuth uses `index.html` as the homepage and `privacy.html` as the privacy policy.

Keep the `google-site-verification` meta tag in `index.html`: Google Search Console uses it to verify control of the homepage. The Google OAuth callback is handled by the Finance Supabase Edge Function in `bopper-hub`; no credentials belong in this repository.
