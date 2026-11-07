# MAMIXcite isolated staging SEO E2E fixture

This public GitHub Pages site intentionally omits title, description, canonical, viewport, and `lang` tags so MAMIXcite's **staging-only** SEO workflow can demonstrate detected findings, reviewed branch-only fixes, and rollback. It is not a production MAMIXcite site and contains no personal or customer data.

The one-line `/.well-known/mamixcite-domain-verification.txt` ownership challenge will be added only after staging issues an actual token. Never include credentials or API secrets. `robots.txt` permits the bounded MAMIXcite crawler, while the page declares `noindex,nofollow` to discourage indexing.

Nothing in the MAMIXcite production application is deployed from this repository.
