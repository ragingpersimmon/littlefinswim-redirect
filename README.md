# littlefinswim-redirect

Redirects the retired domain `littlefinswim.net` to
[glassgardenfins.com](https://glassgardenfins.com/), keeping the path, query string, and fragment.

GitHub Pages cannot send HTTP 301 responses, so each route that existed on the
old domain has a stub page with a canonical link, an instant meta refresh, and a
JavaScript redirect. `404.html` forwards every other path. Publishing this site
also keeps `littlefinswim.net` claimed while its DNS points at GitHub Pages; if
the domain is retired, remove its DNS records before deleting this repository.
