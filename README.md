# Ninety Night public pages

Standalone GitHub Pages site for the Ninety Night iPhone app.

The site contains:

- `/` — public landing page
- `/support/` — support guidance and public GitHub issue link
- `/privacy/` — privacy policy
- `/legal/` — terms and product information

## GitHub Pages

Publish the `main` branch from its repository root. The checked-in `CNAME` file configures the custom domain `ninetynight.app`. If the repository is published at a project URL before the custom domain is active, the relative links still work.

The site is deliberately build-free: it is plain HTML and CSS and can be previewed with:

    python3 -m http.server 8080

Before launch, review the policy against the production App Store, AdMob/UMP, TelemetryDeck, and GitHub configuration. Public support issues should never contain sleep, health, payment, or other sensitive information.
