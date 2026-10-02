# The organisation's github.io root

This repository exists for one reason: GitHub serves a hostname's root
(`https://<org>.github.io/`) only from a repository named exactly
`<org>.github.io`, and the Vouchwell site does not live here.

`index.html` redirects to `/<org>/`, the site built and deployed from
[`site/` in the main repository](https://github.com/vouchwell/vouchwell/tree/main/site).
The path is taken from the hostname, so the redirect keeps working when the
organisation is renamed (it was `proofwire` before the project became
Vouchwell). Keeping the source in one place is why this is a redirect and not
a copy.

Nothing else belongs here. To change the site, change it there.
