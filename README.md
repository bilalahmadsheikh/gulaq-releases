# gulaq — Desktop Vault releases

Official downloads and the **auto-update feed** for the **gulaq Desktop Vault** app.

> This repository hosts only the compiled, signed installers and the update
> manifest. The application source code is maintained in a separate, private
> repository — nothing here exposes source.

## ⬇ Download

**[Download the latest version](https://github.com/bilalahmadsheikh/gulaq-releases/releases/latest)**

- **Windows:** download and run `gulaq Desktop Vault_<version>_x64-setup.exe`.

You also need the free **gulaq Chrome extension** (the desktop app is its companion vault):

👉 https://chromewebstore.google.com/detail/gulaq/ikjempphbbkjfkpngdigdaefanadnicc

## 🔄 Auto-update

The desktop app checks this repository **on launch** and installs new versions
automatically — you don't need to re-download to stay up to date. Every update is
**cryptographically verified** against a public key embedded in the app, so only
releases signed with gulaq's private key are ever installed.

## What each release contains

| File | Purpose |
|------|---------|
| `gulaq Desktop Vault_<version>_x64-setup.exe` | Windows installer |
| `gulaq Desktop Vault_<version>_x64-setup.exe.sig` | Detached signature for the installer |
| `latest.json` | Update manifest the app reads to detect new versions |

## 🐞 Found a bug?

Please [**open an issue**](https://github.com/bilalahmadsheikh/gulaq-releases/issues/new?template=bug_report.md) — see [SUPPORT.md](SUPPORT.md) for what to include. (Don't paste private chat contents or tokens into a public issue.)

## Links

- **Website:** https://projectgoldenage.vercel.app/gulaq
- **Privacy policy:** https://projectgoldenage.vercel.app/gulaq/privacy
- **Terms of use:** https://projectgoldenage.vercel.app/gulaq/terms
- **Support:** https://projectgoldenage.vercel.app/gulaq/support

---

© Project Golden Age — gulaq. Your vault stays on your device; only account metadata is stored in the cloud.
