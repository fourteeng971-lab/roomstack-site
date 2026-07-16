# RoomStack — public site

Support, Privacy Policy, and Terms of Use pages for the RoomStack iOS app.
Served via GitHub Pages (Settings ▸ Pages ▸ Source = `main` / `/ (root)`).

- `index.html` — Support (contact + help topics)
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Use

## Do not hand-edit

These files are **generated** from the app's own source (`RoomStack/Views/Content.swift`)
in the private app repo, so the hosted Privacy Policy can never drift from the copy bundled
in the app — App Review compares the two. To change them, edit the app source, then run
`scripts/build-legal-site.py` and `scripts/publish-site.sh` from the app repo.
