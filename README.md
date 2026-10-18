# Therma public pages

The source of <https://iterloopdev.github.io/therma-legal/>: the support page, privacy policy and terms of service that the Therma app and its store listings link to. GitHub Pages builds the site from this repository's `main` branch.

| Page | File | URL |
|---|---|---|
| Support | `index.md` | `/therma-legal/` |
| Privacy Policy | `privacy.md` | `/therma-legal/privacy` |
| Terms of Service | `terms.md` | `/therma-legal/terms` |

The app links to `/privacy` and `/terms`, so never rename or move those pages.

## Updating the policy or terms

The privacy policy and terms are maintained in the app repository, in `docs/compliance/privacy-policy.md` and `docs/compliance/terms-of-service.md`. To publish a change:

1. Update the document there (with its "Last updated" date) and merge it.
2. Here, replace everything below the front matter (the block between the `---` lines) in `privacy.md` or `terms.md` with the new text.
3. Commit and push to `main`. The site updates within a few minutes.
