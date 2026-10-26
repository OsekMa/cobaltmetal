# Cobalt Metal

This repository is a pure static export of [cobaltmetal.cn](https://cobaltmetal.cn), including the home page, blog, brand pages, articles, and local media assets.

Preview it from the repository root with:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/`. Cloudflare Pages can apply the redirects in `_redirects`; hosts that do not process that file may return 404 for old WordPress query URLs. Known `?p=` IDs are mapped, while unknown IDs can 404.

MariaDB and WordPress backups are stored off-repository on the ops box.
