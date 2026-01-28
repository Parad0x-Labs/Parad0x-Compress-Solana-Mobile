# Third-Party Notices

This document lists third-party software that may be included with, bundled into, or used by **Parad0x Compress** (“the App”).  
All third-party trademarks are the property of their respective owners.

> **Note:** This file is a notices index for transparency. It does not replace the license texts of the third-party projects.

---

## FFmpeg / FFmpegKit (Encoders & Codecs)

The App includes **FFmpeg** via **FFmpegKit**.

- **FFmpeg** is licensed under the **LGPL v2.1 or later**. If built with certain components, FFmpeg may be distributed under the **GPL v3 or later**.
- **FFmpegKit** is distributed under its own license terms and bundles FFmpeg components under the applicable FFmpeg license.

**License(s):**
- FFmpeg: LGPL v2.1+ / GPL v3+ (depending on build configuration)
- FFmpegKit: see FFmpegKit’s license terms and notices

**Source / Corresponding Source:**
- If the distributed build is **LGPL-only**, users must be able to obtain the corresponding source for the LGPL-covered components and any modifications, and must retain the ability to relink/replace the LGPL components as required by the LGPL.
- If the distributed build is **GPL**, additional GPL obligations apply.

**Project references (for license texts and sources):**
- FFmpeg project (licenses + source)
- FFmpegKit project (licenses + source)

**Build disclosure (fill this in):**
- FFmpegKit variant used: `__________` (e.g., “full-gpl”, “full”, “min”, custom)
- Any local modifications: `Yes/No` (if Yes, describe briefly)
- Source availability link (exact version used): `__________`

---

## React Native

The App uses **React Native** and community packages in the React Native ecosystem.

- React Native is commonly distributed under the **MIT License**.
- Individual RN dependencies may have their own licenses (MIT/Apache-2.0/BSD, etc.).

**Project reference:**
- React Native (license + source)

---

## Solana Libraries / Mobile Wallet Adapter

The App uses Solana-related libraries for wallet connection and transaction flows, including **Solana Mobile Wallet Adapter** and **@solana/web3.js** (and/or related packages).

**Licenses:**
- These projects are typically distributed under permissive open-source licenses (commonly **Apache-2.0** or **MIT**), depending on the specific library/package version.

**Project references:**
- Solana Mobile (Mobile Wallet Adapter)
- Solana web3.js (license + source)

---

## Wallet Apps (Third-Party)

Wallet applications (including but not limited to **Phantom** and **Solana Seeker wallet**) are third-party products.  
They are **not** owned by, operated by, or affiliated with Parad0x Labs.

---

## Where to find full license texts

Full license texts for third-party projects can be found in:
- the third-party projects’ repositories and distributions
- your dependency manifests (e.g., `package.json`, Gradle dependencies)
- any license metadata included in the bundled libraries

If you want to provide a more complete bill of materials later, you can add a “Dependencies” appendix listing key packages and versions.

---

## Contact

For questions about these notices: **support@parad0xlabs.com**
