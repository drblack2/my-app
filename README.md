# my-web-app

A beautiful, responsive landing page built with plain HTML, CSS, and JavaScript.new

## Project structure

- `index.html` — page markup
- `style.css` — visual design and responsiveness
- `script.js` — mobile menu and reveal animations
- `images/` — SVG assets for the hero and work sections
- `Dockerfile` — containerizes the site with Nginx
- `Jenkinsfile` — basic CI pipeline example

## Run locally

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Build with Docker

```bash
docker build -t my-web-app .
docker run -p 8080:80 my-web-app
```
