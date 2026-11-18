# dazix.github.io

User site for GitHub Pages, served at **https://vibecoding.sanda.dev/**.

Its custom domain also applies to every project site of this account, so project repositories with Pages
enabled are available under `https://vibecoding.sanda.dev/<repository>/`, for example
[Indoor Navigation](https://vibecoding.sanda.dev/indoor-navigation/).

`index.html` is a plain static page (no build, `.nojekyll`). When a new project is published, add its card, an
entry to the JSON-LD `ItemList` in the same file, and its URL to `sitemap.xml` if it is hosted here.
`og-image.png` (1200×630) is the link preview; regenerate it when the icon row changes.

## DNS

| Host                   | Type  | Value             |
| ---------------------- | ----- | ----------------- |
| `vibecoding.sanda.dev` | CNAME | `dazix.github.io` |
