# kalybospro.github.io

Keeps the old address of the frus widget gallery working. The gallery was served at
`kalybospro.github.io/frus/` while the repository was `KalybosPro/frus`; GitHub does not redirect
Pages when a repository moves, and it moved to `frus-rs/frus`, whose gallery is at
`frus-rs.github.io/frus/`.

`frus/index.html` and `404.html` send any address below `/frus/` there, with its path, query and
`#/` route, so a link to one widget's demo still opens that demo.

**Never create a repository named `frus` under `KalybosPro`:** it would take this address back,
and delete GitHub's redirects from `KalybosPro/frus` to `frus-rs/frus` for good.

Publish after the transfer: push this folder as the repository `KalybosPro/kalybospro.github.io`
(branch `main`), and turn on Pages for it (Settings → Pages → deploy from `main`, `/`).
