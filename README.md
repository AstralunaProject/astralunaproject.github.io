# astralunaproject.github.io

Landing page for the projects published on GitHub Pages under this account, and the domain root that serves `robots.txt` and the sitemap index for all of them.

## Adding a project

1. Publish the project with GitHub Pages and give it its own `sitemap.xml`.
2. Add a card to `index.html`.
3. Add its sitemap to `sitemap.xml`:

   ```xml
   <sitemap><loc>https://astralunaproject.github.io/NAME/sitemap.xml</loc></sitemap>
   ```

The Search Console property for `https://astralunaproject.github.io/` covers every project path, so nothing else is needed there.
