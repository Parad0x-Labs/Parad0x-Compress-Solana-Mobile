# Compliance & Transparency

## On-Device Processing
ParaD0x Compress runs a custom FFmpeg engine locally. No media is ever uploaded to any server for processing.

## Permissions Usage
- **INTERNET**: Required only for Solana RPC calls (verifying Pro payment) and Wallet Adapter communication.
- **READ_MEDIA_IMAGES / READ_MEDIA_VIDEO**: Required to select files for compression.
- **READ_EXTERNAL_STORAGE** (Legacy): Required on older Android versions to access selected files.
- **CAMERA**: Not currently used.

## Payment & Pro Features
- **One-time unlock**: Pro is a lifetime purchase for the device/wallet pair.
- **Local Storage**: Entitlement is stored securely in Android SharedPreferences/Keystore on the device.
- **Uninstalling**: Uninstalling the app clears the local license. Updates preserve it.

## Third-Party Components
This app uses open-source software:
- **React Native** (MIT)
- **FFmpegKit** (LGPL/GPL depending on build config) containing **FFmpeg**
- **Solana Web3.js** & **Mobile Wallet Adapter** (Apache 2.0 / MIT)

## Safety Statement
- No malware.
- No hidden downloads.
- No background crypto mining.
- No background data harvesting.
