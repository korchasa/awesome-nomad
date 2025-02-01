# Static Site Generator

This directory contains a static site generated with Hugo using the [Console theme](https://github.com/mrmierzejewski/hugo-theme-console).

## Preview

To preview the site locally:

1. Make sure you have Hugo installed:
   ```bash
   brew install hugo
   ```

2. Run the Hugo server:
   ```bash
   hugo server
   ```

3. Open http://localhost:1313 in your browser

## Build

To build the site for production:

```bash
hugo --minify
```

The static files will be generated in the `public` directory.

## Theme

This site uses the [Console theme](https://github.com/mrmierzejewski/hugo-theme-console), a minimal and responsive Hugo theme inspired by the system console.

Features:
- Minimal design based on Terminal CSS
- Fast loading (average page load < 1s)
- Mobile-friendly
- Console-style navigation
- Tag and category support