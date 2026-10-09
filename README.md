# opal.design

A door, not a room. This repository exists only to answer `opal.design` and
send it to `more-than.design`, keeping the path it was asked for.

It is served by GitHub Pages, which issues the certificate — the thing
Namecheap's URL forwarding could not do, and the reason `https://opal.design`
used to time out.

`404.html` carries the same redirect as `index.html`, so a deep link survives
the trip rather than landing on a GitHub error page.

`CNAME` is what tells GitHub this repository answers for `opal.design`.
Removing it breaks the domain.
