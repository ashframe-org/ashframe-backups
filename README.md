# Ashframe Backups

The static public archive site used at [backups.ashframe.net](https://backups.ashframe.net/).

It provides a lightweight download page and a Caddy directory-listing template for public archives. It has no JavaScript, analytics, cookies, or external assets.

## Included

- `public/index.html` — archive homepage
- `public/style.css` — shared Ashframe archive styling
- `caddy/ashframe-backups-browse.html` — themed Caddy `file_server browse` template
- `caddy/Caddyfile.example` — minimal example configuration

## Deployment

Copy `public/` to the directory that contains only files intended for public download. Copy the browse template to a readable Caddy configuration directory, then adapt the paths in `caddy/Caddyfile.example`.

Do not place private backups, credentials, server configuration, account data, or unreviewed files in the public archive directory.

## License and branding

The code in this repository is available under the MIT License. The Ashframe name, logo, wordmark, visual identity, and other brand assets are not included in that license; see [BRAND.md](BRAND.md).
