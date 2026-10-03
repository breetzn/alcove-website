# Alcove website

The static website of the Alcove app, at https://alcovecal.app. It is served by GitHub Pages from the `main` branch.

- `index.html`: home page
- `privacy.html`: privacy policy (Google needs it for sign-in verification)
- `style.css`, `assets/`, `fonts/`: look and brand files (Fraunces is under the OFL, see `fonts/OFL.txt`)
- `CNAME`: the custom domain

Update `privacy.html` and its effective date when the app changes what it collects. The source of truth for the data is `docs/firebase.md` in the app repository.
