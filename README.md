# Puso Studios

Static one-page site for [pusostudios.com](https://pusostudios.com).

No build step, backend, or extra dependencies. Open `index.html` or drop the folder onto any static host.

## Local preview

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

## Deploy

The folder is ready as-is for Cloudflare Pages, Netlify, GitHub Pages, or any other static host.

1. Upload the project (or connect the git repo)
2. Set the publish directory to the project root
3. Point `pusostudios.com` at the host

`CNAME` is included for GitHub Pages / Cloudflare Pages.
