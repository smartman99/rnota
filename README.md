# rnota — OTA mock release-history host

Static hosting target for `@bravemobile/react-native-code-push` PoC of `poc-mobile-app`.

URL convention: `${base}/${platform}/${identifier}/${appVersion}.json`

- `histories/EXAMPLE.json` — full ReleaseInfo example
- `histories/<platform>/production/1.0.0.json` — empty histories (no update)
