<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=140&color=0:aa0000,50:d40000,100:ff1a1a&section=header" alt="" width="100%" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://team1661.com/assets/images/1661-logo-white.png">
  <img src="https://team1661.com/assets/images/1661-logo-black.png" alt="Team 1661 logo" width="120">
</picture>

# 📚 team1661-site-docs

**The Griffitrons 1661 documentation site**

[![FRC: Team 1661](https://img.shields.io/badge/FRC-Team%201661-d40000?style=for-the-badge&logo=firstinspires&logoColor=white)](https://team1661.com)
![Quartz: v4](https://img.shields.io/badge/Quartz-v4-4EC9B0?style=for-the-badge)
![Node: 20+](https://img.shields.io/badge/Node-20%2B-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Netlify: hosted](https://img.shields.io/badge/Netlify-hosted-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
[![Netlify Status](https://api.netlify.com/api/v1/badges/598aa8f0-a269-41c2-a28e-0e361e639eb9/deploy-status)](https://app.netlify.com/sites/team1661-site-new/deploys)
[![License](https://img.shields.io/github/license/Robotics1661/team1661-site-docs?style=for-the-badge&color=d40000)](LICENSE.txt)

</div>

---

Source for [team1661.com/docs](https://team1661.com/docs), the Griffitrons 1661 documentation site.

It's built with [Quartz v4](https://quartz.jzhao.xyz/), a static site generator for Markdown notes. The pages
live in `content/` (electronics, system diagrams and more). The `frc_system_diagrams` folder is a git submodule
pointing at [frc_system_diagrams](https://github.com/Robotics1661/frc_system_diagrams).

## 💻 Running locally

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

## 🤝 Contributing

Add or edit Markdown files in `content/`, preview them locally, then open a pull request.

## 📜 License

[MIT](LICENSE.txt). Quartz is copyright jackyzha0 and also MIT licensed.

---

<div align="center">

<sub>Built by students of <a href="https://team1661.com">Griffitrons 1661</a> at The Buckley School 🛠️</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&height=90&color=0:aa0000,50:d40000,100:ff1a1a&section=footer" alt="" width="100%" />

</div>
