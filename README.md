# Soundclaim Artist Portal

Artist-facing portal for Soundclaim — built by Agency 5.

Allows registered artists to view their CMO registration status, catalogue, financials (CMO collections + distributor income breakdown), pending actions, Contract Compass analysis, and messages from their consultant.

## Access

Artists sign in with their own Supabase Auth login, linked to their artist record via `artist_portal_users`. There are no demo accounts.

## Tech

Single-file React app (`index.html`) — no build step required. Runs in any modern browser.

## Related

- [Royalty-Pro](https://github.com/agencyfive5-dotcom/Royalty-Pro) — back-office royalty intelligence tool
feat: add CRBT Income tab to Financials — reads verified data from SoundClaim
