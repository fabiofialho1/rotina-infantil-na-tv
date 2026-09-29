# rotina-infantil-na-tv (moved)

The app moved to **https://routikids.github.io/** (repository `Routikids/routikids.github.io`). All development happens there.

This repository only serves the old address `fabiofialho1.github.io/rotina-infantil-na-tv/` with `index.html` = the redirect page from `legacy-redirect/index.html`: it forwards each device's saved data (localStorage keys starting with `rotina`) to the new address in a `#migrate=` URL fragment, and keeps a pairing QR link's `?parear=CODE`.

- Keep this page published so devices and links that still use the old address keep working.
- Its `<meta name="app-version">` must stay newer than any app version that ran here, so running devices detect an "update", reload and get forwarded.
- Commit messages and PR texts in English.
