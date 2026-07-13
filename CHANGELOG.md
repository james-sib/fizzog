# FIZZOG — Changelog

Rollout log for the official Football Manager face-generator installers —
**FIZZOG 24** (Football Manager 2024) and **FIZZOG 26** (Football Manager 2026).
Downloads: <https://fizzogfm.com> · mirror: this repo's **Releases**. Newest first.

Verify any download against the SHA-256 below with `Get-FileHash file.exe` in PowerShell.

---

## 2026-07-13 — FIZZOG 24 v1.0.14 · FIZZOG 26 v1.0.28

**New — Cut-out (no background).** A new option that generates a transparent,
no-background portrait (the DF11 cut-out look) instead of a framed photo. Available
in both the main app and the mini widget, and can be saved as a favourite/default
with the star. Fully translated into every supported language (29 locales), widget
included. Under the hood the face is generated on a chroma-key green screen and keyed
to transparent locally (~30 ms), so no green ever reaches the user — only the finished
cut-out — and the installer preserves the alpha channel into the FM save.

**Fixes**
- FM24: ginger / red hair now reads correctly from the save (was generating black hair).
- FM24: club kit-colour edge cases tightened.
- FM24: mini-widget "cut picture" checkbox contrast fixed (was near-invisible on the dark widget).
- Both: dropdown text no longer clipped at the bottom (e.g. "grey", "studio").

**SHA-256**
- `FIZZOG-24-Setup-v1.0.14-build2026.07.13.exe` — `71fd3ec5b3eeb60008a270e29858d86f78a1533c34ae2e605c50ca306f85768a`
- `FIZZOG-26-Setup-v1.0.28-build2026.07.13.exe` — `621a922e22f2ac287697593c7f60753438a086220a23601f6e7c40337660ff14`

---

## 2026-07-13 — FIZZOG 24 v1.0.13 · FIZZOG 26 v1.0.27

Fix: academy / reserve / B / U-xx players now get their **parent club's** correct kit
colours (previously affiliate teams fell back to a wrong or blank kit).

---

## 2026-07-13 — FIZZOG 24 v1.0.12 · FIZZOG 26 v1.0.26

First public installers. Realistic AI faces matched to each player's real nationality,
age, hair, build and club colours, installed straight into the Football Manager save.
Free to install; buy credits inside the app.

- `FIZZOG-24-Setup-v1.0.12` — `75e3b655179c393ed7e910adaf0cf59c9a6788b41f2a95b81da3c512069f57c1`
- `FIZZOG-26-Setup-v1.0.26` — `66d2a6aad8c12bbdfc8761645b5c8eab1e39e4a4f082d9bc5315d835d8d8f66c`
