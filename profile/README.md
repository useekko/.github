<p align="center">
  <img src="assets/logo.png" width="120" alt="Ekko" />
</p>

<h1 align="center">Ekko</h1>
<p align="center"><i>Say it like no one is listening.</i></p>

Ekko is a privacy platform: one private identity for every app you already use.
Messages seal themselves on-device with hybrid post-quantum encryption
(X25519 + ML-KEM-768) and travel through the apps you and the people you talk to
already have open. No new messenger, and nobody to talk into switching.

**Status: private alpha.** A small group is testing the browser extension. The code
is not public yet. These repos are where it lands.

## What we are building

| Surface | What it does | Status |
|---|---|---|
| **Browser extension** | Seals and opens messages in the page, inside Instagram, WhatsApp Web, Telegram Web and Messenger. Chrome first. | Private alpha |
| **iOS app** | Your identity on the phone: recovery phrase, contacts, safety numbers, your @handle. | In development |
| **iOS keyboard** | Ekko's own keyboard, so encryption reaches inside the *native* messenger apps, not only the web ones. | In development |
| **Safari extension** | The same protection in Safari, on iPhone and on Mac. | In development |
| **Directory** | Maps @handles to public keys so people can find each other. Optional: skip it and trade invites by hand. | Running |

One identity spans all of it. The same recovery phrase produces the same keys in the
browser and on the phone, so a message sealed in Chrome opens on iOS, and the reverse.

## What lands when the code opens

- **Open source.** The extension, the protocol, and the directory server, published here.
- **Self-hosting.** Run your own directory. No dependency on us.
- **Reproducible builds.** Compile it yourself and verify what you are running.

## Repos

- [**ekko-core**](https://github.com/useekko/ekko-core), the extension, the protocol, the directory.
- [**ekko-ios**](https://github.com/useekko/ekko-ios), the iOS app, the keyboard, the Safari extension.

## Links

- Site: [useekko.app](https://useekko.app)
- X: [@useekko](https://x.com/useekko)
- Discord: [discord.gg/cQytJjVdxu](https://discord.gg/cQytJjVdxu)
- Contact: [kirill@useekko.app](mailto:kirill@useekko.app)

---

These pages fill in as things open up.
