[![Netlify Status](https://api.netlify.com/api/v1/badges/598aa8f0-a269-41c2-a28e-0e361e639eb9/deploy-status)](https://app.netlify.com/sites/team1661-site-new/deploys)

# team1661-site-docs

Source for [team1661.com/docs](https://team1661.com/docs), the Griffitrons 1661 documentation site.

It's built with [Quartz v4](https://quartz.jzhao.xyz/), a static site generator for Markdown notes. The pages
live in `content/` (electronics, system diagrams and more). The `frc_system_diagrams` folder is a git submodule
pointing at [frc_system_diagrams](https://github.com/Robotics1661/frc_system_diagrams).

## Running locally

You'll need Node.js 20 or newer (see `.node-version`).

```bash
git clone --recurse-submodules https://github.com/Robotics1661/team1661-site-docs.git
cd team1661-site-docs
npm ci
npx quartz build --serve     # build and serve the site locally
```

Other scripts: `npm run check` (type check and Prettier check) and `npm run format`. The `docs/` folder is
Quartz's own upstream documentation, not team content.

A `Dockerfile` is also included.

## Contributing

Add or edit Markdown files in `content/`, preview them locally, then open a pull request.

## License

[MIT](LICENSE.txt). Quartz is copyright jackyzha0 and also MIT licensed.
