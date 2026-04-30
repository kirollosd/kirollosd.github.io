# kirollosd.github.io

Source for my personal blog at <https://kirollosd.github.io/>.

## Local development

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # outputs to ./dist
```

## Writing

Posts live in `src/data/blog/` as Markdown with frontmatter (see any existing post for the shape). Pushing to `main` triggers the GitHub Actions workflow at `.github/workflows/deploy.yml`, which builds and deploys to GitHub Pages.

## Credits

Built on [AstroPaper](https://github.com/satnaing/astro-paper) by Sat Naing (MIT).
