<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-did-you-mean/brand/main/social/go-ruby-did-you-mean.png" alt="go-ruby-did-you-mean/go-ruby-did-you-mean.github.io" width="720"></p>

# go-ruby-did-you-mean.github.io

The organization's institutional landing page, served at
<https://go-ruby-did-you-mean.github.io> and built with [Hugo](https://gohugo.io). It
is a single page (custom `layouts/index.html`, capability cards driven by
`[[params.phases]]` in `hugo.toml`).

Documentation lives in a separate repository,
[go-ruby-did-you-mean/docs](https://github.com/go-ruby-did-you-mean/docs), served at
<https://go-ruby-did-you-mean.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
