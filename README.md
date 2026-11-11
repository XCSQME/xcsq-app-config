# XCSQ Public Delivery

This repository contains signed public network configuration and official,
signed Android release assets only. It contains no application source, account
data, server address, credentials or signing keys. GitHub Actions is not used.

Clients verify the Ed25519 signature of `runtime.json` before using it. A
configuration change cannot add features or execute code. Android packages must
also match the advertised SHA-256 and the original Android signing identity.

Customer download page: https://xcsq.site/app

iOS App Store: https://apps.apple.com/app/id6813766459
