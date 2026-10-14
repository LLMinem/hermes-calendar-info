# Hermes Calendar information page

A static homepage and privacy policy for a single-user Calendar integration. The dry humor is intentional. The policy must remain accurate.

- Website: https://llminem.github.io/hermes-calendar-info/
- Privacy: https://llminem.github.io/hermes-calendar-info/#privacy
- Suggested Google authorized domain: `llminem.github.io`. Acceptance in the Google Console is a separate setup check.
- Source: `index.html`, with inline CSS and no client-side scripts, forms, external fonts or analytics.
- Hosting: GitHub Pages from `main`, repository root, HTTPS enforced.

The public repository contains informational website material only. Keep OAuth client files, tokens, calendar content, personal logs and agent configuration outside this repository. `noindex, nofollow` is an indexing request, not access control.

## Update and verify

Edit `index.html`, review the diff and run a secret scan before pushing. Push to `main`, wait for the GitHub Pages deployment to succeed, then retrieve the public URL and compare its bytes with the local HTML. Check desktop and narrow mobile layouts, the privacy anchor, internal links and accessibility with a browser.

The first deployment was checked at 1440×1000 and 390×844. Automated accessibility checks complement, but do not replace, manual inspection.

## Integration status

The site describes intended operation. Publishing it does not authorize Google access or prove the assistant works. Update the deployment wording after live authorization and verification. Before processing Google data through an AI provider, verify the selected provider settings against Google's applicable Limited Use requirements.
