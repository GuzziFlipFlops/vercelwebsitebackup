# Northstar landing page

A lightweight, responsive landing page built with plain HTML, CSS, and JavaScript. It has no build step or third-party runtime dependencies, so it can be deployed directly to Vercel as a static site.

## Customize

- Change the brand name and page copy in `index.html`.
- Update `hello@example.com` in the contact link with your email.
- Adjust the colors and fonts near the top of `styles.css`.
- Replace the description and page title in the `<head>` section of `index.html`.

## Preview locally

Open `index.html` in a browser, or run a local static server from this directory, for example:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import that repository.
3. Keep the framework preset as **Other**. There is no build command; the site files are served from the project root.
4. Deploy. Vercel will provide a public URL and can redeploy on each push to the connected branch.
