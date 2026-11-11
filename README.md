# Pocket Pulls Stripe TEST callbacks

Two isolated static pages for Stripe TEST-mode onboarding:

- `return/` — shown after onboarding returns.
- `refresh/` — shown when the hosted session expires.

These pages are intentionally inert:

- no JavaScript
- no forms
- no links
- no images or external assets
- no cookies
- no API calls
- no credentials
- no database access

They cannot update Pocket Pulls seller data, call Stripe, or trigger transfers, payouts, or settlement.
