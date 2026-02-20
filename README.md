# Ruirui Wan Portfolio

Personal portfolio site for **Ruirui Wan**.

Tagline: **Tech AI / Designer / Game Designer / Vibe Coder**

This repository is a customized version of the `vcard-personal-portfolio` template, converted into a lightweight static portfolio.

## Profile Summary

- AI-focused technologist and designer at the intersection of AI, game development, and creative systems engineering
- Builds interactive systems, AI-driven workflows, and rapid prototyping pipelines
- Open-source contributor (including `oh-my-open-code` and `repo-prompt`)

## Tech Stack

- AI & Tooling: Advanced AI workflow orchestration, vibe coding, AI-assisted rapid development
- Programming: Python, C#, C++
- Game Engines: Unity, Unreal Engine
- Creative & 3D: Blender

## Local Development

Any static file server works. Example:

```bash
npx --yes http-server . -p 4173
```

Then open: `http://127.0.0.1:4173`

## GitHub Pages Deployment

1. Push your latest commit(s) to the branch you want to publish from (commonly `main`).
2. In GitHub: `Settings` -> `Pages`.
3. Under `Build and deployment`, choose `Deploy from a branch`.
4. Set source branch and folder:
- Branch: your publish branch (for example `main`)
- Folder: `/(root)` (or `/docs` if you publish from `docs`)
5. Save and wait for deployment to complete.
6. Open the Pages URL shown in Settings to verify the live site.

## Pre-Push Checklist

- `index.html` exists at the root of the publish source
- All internal nav targets work (`About`, `Resume`, `Portfolio`, `Highlights`, `Contact`)
- No placeholder links (`href="#"`) remain
- CSS/JS/image paths resolve correctly from GitHub Pages

## Post-Deploy Smoke Test

- Site loads without 404
- Primary links work:
  - GitHub: <https://github.com/raydocs>
  - Email: <mailto:ruiruiwan8@gmail.com>
  - Email: <mailto:sjs235@cornell.edu>
- Portfolio filters and section navigation work
- Mobile layout is readable and bottom navigation is usable

## License

MIT (inherits template license)
