# Renzo Viale — Blog

A minimal, fast static site inspired by https://www.renzoviale.com/

## Structure
- `index.html`: homepage
- `essays/index.html`: essays list
- `essays/hello-world.html`: sample essay
- `styles.css`: shared styles

## Local development
No build step. Just open `index.html` in a browser, or run a local server to get clean routing:

```bash
# Python
python -m http.server 5173
# or Node
npx http-server -p 5173
```
Visit http://localhost:5173

## Customization TODOs
- Update links on `index.html` with your real profiles and email.
- Replace the bio text and location.
- Add more posts by duplicating `essays/hello-world.html` and linking from `essays/index.html`.
- Optionally add RSS and analytics later.
