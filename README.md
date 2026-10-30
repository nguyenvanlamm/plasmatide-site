# plasmatide-site

Landing, support and privacy pages for **Plasmatide**, an iPhone game inside a blood vessel: swipe the drifting
plasma drops, call immune cells, stop the germs before they reach the heart.

Live: https://nguyenvanlamm.github.io/plasmatide-site/ · [support](https://nguyenvanlamm.github.io/plasmatide-site/support.html) · [privacy](https://nguyenvanlamm.github.io/plasmatide-site/privacy.html)

Plain static HTML and CSS (`assets/site.css`), no build step and no JavaScript. Fonts are Quicksand and Lexend from
Google Fonts. GitHub Pages serves the `main` branch root directly (no GitHub Actions). Screenshots and the icon come
from the game repo (`design-demos/shots/`, `design-demos/logo/`).

Keep `privacy.html`, `support.html` and `llms.txt` in step with the game when what it stores or sells changes.

Preview locally: `python3 -m http.server 8000` and open http://127.0.0.1:8000/.
