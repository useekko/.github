<p align="center">
  <img src="assets/logo.png" width="120" alt="Ekko" />
</p>

<h1 align="center">Ekko</h1>
<p align="center"><i>Say it like no one is listening.</i></p>

Ekko is a privacy platform: one private identity for every app you already use.
Messages seal themselves on-device with hybrid post-quantum encryption
(X25519 + ML-KEM-768) and travel through the apps you and the people you talk to
already have open. No new messenger, and nobody to talk into switching.

**Status: public alpha. The code is here.** It works, we use it daily, and it has
rough edges — that's what building in public looks like. Install it, read every line
of it, break it, and tell us. The first Chrome Web Store version is in review right
now; TestFlight for the iOS app is next.

## What we are building

| Surface | What it does | Status |
|---|---|---|
| **Browser extension** | Seals and opens messages in the page, inside Instagram, WhatsApp Web, Telegram Web and Messenger. | **Public alpha** — install from a [release](https://github.com/useekko/ekko-core/releases) or the nightly |
| **Directory** | Maps @handles to public keys so people can find each other. Optional: skip it and trade invites by hand, or **self-host it**. | **Open source (AGPL), running** |
| **iOS app** | Your identity on the phone: recovery phrase, contacts, safety numbers, your @handle. | Code public, TestFlight next |
| **iOS keyboard** | Ekko's own keyboard, so encryption reaches inside the *native* messenger apps, not only the web ones. | Code public, TestFlight next |
| **Safari extension** | The same protection in Safari, on iPhone and on Mac. | Code public |

One identity spans all of it. The same recovery phrase produces the same keys in the
browser and on the phone, so a message sealed in Chrome opens on iOS, and the reverse.

## The promises

- **Open source.** The extension ([ekko-core](https://github.com/useekko/ekko-core)),
  the iOS app ([ekko-ios](https://github.com/useekko/ekko-ios)), the protocol, and the
  directory server. GPL/AGPL — it stays open.
- **Self-hosting.** Run your own directory. No dependency on us.
- **Free core, forever.** Encrypting your own messages will never be a paid feature.
- **No telemetry.** We count downloads and newsletter signups, not you.

## Repos

- [**ekko-core**](https://github.com/useekko/ekko-core) — the extension, the protocol, the directory server.
- [**ekko-ios**](https://github.com/useekko/ekko-ios) — the iOS app, the keyboard, the Safari extension.

## Links

- Site + newsletter: [useekko.app](https://useekko.app)
- X: [@useekko](https://x.com/useekko)
- Discord: [discord.gg/cQytJjVdxu](https://discord.gg/cQytJjVdxu)
- Contact: [kirill@useekko.app](mailto:kirill@useekko.app)

---

Because convenience was never meant to sacrifice privacy.
