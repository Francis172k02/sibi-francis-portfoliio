# SibiFrancis J — Backend Developer Portfolio

Live site: https://francis172k02.github.io/sibi-francis-portfolio/

Personal portfolio for SibiFrancis J, Backend Developer (Java, Spring Boot, REST APIs, PostgreSQL, Grails).

## Features
- Dark green hero with portrait, stack chips and resume download
- "The tools I build with" connected stack map with animated wiring
- Skills drawn as the path of a request (Client → API → Service → Data access → Database)
- ERP module deck (Finance, Procurement, Job Work, Inventory, Sales, HR, Reporting)
- In-browser API console (`GET /profile`, `/skills`, `/projects`, `/contact`, `POST /messages`)
- Experience timeline, contact section, Ctrl/⌘+K command menu
- Responsive (desktop, tablet, mobile), keyboard accessible, respects reduced motion

## Tech
Static site: one `index.html` with inline CSS and vanilla JavaScript, no build step. Chosen for zero-config, free hosting on GitHub Pages and fast first load.

## Structure
```
index.html                                  the whole site
SibiFrancis_J_Backend_Developer_Resume.pdf  resume download
favicon.svg, robots.txt, sitemap.xml, .nojekyll
```

## Run locally
Open `index.html` in a browser, or serve the folder:
```
python3 -m http.server 8080
```

## Deploy (GitHub Pages)
1. Push this folder to `github.com/Francis172k02/sibi-francis-portfolio` (public).
2. Repo → Settings → Pages → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
3. After about a minute the site is live at https://francis172k02.github.io/sibi-francis-portfolio/

## Update content
Edit the text in `index.html` (data arrays such as `MODULES`, `LAYERS`, `PERSONAL` hold most content), commit and push; Pages redeploys automatically.
