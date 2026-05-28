# davidyou.com

Personal site for David You — [davidyou.com](https://davidyou.com).

Single-page static site (`index.html`) with no build step. Tabs (Home, Projects, CV, Contact) are switched client-side via hash routing.

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

Served via GitHub Pages from `main`. The `CNAME` file maps the Pages site to `davidyou.com`.
