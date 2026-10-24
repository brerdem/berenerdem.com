# berenerdem.com
Website for Beren Erdem

A plain static "under construction" page: `index.html` plus `assets/`, no build step.

## Run locally

```sh
docker build -t berenerdem .
docker run --rm -p 8080:80 berenerdem
```

Then open http://localhost:8080.

## Deploy (Coolify)

Use the Dockerfile build pack; the container serves the site with `nginx:alpine` on port 80.
