<p align="center">
  <img src="logo.svg" width="35%" alt="mongospec"/>
</p>

**Monokai themes, user-styles, and hacks for (almost) every tool and platform** — from GitHub and GitKraken to VS Code,
Slack, and beyond.  
MIT-licensed, no strings attached.

> **Note:** The repository currently ships only a Stylus **userstyle for GitHub Web**.  
> It was created in the hope that the community will contribute additional themes and hacks.  
> If you have a Monokai tweak for any app, send a PR!

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## Why?

I absolutely love Monokai's coffee-inspired colors and try to configure similar palettes wherever possible—or just use a
ready-made theme, if available. Unfortunately, Monokai themes don't exist for every app, and often, custom colors can’t
be set without resorting to hacks.

I created this repo hoping to gather other Monokai enthusiasts and collectively build a comprehensive collection of
themes, patches, and hacks for our favorite apps and tools.

---

## Repository layout

```

.
├── github/
│   ├── web/        # Stylus / UserCSS for github.com  ← current content
│   ├── desktop/    # Electron CSS-var patcher (WANTED)
│   └── mobile/     # Mobile tweaks / screenshots (WANTED)
├── gitkraken/      # (WANTED) Desktop patcher
├── vscode/         # (WANTED) VS Code color-theme JSON
├── slack/          # (WANTED) Web / desktop themes
├── tools/          # Reusable unpackers, injection helpers, etc.
└── docs/           # Contributing guide, overview, FAQ

```

*Each top-level directory is an **application**.  
Inside an application, each sub-directory is a **client** (`web/`, `desktop/`, `mobile/`, etc.).*

Every directory that contains a theme or patch should have its own `README.md` with quick instructions and screenshots.

---

## Quick start (GitHub Web)

1. Install the **Stylus** browser extension.
2. Open [`github/web/monokai-pro.user.css`](github/web/monokai-pro.user.css) and click **Install style**.
3. Reload any GitHub page — you should see Monokai Pro “Classic” colors (plus JetBrains Mono & Inter fonts).

---

## Contributing

Pull requests are very welcome! If you have **any** Monokai theme, hack, or patch for a desktop or web app:

* Clone / fork the repo.
* Place your files under the proper `/<app>/<client>/` path.
* Add a small `README.md` with install steps and at least one screenshot.
* Target the latest stable release of the app and note the version.
* Stick to MIT-compatible code only.

See **`docs/contributing.md`** for details.

---

## License

Distributed under the **MIT License**. See [LICENSE](LICENSE) for details.