# site/

Static page served at **https://awatere.pages.dev** (Cloudflare Pages project `awatere`).

Deploy from this directory:

```sh
npx wrangler pages deploy site --project-name=awatere --branch=main
```

No build step: it is one self-contained HTML file, so it renders without JavaScript and without a toolchain.
