# Travel Landing Page

A static travel-themed landing page built with HTML, CSS, and JavaScript. It demonstrates a full-screen video background, overlay text, social icons, and a menu toggle.

## Project contents

| File | Purpose |
| --- | --- |
| `index.html` | Page markup and inline menu-toggle behavior |
| `style.css` | Layout and visual styling |
| `video.m4v` | Background video |
| `fb.png`, `insta.png`, `tw.png` | Social icons |

## View locally

Clone the repository and open `index.html` in a browser:

```bash
git clone https://github.com/yash1286/travl.git
cd travl
```

Alternatively, with Python installed, serve the directory locally:

```bash
python -m http.server 8000 --bind 127.0.0.1
```

Open [localhost:8000](http://localhost:8000).

## Scope

This is a frontend practice project. The navigation and social links use placeholder destinations, and the page includes placeholder body copy. There is no booking backend or travel API integration.

Video playback depends on browser codec support and autoplay policy. Visual behavior has not been verified across browsers.

## Possible improvements

Replace placeholder copy and links, improve image alternative text and keyboard navigation, add a reduced-motion option, and optimize the background video for slower connections.
