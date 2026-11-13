# Ronex Shop 1 — releases

This repository holds **only released installers and signed rollout files** for Ronex Shop 1 automatic updates.
It contains no source code, no shop data and no keys.

* `channels/stable.json` — the signed rollout file read by Ronex Shop 1 (1.0.49 and newer). It decides which
  version each shop may install. Shops accept it only if it carries the publisher's signature.
* `channels/test*.json` and releases tagged `test-v…` — **internal update tests only** ("Ronex Update Test").
  They are signed with a separate test key that Ronex Shop 1 does not trust. Do not install them in a shop.
* Releases tagged `v…` — Ronex Shop 1 installers. Install one manually only for recovery, or when told to.
