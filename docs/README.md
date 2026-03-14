# OpenSwitch Playbook — GitHub Pages

This folder contains the content served via GitHub Pages.

When the deployment workflow runs, the built `openswitch-playbook.html` is copied here as `index.html`, making the playbook accessible at:

> **https://baffoura30.github.io/OpenSwitch-playbook/**

## Structure

| File | Description |
|------|-------------|
| `index.html` | Generated playbook (produced by `node build.js`) |

> **Note:** `index.html` is generated automatically by the CI/CD workflow. Do not edit it directly — edit the source files in `src/` and run `node build.js` instead.
