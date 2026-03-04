# csabi.net

A minimal, single‑file static webpage served via GitHub Pages.

## About
This project hosts the source for **https://csabi.net** — a minimalist page containing nothing but:

- the domain name in lowercase  
- a thin blue gradient line  
- a tiny footer  
- auto‑updating year  

No tracking, no scripts (except the tiny year autoupdater), no frameworks, no analytics.

## File Structure

#index.html   # one-line HTML page

## Hosting
The site is deployed using **GitHub Pages**, with:

- 4 required A records for the root domain  
- one CNAME for `www` → `<yourusername>.github.io`  
- free HTTPS once DNS fully propagates  

This repo contains no build system — the HTML is served exactly as written.

## License
This project is intentionally public domain.  
Do whatever you want with it.
