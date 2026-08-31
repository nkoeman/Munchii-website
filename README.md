# Munchii Marketing Website

Static HTML and CSS marketing site for Munchii, including Privacy Policy, Terms of Use, Community Guidelines, and Help & Contact pages.

## Run Locally

```sh
docker compose up --build
```

Open `http://localhost:8080`.

Clean URLs are handled by nginx, so these routes work in the container:

- `http://localhost:8080/privacy`
- `http://localhost:8080/terms`
- `http://localhost:8080/community`
- `http://localhost:8080/support`

The App Store buttons are placeholders marked with `<!-- TODO: App Store URL -->` in `index.html`.
