# ordino-updates

Update feed for [ordino](https://xsugra.github.io/ordino-updates/), a macOS app that arranges every window on a display with one keystroke.

This repository only holds:

- `appcast.xml`: the [Sparkle](https://sparkle-project.org) update feed, served by GitHub Pages at
  `https://xsugra.github.io/ordino-updates/appcast.xml`
- Release archives (`ordino-X.Y.Z.zip`), attached to GitHub Releases

Every archive is signed with ordino's EdDSA update key; the app verifies the signature before installing. Files here are published automatically by ordino's release pipeline. Please don't open pull requests.
