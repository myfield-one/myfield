# MyField

**Your data stays yours.** MyField is a privacy-first foundation that keeps you in control.

This repository is the public home of the MyField project: an overview,
an index of related repositories, and the place for issues and discussions.
It does not contain the MyField platform source code.

Website: [myfield.one](https://myfield.one)

## Repositories

- **[mfid](https://github.com/myfield-one/mfid)** — A DID method for identities owned by device or authenticator keys, without a central registry.
- **[sdk](https://github.com/myfield-one/sdk)** — MyField SDK for third-party web apps: local-first object storage, end-to-end-encrypted sync, and internal MyField authorization.
- **[card](https://github.com/myfield-one/card)** — A privacy-first digital business card by MyField.
- **[example-app-note](https://github.com/myfield-one/example-app-note)** — A small local-first notes app built with @myfield/sdk.

All repositories are licensed under Apache-2.0.

The SDK and mfid are in 1.0 preview. Their APIs may still change slightly
before 1.0 based on feedback.

## Products

- **[MyField](https://myfield.one)** — The privacy-first foundation behind the apps: device-owned authorization, local-first data, encrypted sync, and optional AI.
- **[Keychain](https://myfield.one/home)** — Your passkeys, device keys, and app authorizations, built on [`did:mfid`](https://github.com/myfield-one/mfid).
- **[Turn Field](https://myfield.one/turn)** — Browser extension for saving and reading web pages, local-first (Chrome, Edge, Safari).
- **[Card Field](https://card.myfield.one)** — Privacy-first digital business card; shared card links are encrypted in the browser.
- **[Slide Field](https://slide.myfield.one)** — Browser-local slide editor.

## How MyField works

**Device-owned Authorization.** Each device holds its own key. No shared password.

- Access starts from authorized devices and Keychain.
- No traditional username and password.

**Local-first Architecture.** Content starts local. Sync and AI are optional extensions.

- User content starts on the device.
- Sync and AI extend the experience, never the center of the data model.

**Encrypted Sync Relay.** Cloud sync stores and relays ciphertext.

- Synced data is encrypted before cloud relay.
- Cloud sync relays encrypted data only, never plaintext pages.

## Feedback and support

- **Bugs and feature requests:** [open an issue](../../issues/new/choose) here.
  Issues about the SDK, mfid, or Card Field code can go to that repository.
- **Security vulnerabilities:** do not open a public issue. Follow
  the [security policy](https://github.com/myfield-one/.github/blob/main/SECURITY.md).
- **Never share private data** in issues: no recovery phrases, passphrases,
  keys, tokens, or personal content.

See [CONTRIBUTING.md](CONTRIBUTING.md) for how issues are handled.
