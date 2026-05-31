# StorageCleaner Site Agent Notes

## Product Focus

- This repo is the static public site for StorageCleaner at `storagecleaner.mesikalabs.com`.
- Keep the site aligned with the review-before-delete cleanup positioning.
- Do not add claims about automatic deletion, cloud processing, or future paid gating unless the app repo and App Store metadata already support them.
- Follow `DESIGN.md` for visual rules, current icon usage, navigation structure, and screenshot constraints.

## MesikaLabs Contact Points

- General support: `support@mesikalabs.com`
- Privacy: `privacy@mesikalabs.com`
- Billing: `billing@mesikalabs.com`
- Legal: `legal@mesikalabs.com`
- App-specific support: `storagecleaner@mesikalabs.com`

## Validation

- Local smoke test: `python3 -m http.server 8088 --bind 127.0.0.1`
- Check `/`, `/support/`, `/privacy/`, `/terms/`, `/blog/`, `/blog/feed.json`, `/robots.txt`, and `/sitemap.xml`.
- Hosted checks after deploy: `curl -I -L https://storagecleaner.mesikalabs.com/ https://storagecleaner.mesikalabs.com/robots.txt https://storagecleaner.mesikalabs.com/sitemap.xml`
