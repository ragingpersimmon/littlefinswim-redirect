# littlefinswim-redirect

Redirects `littlefinswim.net` to [glassgardenfins.com](https://glassgardenfins.com/),
keeping the path, query string, and fragment.

The domain was stood down on 2026-11-04 and will not be renewed. This site keeps
forwarding old links until the registration ends on 2027-08-19.

GitHub Pages cannot send HTTP 301 responses, so each route that existed on the
old domain has a stub page with a canonical link, an instant meta refresh, and a
JavaScript redirect. `404.html` forwards every other path.

Publishing this site also keeps `littlefinswim.net` claimed while its DNS points
at GitHub Pages. To finish the retirement, delete the domain's DNS records in
Namecheap on or just before 2027-08-19, confirm it no longer resolves to GitHub
Pages, and then archive or delete this repository.
