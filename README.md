# OddPebble Automation public information

Static application information, privacy policy, terms and contact routes for the owner-only OddPebble Automation application. This public repository contains no OAuth credentials, tokens, videos, private upload receipts or executable automation. The private automation stays in its separate private repository.

## Verified hosting and brand identity

GitHub account and Pages migration completed on **8 November 2026**. The account name is `oddpebble`, the display name is **OddPebble**, and this existing repository is now `oddpebble/oddpebble.github.io`.

The following HTTPS routes were verified at **11:40:02 UTC** after Pages reported `built` with HTTPS enforced:

- https://oddpebble.github.io/
- https://oddpebble.github.io/privacy/
- https://oddpebble.github.io/terms/
- https://oddpebble.github.io/contact/

Assets and navigation use relative links. The former Pages host is not assumed to redirect; use the verified branded addresses above.

The repository kept its stable ID `1448747472`. The current deployment can also be resolved without depending on an account-name string:

```sh
gh api repositories/1448747472/pages --jq .html_url
```

Pages metadata endpoint: https://api.github.com/repositories/1448747472/pages

Contact navigation uses `/contact/` and the branded OddPebble YouTube channel. No unverified email address or private support inbox is advertised.

## Remaining Google account settings

The account owner must separately update Google OAuth Branding homepage, privacy, terms and authorized-domain settings to the verified host above. The application display name should be **OddPebble**. Any support/developer contact email must be a genuinely owned and verified address or appropriate group; no replacement address is invented here. These Google settings have not been independently verified by this site deployment.

The GitHub rename does not itself require replacing an existing OAuth client or token. Google Cloud project ID remains `oddpebble-youtube`.

## Historical scope

Current source content is cleaned. Git history, earlier Actions logs, previous downloaded copies and past chat messages were not rewritten or erased by this migration. No paid domain, subscription or API credit was opened.
