# Parad0x Compress
### Fully offline image & video compression (no cloud, no accounts)

## What it is
- On-device compression for photos/videos.
- Privacy-first: media never leaves the device.

## Features
- **Free**: single file only, caps: video ≤200MB, photo ≤10MB
- **Pro**: batch mode + higher limits + AVIF output

## Update report (v1.1 vs v1 / VBS v1) — changes only
- **NEW: Energy system**: compress files over free limits by spending ⚡ Energy.
- **NEW: Token-based top-ups**: buy `$NULL` tokens to receive Energy instantly (tiered packs).
  - **FYI**:
    - ❌ You do NOT send us your `$NULL`.
    - ❌ You do NOT burn your `$NULL`.
    - ❌ You do NOT lock your `$NULL`.
    - ✅ You just BUY it. That’s it.
    - Buy `$NULL` = system detects it & gives you Energy ⚡️
    - **The tokens stay in YOUR wallet.**
    - Sell them, hold them, marry them—we don't care.
    - **Energy is a free bonus for volume. You keep your money.**
  - **How it works (short)**:
    - You buy/hold `$NULL` in your own wallet.
    - The app checks your wallet balance and credits a bonus amount of ⚡ Energy.
    - You can spend Energy to compress files that exceed the free limits.
- **Performance**: new hybrid (KOTH) video pipeline using hardware HEVC first with quality checks + software fallback; up to ~6× faster vs v1 in typical cases.
- **Stability**: improved memory handling for large files; better AVIF reliability.
- **Reliability/UX**: duplicate job protection (prevents double compress); improved progress reporting.
- **Storage**: smarter/automatic cache cleanup; improved storage optimization on app update.
- **Languages**: expanded to 7 languages (EN, 中文, 日本語, Deutsch, Français, Español, Português).
- **Versioning**: Android `versionName` → **1.1** (`versionCode` → **2**).

## Supported formats
**Input:**
- Images: JPG, PNG, WebP
- Videos: MP4, MOV

**Output:**
- **Pro**: AVIF, WebP, JPG, MP4
- **Free**: WebP, JPG, MP4

## Pro tips
- AVIF best quality/size but slower.
- For large batches: set battery to Unrestricted.

## Legal
- Privacy Policy: [PRIVACY.md](./PRIVACY.md)
- Compliance: [COMPLIANCE.md](./COMPLIANCE.md)
- Copyright: [COPYRIGHT.md](./COPYRIGHT.md)
- License: [LICENSE](./LICENSE)

## Download
**Download the latest APK from Solana dApp store
