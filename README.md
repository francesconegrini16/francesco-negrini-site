# francesco-negrini.it

Static site for the custom domain `francesco-negrini.it`.

## Google OAuth pages

- `/personalassistant/`
- `/personalassistant/privacy/`

## GitHub Pages

Set the repository's Pages source to the `main` branch root and configure the custom domain:

`francesco-negrini.it`

The included `CNAME` file contains the custom domain.

## DNS for apex domain

For GitHub Pages, configure the apex domain records according to GitHub's current documentation.
After DNS resolves and GitHub provisions the certificate, enable **Enforce HTTPS**.

Do not place application secrets, OAuth tokens, or PersonalAssistant source/data in this repository.
