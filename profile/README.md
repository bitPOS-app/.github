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

## fingerprint

The exact commit running on `bitpos.app` right now. Regenerated on every push by [`refresh-verify.yml`](./.github/workflows/refresh-verify.yml).

<!-- VERIFY:START -->
```
  tag    │ build-13
  sha    │ 4775818756ef694ee9814515d320938ebff75ff3
  short  │ 4775818
  built  │ 2026-05-31T23:46:57Z
```
<!-- VERIFY:END -->

```bash
$ curl -s https://bitpos.app/api/version | jq -r .commit
20a4e827e89c6f1bc9a55d50d6b5ffd40c455a83
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
