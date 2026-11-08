# OddPebble Automation public information

Static application information, privacy policy, terms and contact routes for the owner-only OddPebble Automation application. This public repository contains no OAuth credentials, tokens, videos, private upload receipts or executable automation. The private automation stays in its separate private repository.

## Hosting and account-name migration

The site uses GitHub Pages. Its paths are `/`, `/privacy/`, `/terms/` and `/contact/`; assets and navigation use relative links.

The intended branded host is `oddpebble.github.io`. This is a **migration target**, not a claim that this hostname is already live or owned by the operator. The account owner must complete the GitHub username change and the user-site repository must then be named `oddpebble.github.io`. Pages deployment and HTTPS must be verified after the real rename. Do not replace a live host with an unverified destination.

The current Pages deployment can be resolved without embedding a personal username using the stable public repository ID:

```sh
gh api repositories/1448747472/pages --jq .html_url
```

Pages metadata endpoint: https://api.github.com/repositories/1448747472/pages

Contact navigation uses `/contact/` and the branded OddPebble YouTube channel. No unverified email address or private support inbox is advertised. Google OAuth Branding homepage, privacy, terms and authorized-domain settings must be updated separately after the new host is verified.
