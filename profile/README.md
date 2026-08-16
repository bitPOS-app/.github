<div align="center">

```
 _     _ _   ____   ___  ____
| |__ (_) |_|  _ \ / _ \/ ___|
| '_ \| | __| |_) | | | \___ \
| |_) | | |_|  __/| |_| |___) |
|_.__/|_|\__|_|    \___/|____/
```

**A Lightning point of sale you can verify.**

[![stars](https://img.shields.io/github/stars/bitPOS-app/bitpos?color=f7931a&style=flat-square&label=stars)](https://github.com/bitPOS-app/bitpos/stargazers)
[![last commit](https://img.shields.io/github/last-commit/bitPOS-app/bitpos/main?color=f7931a&style=flat-square&label=last%20commit)](https://github.com/bitPOS-app/bitpos/commits/main)
[![release](https://img.shields.io/github/v/release/bitPOS-app/bitpos?color=f7931a&style=flat-square&label=release&include_prereleases)](https://github.com/bitPOS-app/bitpos/releases)
[![license](https://img.shields.io/github/license/bitPOS-app/bitpos?color=f7931a&style=flat-square&label=license)](https://github.com/bitPOS-app/bitpos/blob/main/LICENSE)

</div>

---

## what is bitPOS

bitPOS is a self-hosted Lightning point of sale — a merchant dashboard, a tap-to-pay terminal (the posBOX), and NFC Bolt Card support, all settled over NIP-47 Nostr Wallet Connect against **your own node**. No third party ever touches your sats.

| Project | What it is |
|---------|------------|
| [`bitPOS-app/bitpos`](https://github.com/bitPOS-app/bitpos) | The full stack: API server, web app, landing, posBOX firmware, card writer. |
| [`bitPOS-app/.github`](https://github.com/bitPOS-app/.github) | This profile + the published verification fingerprint. |

---

## fingerprint

The exact commit running on `bitpos.app` right now. Regenerated on every push by [`refresh-verify.yml`](https://github.com/bitPOS-app/.github/blob/main/.github/workflows/refresh-verify.yml).

<!-- VERIFY:START -->
```
  tag    │ untagged
  sha    │ 922ef38688b8a527608ddce48acfdabbc0881310
  short  │ 922ef38
  built  │ 2026-08-16T12:03:42Z
```
<!-- VERIFY:END -->

```bash
$ curl -s https://bitpos.app/api/version | jq -r .commit
922ef38688b8a527608ddce48acfdabbc0881310
```

Two values. They match. That is the entire promise.

---

## why this is here

Custody is a question of trust. Trust is a question of evidence. bitPOS publishes its evidence:

- Every release is a tagged commit in [`bitPOS-app/bitpos`](https://github.com/bitPOS-app/bitpos).
- Every running instance reports its commit at `/api/version`.
- AGPL-3.0-or-later keeps the chain intact across any deployment, fork, or service.

Three independent checks that the code handling your sats is the code on this page.

---

<div align="center">

[**AGPL-3.0-or-later**](https://github.com/bitPOS-app/bitpos/blob/main/LICENSE) · `bitpos.app`

</div>
