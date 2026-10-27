# Researcher Atlas 1.2

An interactive researcher directory with searchable people and groups, researcher profiles, and a geographic map.

## Run locally

```sh
python -m http.server 8000 --directory public
```

Open http://localhost:8000.

## Deployment

Vercel serves `public/` as a static website. No build step, backend, API keys, or environment variables are required. The web page includes its data, images, styles, and JavaScript. Updates pushed to `main` are deployed through the connected Vercel project.

## Files

- `public/index.html`: the complete, self-contained Researcher Atlas 1.2 web application.
- `vercel.json`: static deployment configuration.
