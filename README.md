
# ElegantStore_Final — Final Web Design Project

This final version includes:
- 15 realistic products loaded from `js/products.json`.
- Products page with a Bootstrap-styled toolbar (search input + category select + button).
- Modern layout using Bootstrap 5 and custom CSS.
- Improved cart UI, checkout summary with tax (8%) calculation.
- Dark mode toggle (persists via localStorage).
- Simple register/login (localStorage) and protected dashboard (sessionStorage).

## How to run
Use a static server (recommended) to avoid fetch CORS issues:
```bash
python -m http.server 8000
# open http://localhost:8000
```

## Notes
- Product images use Unsplash Source queries and will load when served over HTTP.
- This is a demo — authentication is not secure for production.
