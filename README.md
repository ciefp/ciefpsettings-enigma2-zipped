# Hi — I'm ciefp 👋

I build focused, practical tooling and packaging for Enigma2 and related embedded/media devices. My work centers on making configuration and deployment simple, repeatable, and reliable for users and plugin authors.

---

## About this account
- 🔧 I create and maintain small utilities, installers, and configuration bundles for Enigma2 and similar platforms.
- 📦 I publish both a source/configuration repo and a prepackaged ZIP version for easy consumption by plugins and users.
- 🤝 I collaborate with plugin authors so they can consume a single, consistent settings package across multiple plugins.

---

## Key repositories
- [ciefpsettings-enigma2](https://github.com/ciefp/ciefpsettings-enigma2) — Core settings, templates, and scripts used by multiple Enigma2 plugins (source of truth for configuration).
- [ciefpsettings-enigma2-zipped](https://github.com/ciefp/ciefpsettings-enigma2-zipped) — Packaged ZIP distribution of the settings for direct inclusion by plugins or installers.

These two repos work together: the source repo holds the canonical settings and the zipped repo provides an easily-installable artifact for plugins that prefer a single-file dependency.

---

## What I build
- Configuration bundles that plugin authors can reuse across multiple Enigma2 extensions.
- Lightweight installers and packaging scripts (ZIPs) so end users and plugin ecosystems can consume settings without complex build steps.
- Small, maintainable automation tools for deployment and device configuration.

---

## Usage (for plugin authors)
1. Reference or download the ZIP from the zipped repo to include default settings with your plugin.
2. If you need to modify defaults, fork or open a PR against the core repo and keep changes minimal and well-documented.
3. When possible, prefer reading defaults from the core repo during development and use the zipped release for runtime distribution.

If you want, I can add example integration snippets for popular plugin frameworks.

---

## Contributing
- Open an issue with reproducible steps if you find a bug or need a change.
- Submit a PR with a short description, tests (if applicable), and notes on compatibility.
- I prioritize small, well-scoped changes that keep cross-plugin compatibility intact.

---

## Featured skills
- Shell scripting & automation
- Packaging (ZIP/installer workflows)
- Linux systems & embedded device configuration
- Enigma2 plugin integrations
- Troubleshooting and reproducible support

---

## Contact & social
Share which channels you prefer and I’ll add them here (LinkedIn, Email, X/Twitter, personal site, Matrix/Mastodon, etc.)
