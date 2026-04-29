# Kai Su Blog

Personal blog powered by Hexo and the Butterfly theme.

The Butterfly theme is installed as a Git submodule at `themes/butterfly`.

## Local Development

```sh
npm install
npm run server
```

## Build

```sh
npm run build
```

The generated static site is written to `public/`.

If you clone this repository manually, initialize the theme submodule first:

```sh
git submodule update --init --recursive
```

## Cloudflare Pages

Connect this GitHub repository in Cloudflare Pages:

- Repository: `Kai-Su2002/kai-su-blog`
- Production branch: `main`
- Build command: `npm run build`
- Build output directory: `public`
- Node version: `22`

After the first deployment, replace the `url` value in `_config.yml` with the assigned `*.pages.dev` URL or your custom domain.
