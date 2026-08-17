# bitPOS

Hosted Lightning point of sale. Source: [`bitPOS-app/bitpos`](https://github.com/bitPOS-app/bitpos).
Service: [bitpos.app](https://bitpos.app). License: [AGPL-3.0-or-later](https://github.com/bitPOS-app/bitpos/blob/main/LICENSE).

Merchants connect their own wallet over NIP-47. bitPOS does not custody
merchant funds. Platform fee: 1% inbound, 0% outbound.

The tree is published for comparison with the running process, not as a
self-hosting kit.

## Fingerprint

Commit on `bitPOS-app/bitpos` `main`. Updated by
[`refresh-verify.yml`](https://github.com/bitPOS-app/.github/blob/main/.github/workflows/refresh-verify.yml).

<!-- VERIFY:START -->
```
  tag    │ build-13
  sha    │ 6b4c1969e48fdc65613b8b5459db20f2964406e6
  short  │ 6b4c196
  built  │ 2026-08-17T04:22:47Z
```
<!-- VERIFY:END -->

```
GET https://bitpos.app/api/version
```

After a production deploy, `commit` equals the SHA above. Until then the
published tree may be ahead of the binary.
